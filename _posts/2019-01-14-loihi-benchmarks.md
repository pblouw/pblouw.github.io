---
layout: post
title: New Paper on Benchmarking Neuromorphic Hardware
---

Through my work at [ABR](https://www.appliedbrainresearch.com), I've been involved in
a project focused on benchmarking the speed and efficiency of a simple 
keyword spotter running on Intel's new neuromorphic research chip 
[Loihi](https://en.wikichip.org/wiki/intel/loihi). A paper outlining this work
is now publically available, along with code for reproducing all the reported
results. For a quick summary, here's the abstract:

  >  Using Intel's Loihi neuromorphic research chip and ABR's Nengo Deep Learning toolkit, we analyze the inference speed, dynamic power consumption, and energy cost per inference of a two-layer neural network keyword spotter trained to recognize a single phrase. We perform comparative analyses of this keyword spotter running on more conventional hardware devices including a CPU, a GPU, Nvidia's Jetson TX1, and the Movidius Neural Compute Stick. Our results indicate that for this inference application, Loihi outperforms all of these alternatives on an energy cost per inference basis while maintaining equivalent inference accuracy. Furthermore, an analysis of tradeoffs between network size, inference speed, and energy cost indicates that Loihi's comparative advantage over other low-power computing devices improves for larger networks.  

For more info, you can check out the [paper](https://arxiv.org/abs/1812.01739), or take a look at the [code](https://github.com/abr/power_benchmarks). A recent [press release](https://newsroom.intel.com/news/intel-announces-neuromorphic-computing-research-collaborators/) from Intel also has some interesting information about the broader context in which this work is situated. 

The cool thing about this work is that it's arguably the first demonstration of neuromorphic chip providing leading energy efficiency on a real-world task in comparison to other programmable architectures. It's still early days though, and there are number of improvements coming down the pipe, so stay tuned.
