# Neuro-Cloud
# AltSchool Cloud Project – Bello Samad

## 🌍 Project Title
**NeuroNest-The Future of Personalized Mental Wellness**

## 🧠 Project Pitch
NeuroNest is an intelligent mental wellness platform that uses AI and real-time brain-pattern recognition to deliver personalized mental health support. Unlike generic apps, it adapts to each user's cognitive rhythms using data from wearable EEG devices and behavior analytics — making emotional care truly proactive, not reactive.

## 👩🏽‍💻 About ME
Bello Samad is a seasoned Cloud Engineer with deep expertise in building secure, scalable, and intelligent systems for health-focused tech startups. At NeuroNest, he leads the development of its hybrid cloud infrastructure — ensuring sensitive neuro-data is processed efficiently and privately using edge-AI and encrypted cloud services. With some experience in the field, he has worked on mission-critical platforms across the fintech and healthtech sectors. Samad holds multiple cloud certifications (including AWS Solutions Architect) and is passionate about ethical AI, cognitive technology, and human-centered design.
    <br>Past Projects: Real-time patient monitoring dashboards, AI-driven fintech analytics systems <br>
    Education: B.Sc. in Computer Science, AltSchool Africa – School of Engineering
---


🌐 Public IP: (http://13.62.47.169/)

---

## 📸 Screenshot of the Landing Page
<img width="960" alt="Neurosnip" src="https://github.com/user-attachments/assets/ac640e4d-d66c-4984-afbc-66308068b39a" />

## 🔧  Nginx Setup
![Nginx ss](https://github.com/user-attachments/assets/a8d9c5a4-5d8b-4004-a934-4129317cadc3)

## 🌐 EC2 Instance
<img width="959" alt="image" src="https://github.com/user-attachments/assets/c7379781-e19e-46d8-be2f-1969cfccd073" />



---

## 🔗 GitHub Repository

📁 https://github.com/Techpro101/Neuro-Cloud/tree/main

✉️ samadbello21@gmail.com

---

## 🛠️ Steps Taken
Signed up my AWS and added billing methods to it

## EC2 Instance

Then I went into the EC2 instance, Created a new instance, Named the instance and selected an Ubuntu distribution 
Created a New keypair, named it and stored it in a folder already I created 
I also selected a custom domain
Allowed HTTP and HTTPS on the internet then I launched my instance 
Now instance is up and running 

## Connecting My EC2 instance to my local computer Bash

I cd into where my key pair is and list 
ran the command to change the permission of the key pair 
then I copied the command from my instance and pasted on my bash 
EC2 instance is up and running on bash 
 
## Web Server Setup-installing Nginx
I update my instance using the command "sudo apt update "
I upgraded my instance using the command "sudo apt upgrade"
install Nginx using command "sudo apt install Nginx" Yes
checked if my Nginx is up and running by running command "sudo apt systemctl status Nginx

Creating a personalized landing page and connecting it 
used html and css to that already initially 
Move my files from my local computer to my Ec2 Instance using command "scp -1 "Neuro-key.pem" ubuntu@13.62.47.169


## Summary

### 1️⃣ Server Provisioning (AWS EC2)
- Launched an **Ubuntu 22.04 LTS** instance via AWS EC2
- Used **t2.micro** instance (Free Tier)
- Downloaded `.pem` SSH key
- Opened these ports in the security group:
  - `22` – SSH
  - `80` – HTTP
  - `443` – HTTPS (for SSL)

---

### 2️⃣ Connecting to Server via SSH
```bash
ssh -i "Neuro-key.pem" ubuntu@13.62.47.169
