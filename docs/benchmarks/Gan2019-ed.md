---
comments: true
---

# An Open-Source Benchmark Suite for Microservices and Their Hardware-Software Implications for Cloud & Edge Systems

## Overview 

<!-- title, authors, venue -->
Gan, Y. et al. 2019. An Open-Source Benchmark Suite for Microservices and Their Hardware-Software Implications for Cloud & Edge Systems. Proceedings of the Twenty-Fourth International Conference on Architectural Support for Programming Languages and Operating Systems (2019), 3–18.

### How Many Passes? 

<!-- just a quick indication of my understanding of the paper -->

:white_check_mark: :white_check_mark:


<!-- personal ratings, max: five stars-->

### My Ratings 

- novelty: :star:
- readability: :star: :star: :star: 
- reproducability: :star:
- practicability: :star: :star: :star: :star: 

## High-Level Ideas 

The paper introduces *DeathStarBench*, a benchmark suite for understanding the implications of microservices on the cloud system stack. 

Besides of the main contributions in the benchmark design and findings, the paper also includes a good background on microservices and its benefits. For example, one of the key benefits of microservices is provisioning agility---components of the same end-to-end application can be managed and scaled individually (not necessarily meant independently though). Microservices also allow resource managers better flexibility in packing services based on their resource bottlenecks. 

A lightweight distributed tracing system at the RPC granularity 

What does "real users of the services" mean? Does the authors recruit participants? 

It is intuitive that microserivces will be more network-bound than single-service applications. The key question is probably how to mitigate the network overhead. The paper proposes the idea of offloading RPC processing to an FPGA co-located in the same server can reduce the network overhead. 

The paper shows the implication on microservice performance when a component is mismanaged and demonstrates that existing resource management techniques (determining when to scale and how much to scale) do not work well for microservices. Though it does not look like the paper has suggestions on how to improve on this front. 


## Key Novelties 

Does DeathStarBench support dynamic call graph structures? 



## Evaluation Highlights 


## A Closing Thought 
