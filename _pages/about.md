---
layout: custom_home
title: Home
permalink: /
description: Ph.D. student at Zhejiang University, focusing on adversarial machine learning, real-time object detection, and LLM serving systems.
---

<!-- ===== 双栏总览：About Me + Research Roadmap ===== -->
<div class="overview-grid" id="overview">
    <div class="overview-left" id="about">
        <h2><i class="fas fa-user"></i> About Me</h2>
        <p>I am a Ph.D. student at <strong>Zhejiang University</strong>, advised by <a href="https://cwang-zju.github.io/">Prof. Cong Wang</a>. I am a member of <a href="http://nesc.zju.edu.cn/#/">ZJU NeSC group</a>. My research focuses on <strong>adversarial machine learning</strong>, with particular emphasis on:</p>
        <ul>
            <li>Adversarial attacks & defenses in object detection</li>
            <li>LLM serving system security</li>
        </ul>
        <div class="research-interests">
            <span class="tag">🔒 AdvML</span>
            <span class="tag">🤖 LLM Security</span>
            <span class="tag">⚡ Edge AI</span>
        </div>
        
        <h3 style="margin-top:24px; margin-bottom:12px; font-size:1.1rem;"><i class="fas fa-graduation-cap"></i> Education</h3>
        <div class="education-item">
            <div class="degree">Ph.D. in Control Science and Engineering</div>
            <div class="details">Zhejiang University &nbsp;|&nbsp; 2023.9 - 2026.9 (Expected)</div>
        </div>
        <div class="education-item">
            <div class="degree">M.S. in Electronic Information</div>
            <div class="details">Zhejiang University &nbsp;|&nbsp; 2021.9 - 2023.7 (Converted to Ph.D.)</div>
        </div>
        <div class="education-item">
            <div class="degree">B.S. in Automation</div>
            <div class="details">Zhengzhou University &nbsp;|&nbsp; 2016.9 - 2020.7</div>
        </div>
    </div>

    <div class="overview-right" id="roadmap">
        <h2><i class="fas fa-project-diagram"></i> Research Roadmap</h2>
        
        <img src="{{ '/assets/img/research_roadmap.svg' | relative_url }}" alt="Research Roadmap" style="width:100%; max-width:900px; border-radius:12px; margin:0;">
        
        <p style="font-size:0.9rem; color:#64748b; margin-top:12px; font-style:italic;">
            My research follows a bottom-up approach: from component-level defense (CVPR'25), 
            through architecture-level attacks (IEEE TIFS'26), to system-level vulnerabilities (arXiv'26). 
            Collaborations extend these insights to edge optimization (ICDCS'25, AAAI'25).
        </p>
    </div>
</div>

<!-- ===== Selected Publications (单栏) ===== -->
<section id="publications">
    <h2><i class="fas fa-file-alt"></i> Selected Publications</h2>
    <p style="color: var(--text-light); font-size: 0.9rem; margin-bottom: 20px;">
        See the <a href="{{ '/publications/' | relative_url }}" style="color: var(--primary);">full list of publications</a> or <a href="https://scholar.google.com/citations?user=RFuhM2IAAAAJ&hl=zh-CN" style="color: var(--primary);" target="_blank" rel="noopener noreferrer">Google Scholar</a>.
    </p>
    
    <div class="pub-list">
        <p class="pub-item">
            <span class="pub-badge" style="background: #0076df;">CVPR 2025</span>
            <strong>Can't Slow Me Down: Learning Robust and Hardware-Adaptive Object Detectors against Latency Attacks for Edge Devices</strong><br>
            <span class="pub-authors"><strong>Tianyi Wang</strong>, Zichen Wang, Cong Wang, Yuanchao Shu, Ruilong Deng, Peng Cheng, Jiming Chen</span><br>
            <span class="pub-venue">Proceedings of the Computer Vision and Pattern Recognition Conference, pp. 19230--19240</span>
        </p>

        <p class="pub-item">
            <span class="pub-badge" style="background: #6b7280;">arXiv</span>
            <strong>Rethinking Latency Denial-of-Service: Attacking the LLM Serving Framework, Not the Model</strong><br>
            <span class="pub-authors"><strong>Tianyi Wang</strong>, Huawei Fan, Yuanchao Shu, Peng Cheng, Cong Wang</span><br>
            <span class="pub-venue">arXiv preprint arXiv:2602.07878</span>
        </p>

        <p class="pub-item">
            <span class="pub-badge" style="background: #ff3636;">IEEE TIFS</span>
            <strong>The Chosen-Object Attack: Exploiting the Hungarian Matching Loss in Detection Transformers for Fun and Profit</strong><br>
            <span class="pub-authors"><strong>Tianyi Wang</strong>, Cong Wang, Zhenyu Wen, Ruilong Deng, Yuanchao Shu, Peng Cheng, Jiming Chen</span><br>
            <span class="pub-venue">IEEE Transactions on Information Forensics and Security</span>
        </p>

        <p class="pub-item">
            <span class="pub-badge" style="background: #00ab37;">AAAI 2025</span>
            <strong>Fed-DFA: Federated Distillation for Heterogeneous Model Fusion through the Adversarial Lens</strong><br>
            <span class="pub-authors">Zichen Wang, Feng Yan, <strong>Tianyi Wang</strong>, Cong Wang, Yuanchao Shu, Peng Cheng, Jiming Chen</span><br>
            <span class="pub-venue">Proceedings of the AAAI Conference on Artificial Intelligence, Vol. 39, No. 20, pp. 21429--21437</span>
        </p>

        <p class="pub-item">
            <span class="pub-badge" style="background: #f29105;">ICDCS 2025</span>
            <strong>Hetero<sup>2</sup>Pipe: Pipelining Multi-DNN Inference on Heterogeneous Mobile Processors under Co-Execution Slowdown</strong><br>
            <span class="pub-authors">Yuhao Shen, Zichen Wang, <strong>Tianyi Wang</strong>, Chaojie Gu, Zhenyu Wen, Yuanchao Shu, Cong Wang</span><br>
            <span class="pub-venue">2025 IEEE 45th International Conference on Distributed Computing Systems (ICDCS), pp. 483--493</span>
        </p>
    </div>
</section>
