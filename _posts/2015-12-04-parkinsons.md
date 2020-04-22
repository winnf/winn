---
title:  "Freeze the Freeze"
date:   2015-12-04 15:04:23
categories: [projects]
tags: [sensors, health, arduino, parkinson's disease]
---

![hardware](gait.png)

### What is Parkinson's Disease?
It is a very common motor system disorder, with approximately seven to ten million people living with the condition worldwide. It is a neurodegenerative disorder where symptoms progress over time and is more common in those who are above 50 years old. Parkinson’s Disease is developed when the brain stops producing a neurotransmitter called dopamine, caused by damage in the basal ganglia, which transmits signals between the substantia nigra (midsection) to other brain regions. A lack of dopamine leads to cognitive impairments and hinders the brain’s ability to control body movements. It is fairly difficult to predict and diagnose patients with Parkinson’s Disease when it begins to develop because symptoms only start to appear when approximately 80% of the nerve cells in the substantia nigra have been lost.

---

### Symptom: Gait Freezing
is a very important symptom of Parkinson’s Disease where the patient feels as though their feet is glued to the ground. They experience difficulty lifting the foot up or taking normal strides during their walk, thus we can visually see the hesitation during freezing. Researchers are unsure why freezing occurs but through experiments, it was found that the risk of freezing increases when the patient undergoes turning, pivoting, walking through tight spaces such as doorways, and during stressful conditions such as approaching objects. Freezing of gait is one of the more serious problems because it increases a patient’s risk of falling and breaking their bones.

---

### The Project
aims to address the ***issue of freezing of gait in Parkinson’s disease patients by developing a product that prevents freezing upon detection***. We developed an arduino prototype, which is connected to a circuit on a breadboard. The circuit is composed of an IMU, which collects motion data, and a vibrating motor. In order to analyze common patterns of freezing, we attached our prototype on the subject’s shoe and conducted walking, stopping and freezing trials. Upon repeated trials, we identified unique patterns in pitch angle and rotational velocity data then developed a program to detect those patterns. By incorporating both pitch angle and rotational velocity data in detecting freezing, we increased the reliability of our product in detecting freezing in various conditions. When it reports freezing, the arduino would send a signal to the vibrating motor attached to the subject’s calcaneal tendon. This vibrating stimulus helps alleviate symptoms of freezing in Parkinson’s disease patients.
