---
layout: default
title: Research Projects
projects:
  - link: project/
    name: Concurrency
    summary: Concurrency.
  - link: project/
    name: Approximate Computing
    summary: Approximate Computing
---

Our research crosses multiple layers of the system stack, from hardware to programming languages and applications. Our research has four main themes. The concurrency theme addresses challenges in writing, testing and debugging concurrent programs. The approximate computing theme explores accuracy trade-offs across the system stack for better energy efficiency and performance. The emerging applications theme focuses on building systems to better support new applications, from mobile apps to graph analytics. The emerging technologies theme aims at taking advantage of new storage and compute technologies in building new systems.

### Concurrency
Read about it [here][project].

[project]: project/index.html

### Approximate Computing
Improving energy efficiency is paramount in mobile devices and online service infrastructures. Even more importantly, as we approach the limits of silicon device scaling, it might be an enabler for future systems performance and features. Many important applications such as computer vision, machine learning, signal processing, web search, augmented reality, big data analytics, and many more, can inherently tolerate inaccurate computation at various levels. With approximate computing, this fact can be exploited for fundamentally more efficient computing systems.

The key idea in approximate computing is to trade off accuracy in computation, storage, and communication for better performance and energy efficiency. It enables effective use of more aggressive transistor technology, analog computing techniques in a more general way, and new optimizations or code transformations (e.g., using fundamentally approximate models of execution like neural networks).

Taking advantage of approximate computing, though, requires overcoming many technical challenges. Programmers need a reasonable model to write code for and they need tools for testing and debugging approximate programs. The system needs to offer meaningful guarantees of output quality otherwise unusable output actually leads to energy waste. Our research aims to develop a comprehensive solution across the entire system stack, including: language and runtime techniques to express and enforce quality metrics where inaccuracy can be tolerated (EnerJ); language tools, including approximation recommenders and debuggers; compilers to communicate the information to the hardware; microarchitectures and hardware techniques for approximate execution ([NPU][nhl], SNNAP); approximate data storage and communication services; and abstractions for approximate hardware design.
[nhl]: /
