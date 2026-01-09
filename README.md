This repository studies reinforcement learning under partial observability (POMDP) with a focus on learned memory management.

We propose an approach where past observations are stored, compressed, or discarded based on their information value, learned jointly with the policy.
By integrating future prediction signals and memory utility estimation, the agent achieves stable long-horizon performance while significantly reducing memory usage and failure spikes.

Experiments on POMDP benchmarks (e.g., partially observed control tasks) demonstrate that effective memory control can improve robustness without sacrificing performance.
