---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

# Education
* **M.Sc. in Artificial Intelligence for Biomedicine and Healthcare**  
  *University College London (UCL), UK*  
  *Sep. 2024 - Sep. 2025 (expected)*  

* **B.Sc. in Computer Science (Honors)**  
  *McGill University, Canada*  
  *Sep. 2020 - May 2024*  
  - Graduated with First Class Honors  

---

# Work Experience
* **Spring 2023: Research Assistant**  
  *McGill University*  
  - Assisted in the development of machine learning models for tumor metastasis prediction  
  - Supervisor: Professor [Name Placeholder]

* **Summer 2021: Teaching Assistant**  
  *SuZhou EA*  
  - Provided one-on-one teaching in IGCSE Math and Computer Science  
  - Received the Excellent Teaching Assistance Award  

---

# Skills
* **Frameworks:**  
  PyTorch, TensorFlow  

* **Programming Languages:**  
  Python, Bash, Java, Ocaml, C, C++, R  

---

# Publications
<ul>
  {% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
</ul>

---

# Projects
### Handwritten Digit Recognition with CustomMLP
*Developer | Sep. 2023 - Present*  
- Developed a high-performance Multilayer Perceptron (MLP) from scratch using only NumPy for MNIST digit recognition.  

### Chest X-ray Classification for Pneumonia Detection
*Developer | Oct. 2024*  
- Built a custom CNN, achieving 95.72% validation accuracy.  
- Implemented Batch Normalization and Dropout techniques to prevent overfitting.  

### Diabetic Retinopathy Detection
*Kaggle Participant | Nov. 2024*  
- Created a hybrid CNN architecture using EfficientNet and ResNet.  
- Experimented with CosineAnnealingLR scheduler for enhanced training optimization.  

---

# Talks
<ul>
  {% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}
</ul>

---

# Teaching
<ul>
  {% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
</ul>

---

# Service and Leadership
* Currently enrolled in the MSc AI for Biomedicine and Healthcare program at UCL.
* Participated in various Kaggle competitions, emphasizing practical applications of deep learning in healthcare.

