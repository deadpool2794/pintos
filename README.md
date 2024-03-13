# Pintos Priority Scheduling Project

## Overview Project-1

This project is an extension of the Pintos operating system, focusing on implementing priority scheduling and removing busy waiting from the provided implementation. Priority scheduling assigns priority levels to threads, and the scheduler selects the highest-priority thread for execution.

## Features

1. **Priority Scheduling:**
   - Threads are assigned priority levels.
   - The scheduler selects the highest-priority thread for execution.

2. **Removal of Busy Waiting:**
   - Replaced busy waiting with the use of semaphores and condition variables for synchronization.

## Getting Started

### Prerequisites

Make sure you have the following prerequisites installed:

- [Pintos](https://web.stanford.edu/class/cs140/projects/pintos/pintos_1.html)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/deadpool2794/pintos.git
   ```

2. Build Pintos:

   ```bash
   cd pintos/src/threads
   make
   ```

3. Run Pintos tests:

   ```bash
   make check
   ```

## Implementation Details

### Priority Scheduling

- Implemented priority levels for threads.
- Modified the scheduler to select the highest-priority thread for execution.

### Removal of Busy Waiting

- Replaced busy waiting with semaphores and condition variables for synchronization.
- Improved overall system efficiency and responsiveness.



## License

This project is licensed under the MIT License

## Acknowledgments

- Credits to the original Pintos development team for providing the base implementation.

## Contact

For any questions or concerns, please contact abdulalimkhan10@gmail.com



