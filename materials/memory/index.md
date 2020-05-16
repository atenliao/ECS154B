# Memory System Architecture

![HBM memory](./hbm.jpg)

In this section, we're going to learn about what I believe is the most important part of the computer's architecture: the memory system.
Moving data from point A to point B is one of the main bottlenecks in all of today's systems.
Shown above is a picture of HBM (high-bandwidth memory) which is a relatively new memory technology primarily used in GPUs and other accelerators to try to overcome this memory bottleneck.

## Memory intro and Technology

In this section, we'll be talking about how memory *works* and [memory technology](./technology.md).
We'll find that while there are many different memory technologies, none are "best".

* [Memory intro and technology](./technology.md)
  * [Introduction: Why does memory architecture matter? **VIDEO**](./technology.md#introduction-why-does-memory-architecture-matter-video-)
  * [Memory technology **VIDEO**](./technology.md#memory-technology-video-)
  * [Moving data around **VIDEO**](./technology.md#moving-data-around-video-)
  * [**QUIZ** Memory technology](./technology.md#quiz-memory-technology)

## Caches and the Memory Hierarchy

Since no one technology is the best, we want to create a memory hierarchy with [caches](./caches.md).
We will discuss the underlying principles that make caches efficient, and how hardware caches are designed.

* [Caches and the Memory Hierarchy](./caches.md)
  * [Memory hierarchy introduction](./caches.md#memory-hierarchy-introduction)
  * [Basic caching](./caches.md#basic-caching)
    * [Combining memory technologies into a single system **VIDEO**](./caches.md#combining-memory-technologies-into-a-single-system-video)
    * [Locality and caching **VIDEO**](./caches.md#locality-and-caching-video)
    * [Cache performance **VIDEO**](./caches.md#cache-performance-video)
    * [**QUIZ** Basic caching](./caches.md#quiz-basic-caching)
  * [Memory hierarchy **VIDEO**](./caches.md#memory-hierarchy-video)
  * [Cache design](./caches.md#cache-design)
    * [Direct-mapped caches **VIDEO**](./caches.md#direct-mapped-caches-video)
    * [Set-associative caches **VIDEO**](./caches.md#set-associative-caches-video)
    * [**QUIZ** Cache design](./caches.md#-quiz-cache-design)
  * [Replacement policies **VIDEO**](./caches.md#replacement-policies-video)
  * [Write-back policies **VIDEO**](./caches.md#write-back-policies-video)
  * [Summary of caches **VIDEO**](./caches.md#summary-of-caches-video)
    * [**QUIZ** Summary of caches](./caches.md#-quiz-summary-of-caches)

### [Assignment 4](https://github.com/jlpteaching/dinocpu-sq20/blob/master/assignments/assignment-4.md) **DUE 5/25**

## Virtual memory

Finally, we'll step up a level and look at how operating systems allow multiple programs to share a single memory through [virtualization](./virtual.md).

* [Virtual memory](./virtual.md)
  * ![under construction](/under-construction.png)

## Summary

* [Summary](./summary.md)
  * ![under construction](/under-construction.png)

[Up next: Parallel Architecture.](../parallel/index.md)
