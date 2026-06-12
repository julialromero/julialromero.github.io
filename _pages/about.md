---
permalink: /
layout: home
title: ""
excerpt: "About me"
author_profile: false
redirect_from: 
  - /about/
  - /about.html
---

<div class="home-shell">
  <aside class="home-rail" aria-label="Page sections">
    <nav>
      <a href="#bio" data-section-link>Bio</a>
      <a href="#recent-news" data-section-link>Recent News</a>
      <a href="#publications" data-section-link>Publications</a>
      <a href="#patents" data-section-link>Patents</a>
      <a href="#personal" data-section-link>Personal</a>
    </nav>
  </aside>

  <div class="home-main">
<section class="home-hero" aria-labelledby="home-title">
  <div class="home-hero__media">
    <img src="{{ '/images/julia-romero-profile-mountain.jpeg' | relative_url }}" alt="Julia Romero in front of the Flatirons">
  </div>

  <div class="home-hero__content">
    <h1 id="home-title">Julia Romero, PhD</h1>
    <p class="home-hero__subtitle">AI/ML Research Scientist</p>

    <p class="home-tags" aria-label="Research keywords">
      <span>Computer Vision</span>
      <span class="home-tags__separator" aria-hidden="true">&diam;</span>
      <span>Geospatial AI</span>
      <span class="home-tags__separator" aria-hidden="true">&diam;</span>
      <span>Mobile/Wearable Computing</span>
    </p>

    <div class="home-linkbar" aria-label="Profile links">
      <a href="mailto:julialromero@gmail.com" class="profile-icon" aria-label="Email" data-label="Email">
        <svg class="profile-icon__svg" viewBox="0 0 24 24" aria-hidden="true" focusable="false">
          <path d="M3 5.25A2.25 2.25 0 0 1 5.25 3h13.5A2.25 2.25 0 0 1 21 5.25v13.5A2.25 2.25 0 0 1 18.75 21H5.25A2.25 2.25 0 0 1 3 18.75V5.25Zm2.36-.75 6.64 5.24 6.64-5.24H5.36Zm14.14 1.53-6.57 5.18a1.5 1.5 0 0 1-1.86 0L4.5 6.03v12.72c0 .41.34.75.75.75h13.5c.41 0 .75-.34.75-.75V6.03Z"/>
        </svg>
      </a>
      <a href="{% if site.author.googlescholar %}{{ site.author.googlescholar }}{% else %}#{% endif %}" class="profile-icon" aria-label="Google Scholar" data-label="Google Scholar">
        <svg class="profile-icon__svg" viewBox="0 0 24 24" aria-hidden="true" focusable="false">
          <path d="M5.242 13.769L0 9.5 12 0l12 9.5-5.242 4.269C17.548 11.249 14.978 9.5 12 9.5c-2.977 0-5.548 1.748-6.758 4.269zM12 10a7 7 0 1 0 0 14 7 7 0 0 0 0-14z"/>
        </svg>
      </a>
      <a href="{% if site.author.linkedin %}https://www.linkedin.com/in/{{ site.author.linkedin }}{% else %}#{% endif %}" class="profile-icon" aria-label="LinkedIn" data-label="LinkedIn">
        <svg class="profile-icon__svg" viewBox="0 0 24 24" aria-hidden="true" focusable="false">
          <path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433c-1.144 0-2.063-.926-2.063-2.065 0-1.138.92-2.063 2.063-2.063 1.14 0 2.064.925 2.064 2.063 0 1.139-.925 2.065-2.064 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/>
        </svg>
      </a>
      <a href="{% if site.author.github %}https://github.com/{{ site.author.github }}{% else %}#{% endif %}" class="profile-icon" aria-label="GitHub" data-label="GitHub">
        <svg class="profile-icon__svg" viewBox="0 0 24 24" aria-hidden="true" focusable="false">
          <path d="M12 .297c-6.63 0-12 5.373-12 12 0 5.303 3.438 9.8 8.205 11.385.6.113.82-.258.82-.577 0-.285-.01-1.04-.015-2.04-3.338.724-4.042-1.61-4.042-1.61C4.422 18.07 3.633 17.7 3.633 17.7c-1.087-.744.084-.729.084-.729 1.205.084 1.838 1.236 1.838 1.236 1.07 1.835 2.809 1.305 3.495.998.108-.776.417-1.305.76-1.605-2.665-.3-5.466-1.332-5.466-5.93 0-1.31.465-2.38 1.235-3.22-.135-.303-.54-1.523.105-3.176 0 0 1.005-.322 3.3 1.23.96-.267 1.98-.399 3-.405 1.02.006 2.04.138 3 .405 2.28-1.552 3.285-1.23 3.285-1.23.645 1.653.24 2.873.12 3.176.765.84 1.23 1.91 1.23 3.22 0 4.61-2.805 5.625-5.475 5.92.42.36.81 1.096.81 2.22 0 1.606-.015 2.896-.015 3.286 0 .315.21.69.825.57C20.565 22.092 24 17.592 24 12.297c0-6.627-5.373-12-12-12"/>
        </svg>
      </a>
    </div>
  </div>
