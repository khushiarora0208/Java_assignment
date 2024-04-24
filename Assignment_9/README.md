1. **CustomThread Class**:
   - Extends the `Thread` class.
   - It has a constructor that takes a `String` parameter to set the name of the thread.
   - Overrides the `run()` method, where the thread's operation is defined.
   - In the `run()` method, it simulates some operation by counting down from 4 to 1, pausing for 500 milliseconds in each iteration using `Thread.sleep()`.
   - If interrupted during sleep, it catches `InterruptedException` and prints a message.
   - After completing the task, it prints that the thread is exiting.

2. **CustomRunnable Class**:
   - Implements the `Runnable` interface.
   - It has a constructor that takes a `String` parameter to set the name of the thread.
   - Implements the `run()` method similar to `CustomThread`, simulating an operation by counting down and pausing for 500 milliseconds.

3. **ThreadDemo Class**:
   - Contains the `main()` method, which serves as the entry point of the program.
   - Creates two instances of `CustomThread`, each with a unique name.
   - Starts both threads using the `start()` method.
   - Uses `join()` method to ensure that the main thread waits for both threads to complete their execution before proceeding.
   - Catches `InterruptedException` if the main thread is interrupted while waiting.
   - Prints a message indicating that the main thread is exiting after both threads have completed their tasks.

In summary, the code demonstrates the creation and execution of threads using both the `Thread` class and the `Runnable` interface. It showcases thread synchronization using the `join()` method to ensure orderly execution of threads. Additionally, it handles potential interruptions gracefully.
