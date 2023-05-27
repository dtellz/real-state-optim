# Cost Optimization Algorithm for Real Estate

This project implements a cost optimization algorithm for real estate design configurations. It aims to find the best design configuration that balances cost-effectiveness and resource efficiency.

## Description

The cost optimization algorithm works by generating random design configurations and evaluating them based on cost and efficiency. The evaluation is currently simulated using random cost and efficiency values. However, these evaluations should be replaced with real evaluation metrics specific to real estate design in a production-ready implementation.

The algorithm iterates through a specified number of iterations, continually comparing the current best design with new candidate designs. The best design is updated whenever a candidate design has a lower cost and higher efficiency.

## Getting Started

To use the cost optimization algorithm, follow these steps:

1. Clone or download the project repository.

2. Import the project into an IntelliJ or Scala-supported environment.

3. Open the `costOptimisationAlgorithm` object file located in the `src/main/scala` directory.

4. Ensure that the necessary Scala and sbt configurations are properly set up in your project.

5. Compile and run the `costOptimisationAlgorithm` object file.

## Configuration

The algorithm's behavior can be configured through the following parameters:

- `iterations`: The number of iterations for the optimization loop. Higher values may yield better results but also increase processing time.

- Evaluation Metrics: The evaluation metrics in the `evaluateDesign` function should be replaced with actual evaluation algorithms and metrics relevant to real estate design.

Feel free to customize and enhance the project to suit your specific requirements.