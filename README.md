<!-- Replace before publishing: YOUR_FIGMA_LINK, YOUR_FIGMA_LINK_BUG_TRACKER, YOUR_FIGMA_LINK_DEVICE_MONITOR, and the sentiment repo link -->

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=190&section=header&text=Disha%20A&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=AI%20Engineer%20(Fresher)%20%7C%20Computer%20Vision%20%E2%80%A2%20NLP%20%E2%80%A2%20FastAPI%20%E2%80%A2%20React&descSize=18&descAlignY=58" alt="Disha A banner"/>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&duration=3000&pause=1000&color=6366F1&center=true&vCenter=true&width=700&lines=Building+and+serving+AI+models;Computer+Vision+%7C+NLP+%7C+FastAPI+%7C+Docker;React+dashboards+for+model+outputs;Honest+evaluation+and+clear+documentation" alt="Typing animation"/>
</p>

<p align="center">
  📍 Bengaluru, India &nbsp;•&nbsp; 🎓 BCA 2026 (CGPA 7.85) &nbsp;•&nbsp; 🟢 Open to AI Engineer and Software Engineer roles (fresher)
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/disha-a-85b92934b/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:dishagowda154@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://github.com/dishagowda145?tab=repositories"><img src="https://img.shields.io/badge/Projects-181717?style=for-the-badge&logo=github&logoColor=white" alt="Projects"/></a>
  <a href="YOUR_FIGMA_LINK"><img src="https://img.shields.io/badge/Figma-Designs-F24E1E?style=for-the-badge&logo=figma&logoColor=white" alt="Figma designs"/></a>
</p>

---

## 👩‍💻 About me

I'm a 2026 BCA graduate and Python full-stack developer moving into *AI engineering*. I like taking a model from a notebook idea to something people can actually use: preprocessing, training, evaluation, an API, a container and a simple interface.

- 👁️ Fine-tuned a *Vision Transformer* for real-time face mask detection, served with *FastAPI* and packaged with *Docker*
- 💬 Built an *NLP pipeline* for movie-tweet sentiment: TF-IDF features, six scikit-learn models, proper held-out evaluation
- ⚛️ Built *React* interfaces and *REST APIs* (Flask, Django) that can show model outputs in a dashboard
- 🧪 Evaluate honestly: I caught a misleading 100% score caused by testing on training data and fixed the split
- 🐞 Interned as a *Python Full Stack Developer*: Django, REST APIs and SQL in an agile team
- 📝 I document what I build so teammates can pick it up quickly

---

## 🤖 AI projects

<table>
<tr>
<td width="50%" valign="top">

### 😷 [Face Mask Detection](https://github.com/dishagowda145/face-mask-detection-system)
Vision Transformer OpenCV Flask FastAPI Docker

Detects whether a person is wearing a mask from a live webcam stream, an uploaded image or an uploaded video.

- 🧠 Fine-tuned a pretrained *Vision Transformer (ViT)* for mask / no-mask classification
- 🎥 *Flask* web app with live webcam, image and video inference using *OpenCV*
- ⚡ *FastAPI* endpoints that serve the model for other apps to call
- 🐳 *Docker* for a reproducible setup
- 📈 Results: add your accuracy and dataset here

