# Java Interview Questions - Threads - Part3
## 5) Java Threads

#### Java ExecutorService and Thread Pools Tutorial
 
* We know how to create threads in Java by extending the Thread class or implementing the Runnable interface.

* While it is easy to create one or two threads and run them, it becomes a problem when your application requires creating 20 or 30 threads for running tasks concurrently.

* Also, it won�t be exaggerating to say that large multi-threaded applications will have hundreds, if not thousands of threads running simultaneously. So, it makes sense to separate thread creation and management from the rest of the application.

#### Executors, A framework for creating and managing threads.

* **Executors framework helps you with -**

* **Thread Creation:** 
  * It provides various methods for creating threads, more specifically a pool of threads, that your application can use to run tasks concurrently.

* **Thread Management:** 
  * It manages the life cycle of the threads in the thread pool. You don�t need to worry about whether the threads in the thread pool are active or busy or dead before submitting a task for execution.

* **Task submission and execution:** 
  * Executors framework provides methods for submitting tasks for execution in the thread pool, and also gives you the power to decide when the tasks will be executed. For example, You can submit a task to be executed now or schedule them to be executed later or make them execute periodically.