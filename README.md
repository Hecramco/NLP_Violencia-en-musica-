
# 🎵 NLP Project: Identifying Violence in Music Lyrics

**A project developed for Saturdays AI 2020**
*Read the full article in Spanish on [Medium](https://medium.com/saturdays-ai/o%C3%ADmos-o-escuchamos-m%C3%BAsica-2859085f057f)*

---

## 📌 Overview

Modern music streaming platforms grant us easy access to thousands of songs. However, the lyrical content is often overlooked, and children may be exposed to violent messages without awareness or consent.

This project explores how **Natural Language Processing (NLP)** can be used to identify and bring awareness to violent content in music lyrics **without censorship**. We also consider that some lyrics express anger rooted in social injustice or reflect the violent realities of certain societies. Hence, violence in lyrics goes beyond swearing or vulgar language and can include **symbolic, physical, or gender-based violence**, especially against women.

The goal of this project is to contribute toward the [United Nations Sustainable Development Goals (SDGs)](https://sdgs.un.org/goals), specifically **Goal 5: Gender Equality**, by creating tools that help identify and raise awareness about violence in musical content.

---

## 🎯 Objective

Due to the lack of a publicly available dataset specifically labeled for this task, the scope of the project was limited to classifying whether or not a song lyric contains any kind of **violent content**.

---

## ⚙️ Installation

Clone the repository and install the required dependencies:

```bash
git clone https://github.com/Hecramco/NLP_Violencia-en-musica-.git
cd NLP_Violencia-en-musica-
pip install -r requirements.txt
jupyter notebook
```

---

## 📂 Project Structure

* `data/`: (Not included) This directory was used to store lyrics datasets. You may need to provide your own.
* `notebooks:`: Jupyter Notebooks with exploratory analysis, preprocessing, modeling, and evaluation.
* `requirements.txt`: Requirements to run the experiments.

---

## 💡 Key Features

* Text preprocessing (tokenization, lemmatization, cleaning)
* Custom dataset building using web scraping and manual labeling
* Annotation strategies for violence in lyrics based on common types of violence and explicit language
* Binary classification model: Violent / Non-violent
* Exploratory analysis and visualizations

---

## 📖 Limitations

* No large public dataset available for violence in lyrics
* Subjectivity in defining what constitutes “violence”
* Cultural and contextual interpretations can vary

---

## 🌍 Contribution to SDGs

This project contributes to:

* **Goal 5 – Gender Equality**: By identifying lyrics that contain gender-based or symbolic violence, we aim to foster awareness and promote more responsible media consumption.

---


## 📜 License

This project is released under the MIT License. See `LICENSE` for more details.


Here's a revised and polished version of your section for clarity, grammar, and professional tone:

---

## 🧭 Possible Improvements and Next Steps

* This project was originally developed in 2020, prior to the widespread availability of Large Language Models (LLMs).
* The use of LLM APIs today could significantly enhance the project by assisting with **automatic annotation**, **context-aware labeling**, and **violence detection** through carefully designed **prompt-based framing**.
* LLMs could also help in identifying more nuanced or implicit forms of violence, including symbolic, gender-based, or contextual violence that traditional models might miss.


#