[![Code](https://img.shields.io/badge/GitHub-Code-181717?logo=github&logoColor=white)](https://github.com/dishagowda145/face-mask-detection-system)

</td>
<td width="50%" valign="top">

### 🎬 [Movie Tweet Sentiment Analysis](https://github.com/dishagowda145?tab=repositories)
Python scikit-learn TF-IDF VADER Pandas

Classifies movie tweets as positive, negative or neutral and compares classical ML models.

- 🧹 Text cleaning, VADER labelling and *TF-IDF* feature extraction
- 📊 Compared six models (Logistic Regression, SVM, Naive Bayes, Random Forest, Decision Tree, KNN) using accuracy, precision, recall, F1 and a confusion matrix
- 🏆 *KNN* performed best (0.60 accuracy) on a small 80-tweet sample
- ⚠️ Known limits: small dataset and VADER-generated labels; next step is more, human-labelled data and a transformer model
- 🚧 *In progress:* LLM comparison script and an MCP server for the sentiment tool (full LLM evaluation still to run)

[![Code](https://img.shields.io/badge/GitHub-Code-181717?logo=github&logoColor=white)](https://github.com/dishagowda145?tab=repositories)

</td>
</tr>
</table>

---

## 🚀 Full-stack projects

<table>
<tr>
<td width="50%" valign="top">

### 🐞 [Bug Tracker Dashboard](https://github.com/dishagowda145/bug-tracker-dashboard)
React JavaScript Flask REST API SQLite unittest GitHub Actions Figma

Teams sign in, report bugs, assign them and track progress on a dashboard. Admins assign and delete; users update their own or assigned bugs.

- 🔐 Hashed passwords, expiring tokens, parameterised SQL, validation, server-side role checks and login lockout
- 📊 Status cards (Open, In progress, Resolved), filters and priority badges
- ✅ 14 unit tests (including a SQL-injection test) running in CI on every push
- 🎨 Figma mockup, built to match at 1440 px and 375 px

[![Figma](https://img.shields.io/badge/Figma-View_design-F24E1E?logo=figma&logoColor=white)](YOUR_FIGMA_LINK_BUG_TRACKER)
[![Code](https://img.shields.io/badge/GitHub-Code-181717?logo=github&logoColor=white)](https://github.com/dishagowda145/bug-tracker-dashboard)

</td>
<td width="50%" valign="top">

### 📡 [Network Device Monitor](https://github.com/dishagowda145/network-device-monitor)
React JavaScript Flask REST API SQLite unittest GitHub Actions Figma

Checks whether devices or websites are reachable, shows live up/down status and response times, and raises alerts when a device goes down or recovers.

- ⚡ React dashboard on a Flask REST API (7 endpoints) with SQL history
- 🔁 Background TCP checks every 30 seconds; alerts only on state change
- 🔐 Validation, parameterised queries, timeouts and SSRF protection
- ✅ 15 unit tests using a real local TCP server, running in CI

[![Figma](https://img.shields.io/badge/Figma-View_design-F24E1E?logo=figma&logoColor=white)](YOUR_FIGMA_LINK_DEVICE_MONITOR)
[![Code](https://img.shields.io/badge/GitHub-Code-181717?logo=github&logoColor=white)](https://github.com/dishagowda145/network-device-monitor)

</td>
</tr>
</table>

---

## 🔧 Systems projects

| Project | What it shows |
|---|---|
| [Packet Sniffer](https://github.com/dishagowda145/packet-sniffer) (C, raw sockets) | Parses Ethernet, ARP, IPv4, TCP, UDP and ICMP; filtering; bounds-checked parsing |
| [Mini Unix Shell](https://github.com/dishagowda145/mini-shell) (C) | fork/exec, multi-stage pipes, redirection, signals, background jobs |

---

## 🛠️ Tech stack

*AI / ML*<br/>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white"/>
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white"/>
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>

*Back-end, serving and databases*<br/>
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
<img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white"/>
<img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
<img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white"/>

*Front-end*<br/>
<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
<img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white"/>

*Tools*<br/>
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
<img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white"/>

*Also:* REST APIs • Model evaluation (precision, recall, F1, confusion matrix) • Unit testing • CI • Agile • Debugging • Data structures and algorithms

---

## 🎓 Education and experience

- 💼 *Python Full Stack Development Intern*, Robowaves Company Pvt. Ltd. (Feb to Apr 2026)
- 🎓 *BCA*, East West College of Management, Bengaluru (2023 to 2026), CGPA 7.85
- 📜 *Certification:* Python Full Stack Development, SQL (QSpiders)

## 📚 Currently learning

- Computer vision beyond classification: detection, segmentation and multimodal models (CLIP, BLIP)
- Experiment tracking with MLflow and Weights & Biases
- Finishing LLM-based evaluation for my sentiment project
- Serving models with FastAPI and visualising outputs in React dashboards

---

## 📊 GitHub stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=dishagowda145&show_icons=true&theme=tokyonight&hide_border=true" height="165" alt="GitHub stats"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=dishagowda145&layout=compact&theme=tokyonight&hide_border=true" height="165" alt="Top languages"/>
</p>

---

## 🤝 Let's connect

I'm looking for *AI Engineer and entry-level Software Engineer roles* where I can build and ship computer vision and NLP applications and learn from a strong team.

📧 [dishagowda154@gmail.com](mailto:dishagowda154@gmail.com) &nbsp;|&nbsp; 💼 [LinkedIn](https://www.linkedin.com/in/disha-a-85b92934b/)

<p align="center"><i>Build • Evaluate • Serve • Improve</i></p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" alt="footer"/>
