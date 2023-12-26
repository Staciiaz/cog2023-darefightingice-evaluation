# Achieving Fairness in DareFightingICE Agents Evaluation Through a Delay Mechanism

This repository contains the code for the paper "Achieving Fairness in DareFightingICE Agents Evaluation Through a Delay Mechanism" accepted at [CoG 2023](https://2023.ieee-cog.org/).

## Abstract

This paper proposes a delay mechanism to mitigate the impact of latency differences in the gRPC framework---a high-performance, open-source universal remote procedure call (RPC) framework---between different programming languages on the performance of agents in DareFightingICE, a fighting-game research platform. The study finds that gRPC latency differences between Java and Python can significantly impact real-time decision-making. Without a delay mechanism, Java-based agents outperform Python-based ones due to lower gRPC latency on the Java platform. However, with the proposed delay mechanism, both Java-based and Python-based agents exhibit similar performance, leading to a fair comparison between agents developed using different programming languages. Thus, this work underscores the crucial importance of considering gRPC latency when developing and evaluating agents in DareFightingICE, and the insights gained could potentially extend to other gRPC-based applications.