</section>

<section class="home-section home-bio" id="bio" aria-labelledby="about-me">
  <div class="section-heading-row">
    <div>
      <p class="home-bio__notice">I am on the job market and seeking Research Scientist roles!</p>
      <h2 id="about-me">About Me</h2>
    </div>
  </div>
  <div class="about-copy">
    <p>I research machine learning for spatiotemporal sensor data, developing effective data- and resource-efficient methods for computer vision, human-centered sensing, and Earth Observation. I recently completed my Ph.D. in Computer Science at the <a href="https://www.colorado.edu/">University of Colorado Boulder</a>, and my research spans these topics:</p>

    <ul>
      <li><strong>Vision &amp; Geospatial Foundation Models</strong>: I develop and interpret self-supervised vision foundation models for Earth Observation tasks, examining the full pipeline from pretraining to downstream adaptation. I implemented and maintained multi-cluster distributed computing infrastructure on an NSF supercomputer to support large-scale pretraining (before LLMs knew Slurm scripting...) <a href="#publication-geospatial">[in submission, 2026]</a></li>
      <li><strong>Multimodal Video Understanding</strong>: I build graph-based vision models for fine-grained activity recognition that are trained on diverse data but infer using only a single-input from egocentric (smart-glasses) video <a href="https://openaccess.thecvf.com/content/ICCV2025W/SG2RL/papers/Romero_Long-form_Reasoning_for_Keystep_Recognition_using_Graph_Neural_Networks_ICCVW_2025_paper.pdf">[ICCVW'25]</a>. This work with <a href="https://community.intel.com/t5/Blogs/Tech-Innovation/Artificial-Intelligence-AI/Improving-Video-Understanding-Through-Graph-Based-AI-for-Better/post/1720916">Intel Labs</a> won 1st place in Meta's Ego-Exo4D challenge (out of 20+ teams) and led to an invited spotlight talk at the <a href="https://youtu.be/iz2Flo4ZVm4?t=2472">CVPR 2025 Egocentric Vision Workshop</a>.</li>
      <li><strong>Human-Centered Sensing Systems</strong>: I design sensing algorithms for resource-constrained wearables and ML pipelines for health data, spanning physiological monitoring with smart earbuds <a href="https://dl.acm.org/doi/10.1145/3638550.3641136">[HotMobile'24]</a>, injury-risk modeling, basketball activity recognition <a href="https://www.mdpi.com/1424-8220/23/13/5879">[Sensors'23]</a>, and large-scale analysis of physical activity behavior <a href="https://www.mdpi.com/1660-4601/19/19/12933">[IJERPH'22]</a>.</li>
    </ul>

    <p>My Ph.D. research was funded in part by an <a href="https://www.nsf.gov/awardsearch/show-award/?AWD_ID=1941898">NSF IUCRC award</a> from a proposal I co-wrote, which supported a 2.5-year collaboration with Intel Labs from 2023 to 2025. Previously, I was a research intern at <a href="https://www.nokia.com/bell-labs/research/sdsr/device-software/">Nokia Bell Labs</a> in Cambridge, UK, and worked on wearable computing and health ML at <a href="https://www.stryd.com/us/en">Stryd</a>, <a href="https://kinesisintegrated.com/">Kinesis Integrated</a>, and the <a href="https://www.jhuapl.edu/">Johns Hopkins Applied Physics Laboratory</a>.</p>

    <p>I am currently seeking Research Scientist roles in AI/ML, especially in computer vision, foundation models and self-supervised learning, or sensing systems.</p>
  </div>
</section>

<section class="home-section home-news" id="recent-news" aria-labelledby="recent-news-title">
  <div class="section-heading-row">
    <div>
      <h2 id="recent-news-title">Recent News</h2>
    </div>
  </div>

  <div class="news-list" aria-label="Recent News">
    <article class="news-item">
      <time datetime="2026-05">May 2026</time>
      <p>Defended my Ph.D. dissertation, <em>Effective and Efficient Machine Learning for Sensor Data: From Wearable Sensing to Earth Observation</em>!</p>
    </article>
    <article class="news-item">
      <time datetime="2026-05">May 2026</time>
      <p>Submitted first-author work on self-supervised geospatial foundation models to ACM SIGSPATIAL.</p>
    </article>
    <article class="news-item">
      <time datetime="2025-10">Oct 2025</time>
      <p>Presented our graph-based keystep recognition paper at the ICCV 2025 Workshop on Scene Graphs and Graph Representation Learning.</p>
    </article>
    <article class="news-item">
      <time datetime="2025-07">Summer 2025</time>
      <p>Consulted for <a href="https://kinesisintegrated.com/">Kinesis Integrated</a> on ML for injury modeling in endurance athletes.</p>
    </article>
    <article class="news-item">
      <time datetime="2025-06">Jun 2025</time>
      <p>Won 1st place (of 20+ teams) in the Ego-Exo4D Keystep Recognition Challenge and gave an invited spotlight talk at the <a href="https://youtu.be/iz2Flo4ZVm4?t=2472">CVPR Egocentric Vision Workshop</a>.</p>
    </article>
    <article class="news-item">
      <time datetime="2024-02">Feb 2024</time>
      <p>Presented <em>OptiBreathe</em> at ACM HotMobile 2024 and filed two related patent applications with Nokia Bell Labs.</p>
    </article>
    <article class="news-item">
      <time datetime="2023-06">Summer 2023</time>
      <p>Research intern in the Pervasive Systems group at <a href="https://www.nokia.com/bell-labs/research/sdsr/device-software/">Nokia Bell Labs</a> (Cambridge, UK), working on respiratory sensing from in-ear PPG.</p>
    </article>
    <article class="news-item">
      <time datetime="2023-04">Apr 2023</time>
      <p>Awarded NSF IUCRC funding for our proposal on graph representation learning, launching a 2.5-year collaboration with <a href="https://community.intel.com/t5/Blogs/Tech-Innovation/Artificial-Intelligence-AI/Improving-Video-Understanding-Through-Graph-Based-AI-for-Better/post/1720916">Intel Labs</a>.</p>
    </article>
    <article class="news-item">
      <time datetime="2022-06">Summer 2022</time>
      <p>Data engineering intern at <a href="https://www.stryd.com/us/en">Stryd</a> (Boulder, CO), where I built and deployed injury-risk models for runners.</p>
    </article>
    <article class="news-item">
      <time datetime="Summer 2020">2020 and 2021</time>
      <p>Data science intern at Johns Hopkins Applied Physics Laboratory, building disability-claims analytics now in use by SSA claims courts.</p>
    </article>
  </div>
</section>

<section class="home-section" id="publications" aria-labelledby="publications-title">
  <div class="section-heading-row">
    <div>
      <h2 id="publications-title">Publications</h2>
    </div>
  </div>
  <div class="publication-list" aria-label="Publications">
    <article class="publication-item publication-item--with-thumb" id="publication-geospatial">
      <div class="publication-thumb">
        <img src="{{ '/images/foundation-model-thumbnail.png' | relative_url }}" alt="Teaser thumbnail for self-supervised geospatial transfer work">
      </div>
      <div class="publication-body">
        <p class="publication-authors"><span class="publication-author-highlight">Julia L. Romero</span>, Q. Lv, M. Karimzadeh.</p>
        <div class="publication-title-row">
          <p class="publication-title">&ldquo;How do Self-Supervised Remote Sensing Vision Models Transfer to Downstream Tasks?&rdquo;</p>
          <div class="publication-links" aria-label="Publication links">
            <span class="publication-link publication-link--disabled" aria-label="Arxiv paper coming soon" data-label="Arxiv paper coming soon">
              <svg class="publication-link__icon" viewBox="0 0 24 24" aria-hidden="true" focusable="false">
                <path d="M14.25 2.25H6A2.25 2.25 0 0 0 3.75 4.5v15A2.25 2.25 0 0 0 6 21.75h12A2.25 2.25 0 0 0 20.25 19.5V8.25L14.25 2.25Zm-.75 1.81 4.94 4.94H15A1.5 1.5 0 0 1 13.5 7.5V4.06Zm4.5 16.19H6a.75.75 0 0 1-.75-.75v-15A.75.75 0 0 1 6 3.75h6v3.75A3 3 0 0 0 15 10.5h3.75v9a.75.75 0 0 1-.75.75Z"/>
              </svg>
            </span>
          </div>
        </div>
        <p class="publication-meta">In submission, May 2026.</p>
      </div>
    </article>

    <article class="publication-item publication-item--with-thumb">
      <div class="publication-thumb">
        <img src="{{ '/images/graph-thumbnail.png' | relative_url }}" alt="Teaser thumbnail for graph-based keystep recognition paper">
      </div>
      <div class="publication-body">
        <p class="publication-authors"><span class="publication-author-highlight">Julia L. Romero</span>, K. Min, S. Tripathi, M. Karimzadeh.</p>
        <div class="publication-title-row">
          <p class="publication-title">&ldquo;Graph-Based Multimodal and Multi-view Alignment for Keystep Recognition.&rdquo;</p>
          <div class="publication-links" aria-label="Publication links">
            <a href="https://openaccess.thecvf.com/content/ICCV2025W/SG2RL/papers/Romero_Long-form_Reasoning_for_Keystep_Recognition_using_Graph_Neural_Networks_ICCVW_2025_paper.pdf" class="publication-link" aria-label="Paper link" data-label="Paper">
              <svg class="publication-link__icon" viewBox="0 0 24 24" aria-hidden="true" focusable="false">
                <path d="M14.25 2.25H6A2.25 2.25 0 0 0 3.75 4.5v15A2.25 2.25 0 0 0 6 21.75h12A2.25 2.25 0 0 0 20.25 19.5V8.25L14.25 2.25Zm-.75 1.81 4.94 4.94H15A1.5 1.5 0 0 1 13.5 7.5V4.06Zm4.5 16.19H6a.75.75 0 0 1-.75-.75v-15A.75.75 0 0 1 6 3.75h6v3.75A3 3 0 0 0 15 10.5h3.75v9a.75.75 0 0 1-.75.75Z"/>
              </svg>
            </a>
            <a href="https://github.com/geohai/graphs-for-keystep-recognition" class="publication-link" aria-label="Code link" data-label="Code">
              <svg class="publication-link__icon" viewBox="0 0 24 24" aria-hidden="true" focusable="false">
                <path d="M12 .297c-6.63 0-12 5.373-12 12 0 5.303 3.438 9.8 8.205 11.385.6.113.82-.258.82-.577 0-.285-.01-1.04-.015-2.04-3.338.724-4.042-1.61-4.042-1.61C4.422 18.07 3.633 17.7 3.633 17.7c-1.087-.744.084-.729.084-.729 1.205.084 1.838 1.236 1.838 1.236 1.07 1.835 2.809 1.305 3.495.998.108-.776.417-1.305.76-1.605-2.665-.3-5.466-1.332-5.466-5.93 0-1.31.465-2.38 1.235-3.22-.135-.303-.54-1.523.105-3.176 0 0 1.005-.322 3.3 1.23.96-.267 1.98-.399 3-.405 1.02.006 2.04.138 3 .405 2.28-1.552 3.285-1.23 3.285-1.23.645 1.653.24 2.873.12 3.176.765.84 1.23 1.91 1.23 3.22 0 4.61-2.805 5.625-5.475 5.92.42.36.81 1.096.81 2.22 0 1.606-.015 2.896-.015 3.286 0 .315.21.69.825.57C20.565 22.092 24 17.592 24 12.297c0-6.627-5.373-12-12-12"/>
              </svg>
            </a>
          </div>
        </div>
        <p class="publication-meta">International Conference on Computer Vision Workshops (ICCVW), 2025</p>
        <p class="publication-note">1st place, Ego-Exo4D Keystep Recognition Challenge for Video Understanding</p>
        <p class="publication-note">Invited spotlight talk @ CVPR Egocentric Vision Workshop, 2025</p>
      </div>
    </article>

    <article class="publication-item publication-item--with-thumb">
      <div class="publication-thumb">
        <img src="{{ '/images/optibreathe-thumbnail.png' | relative_url }}" alt="Teaser thumbnail for OptiBreathe paper">
      </div>
      <div class="publication-body">
        <p class="publication-authors"><span class="publication-author-highlight">Julia L. Romero</span>, A. Ferlini, D. Spathis, T. Dang, K. Farrahi, F. Kawsar, A. Montanari.</p>
        <div class="publication-title-row">
          <p class="publication-title">&ldquo;OptiBreathe: An Earable-based PPG System for Continuous Respiration Rate, Breathing Phase, and Tidal Volume Monitoring.&rdquo;</p>
          <div class="publication-links" aria-label="Publication links">
            <a href="https://dl.acm.org/doi/10.1145/3638550.3641136" class="publication-link" aria-label="Paper link" data-label="Paper">
              <svg class="publication-link__icon" viewBox="0 0 24 24" aria-hidden="true" focusable="false">
                <path d="M14.25 2.25H6A2.25 2.25 0 0 0 3.75 4.5v15A2.25 2.25 0 0 0 6 21.75h12A2.25 2.25 0 0 0 20.25 19.5V8.25L14.25 2.25Zm-.75 1.81 4.94 4.94H15A1.5 1.5 0 0 1 13.5 7.5V4.06Zm4.5 16.19H6a.75.75 0 0 1-.75-.75v-15A.75.75 0 0 1 6 3.75h6v3.75A3 3 0 0 0 15 10.5h3.75v9a.75.75 0 0 1-.75.75Z"/>
              </svg>
            </a>
          </div>
        </div>
        <p class="publication-meta">International Workshop on Mobile Computing Systems and Applications (HotMobile), 2024</p>
      </div>
    </article>

    <article class="publication-item publication-item--with-thumb">
      <div class="publication-thumb">
        <img src="{{ '/images/basketball-thumbnail.png' | relative_url }}" alt="Teaser thumbnail for basketball activity recognition paper">
      </div>
      <div class="publication-body">
        <p class="publication-authors">A. Hoelzemann, <span class="publication-author-highlight">Julia L. Romero</span>, M. Bock, K. Van Laerhoven, Q. Lv.</p>
        <div class="publication-title-row">
          <p class="publication-title">&ldquo;Hang-Time HAR: A Dataset for Basketball Activity Recognition Using Wrist-Worn Inertial Sensors.&rdquo;</p>
          <div class="publication-links" aria-label="Publication links">
            <a href="https://www.mdpi.com/1424-8220/23/13/5879" class="publication-link" aria-label="Paper link" data-label="Paper">
              <svg class="publication-link__icon" viewBox="0 0 24 24" aria-hidden="true" focusable="false">
                <path d="M14.25 2.25H6A2.25 2.25 0 0 0 3.75 4.5v15A2.25 2.25 0 0 0 6 21.75h12A2.25 2.25 0 0 0 20.25 19.5V8.25L14.25 2.25Zm-.75 1.81 4.94 4.94H15A1.5 1.5 0 0 1 13.5 7.5V4.06Zm4.5 16.19H6a.75.75 0 0 1-.75-.75v-15A.75.75 0 0 1 6 3.75h6v3.75A3 3 0 0 0 15 10.5h3.75v9a.75.75 0 0 1-.75.75Z"/>
              </svg>
            </a>
          </div>
        </div>
        <p class="publication-meta">Sensors, 2023</p>
      </div>
    </article>

    <article class="publication-item publication-item--with-thumb">
      <div class="publication-thumb">
        <img src="{{ '/images/activity-thumbnail.png' | relative_url }}" alt="Teaser thumbnail for physical activity habits paper">
      </div>
      <div class="publication-body">
        <p class="publication-authors"><span class="publication-author-highlight">Julia L. Romero</span>, Q. Lv.</p>
        <div class="publication-title-row">
          <p class="publication-title">&ldquo;Global Impact of the COVID-19 Pandemic on Physical Activity Habits of Competitive Runners: An Analysis of Wearable Device Data.&rdquo;</p>
          <div class="publication-links" aria-label="Publication links">
            <a href="https://www.mdpi.com/1660-4601/19/19/12933" class="publication-link" aria-label="Paper link" data-label="Paper">
              <svg class="publication-link__icon" viewBox="0 0 24 24" aria-hidden="true" focusable="false">
                <path d="M14.25 2.25H6A2.25 2.25 0 0 0 3.75 4.5v15A2.25 2.25 0 0 0 6 21.75h12A2.25 2.25 0 0 0 20.25 19.5V8.25L14.25 2.25Zm-.75 1.81 4.94 4.94H15A1.5 1.5 0 0 1 13.5 7.5V4.06Zm4.5 16.19H6a.75.75 0 0 1-.75-.75v-15A.75.75 0 0 1 6 3.75h6v3.75A3 3 0 0 0 15 10.5h3.75v9a.75.75 0 0 1-.75.75Z"/>
              </svg>
            </a>
          </div>
        </div>
        <p class="publication-meta">International Journal of Environmental Research and Public Health, 2022</p>
      </div>
    </article>

    <p class="publication-footer">Full list on <a href="{% if site.author.googlescholar %}{{ site.author.googlescholar }}{% else %}#{% endif %}">Google Scholar</a>.</p>
  </div>
</section>

<section class="home-section" id="patents" aria-labelledby="patents-title">
  <div class="section-heading-row">
    <div>
      <h2 id="patents-title">Patents</h2>
    </div>
  </div>
  <div class="publication-list" aria-label="Patents">
    <article class="publication-item">
      <p class="publication-title"><a href="https://patents.google.com/patent/GB202400386D0/en?q=(Context-Aware+Adaptive+Control+of+Sound+Leakage)&amp;oq=Context-Aware+Adaptive+Control+of+Sound+Leakage">Context-Aware Adaptive Control of Sound Leakage.</a></p>
      <p class="publication-authors">Julia Lee Romero, Andrea Ferlini.</p>
      <p class="publication-meta">GB Patent Application No. 2400386.5 · Filed January 2024 with Nokia Bell Labs · Patent pending</p>
    </article>

    <article class="publication-item">
      <p class="publication-title"><a href="https://patents.google.com/patent/US20250268489A1/en">Biometric Authentication and Device Unlock Using Pulse Time and Interbeat Interval.</a></p>
      <p class="publication-authors">Julia Lee Romero, Andrea Ferlini, Alessandro Montanari.</p>
      <p class="publication-meta">GB Patent Application No. 2402508.2 · Filed February 2024 with Nokia Bell Labs · Patent pending</p>
    </article>
  </div>
</section>

<section class="home-section" id="personal" aria-labelledby="personal-title">
  <div class="section-heading-row">
    <div>
      <h2 id="personal-title">Personal</h2>
    </div>
  </div>
  <div class="about-copy">
    <p>In my free time I enjoy training for <a href="https://ultrasignup.com/results_participant.aspx?fname=Julia&amp;lname=Romero">ultramarathons</a>, skiing, playing soccer, and being in nature. I also enjoy playing instruments with friends, listening to music, and learning music production software.</p>
  </div>
</section>
  </div>
</div>
