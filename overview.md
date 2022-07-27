# WarpDrive: Extremely Fast End-to-End Deep Multi-Agent Reinforcement Learning on a GPU

WarpDrive is a flexible, lightweight, and easy-to-use open-source reinforcement learning (RL) 
framework that implements end-to-end multi-agent RL on a single or multiple GPUs (Graphics Processing Unit). 

Using the extreme parallelization capability of GPUs, WarpDrive enables orders-of-magnitude 
faster RL compared to CPU simulation + GPU model implementations. It is extremely efficient as it avoids back-and-forth data copying between the CPU and the GPU, 
and runs simulations across multiple agents and multiple environment replicas in parallel. WarpDrive also provides the auto scaling tools to achieve the optimal throughput per device (version 1.3), to perform the distributed asynchronous training among multiple GPU devices (version 1.4), to combine multiple GPU blocks for one environment replica (version 1.6).
Together, these allow the user to run thousands of concurrent multi-agent simulations and train 
on extremely large batches of experience, achieving over 100x throughput over CPU-based counterparts.

