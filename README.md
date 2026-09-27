<p align="center">
  <img src="./assets/header.jpeg" alt="PROJECT.EXE — pixel-art hands reaching toward a retro computer window" width="60%" />
</p>

<h1 align="center">Isaack Joshua</h1>

<p align="center">
  <b>Machine Learning Engineer</b> · PyTorch · TensorFlow · ONNX · LLM agents<br/>
  Dar es Salaam, Tanzania · UTC+3 · Remote worldwide or relocating
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=VT323&size=26&duration=2600&pause=900&color=FFFFFF&center=true&vCenter=true&width=600&height=40&lines=%3E%20training%20models%20that%20leave%20the%20notebook;%3E%20PyTorch%20%E2%86%92%20ONNX%20%E2%86%92%20on-device%20inference;%3E%20medical%20imaging%20%C2%B7%20LLM%20agents%20%C2%B7%20edge%20AI;%3E%20open%20to%20remote%20ML%20%2F%20AI%20roles%20%E2%80%94%20worldwide" />
    <img alt="training models that leave the notebook" src="https://readme-typing-svg.demolab.com?font=VT323&size=26&duration=2600&pause=900&color=000000&center=true&vCenter=true&width=600&height=40&lines=%3E%20training%20models%20that%20leave%20the%20notebook;%3E%20PyTorch%20%E2%86%92%20ONNX%20%E2%86%92%20on-device%20inference;%3E%20medical%20imaging%20%C2%B7%20LLM%20agents%20%C2%B7%20edge%20AI;%3E%20open%20to%20remote%20ML%20%2F%20AI%20roles%20%E2%80%94%20worldwide" />
  </picture>
</p>

<p align="center">
  <a href="https://isaackjoshua.com/Isaack_Joshua_Lukumay_CV.pdf"><img src="https://img.shields.io/badge/%E2%86%93%20Download%20CV-FFFFFF?style=for-the-badge" alt="Download CV" /></a>
  <a href="https://isaackjoshua.com"><img src="https://img.shields.io/badge/isaackjoshua.com-000000?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website" /></a>
  <a href="https://www.linkedin.com/in/isaack-joshua-7277ba29a"><img src="https://img.shields.io/badge/LinkedIn-000000?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:isaackjoshua23@gmail.com"><img src="https://img.shields.io/badge/Email-000000?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

> [!TIP]
> **Hiring?** I'm open to remote **ML / AI engineering** roles worldwide — including ML-heavy backend work — and to relocation. Contract or internship now, full-time from October 2026. EAT (UTC+3) covers the full European workday and US East Coast mornings. Fastest reply: [isaackjoshua23@gmail.com](mailto:isaackjoshua23@gmail.com)

## $ whoami

I'm a machine learning engineer who builds AI systems end to end: **training and fine-tuning models in PyTorch and TensorFlow**, **exporting them to ONNX so inference runs on the device people actually have**, and building the FastAPI services and apps that carry them into production. Most of my work is medical imaging for low-resource clinics — offline, on-device, low-bandwidth.

```python
class Isaack:
    role      = "Machine Learning Engineer"
    now       = "ML Intern @ ETH Lab, MUHAS"
    education = "B.Sc. (Hons) Computer Science, St. Joseph University in Tanzania (2026)"
    based_in  = "Dar es Salaam, Tanzania · UTC+3"
    speaks    = ["English", "Swahili"]
    focus     = ["computer vision", "medical imaging", "on-device inference", "LLM agents"]
    also      = ["FastAPI backends", "model serving", "Linux deployment"]
    open_to   = ["remote (worldwide)", "relocation", "full-time", "contract", "internship-to-hire"]

    def principle(self) -> str:
        return "Models should ship, not just score."
```

## $ cat experience.log

**Machine Learning Intern** — ETH Lab (Emerging Technologies for Healthcare), MUHAS · *Mar 2025 – present*

- Built **Mwana AI**, offline breast-ultrasound classification for Tanzanian clinics — PyTorch → ONNX Runtime → Flutter
- Trained a CNN for **TB/HIV co-infection detection** from chest X-rays, with Grad-CAM explanations and ROC/AUC evaluation across demographic subgroups
- Fine-tuning **RETFound** for diabetic retinopathy; transfer learning on cardiac imaging for dilated-cardiomyopathy prediction
- Structured data for a multi-institution respiratory study (Aga Khan University, University of Warwick, NTLP)

**B.Sc. (Hons) Computer Science** — St. Joseph University in Tanzania · *2023 – 2026*

## $ ls ~/projects --featured

<table>
  <tr>
    <td width="50%" valign="top">

