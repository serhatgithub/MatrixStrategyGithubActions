# GitHub Actions Matrix Demo

This project demonstrates the **Matrix Strategy** feature in GitHub Actions.

### Purpose
The workflow initiates 4 simultaneous processes to observe execution behavior:
* **Successful Runs**: Processes that complete without errors.
* **Failed Runs**: Simulated crashes to test failure handling.

### Results
The execution shows that while some jobs fail (e.g., version 1.24), others continue to run independently. This confirms that matrix jobs can operate in isolation without one failure stopping the entire workflow.
