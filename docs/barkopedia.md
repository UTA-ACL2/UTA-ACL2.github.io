# Barkopedia: A Canine Vocalization Understanding Challenge <!-- omit from toc -->

[![Hugging Face](https://img.shields.io/badge/%F0%9F%A4%97%20-Hugging%20Face-yellow)](https://huggingface.co/safe-challenge)

<img src="../static/images/overall_banner.png" width="900px">

**👉 All participants must register for the competition by completing this [Google Form](https://forms.gle/5J8Yuh41Lv8GAF7w8)**

[📊 Overview](#-overview) • [🥇 Detailed Leaderboard](#-detailed-leaderboard) • [🏆 Prize](#-prize) • [📜 Paper Submission and Dates](#-paper-submission-and-dates) • [📝 Tasks](#-tasks) • [📈 Data](#-data) • [🤖 Model Submission](#-model-submission) • [📂 Create Model Repo](#-create-model-repo) • [🔘 Submit](#-submit) • [🆘 Helpful Stuff](#-helpful-stuff) • [🔍 Evaluation](#-evaluation) • [⚖️ Rules](#️-rules)

## 📣 Updates

**2025-04-15**  
- Competition officially launches; training data is released.

## 📊 Overview

Dogs use vocalizations to communicate intentions, emotions, and contextual cues. While prior research shows that machine learning models can classify dog barks based on context, individual identity, and emotion, existing studies often suffer from limited scale, generalizability, or robustness due to small datasets or handcrafted features.

This challenge, hosted at [IJCAI 2025](https://2025.ijcai.org/), addresses these issues by providing a large-scale, diverse benchmark dataset of real-world dog vocalizations sourced from YouTube and Reddit. The competition includes eight tasks designed to promote research at the intersection of machine learning, audio/speech processing, and animal communication.

Sign up here to participate and stay informed: [Google Form](https://forms.gle/5J8Yuh41Lv8GAF7w8)

<!-- ## 🥇 Detailed Leaderboard
[Public Leaderboard](https://safe-challenge-leaderboard-public.hf.space)
<iframe
	src="https://safe-challenge-leaderboard-public.hf.space"
	frameborder="0"
	width="850"
	height="450"
></iframe> 
-->

## 🏆 Prize

Top-performing solutions may be eligible for research grants to support continued development.

**Registration is required to participate:**
- Sign up: [Google Form](https://forms.gle/5J8Yuh41Lv8GAF7w8)
- Contact us: tobedecided@gmail.com
- Open an issue: [GitHub Repo](https://github.com/uta-acl2/Barkopedia)
- See submission instructions and [🆘 Helpful Stuff](#-helpful-stuff) for debugging examples.

## 📜 Important Dates

- **04/15/2025:** Competition announcement and training data release  
- **05/15/2025:** Participant registration deadline  
- **06/01/2025:** Validation data and baseline results released  
- **07/01/2025:** Submission portal opens for test data  
- **07/15/2025:** Final submission deadline  
- **08/01/2025:** Preliminary results announced; feedback period opens  
- **08/15/2025:** Deadline for challenge reports and code submission  
- **08/30/2025:** Final results and winner announcement  
- **09/15/2025:** Presentation of winning solutions at IJCAI 2025

For questions regarding paper submission, please contact: **acm.ihmmsec25@gmail.com**

## 📝 Tasks

The competition includes six core tasks. The first five involve classifying dog barks by categories such as individual, breed, sex, environment, etc. The final task focuses on audio denoising to extract pure dog barks from noisy recordings. All tasks open simultaneously.

- **Task 1 (✅ Open):** Dog Breed / Sex / Age Classification  
  [SAFEChallengePractice](https://huggingface.co/spaces/safe-challenge/SAFEChallengePractice)

- **Task 2 (✅ Open):** Dog Individual Recognition  
  [SAFEChallengeTask1](https://huggingface.co/spaces/safe-challenge/SAFEChallengeTask1)

- **Task 3 (✅ Open):** Dog Activity & Environment Classification  
  [SAFEChallengeTask2](https://huggingface.co/spaces/safe-challenge/SAFEChallengeTask2)

- **Task 4 (✅ Open):** Dog Emotion Classification  
  [SAFEChallengeTask2](https://huggingface.co/spaces/safe-challenge/SAFEChallengeTask2)

- **Dog Vocal Separation (DVS): ✅ Open** \
  [Barkopedia-Dog_Vocal_Separation](https://huggingface.co/spaces/ArlingtonCL2/Barkopedia-Dog_Vocal_Separation)

- **Task 6 (✅ Open):** Dog Vocal Detection (DVD)  
  [SAFEChallengeTask2](https://huggingface.co/spaces/safe-challenge/SAFEChallengeTask2)

## 📈 Data

Each task includes a corresponding dataset with a dataset card available on its Hugging Face page.

## 🤖 Result Submission

This is a generic leaderboard-style competition. Participants submit `.csv` files with results, which are evaluated on a public test set.

### 🔘 Submit

Once your result `.csv` file is ready:

- Visit the submission space for the specific task  
- Log in with your Hugging Face account  
- If working in a team, submit under a shared account for consistency  
- Upload your `.csv` file and click **Submit** 🎉  
- Use the **same username** across all team submissions

## 🆘 Helpful Stuff

If your submission fails, errors will not be shown directly (private eval space). You can:
- Open a GitHub issue or email us with your submission ID for log retrieval.
- Test locally using the provided debug examples.

## 🔍 Evaluation

Evaluation metrics vary by task. See each task’s Hugging Face space for details.

## ⚖️ Rules

Rules and requirements are defined per task. Be sure to review the task-specific documentation.
