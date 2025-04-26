
# Bank Queue Simulation

This Java-based project simulates the queue management system at a bank's service counters, aimed at optimizing customer service and minimizing waiting times.

## Features
- **Queue Management**: Simulates customer queues across multiple service counters.
- **Customer Handling**: Manages customer arrival, service time, and waiting time.
- **Performance Analysis**: Provides insights into queue efficiency and customer satisfaction.

## Project Structure
- **Queue Data Structure**: Implements a FIFO queue using Java's `LinkedList`.
- **Customer Class**: Represents a customer with attributes like arrival time, service time, and start time.
- **ServiceCounter Class**: Manages individual service counters, including queue length and total service time.
- **BankSimulation Class**: Controls the simulation, managing customer assignment to counters and overall performance metrics.

## How to Run
1. **Clone the Repository:**
    ```bash
    git clone https://github.com/yourusername/bank-queue-simulation.git
    cd bank-queue-simulation
    ```

2. **Compile the Code:**
    ```bash
    javac BankSimulation.java
    ```

3. **Run the Simulation:**
    ```bash
    java BankSimulation
    ```

### Input Parameters:
- **Number of Service Counters**: Number of counters available for customer service.
- **Number of Customers**: Total number of customers arriving at the bank.
- **Service Time**: Time each customer will take at the counter (in minutes).
- **Customer Arrival Rate**: Rate at which customers arrive at the bank (in minutes).

### Example:
**Input**:
```
Enter number of service counters: 2
Enter number of customers: 5
Enter time each customer will take at the counter: 4
Enter rate of customer arrival at the bank (in minutes): 2
```

**Output**:
- Total time taken to serve all customers
- Number of customers served by each counter
- Average service time per customer

