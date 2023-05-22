---
comments: true
---

# Palette Load Balancing: Locality Hints for Serverless Functions

## Overview 

<!-- title, authors, venue -->
Abdi, M. et al. 2023. Palette Load Balancing: Locality Hints for Serverless Functions. Proceedings of the 18th European Conference on Computer Systems, (2023).


### How Many Passes? 

<!-- just a quick indication of my understanding of the paper -->

:white_check_mark: :white_check_mark:


<!-- personal ratings, max: five stars-->

### My Ratings 

- novelty: :star:
- readability: :star: :star: :star: 
- reproducability: :star:
- practicability: :star: :star: :star: :star: 

## Why This Paper? 

Microservices deployment often rely on serverless platforms. The efficiency of microservices therefore can be improved by having a better managed serverless platform. This paper showcases the Palette's benefit with a commonly-used microservice application (modified to use in-memory cache). In short, this paper does not specifically target at microservices, but it is well within the microservice ecosystem.

A number of the authors are from the Microsoft Azure Systems Research and have done some great work in characterizing real-world serverless performance[^1] and improving serverless function caching[^2] from the cloud providers' perspective.

[^1]: Shahrad, M. et al. 2020. Serverless in the wild: Characterizing and optimizing the serverless workload at a large cloud provider. 2020 USENIX Annual Technical Conference (USENIX ATC 20) (2020), 205–218.
[^2]: Romero, F. et al. 2021. Faa$T: A Transparent Auto-Scaling Cache for Serverless Applications. Proceedings of the ACM Symposium on Cloud Computing (Nov. 2021), 122–137.



## High-Level Ideas 

This paper tries to bring the data and computation closer for serverless applications. This improvement can be huge because serverless paradigm is often considered to be stateless. Any attempts to utilize existing serverless platforms to run data-intensive and stateful applications require some painstaking maneuver. Interesting readers can look at LambdaML [^3] and FuncPipe [^4], two recent works in supporting distributed training on serverless platforms from the cloud user's perspective. 

[^3]: Jiang, J. et al. 2021. Towards Demystifying Serverless Machine Learning Training. Proceedings of the 2021 International Conference on Management of Data (New York, NY, USA, Jun. 2021), 857–871.
[^4]: Liu, Y. et al. 2022. FuncPipe: A Pipelined Serverless Framework for Fast and Cost-efficient Training of Deep Learning Models. arXiv [cs.DC]. To appear in ACM SIGMETRICS 2023. 


## Key Novelties 



## Evaluation Highlights 


## A Closing Thought 


<!-- when executing and serving requests, current frameworks do not consider locality. This is shocking -->