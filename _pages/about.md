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

Hi! My name is Haoran Sun (孙皓然). I am a PhD student at the <a href="https://www.pku.edu.cn/">Center on Frontiers of Computing Studies, School of Computer Science, Peking University</a>, advised by <a href="https://cfcs.pku.edu.cn/english/people/faculty/xiaotiedeng/index.htm">Prof. Xiaotie Deng</a>. I received my B.E. in Artificial Intelligence (Tong Class) and B.A. in Economics (Double Major) from <a href="https://yuanpei.pku.edu.cn/">Yuanpei College, Peking University</a> in 2024.

My broader research interests lie at the intersection of game theory and AI — see our survey [\[P1\]]({{ '/papers/' | relative_url }}#P1). A line of my work has investigated how to leverage modern AI technology (neural networks) to discover high-revenue auction mechanisms (see [\[C2\]]({{ '/papers/' | relative_url }}#C2), [\[C7\]]({{ '/papers/' | relative_url }}#C7), and [\[C9\]]({{ '/papers/' | relative_url }}#C9)). More recently, I have been focusing on the training of foundation models, specifically post-training mechanisms and infrastructure (see [\[C8\]]({{ '/papers/' | relative_url }}#C8), [\[P6\]]({{ '/papers/' | relative_url }}#P6), and [\[P3\]]({{ '/papers/' | relative_url }}#P3)). Moreover, I am also interested in the product form of foundation models, i.e., how to monetize in the LLM era (see [\[P5\]]({{ '/papers/' | relative_url }}#P5) and [\[C6\]]({{ '/papers/' | relative_url }}#C6)).

You can find my publications on <a href='https://scholar.google.com/citations?user=kfbX33MAAAAJ'>Google Scholar</a>.
Reach me at <a href="mailto:{{ site.author.email }}">{{ site.author.email }}</a>.
<!-- <img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>. -->


# 🔥 News
- *2026.05*: &nbsp;🎉 Our paper has been accepted to <b>ICML 2026</b>!
- *2026.04*: &nbsp;🎉🎉 Honored to co-organize the <b>AIMS</b> Workshop [(AI for Mechanism Design and Strategic Decision Making)](https://alimama-tech.github.io/aims-2026) at <b>ICLR 2026</b>! Looking forward to seeing you in Rio de Janeiro!

<!-- - *2026.01*: &nbsp;🎉 Our papers have been accepted to <b>WWW 2026</b> and <b>ICLR 2026</b>!
- *2025.09*: &nbsp;🎉 Our paper has been accepted to <b>NeurIPS 2025</b>!
- *2025.05*: &nbsp;🎉 Our paper has been accepted to <b>IJCAI 2025</b>! -->

<span class='anchor' id='publications'></span>

# 📝 Selected Papers (* indicates equal contribution)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2026</div><img src="{{ '/images/CA-AMA.png' | relative_url }}" alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Enhancing Affine Maximizer Auctions with Correlation-Aware Payment](https://arxiv.org/abs/2602.09455)

**Haoran Sun**, Xuanzhi Xia, Xu Chu, Xiaotie Deng

- Proposed correlation-aware affine maximizer auctions for correlated bidders.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2026</div><img src="{{ '/images/benefits.png' | relative_url }}" alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Benefits and Pitfalls of Reinforcement Learning for Language Model Planning: A Theoretical Perspective](https://arxiv.org/abs/2509.22613)

Siwei Wang$^\*$, Yifei Shen$^\*$, **Haoran Sun$^\*$**, Shi Feng$^\*$, Shang-Hua Teng, Li Dong, Yaru Hao, Wei Chen

- Theoretical analysis of RL methods for LLM planning, revealing benefits and pitfalls.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">WWW 2026</div><img src="{{ '/images/OD-VVCA.png' | relative_url }}" alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Scalable Virtual Valuations Combinatorial Auction Design by Combining Zeroth-Order and First-Order Optimization Methods](https://dl.acm.org/doi/abs/10.1145/3774904.3792377)

Zhijian Duan$^\*$, **Haoran Sun$^\*$**, Yichong Xia, Siqiang Wang, Zhilin Zhang, Chuan Yu, Jian Xu, Xiaotie Deng

- Novel combinatorial auction design combining zeroth-order and first-order optimization.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src="{{ '/images/RLHF_Game.png' | relative_url }}" alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Mechanism Design for LLM Fine-tuning with Multiple Reward Models](https://proceedings.neurips.cc/paper_files/paper/2025/hash/ea21628f0fc0de542373be4c88343478-Abstract-Conference.html)

**Haoran Sun**, Yurong Chen, Siwei Wang, Wei Chen, Xiaotie Deng

- Mechanism design framework for LLM fine-tuning with multiple reward models.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI 2025</div><img src="{{ '/images/GT_and_LLM.png' | relative_url }}" alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Game Theory Meets Large Language Models: A Systematic Survey](https://www.ijcai.org/proceedings/2025/1184.pdf)

**Haoran Sun**, Yusen Wu, Yukun Cheng, Xu Chu

- Comprehensive survey on the intersection of game theory and LLMs.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023 Spotlight</div><img src="{{ '/images/AMenuNet.png' | relative_url }}" alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Scalable Neural Network for DSIC Affine Maximizer Auction Design](https://proceedings.neurips.cc/paper_files/paper/2023/hash/af31604708f3e44b4de9fdfa6dcaa9d1-Abstract-Conference.html)

Zhijian Duan, **Haoran Sun**, Yurong Chen, Xiaotie Deng

- Neural network approach for designing affine maximizer auctions.
</div>
</div>

*[See full paper list →]({{ '/papers/' | relative_url }}#papers-in-progress)*

<br>

# 🎖 Honors and Awards

- *2024.12* 🥉 3rd Place in NeurIPS 2024 Auto-Bidding in Large-Scale Auctions Competition (General Track)
- *2024.06* 🏆 Song Qingling Scholarship, Peking University
- *2023.10* 🏆 Yang Fuqing & Wang Yangyuan Academician Scholarship (Top 10%), Peking University
- *2023.10* 🏆 Outstanding Research Award, Peking University
- *2023.08* 🥇 6th Place in IJCAI Mahjong AI Competition (IJCAI 2023); 8th Place (IJCAI 2024)

<br>

# 💬 Academic Service

- Workshop Organizer: ICLR 2026 Workshop on AI for Mechanism Design and Strategic Decision Making (AIMS)
- Peer Review: ICLR 2026, NeurIPS (2024-2026), ICML (2024-2026), WWW 2024, COLM 2026, IEEE TCE

<br>

# 📖 Educations

<div class="education-list" markdown="0">
<div class="education-with-logo">
<img src="images/pku.png" alt="Peking University" class="education-with-logo__logo">
<div class="education-with-logo__text" markdown="1">
*2024.09 - 2029.07 (Expected)*, PhD in Computer Science, Center on Frontiers of Computing Studies, School of Computer Science, Peking University. Advisor: Prof. Xiaotie Deng.
</div>
</div>
<div class="education-with-logo">
<img src="images/pku.png" alt="Peking University" class="education-with-logo__logo">
<div class="education-with-logo__text" markdown="1">
*2020.09 - 2024.07*, B.E. in Artificial Intelligence and B.A. in Economics (Double Major), Tong Class, Yuanpei College, Peking University.
</div>
</div>
</div>

# 💻 Internships
- *2025.09 - Now*, Research Intern, JD Technology, Beijing, China. Mentored by Junwu Xiong (AI Infra Team).
- *2025.02 - 2025.09*, Research Intern, Alimama, Alibaba Group, Beijing, China. Mentored by Zhilin Zhang (Advertising Group).
- *2023.06 - 2024.03*, Research Intern, Microsoft Research Asia, Beijing, China. Mentored by Wei Chen (Theory Group).