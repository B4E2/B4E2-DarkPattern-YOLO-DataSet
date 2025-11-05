# B4E2-DarkPattern-YOLO-DataSet

Hello! 👋
We are Team B4E2 (Lee Donghun, Kim Yubin, Jang Seyoung, Jeon Sukyung, Jung Jaewoong, Choi Sunghoon) from the BoB 14th Next-Generation Security Leader Program – Security Consulting Track.

This repository provides a labeled dataset for dark pattern detection in Korean online environments, designed for both academic research and AI model development.

🧭 Project Overview

This project aims to analyze and mitigate dark patterns — deceptive interface designs that mislead users into unintended actions such as unwanted purchases, subscriptions, or data sharing.

We conducted a domestic perception survey and collected real-world examples of dark pattern experiences from Korean users.
The responses were analyzed, categorized, and labeled to create an AI-trainable dataset for automated dark pattern recognition.

🔎 What Are Dark Patterns?

Dark Patterns refer to deceptive design practices in digital interfaces — such as websites or apps — that manipulate users into performing actions they did not intend.

Examples include:

“Free trial” buttons that actually start paid subscriptions

Hidden or hard-to-find account cancellation options

Pre-checked boxes for data collection or email consent

Confusing popup prompts that mislead users into agreeing to terms

These patterns undermine transparency and trust in digital environments.

💾 Dataset Description (for AI Model Training)

This dataset contains 1,960 labeled samples prepared for YOLOv12x-based AI training.
Each sample was manually labeled according to the UI elements where dark patterns most frequently occur:

Label	Description
Button	Misleading or deceptive call-to-action buttons
Checkbox	Hidden or pre-selected user consent options
QR Code	Misused or manipulative QR-based elements
Popup	Intrusive or confusing modal windows
Input Bar	Ambiguous input fields or data collection traps

These labels enable the training of object detection models that can automatically identify dark pattern components in screenshots, web pages, or app interfaces.

📊 Dataset Summary
Item	Description
Total Samples	1,960
Format	Image + YOLO annotation files
Label Categories	Button, Checkbox, QR Code, Popup, Input Bar
Purpose	Dark pattern detection, UI security research
Region	South Korea
Collection Period	2025
Use Case	AI training, academic research, UX fairness studies
🧠 Research Goals

Analyze dark pattern occurrences in Korean online services

Improve user awareness of deceptive UI mechanisms

Develop AI-based detection models for unethical UX designs

Support policy and guideline development for transparent digital experiences

⚠️ Usage Policy

This dataset is provided for research and non-commercial use only.

All personally identifiable information has been removed or anonymized.

When using this dataset, please cite the source as follows:

Source: BoB 14th – Team B4E2, Korean Dark Pattern Recognition Dataset (2025)

🚀 Future Work

Development of a YOLOv12x-based dark pattern detection model

Visualization of dark pattern hotspots in Korean web/app services

Proposal of security consulting guidelines for ethical UX design

📫 Contact

Team: B4E2 (BoB 14th Security Consulting Track)
Members: Lee Donghun, Kim Yubin, Jang Seyoung, Jeon Sukyung, Jung Jaewoong, Choi Sunghoon
Inquiries: (to be added)
Project Year: 2025

🛡️ Team B4E2 strives to create a safer, more transparent, and user-centered digital environment.
Your interest and participation contribute to building a fairer online society. 🌍
