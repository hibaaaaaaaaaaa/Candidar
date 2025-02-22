# Candidar - AI Mock Interview Platform
## Abstract
**Candidar** is an **AI-powered** platform designed to help job seekers enhance their interview skills through real-time mock interviews and personalized feedback.

The name **Candidar** combines candidate with **dar - دار**, the Moroccan word for **home**, symbolizing a place where **Moroccan** users can feel safe, supported, and empowered in their journey toward securing their dream jobs. Just as  **dar - دار** is a space of comfort and growth, Candidar provides an environment for individuals to refine their interview abilities, build confidence, and prepare for professional success.

<p align="center">
  <img src="https://github.com/user-attachments/assets/468cf637-4b21-447e-ba81-f288da3252e7" />
</p>

By simulating realistic interviews specific to different job roles and offering insightful feedback, Candidar equips users with the necessary tools to navigate the competitive **Moroccan job market** and stand out to potential employers.
## Background and Problem Statement
### Background
Each year in **Morocco**, `90,000` graduates enter a challenging job market, where `25.9%` remain unemployed. A significant factor contributing to this is the lack of effective interview skills, as over `70%` of job seekers struggle to present themselves confidently during interviews due to limited preparation and access to professional guidance.
  
<p align="center">
  <img src="https://github.com/user-attachments/assets/d2141ae5-ce03-47db-bbcc-b08d3efc9703" />
</p>

### Problem Statement
Job seekers face the following challenges:
* Inadequate preparation for interviews.
* Limited access to affordable and realistic training tools.
* A lack of feedback to identify areas for improvement.

**Candidar** tackles these issues by providing an accessible AI platform for realistic, role-specific mock interviews and personalized feedback to empower job seekers to succeed in their careers.

## Proposed Solution
**Candidar** provides an innovative approach to interview preparation, offering a dynamic, AI-powered platform that helps job seekers practice and improve their skills through realistic, real-time simulations.
* Features include :

     * **User Information Input :** Users specify the job they’re applying for.

    *  **Psychometric Test :** An MCQ test to assess reasoning and aptitude.

    * **Virtual Interview :** Users select their interviewer type (Hiring Manager, HR Manager, or Technical Expert) and participate in a vocal interview simulation.
    * **Detailed Feedback :** Users receive scores and personalized recommendations to improve their interview skills.

## Usage and Technical Architecture
### Usage

* **Step 1 :** Enter user details and specify the desired job position.

* **Step 2 :** Complete the psychometric test to assess reasoning and problem-solving skills.

*  **Step 3 :** Choose the type of interviewer (Hiring Manager, HR Manager, or Technical Expert).

* **Step 4 :** Participate in a vocal interview simulation and receive detailed feedback with scores and areas for improvement.

<p align="center">
  <img src="https://github.com/user-attachments/assets/268c84cb-49d1-4c60-abb2-4aeed39b4799" />
</p>



### Technical Architecture

#### 📝 Text Generation Models
- **Gemini-1.5-pro**: Generates psychometric and interview questions.
- **Mixtral-8x7B**: Evaluates responses and provides feedback.

#### 🔊 Speech Processing
- **Speech Synthesis Web Speech API**: Converts text-based questions into speech.
- **Speech Recognition Web Speech API**: Transcribes user responses.

#### 💾 Data Storage
- Interview data (questions and responses) is stored in **JSON format** for further processing.

#### 📊 Feedback Mechanism
- A final evaluation phase analyzes user responses and provides:
  - **Score**
  - **Feedback**
  - **Improvement suggestions**

<p align="center">
  <img src="https://github.com/user-attachments/assets/75ae0b91-5765-4d31-bed0-9c7ac437564f" />
</p>

## Demo

https://youtu.be/4WpMQw8b1aI?si=EwVcgw8MNssT6BA7

https://youtu.be/TsOnK9ia-rg?si=i4lW41qkgcCBlVNL
