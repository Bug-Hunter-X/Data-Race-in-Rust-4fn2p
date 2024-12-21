This repository demonstrates a simple data race bug in Rust and its solution.  The bug occurs because multiple mutable references to the same variable are created without proper synchronization, leading to unpredictable behavior.  The solution demonstrates the use of mutexes to prevent data races.