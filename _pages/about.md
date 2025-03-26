---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am Yiwei Zhang, a fourth-year Ph.D. student in [Institute of Computing Technology (ICT)](http://english.ict.cas.cn/), [University of Chinese Academy of Sciences (UCAS)](https://www.ucas.ac.cn/), advised by Prof. Yunquan Zhang. I am currently a full-time research intern in Heterogeneous Extreme Computing (HEX) Group of Microsoft Research Asia (MSRA), advised by [Dr. Kun Li](https://www.likun.tech/) and [Dr. Ting Cao](https://www.microsoft.com/en-us/research/people/ticao/).
I obtained my B.Eng. degree from [the Department of Computer Science and Technology, Tsinghua University](https://www.cs.tsinghua.edu.cn/) in 2021.

My research interests include high-performance computing and parallel heterogeneous computing. Previously, I focused primarily on data-level parallel optimization for stencil computations, with related research published at the two top international HPC conferences. Recently, I have developed a strong interest in MLSys and LLMs. If you are interested in collaborating or have any guidance to offer, I would be delighted to hear from you.

If you'd like to discuss anything further, please don't hesitate to reach out.


# 🔥 News
- *2024.11*: &nbsp;🎉🎉 Our paper *Jigsaw: Toward Conflict-free Vectorized Stencil Computation by Tessellating Swizzled Registers* has been accepted by **ACM SIGPLAN Annual Symposium on Principles and Practice of Parallel Programming 2025 (PPoPP'25)**. 
- *2024.11*: &nbsp;🎉🎉 Our paper *LoRAStencil: Low-Rank Adaptation of Stencil Computation on Tensor Cores* was nominated for the **SC'24 Best Reproducibility Advancement Award**.
- *2024.07*: &nbsp;🎉🎉 Our paper *LoRAStencil: Low-Rank Adaptation of Stencil Computation on Tensor Cores* has been accepted by **International Conference for High Performance Computing, Networking, Storage and Analysis (SC'24)**.


# 📝 Publications 

- [**PPoPP'25**] [Jigsaw: Toward Conflict-free Vectorized Stencil Computation by Tessellating Swizzled Registers](https://dl.acm.org/doi/abs/10.1145/3710848.3710886)  
 **Yiwei Zhang**, Kun Li, Liang Yuan, Haozhi Han, Yunquan Zhang, Ting Cao and Mao Yang. In ACM SIGPLAN Annual Symposium on Principles and Practice of Parallel Programming, Las Vegas, NV, USA. pp. 481-495. Association for Computing Machinery, 2025.

- [**SC'24**] [LoRAStencil: Low-Rank Adaptation of Stencil Computation on Tensor Cores](https://ieeexplore.ieee.org/abstract/document/10793164)  
**Yiwei Zhang**, Kun Li, Liang Yuan, Jiawen Cheng, Yunquan Zhang, Ting Cao and Mao Yang. In International Conference for High Performance Computing, Networking, Storage and Analysis, Atlanta, GA, USA. pp. 839-855. IEEE Computer Society, 2024.

- [**PPoPP'25**] [FlashFFTStencil: Bridging Fast Fourier Transforms to Memory-Efficient Stencil Computations on Tensor Core Units](https://dl.acm.org/doi/abs/10.1145/3710848.3710897)  
Haozhi Han, Kun Li, Wei Cui, Donglin Bai, **Yiwei Zhang**, Liang Yuan, Yifeng Chen, Yunquan Zhang, Ting Cao and Mao Yang. In ACM SIGPLAN Annual Symposium on Principles and Practice of Parallel Programming, Las Vegas, NV, USA. pp. 355-368. Association for Computing Machinery, 2025.

- [**PPoPP'23**] [Generating Fast FFT Kernels on CPUs via FFT-Specific Intrinsics](https://dl.acm.org/doi/abs/10.1145/3572848.3577477)  
Zhihao Li, Haipeng Jia, Yunquan Zhang, Yuyan Sun, **Yiwei Zhang** and Tun Chen. In ACM SIGPLAN Annual Symposium on Principles and Practice of Parallel Programming, Montreal, QC, Canada. pp.427 - 428. Association for Computing Machinery, 2023.

- [**ICASSP'21**] [Decision Tree Based Inter Partition Termination For Av1 Encoding](https://ieeexplore.ieee.org/abstract/document/9413481?casa_token=PV-wJc_JQCAAAAAA:2FaGOOheYZzkrmQ70AJYsTr_r7jnCU8apheJvm6LGVia-RAj36ujIqix0pA6vLKw6xsqH_J5wa8J)  
Xinyao Chen, **Yiwei Zhang**, Yanghao Li and Jiangtao Wen. In 2021 IEEE International Conference on Acoustics, Speech and Signal Processing, Toronto, ON, Canada. pp. 1585-1589. IEEE, 2021.

# 🎖 Honors and Awards
- *2025.01* - Director's Excellence Award (Institute of Computing Technology), University of Chinese Academy of Sciences.
- *2024.11* - Best Reproducibility Advancement Award Nomination, SC'24.
- *2024.10* - First-Class Graduate Academic Scholarship, University of Chinese Academy of Sciences.
- *2024.05* - Honors for Merit Student, University of Chinese Academy of Sciences. 

# 📖 Educations
- *2021.09 - Present*, Ph.D. student, [Institute of Computing Technology (ICT)](http://english.ict.cas.cn/), [University of Chinese Academy of Sciences (UCAS)](https://www.ucas.ac.cn/). 
- *2017.09 - 2021.07*, Undergraduate student, [Department of Computer Science and Technology, Tsinghua University](https://www.cs.tsinghua.edu.cn/).

# 💬 Invited Talks
- *2025.03*, "Jigsaw: Toward Conflict-free Vectorized Stencil Computation by Tessellating Swizzled Registers". ACM SIGPLAN Annual Symposium on Principles and Practice of Parallel Programming (**PPoPP**), Las Vegas, NV, USA.
- *2025.03*, "FlashFFTStencil: Bridging Fast Fourier Transforms to Memory-Efficient Stencil Computations on Tensor Core Units". ACM SIGPLAN Annual Symposium on Principles and Practice of Parallel Programming (**PPoPP**), Las Vegas, NV, USA.
- *2024.11*, "LoRAStencil: Low-Rank Adaptation of Stencil Computation on Tensor Cores". High Performance Youth Forum, Chongqing, China.
- *2024.11*, "LoRAStencil: Low-Rank Adaptation of Stencil Computation on Tensor Cores". International Conference for High Performance Computing, Networking, Storage and Analysis (**SC**), Atlanta, GA, USA. 


# 💻 Internships
- *2024.05 - Present*, Heterogeneous Extreme Computing (HEX), Microsoft Research Asia (MSRA), Beijing, China.