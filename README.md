![Header](https://capsule-render.vercel.app/api?type=waving&color=gradient&height=250&section=header&text=Hy%20La&fontSize=80&animation=fadeIn&fontAlignY=35&desc=Embedded%20%7C%20AI%20%7C%20Edge%20Computing&descAlignY=55&descSize=25)

<p align="center">
  <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=500&size=25&pause=1000&color=2E91E0&center=true&vCenter=true&width=600&lines=Code+is+for+humans+to+read.;Machines+just+execute+it.;Evidence-Based+Engineering." alt="Typing SVG" /></a>
</p>

---

---

### 🚀 About Me
**I bridge the gap between Hardware and Intelligence.**
As a Software Engineer specializing in **Embedded Systems** and **Applied AI**, I build systems that are both robust and smart. My expertise spans from low-level **C/C++** and **Linux** optimizations to deploying **Computer Vision** and **LLM/RAG** solutions. I focus on precision, clarity, and bringing intelligence to the edge.

<p align="left"> 
  <img src="https://komarev.com/ghpvc/?username=LahyUS&label=Profile%20Views&color=0e75b6&style=flat" alt="Profile Views" /> 
</p>

- 🔭 I’m currently working on **High-Performance IP Camera Systems**.
- 🌱 I’m currently exploring **Applied AI in Embedded Systems**.
- 💬 Ask me about **Embedded C, IoT Protocols, and Multimedia Pipelines**.

---

---

### 🛠️ Tech Stack & Arsenal

| Core Languages | Embedded & System | DevOps & Tools | Protocols | AI & Data |
| :--- | :--- | :--- | :--- | :--- |
| ![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white) <br> ![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=c%2B%2B&logoColor=white) <br> ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) | ![ARM Linux](https://img.shields.io/badge/ARM_Linux-FCC624?style=flat&logo=linux&logoColor=black) <br> ![Buildroot](https://img.shields.io/badge/Buildroot-292D3E?style=flat&logo=buildroot&logoColor=white) <br> ![FFmpeg](https://img.shields.io/badge/FFmpeg-007808?style=flat&logo=ffmpeg&logoColor=white) | ![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat&logo=cmake&logoColor=white) <br> ![Make](https://img.shields.io/badge/GNU_Make-A42E2B?style=flat&logo=gnu&logoColor=white) <br> ![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat&logo=jira&logoColor=white) | ![MQTT](https://img.shields.io/badge/MQTT-3C5280?style=flat&logo=mqtt&logoColor=white) <br> ![ONVIF](https://img.shields.io/badge/ONVIF-4B4B4B?style=flat&logo=camera&logoColor=white) <br> ![SSL](https://img.shields.io/badge/OpenSSL-721412?style=flat&logo=openssl&logoColor=white) | ![HuggingFace](https://img.shields.io/badge/-HuggingFace-FDEE21?style=flat&logo=HuggingFace&logoColor=black) <br> ![Computer Vision](https://img.shields.io/badge/Computer_Vision-5C5C5C?style=flat&logo=opencv&logoColor=white) <br> ![PaddleOCR](https://img.shields.io/badge/PaddleOCR-000000?style=flat&logo=paddlepaddle&logoColor=white) |

---

### 📂 Private Engineering Showcase

#### 1. 📡 AmpacsSDK: Modular IoT Framework
> **Role**: Core SDK Developer | **Focus**: System Integration, MQTT, HAL
>
> ![Status](https://img.shields.io/badge/Status-Active_Development-success) ![Commits](https://img.shields.io/badge/Evidence-44_Commits-blue)
>
> 🛠️ **Stack**: ![C](https://img.shields.io/badge/-C-00599C?logo=c&logoColor=white) ![MQTT](https://img.shields.io/badge/-MQTT-3C5280?logo=mqtt&logoColor=white) ![Paho](https://img.shields.io/badge/-Paho-ECD53F) ![PlantUML](https://img.shields.io/badge/-PlantUML-blue)
>
> 📝 **Description**: A modular IoT Framework SDK designed for embedded devices, providing backend-agnostic MQTT connectivity, portable HAL abstractions, and dynamic command handling.

**Key Engineering Contributions**:
*   🧩 **Backend-Agnostic Architecture**: Decoupled the MQTTS library from Paho/EMQX using opaque handles and weak symbols, allowing seamless backend switching.
*   🌙 **Portable Day/Night SDK**: Designed a HAL-based `dnm_api` module that abstracts hardware specifics, enabling standard integration across different chipsets.
*   ⚡ **Dynamic Command Handling**: Implemented a callback manager system for runtime registration of custom MQTT command handlers.

---

#### 2. 🎥 IP_Cam: High-Performance AV Pipeline
> **Role**: Core System Engineer | **Focus**: Rainbow Capture, Opus, Buildroot
>
> ![Status](https://img.shields.io/badge/Status-Production_Ready-success) ![Commits](https://img.shields.io/badge/Evidence-32_Commits-blue)
>
> 🛠️ **Stack**: ![C](https://img.shields.io/badge/-C-00599C?logo=c&logoColor=white) ![Buildroot](https://img.shields.io/badge/-Buildroot-292D3E?logo=buildroot&logoColor=white) ![Opus](https://img.shields.io/badge/-Opus-black) ![CMake](https://img.shields.io/badge/-CMake-064F8C?logo=cmake&logoColor=white)
>
> 📝 **Description**: A high-performance audio/video pipeline for IP Cameras, featuring low-latency Opus audio integration and a robust HAL-based architecture for Day/Night mode control.

**Key Engineering Contributions**:
*   🔊 **Low-Latency Audio**: Integrated Opus codec and restored the full **Resampler → Mixer → Playback** pipeline for multi-source mixing.
*   🏗️ **Hardware Abstraction**: Migrated the Day/Night mode logic to a HAL architecture (`daynight_hal`), isolating it from the Vendor's SDK for improved testability.
*   📦 **Build System Optimization**: Refined **Buildroot** configurations and **CMake** logic to support modular feature toggling.

---

#### 3. 🌐 Onvif: Interoperability Standard
> **Role**: Protocol Engineer | **Focus**: Profile S/T, SOAP, System Services
>
> ![Status](https://img.shields.io/badge/Status-Stable-success) ![Commits](https://img.shields.io/badge/Evidence-15_Commits-blue)
>
> 🛠️ **Stack**: ![C++](https://img.shields.io/badge/-C++-00599C?logo=c%2B%2B&logoColor=white) ![gSOAP](https://img.shields.io/badge/-gSOAP-blue) ![ONVIF](https://img.shields.io/badge/-ONVIF-4B4B4B?logo=camera&logoColor=white) ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white)
>
> 📝 **Description**: Implementation of ONVIF Profile S/T standards for IP Cameras, ensuring interoperability through reliable SOAP services for imaging and system management.

**Key Engineering Contributions**:
*   🖼️ **Imaging Service Reliability**: Resolved critical profile lookup bugs in `GetImagingSettings` and synchronized IR cut filter state between ONVIF, ISP, and NVRAM.
*   🕒 **Time Synchronization**: Implemented `SetSystemDateAndTime` compliant with ONVIF specs using precise `clock_settime` syscalls.

---

#### 4. 🔐 SSL-FFPlayer: Secure Media Playback
> **Role**: Multimedia Engineer | **Focus**: FFmpeg, SDL, OpenSSL
>
> ![Status](https://img.shields.io/badge/Status-Maintenance-yellow) ![Commits](https://img.shields.io/badge/Evidence-9_Commits-blue) ![Solo](https://img.shields.io/badge/Role-Solo_Developer-red)
>
> 🛠️ **Stack**: ![C](https://img.shields.io/badge/-C-00599C?logo=c&logoColor=white) ![FFmpeg](https://img.shields.io/badge/-FFmpeg-007808?logo=ffmpeg&logoColor=white) ![SDL2](https://img.shields.io/badge/-SDL2-black) ![OpenSSL](https://img.shields.io/badge/-OpenSSL-721412?logo=openssl&logoColor=white)
>
> 📝 **Description**: A secure, low-latency media player built with FFmpeg and SDL, optimized for synchronized audio/video playback over encrypted SSL streams.

**Key Engineering Contributions**:
*   ⏱️ **A/V Synchronization**: Re-engineered sync logic to slave video frames to the audio master clock, achieving lip-sync accuracy for low-latency streams.
*   🔒 **Secure Streaming**: Integrated Client Certificate authentication directly into the FFmpeg transport layer.


#### 5. 🤖 R-MCAL Chatbot: AUTOSAR Assistant
> **Role**: Personal Project | **Focus**: RAG, LLM Optimization, Deployment
>
> ![Status](https://img.shields.io/badge/Status-Prototype-orange) ![Commits](https://img.shields.io/badge/Evidence-6_Commits-blue)
>
> 🛠️ **Stack**: ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) ![LangChain](https://img.shields.io/badge/-LangChain-1C3C3C?logo=langchain&logoColor=white) ![Transformers](https://img.shields.io/badge/-Transformers-FFD21E?logo=huggingface&logoColor=black) ![Gradio](https://img.shields.io/badge/-Gradio-FD7900?logo=gradio&logoColor=white) ![Flask](https://img.shields.io/badge/-Flask-000000?logo=flask&logoColor=white) ![MySQL](https://img.shields.io/badge/-MySQL-4479A1?logo=mysql&logoColor=white) ![Jupyter](https://img.shields.io/badge/-Jupyter-F37626?logo=jupyter&logoColor=white) ![NLP](https://img.shields.io/badge/-NLP-black)
>
> 📝 **Description**: An intelligent RAG-based chatbot assistant trained on complex AUTOSAR MCAL specifications to answer technical queries and accelerate development.

**Key Engineering Contributions**:
*   🧠 **RAG System**: Built a Retrieval-Augmented Generation pipeline to query complex **AUTOSAR** MCAL specifications.
*   ⚡ **Optimization & Research**: Researched and optimized model performance for domain-specific technical documentation.
*   🚀 **Deployment**: Managed end-to-end deployment of the chatbot assistant.

#### 6. 🚗 Renesas OTA: FOTA Installer (Former Company)
> **Role**: Embedded Software Engineer | **Focus**: SOTA/FOTA, Xen Hypervisor, Reliability
>
> ![Status](https://img.shields.io/badge/Status-Delivered-success) **[Renesas Design Vietnam]**
>
> 🛠️ **Stack**: ![C](https://img.shields.io/badge/-C-00599C?logo=c&logoColor=white) ![Shell](https://img.shields.io/badge/-Shell-121011?logo=gnu-bash&logoColor=white) ![Linux](https://img.shields.io/badge/-Linux-FCC624?logo=linux&logoColor=black) ![Xen](https://img.shields.io/badge/-Xen_Hypervisor-black)
>
> 📝 **Description**: Developed a fail-safe Firmware Over-The-Air (FOTA) installer for Spider S4/S4N automotive boards, managing eMMC/Flash updates with automatic fallback and cloud triggering.

**Key Engineering Contributions**:
*   🔄 **Fail-Safe Updates**: Implemented a robust fallback mechanism to revert firmware to a previous stable version upon update failure.
*   📦 **Binary Frame Design**: Designed a custom data frame protocol for secure reliability verification (checksum, length, data) of update binaries.
*   🚦 **Dual Memory Support**: Engineered the installer to support both eMMC and Flash memory targets.
*   📜 **Automation**: Wrote comprehensive Shell scripts to orchestrate the update process seamlessly on Linux/Xen environments.

---

### 🌟 Personal, Freelance & Academic

#### 7. 🏥 ClinicPRO: Desktop Management App (Freelance)
> **Role**: Full Stack Developer | **Focus**: Python, Custom Widgets, Layout, Backup
>
> ![Status](https://img.shields.io/badge/Status-Delivered-success) ![Commits](https://img.shields.io/badge/Evidence-7_Commits-blue) ![Solo](https://img.shields.io/badge/Role-Solo_Developer-red)
>
> 🛠️ **Stack**: ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) ![CustomTkinter](https://img.shields.io/badge/-CustomTkinter-blue) ![PaddleOCR](https://img.shields.io/badge/-PaddleOCR-000000?logo=paddlepaddle&logoColor=white) ![SQLite](https://img.shields.io/badge/-SQLite-003B57?logo=sqlite&logoColor=white)
>
> 📝 **Description**: A comprehensive desktop management application for clinics, featuring OCR-based record processing, automated cloud backups, and financial reporting.

**Key Engineering Contributions**:
*   👁️ **OCR Integration**: Implemented smart record importing using **PaddleOCR** and Tesseract with spatial parsing for Vietnamese medical forms.
*   ☁️ **Resilient Data**: Built an automated backup system with daily rotation and secondary cloud sync support.
*   📄 **PDF Engine**: Developed a robust PDF report generator using ReportLab to handle complex layouts and financial tables.


#### 8. 🧠 Video Anomaly Detection (Collaboration)
> **Role**: AI Engineer (Co-Author) | **Focus**: Computer Vision, Evaluation Logic
>
> ![Status](https://img.shields.io/badge/Status-Research-purple) ![Commits](https://img.shields.io/badge/Evidence-11_Commits-blue)
>
> 🛠️ **Stack**: ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) ![OpenCV](https://img.shields.io/badge/-OpenCV-5C5C5C?logo=opencv&logoColor=white) ![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?logo=pytorch&logoColor=white) ![NumPy](https://img.shields.io/badge/-NumPy-013243?logo=numpy&logoColor=white)
>
> 📝 **Description**: Collaborated research on detecting anomalies in surveillance video, focusing on pixel-level evaluation metric implementation and parameter tuning.
>
> 🔗 **Remote Repo**: [anhhuu/anodetection-aemem](https://github.com/anhhuu/anodetection-aemem)

**Key Engineering Contributions**:
*   📉 **Pixel-Level Eval**: Implemented fine-grained evaluation metrics for anomaly localization.
*   ⚙️ **Optimization**: Tuned Image Difference thresholds to improve detection rates on the **UCSD Ped2** dataset.

![Anomaly Detection Demo](Knowledge_Base/Anomaly_Detection/docs/avenue_demo.png)

#### 9. 🔢 Big Number: C++ High-Precision Library (Academic)
> **Role**: Academic Project | **Focus**: QInt/QFloat, Operator Overloading, Calculator
>
> 🛠️ **Stack**: ![C++](https://img.shields.io/badge/-C++-00599C?logo=c%2B%2B&logoColor=white) ![Algorithms](https://img.shields.io/badge/-Algorithms-red)
>
> 📝 **Description**: A C++ library implementing 16-byte `QInt` and `QFloat` data types to handle numbers exceeding standard limits, featuring a calculator application demonstration.
>
> 🔗 **Remote Repo**: [LahyUS/Big-Number](https://github.com/LahyUS/Big-Number)

---

### 📫 Connect with Me
<p align="center">
  <a href="https://www.linkedin.com/in/nhat-hy-la-40b379221/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <br>
  <b>📧 Email: lahyus7399@gmail.com</b>
  <br>
  <b>📞 Phone: (+84) 836 476 472</b>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer"/>
</p>