#### [Mwana AI](https://isaackjoshua.com/projects/mwana-ai)
<sub>ML · ON-DEVICE BREAST ULTRASOUND SCREENING</sub>

Classifies lesions into BI-RADS categories, segments the region of interest and writes a structured clinical report — **fully on-device, no cloud after first setup**. Built at the ETH Lab (MUHAS) for clinics where radiologists are scarce.

`PyTorch` `ONNX Runtime` `Flutter`

[Case study →](https://isaackjoshua.com/projects/mwana-ai) · Android + iOS · source private

</td>
    <td width="50%" valign="top">

#### [TB-Classifier](https://github.com/Isaackjoshua/TB-Classifier)
<sub>ML · CHEST X-RAY TUBERCULOSIS SCREENING</sub>

A CNN that classifies chest X-rays as **Normal or Tuberculosis**, trained on the public TB Chest X-ray dataset. Ships with a reproducible training script, a `predict_from_image_path()` inference API and a Streamlit app for interactive predictions.

`TensorFlow` `Keras` `Streamlit`

[Repo →](https://github.com/Isaackjoshua/TB-Classifier)

</td>
  </tr>
  <tr>
    <td width="50%" valign="top">

#### [Afya-Predict](https://github.com/Isaackjoshua/Afya_Predict)
<sub>ML · DISEASE-OUTBREAK EARLY WARNING</sub>

A modular platform for predicting disease outbreaks in Tanzania, designed to take in health-facility, climate and mobility data and surface early-warning signals for public-health teams. **Plug-in data sources** let it grow across regions and diseases without rewriting the core pipeline.

`Python` `Machine learning` `Epidemiological modelling`

[Repo →](https://github.com/Isaackjoshua/Afya_Predict) · [Case study →](https://isaackjoshua.com/projects/afya-predict)

</td>
    <td width="50%" valign="top">

#### [Triage](https://github.com/Isaackjoshua/Triage)
<sub>AI AGENT · MACHINE DIAGNOSTICS</sub>

Point it at a faulty computer: it runs tiered diagnostics, applies the software fixes it safely can, and escalates hardware or high-risk issues to a human. **What it's allowed to touch is enforced in the architecture**, not left to the model.

`Python` `LLM tool-use` `Cross-platform`

[Repo →](https://github.com/Isaackjoshua/Triage) · [Case study →](https://isaackjoshua.com/projects/triage)

</td>
  </tr>
  <tr>
    <td width="50%" valign="top">

#### [Lyceum](https://github.com/Isaackjoshua/Lyceum)
<sub>LLM APP · AI TUTOR FOR THE DESKTOP</sub>

Turns any LLM into a structured, interactive tutor — explanation, worked examples and adaptive questioning instead of one-shot answers. **Bring your own key and model** (Claude, GPT, Kimi or local): no vendor lock-in.

`TypeScript` `Electron` `React`

[Repo →](https://github.com/Isaackjoshua/Lyceum) · [Case study →](https://isaackjoshua.com/projects/lyceum)

</td>
    <td width="50%" valign="top">

#### [Amana255 · Escrow](https://github.com/Isaackjoshua/Escrow)
<sub>BACKEND · MOBILE-MONEY ESCROW FOR EAST AFRICA</sub>

Holds funds until the buyer confirms delivery. Selcom mobile-money deposits and payouts (M-Pesa, Tigo Pesa, Airtel Money), **SMS OTP on every financial action**, atomic state transitions, an immutable audit log and HMAC-verified webhooks.

`TypeScript` `Express` `PostgreSQL` `Prisma` `Redis` `Docker`

[Repo →](https://github.com/Isaackjoshua/Escrow) · [Case study →](https://isaackjoshua.com/projects/amana)

</td>
  </tr>
</table>

## $ ls ~/projects --more

| Project | What it is | Stack |
| :-- | :-- | :-- |
| [**Image_info_Extractor**](https://github.com/Isaackjoshua/Image_info_Extractor) | CLI that reads echocardiogram report pages with Claude vision and writes one structured row per patient to Excel | Python · Claude API |
| [**muungano-bot**](https://github.com/Isaackjoshua/muungano-bot) | Swahili WhatsApp bot that answers questions about the Union of Tanganyika and Zanzibar from a vetted knowledge base — built for a university innovation contest | Python · FastAPI · Twilio · Gemini |
| [**DICOM → Video**](https://github.com/Isaackjoshua/DICOM) | Desktop tool that turns multi-frame, multi-series DICOM studies into MP4 / AVI / MKV with correct windowing and preserved frame rate | Python · PyQt6 · pydicom · FFmpeg |
| [**Izy**](https://github.com/Isaackjoshua/Izy) | Local-first focus companion — an always-on-top mascot that tracks whether you're on task and holds natural-language reminders | Python |
| [**InviteFlow**](https://github.com/Isaackjoshua/InviteFlow) | Event invitation management with QR-code check-in and Twilio messaging | React · Express · PostgreSQL · Twilio |

## $ cat stack.txt

<table>
  <tr>
    <td width="33%" valign="top">

**ML & deep learning**

Training, fine-tuning and export — PyTorch, TensorFlow/Keras and Hugging Face through to ONNX Runtime, so inference runs on the device instead of a server. Computer vision for medical imaging: classification, segmentation, Grad-CAM.

![PyTorch](https://img.shields.io/badge/PyTorch-000000?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-000000?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-000000?style=for-the-badge&logo=keras&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-000000?style=for-the-badge&logo=huggingface&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX-000000?style=for-the-badge&logo=onnx&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-000000?style=for-the-badge&logo=scikitlearn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-000000?style=for-the-badge&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-000000?style=for-the-badge&logo=pandas&logoColor=white)

</td>
    <td width="33%" valign="top">

**LLMs & model serving**

LLM tool-use agents with hard safety boundaries and vendor-agnostic LLM apps. FastAPI services put models behind an API, with Celery and Redis keeping slow work off the request path.

![Python](https://img.shields.io/badge/Python-000000?style=for-the-badge&logo=python&logoColor=white)
![Claude API](https://img.shields.io/badge/Claude%20API-000000?style=for-the-badge&logo=anthropic&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-000000?style=for-the-badge&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-000000?style=for-the-badge&logo=streamlit&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-000000?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-000000?style=for-the-badge&logo=redis&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-000000?style=for-the-badge&logo=celery&logoColor=white)

</td>
    <td width="33%" valign="top">

**Ship & run**

Ubuntu servers with nginx, Docker and TLS. Flutter for mobile, Electron and PyQt6 for desktop. Offline-first wherever the network can't be trusted.

![Linux](https://img.shields.io/badge/Linux-000000?style=for-the-badge&logo=linux&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-000000?style=for-the-badge&logo=docker&logoColor=white)
![nginx](https://img.shields.io/badge/nginx-000000?style=for-the-badge&logo=nginx&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-000000?style=for-the-badge&logo=flutter&logoColor=white)
![Electron](https://img.shields.io/badge/Electron-000000?style=for-the-badge&logo=electron&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-000000?style=for-the-badge&logo=typescript&logoColor=white)
![Git](https://img.shields.io/badge/Git-000000?style=for-the-badge&logo=git&logoColor=white)

</td>
  </tr>
</table>

## $ git log --graph

<p align="center">
  <img height="165" alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=Isaackjoshua&show_icons=true&count_private=true&include_all_commits=true&hide_border=true&bg_color=000000&title_color=FFFFFF&text_color=BFBFBF&icon_color=FFFFFF&ring_color=FFFFFF" />
  <img height="165" alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Isaackjoshua&layout=compact&langs_count=8&hide_border=true&bg_color=000000&title_color=FFFFFF&text_color=BFBFBF" />
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Isaackjoshua/Isaackjoshua/output/snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Isaackjoshua/Isaackjoshua/output/snake-light.svg" />
    <img alt="Contribution graph being eaten by a snake" src="https://raw.githubusercontent.com/Isaackjoshua/Isaackjoshua/output/snake-light.svg" />
  </picture>
</p>

## $ ./contact --hire

Hiring for **ML / AI engineering** — or backend work that sits close to the models? Full-time, contract or internship-to-hire, email is the fastest way to reach me. Tell me the constraint you're building against and I'll tell you straight whether I'm the right person for it.

<p>
  <a href="mailto:isaackjoshua23@gmail.com"><img src="https://img.shields.io/badge/isaackjoshua23%40gmail.com-000000?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://www.linkedin.com/in/isaack-joshua-7277ba29a"><img src="https://img.shields.io/badge/LinkedIn-000000?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://isaackjoshua.com"><img src="https://img.shields.io/badge/isaackjoshua.com-000000?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website" /></a>
  <a href="https://isaackjoshua.com/Isaack_Joshua_Lukumay_CV.pdf"><img src="https://img.shields.io/badge/%E2%86%93%20Download%20CV-FFFFFF?style=for-the-badge" alt="Download CV" /></a>
</p>

<br/>

<p align="center"><sub><code>PROJECT.EXE</code> exited with status 0 · built in Dar es Salaam, Tanzania</sub></p>
