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

<span class='anchor' id='About-me'></span>
# 🙋‍♀️ About me
Hi! I’m Evelyn, a Master’s student in the Machine Learning and Data Science (MLDS) program at Northwestern University, previously graduating from UC San Diego with dual degree in Data Science and Mathematics & Economics. I’m passionate about leveraging data analytics and domain expertise to build AI solutions that are thoughtful, responsible, and human-centered.

I am seeking a 2026 Summer Internship as a Data Scientist, Machine Learning Engineer, Data Analyst, or Business Intelligence Engineer. Driven by curiosity and a commitment to lifelong learning, I continuously explore new technologies, frameworks, and methodologies to stay at the forefront of AI and machine learning innovation.

Please feel free to reach out at xinqihuang2026@u.northwestern.edu if my experience and skill set align with opportunities you’d like to discuss.

When I’m not deep in data, you can find me enjoying a good movie, watching sunsets wherever I am (La Jolla Shores is still my favorite!), or giving myself a fresh manicure. I’m all about finding joy in the little things and keeping life vibrant and fun! ✨

<span class='anchor' id='Educations'></span>
# 📖 Educations
- *2025.09 - 2026.12*: Machine Learning and Data Science (MLDS), Northwestern University
- *2021.09 - 2025.06*: Bachelor of Science in Data Science and Joint Mathematics–Economics, UC San Diego



