---
layout: post
title: "Some general features about our project"
description: "General information"
date: 2024-08-15
tags: [introduction, general]
comments: true
---

Let's make your own posts!
---


# Team description
## Teammates
  1. Bùi Như Hưng
  2. Nguyễn Châu Phúc Huy
  3. Vương Nguyên Hân
  4. Trương Uyển Nhi
  5. Trần Tấn Đạt

## Team moto!
blabla~


---

# Team Project
  Basic Sign Language Recognition using Teachable Machine
## Project goal 
  Our goal is to enable computers to recognize basic sign language gestures using machine learning. This helps raise awareness about communication barriers for the hearing-impaired and can support daily interactions, especially in education and public services.
  The project promotes inclusivity and shows how beginner-friendly tools like Teachable Machine can be applied to real-world problems.
## Inside our project:
### Dataset and Class Configuration
  We collected images of basic hand gestures representing numbers from **0 to 5**.  
  Each class includes **900–1000 images**, ensuring variety in lighting, background, and hand positioning.  
  Class labels are clearly distinguishable and logically organized to support effective training.
### Teachable Machine Setup
  We used **Google’s Teachable Machine** with the **Image Project > Standard Image Model** option.  
  The model was trained using our custom dataset, with a clear split between training and testing sets for balanced evaluation.
### Code and customization
  After training, we exported the model as TensorFlow code.
  We modified the Python script to perform hand gesture recognition through either webcam input or static images.
  We customized the interface to show prediction accuracy and visual feedback.
### Running the project
  When the user shows a gesture in front of the webcam, the system identifies and displays the result in real-time.
  Alternatively, the user can upload an image, and the system will perform gesture recognition on the uploaded image as well.
  The results are displayed through a feedback interface along with the prediction confidence percentage.
## Our future plan for this project
  Increase the number of gestures to include full alphabet and daily phrases.
  Add voice output to make the tool usable in real-time conversation.
  Build a mobile-friendly version using TensorFlow Lite.
  Improve the model by collecting more diverse datasets with different people and backgrounds.
  We want to create a tool that not only recognizes signs but also actively helps people with hearing difficulties engage with others more easily.
## Code explanation 

~~~python
print("hello world")
~~~

![spongebob](https://i.guim.co.uk/img/static/sys-images/Guardian/Pix/pictures/2009/7/24/1248436779217/SpongeBob-SquarePants-10t-001.jpg?width=465&dpr=1&s=none&crop=none)

---

