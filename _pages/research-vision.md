---
layout: single
title: Hardware-aware Scheduling for AI-and-RAN Coexistence
permalink: /research-vision/
author_profile: true   
---

I am seeking a Ph.D. opportunity for Fall 2027 to explore the evolution of AI-native 6G systems. The next generation of wireless networks will not simply carry data; they will actively **host AI workloads alongside real-time communication tasks on the same physical hardware**.

This convergence introduces a fundamental tension: radio access networks demand **deterministic, sub-millisecond processing**—exemplified by massive MIMO baseband pipelines such as channel estimation, beamforming, and channel decoding that must complete within every transmission slot—while AI inference is dynamic, resource-hungry, and unpredictable. Resolving this tension requires more than faster hardware. It requires a new class of scheduling intelligence that understands the structure of the underlying platform and makes decisions accordingly. 

My research focuses on **hardware-aware scheduling for AI-and-RAN coexistence**, asking how a resource manager can reason about heterogeneous compute constraints to guarantee real-time communication performance while accommodating AI workloads on shared infrastructure. I treat **massive MIMO signal processing as the canonical real-time workload** my scheduler must protect: its tight, predictable compute deadlines make it the sharpest test of whether AI inference and communication can truly share the same GPU, CPU, or ASIC fabric. I am particularly interested in learning-based approaches that adapt to dynamic workload patterns without violating the hard timing requirements that wireless systems cannot compromise.

Longer term, I want to move beyond scheduling policies toward **a principled theory of predictability for AI workloads in time-critical wireless systems**, understanding not just how to schedule, but what guarantees are even possible when communication and computation converge at the network edge.