<span class='anchor' id='Internship'></span>
# 💻📝 Internships and Experiences
- *2025.09 - Present*: Data Scientist (Industry Practicum) at Mintel
- *2024.07 - 2024.09*: Data Science Intern at [POIZON](https://www.poizon.com/?srsltid=AfmBOor8QRby4vG1Z0xDrKSiUV0dd-SEuqfu7PAvYC8Wv3ocI-tVeOPU)
- *2023.08 - 2023.10* : Business Analyst Intern at [Arthur D. Little](https://www.adlittle.com/en)


<span class='anchor' id='Research_and_Publications'></span>
# 🔬 Research and Publications
- *2024.04 - 2025.07*: Machine Learning Research Assistant at [MixLab @ UCSD HDSI](https://maitrix.org/about/)
{% raw %}
- *2024.01 - 2024.04* : sUndergraduate Researcher at [The Economic Research Lab](https://economics.ucsd.edu/undergraduate-program/resources/undergraduate-graduate-research-lab/undergrad-profiles/huang-x.html)

<p><strong>Do Vision-Language Models Have an Internal World Model? Towards an Atomic Evaluation</strong></p>
<p>Qiyue Gao*, Xinyu Pi*, Kevin Liu, Junrong Chen, Ruolan Yang, <strong>Xinqi Huang</strong>, Xinyu Fang, Lu Sun, Gautham Kishore, Bo Ai, Stone Tao, Mengyang Liu, Jiaxi Yang, Chao-Jung Lai,
Chuanyang Jin, Jiannan Xiang, Benhao Huang, Zeming Chen,
David Danks, Hao Su, Tianmin Shu, Ziqiao Ma, Lianhui Qin, Zhiting Hu </p>
<p>ACL 2025 Findings</p>
<p><a href="https://arxiv.org/abs/2506.21876" target="_blank">arXiv:2506.21876</a></p>
<p><a href="https://wm-abench.maitrix.org/" target="_blank">Website</a></p>
{% endraw %}

<p><strong>PAN: A World Model for General, Interactable, and Long-Horizon
World Simulation</strong></p>
<p>PAN Team, Institute of Foundation Models, as Contributors to the evaluation section</p>
<p><a href="https://arxiv.org/abs/2511.09057" paper</a></p>
<p><a href="https://ifm.mbzuai.ac.ae/pan/" target="_blank">Pan World Model Website</a></p>


 
<span class='anchor' id='Project'></span>
# 🧠 Projects

<div class='paper-box' >
  <div class='paper-box-image'>
    <div>
      <img src='images/vlm.png' alt="Project Image" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  [VLM Benchmark: WM-ABench](https://wm-abench.maitrix.org/)
  
  **Using Maniskill simualtor, we generated 37K+ image-based Q&A scenarios for benchmarking 11 commercial and open-source Vision-Language Models (including GPT, Gemini, Claude, and Qwen) perception and prediction capability for downstream robotic manipulation tasks.**

  [link to video demo](https://www.youtube.com/watch?v=Yek6PInUoWY&t=2s)

  [link to dataset](https://huggingface.co/datasets/maitrix-org/WM-ABench)

  [link to code](https://github.com/gaoq111/benchmark_maniskill2)

  </div>
</div>


<div class='paper-box' >
  <div class='paper-box-image'>
    <div>
      <img src='images/ebird.png' alt="Project Image" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  ETL and Data Visualization: Ebird spot map
  
  **Explore real-time bird migration through an automated data pipeline! Using ebird api, Apache Airflow, PostgreSQL, Docker, SQL, HTML, Streamlit and Prediction Modeling, we built an end-to-end system delivering up-to-date bird location insights with role-specific visualizations and a reliable two-stage deployment.**

  [link to github](https://github.com/evelynh037/ebird-data-analysis)

  [Streamlit app demo](https://ebird-data-analysis-79q4xqgr2x6fgjkgfonpzs.streamlit.app )

  [Demo map](https://evelynh037.github.io/ebird-data-analysis/)

  </div>
</div>


<div class='paper-box' >
  <div class='paper-box-image'>
    <div>
      <img src='images/capstone_cover.png' alt="Project Image" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  [Causal Discovery and Deep learning: Ensemble Deep Learning for Stock Return Prediction in Volatile Markets](https://acai1031.github.io/DSC180B-Capstone-Website/)
  

  Financial market volatility, driven by economic conditions, corporate shocks, and investor behavior, makes stock return forecasting highly challenging.

  **Traditional methods, such as macroeconomic analysis and sentiment analysis, have limitations in capturing the complex relationships between stock returns and external factors.**

  **Our goal is to develop an advanced stock return prediction framework that leverages causal discovery algorithms to enhance interpretability and accuracy.**

  [link to github](https://github.com/VivianZhao12/CAPSTONE-stockreturn)

  [link to report](https://acai1031.github.io/DSC180B-Capstone-Website/docs/report.pdf)
  
  [link to poster](https://acai1031.github.io/DSC180B-Capstone-Website/docs/poster.pdf)

  </div>
</div>


<div class='paper-box' >
  <div class='paper-box-image'>
    <div>
      <img src='images/twitter_project_cover.jpg' alt="Project Image" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  [Storytelling Visualization: Campaigning on Twitter](https://evelynh037.github.io/dsc106-Campaigning-on-Twitter/)
  

  **Explore the "word war" of the 2016 election through this storytelling project! Using NLP, sentiment analysis, and interactive visualizations, we uncovered how candidates turned Twitter into a campaign battlefield, shaping the outcome one tweet at a time.**

  [A Demo](https://youtu.be/8z-ffypoqEg?feature=shared)

  </div>
</div>

<div class='paper-box'>
<div class='paper-box-image'>
    <div>
      <img src='images/sentiment_cover.jpeg' alt="Project Image" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  [Predictive task: Advancing Multimodal Sentiment Analysis through Enhanced Sarcasm Detection](https://github.com/VivianZhao12/Multimodal-Sentiment-Analysis-with-Sarcasm-Detection/blob/cc3cc0e82663c2637f261e495aa2daccd7a6c400/DSC190__MLFL_Sentiment_Detection.pdf)
  
  **Sarcasm Hard to Catch? Not Anymore! This project combines text and audio to detect sarcasm, making sentiment analysis easier. We thoughtfully designed every step, from data collection and feature engineering to model building. With our sarcasm detection model, we’ve cracked the code of complex emotions. Because sometimes, tone says it all!**

  </div>
</div>

<div class='paper-box'>
<div class='paper-box-image'>
    <div>
      <img src='images/causal_cover.jpg' alt="Project Image" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  [Casual Discovery: Algorithm Comparison on Simulated Mental Health and Remote Work data ](https://github.com/VivianZhao12/CAPSTONE-Causal-Inference-between-Remote-Work-and-Mental-Health/blob/main/docs/Q1_final_report.pdf)

  **Dive into this project to discover how well different causal algorithms uncover relationships between variables!  Explore how a person's work enviroment, daily habits and mental health connect in our simulated dataset.**

  </div>
</div>

<div class='paper-box'>
<div class='paper-box-image'>
    <div>
      <img src='images/car_cover.webp' alt="Project Image" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  [Data Minning: Used Car Price Prediction](https://github.com/vickyli1015/DSC148_Final_Project/blob/b977119971e14d0452b6911bc472a0ffb7479124/dsc148_final__3_.pdf)
  
  **Ever wondered what drives the price of a second-hand car? We built an XGB Regressor that beat baseline models by over 50% in RMSE. From mileage to color quirks, we unraveled the secrets behind used car pricing with data minning! 🚗✨**

  </div>
</div>


<div class='paper-box'>
<div class='paper-box-image'>
    <div>
      <img src='images/city_name_cover.png' alt="Project Image" width="100%">
    </div>
  </div>
  <div class='paper-box-text' markdown="1">

  [Storytelling Visualization: Pattern of US City Names](https://fjiang316.github.io/dsc106-project3/)

  **Discover how US cities got their names from around the world! Explore migration and immigration patterns through the checkboxes, hover to the points for details, and read the story to see how history shaped these connections.**

  </div>
</div>
Explore more projects in [my GitHub page! ](https://github.com/evelynh037)
Dive in and join me as I continue creating, learning, and growing! 🚀✨


<span class='anchor' id='Something'></span>
# 👀 Something else
<section id="something-else" style="background-color:rgb(255, 255, 255); padding: 0em 0em; font-family: 'Arial', sans-serif;">
    <h2></h2>
    <p > </p>
    <div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 2em; max-width:900px; margin: 0 auto;">
        <!-- First Card -->
        <div style="background-color: white; border-radius: 10px; box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1); overflow: hidden; transition: transform 0.3s ease, box-shadow 0.3s ease;">
            <a href="/_pages/sunset.html" style="text-decoration: none; color: inherit;">
                <img src="images/sunset_cover.jpeg" alt="Sunset" style="width: 100%; display: block;">
                <div style="padding: 1.5em; text-align: center;">
                    <h3 style="font-size: 1.5em; color: #333;">🌅 Sunsets</h3>
                    <!-- <p style="color: #777; font-size: 1em;">Experience the moments through my lens</p> -->
                </div>
            </a>
        </div>
        <!-- Second Card -->
        <div style="background-color: white; border-radius: 10px; box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1); overflow: hidden; transition: transform 0.3s ease, box-shadow 0.3s ease;">
            <a href="/_pages/nail.html" style="text-decoration: none; color: inherit;">
                <img src="images/nail_cover.jpeg" alt="Nail Art" style="width: 100%; display: block;">
                <div style="padding: 1.5em; text-align: center;">
                    <h3 style="font-size: 1.5em; color: #333;">💅 Nail Art</h3>
                    <!-- <p style="color: #777; font-size: 1em;"> Find the Artistic Side of Me</p> -->
                </div>
            </a>
        </div>
        <div style="background-color: white; border-radius: 5px; box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1); overflow: hidden; transition: transform 0.3s ease, box-shadow 0.3s ease;">
            <a href="/_pages/piano.html" style="text-decoration: none; color: inherit;">
                <img src="images/music_cover.jpeg" alt="Nail Art" style="width: 100%; display: block;">
                <div style="padding: 1.5em; text-align: center;">
                    <h3 style="font-size: 1.5em; color: #333;">🎵 Music Clips </h3>
                    <!-- <p style="color: #777; font-size: 1em;"> Explore the Music Side of Me</p> -->
                </div>
            </a>
        </div>
    </div>
</section>
