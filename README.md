# Concurrency and Threads

## Learning Goals

After this week, you should:

  * Understand the purpose(s) of concurrent programming
  * Understand why common (unit)testing techniques do not apply to concurrent
    programs
  * Be able to create threads in Java
  * Understand the problems that occur with concurrent programming, and their
    solutions. Specifically:
      * Identify and fix race conditions in code
      * Identify and fix visibility issues in code
      * Understand how deadlocks occur, and (loosely) how to deal with them
  * Understand and use the producer/consumer pattern
  * Be able to use threadpools from the java executor framework.
  * Be able to use and explain the java types Thread, Runnable, Callable, and Future
## Business competences (Concurrency/threads)

As a programmer there are problems that can only (realistically) be solved using
concurrency features

Taking advantage of modern multi-kernel CPU requires an understanding of how to
program with threads

These lessons will provide the student with the necessary background to use these
features in Java, with most concepts being generalisable to many other languages
as well.

## Plan

### [Day 1](Day1) - Concurrency, Thread, Runnable, basic Synchronization

### Day 2 - Threads Continued, Producer Consumer, DeadLocks

### [Day 3](Day3) - Thread Continued, Callables and Futures

### Day 4 - JavaScript, AJAX, JSON continue

### Day 5 - Study point exercises


## Resources: 

### General

### Day-1

  * [The well-grounded Java developer](https://manning-content.s3.amazonaws.com/download/e/15b9513-9763-41e7-9178-5cded4d02996/TWGJD_sample_ch04.pdf)  
  I recommend reading the introduction, 4.1.1 (and the 4.1 intro), 4.1.3, 4.2.1
  (and the 4.2 intro) and 4.6 **after the lecture**.
  * [slides](https://docs.google.com/presentation/d/1BInXQP497r0TLDH7xUP7Oc06LcHXHkU58IocN-g3djo/edit?usp=sharing)


### Day-2
"Mandatory" Study materials:
  * [Short video](https://www.youtube.com/watch?v=VXJSJ6c3ZIs)  
    Watch  before the lesson to get a conceptual idea about the Producer-Consumer
    problem. Ignore the talk about ring-buffers
  * [Deadlock wikipedia article](https://en.wikipedia.org/wiki/Deadlock)  
    Read the introduction, and section 1. If you are still confused after the
    lecture, you can read section 2 as well.
  * [The well-grounded Java developer](https://manning-content.s3.amazonaws.com/download/e/15b9513-9763-41e7-9178-5cded4d02996/TWGJD_sample_ch04.pdf)  
    4.2.4 Gives a dead-lock code example with explanation
  * [Slides](https://docs.google.com/presentation/d/1GVBy3TSMdaFfSZphN79utRxk1koPO8i9NuNoCX3lKNs/edit?usp=sharing)

Optional Study material (you may read this after the lecture, if you need to)
- [Producer/Consumer Solution using BlockingQueue](http://www.java67.com/2015/12/producer-consumer-solution-using-blocking-queue-java.html) -- an actual code example

### Day-3
These are not "read it to learn" resources, rather, they are links to the
javadoc pages for the classes we work with. You should read the general
descriptions and skim the method lists for *the first two*. Use the rest as/if/when
you need them.

Useful reading:
* [Java callable api doc](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/Callable.html) -- the actual future class
* [Java Future api doc](https://docs.oracle.com/javase/7/docs/api/java/util/concurrent/Future.html) -- the actual future class
* [Slides](Day3)

Useful for looking up methods as you need them:
* [Java Executors class](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/Executors.html) -- has static methods to instantiate common executor services.
* [Java CompletableFuture api doc](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/CompletableFuture.html) -- the actual CompletableFuture class
* [Java ExecutorService api doc](https://docs.oracle.com/javase/8/docs/api/java/util/concurrent/ExecutorService.html#submit(java.util.concurrent.Callable)) -- The ExecuterService interface.

## Exercises 
*Will follow*
<!-- - [Exercises Day-1](https://docs.google.com/document/d/1zezTIruAiSkhhNCRHJh4EYOcf_mgMblGs6U_XmQ3vp4/edit?usp=sharing)
- [Exercises Day-2](https://docs.google.com/document/d/1A3rBzbbppVZKx-YrGJKWdgsWKs8xNrTR2BeG7zVu6hg/edit?usp=sharing) (Producer/Consumer and Deadlocks)
- [Exercises Day-3](https://docs.google.com/document/d/1AkC59GQm5sbwWpKkideE9kI9KmbscIwKOygn9b_FJMU/edit?usp=sharing) (Using an executor service)
 -->
