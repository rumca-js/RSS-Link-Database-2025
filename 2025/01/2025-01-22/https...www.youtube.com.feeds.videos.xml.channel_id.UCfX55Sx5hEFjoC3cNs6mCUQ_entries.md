# Source:The Linux Foundation, URL:https://www.youtube.com/feeds/videos.xml?channel_id=UCfX55Sx5hEFjoC3cNs6mCUQ, language:en

## Mentorship Session: Designing Custom Linux Schedulers with sched_ext
 - [https://www.youtube.com/watch?v=jsLjg9tGuVI](https://www.youtube.com/watch?v=jsLjg9tGuVI)
 - RSS feed: $source
 - date published: 2025-01-22T18:53:03+00:00

Mentor: Andrea Righi, Principal Software Engineer, NVIDIA

The Linux kernel provides a single scheduler that must handle a wide range of different architectures and workloads, making it a robust, but sometimes also a rigid, component, which offers limited room for experimentation and customization.

sched_ext is a new technology, introduced in Linux 6.12, that allows to dynamically replace the default kernel scheduling policy at runtime with custom BPF programs.

The main benefits include the ease of experimentation, through a fast edit/compile/test cycle, along with an extensive customization and control over scheduling policies. It can also help lower the entry barriers for scheduler development, empowering a broader range of developers and kernel enthusiasts to contribute and bring fresh ideas to scheduler design.

