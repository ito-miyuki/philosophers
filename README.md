# 🍽️ Philosophers

Welcome to the **Philosophers** project! This is an implementation of the classic [Dining Philosophers problem](https://en.wikipedia.org/wiki/Dining_philosophers_problem) in C. The problem explores how multiple philosophers (or threads) can share limited resources without getting stuck—just like real-life concurrency challenges in programming!


## Getting Started

### Prerequisites

To build and run this project, you’ll need:

- A **C compiler** (like `gcc`)
- `make` (to compile the project)

### Installation & Running

1. **Clone the repository**:

   ```bash
   git clone https://github.com/ito-miyuki/philosophers.git
   cd philosophers

2. Compile the program:

    ```bash
    make
    ```

3. Run it:

   ```bash
   ./philo time_to_die time_to_eat time_to_sleep [how_many_times_philosophers should eat]
   ```

Time should be provided in milliseconds. [how_many_times_philosophers should eat] is optional.

For example:
```bash
./philo 3 150 60 60 4
```



Thanks for stopping by! Hope you have fun with the project!💫


