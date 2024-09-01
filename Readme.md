# AI-Enhanced Healthcare Diagnostics and Management System inspired by ZK Medical Billing Platform

This README provides an overview of the project, including team details, relevant links, tasks completed, tech stack, key features, and steps to run the project locally.

## Team Details

*Team Name:* RISE

*Team Leader:* [@LeoAB03](https://github.com/LeoAB03)

*Team Members:*

- *Abhigyan Bhardwaj* - 2022UMV7630 - [@LeoAB03](https://github.com/LeoAB03)
- *Ayush Kumar* - 2022UMV7644 - [@ak35Ayush](https://github.com/ak35Ayush)
- *Ayush Jain* - 2022UEA6548 - [@ayush14189](https://github.com/ayush14189)
- *Aishwina Nainwal* - 2023UEC2605 - [@AishwinaNainwal](https://github.com/AishwinaNainwal)
- *Krish Sharma* - 2022UEA6506 - [@Krishsh93](https://github.com/Krishsh93)
- *Ankit Sneh* - 2022UEA7618 - [@ENDOMINOUSANK](https://github.com/ENDOMINOUSANK)

## Project Links

- *Internal Presentation:* [Internal Presentation](URL TO PPT UPLOADED TO GITHUB)
- *Final SIH Presentation:* [Final SIH Presentation](URL TO PPT UPLOADED TO GITHUB)
- *Video Demonstration:* [Watch Video](UNLISTED YOUTUBE LINK)
- *Live Deployment:* [View Deployment](DEPLOYED LINK IF ANY)
- *Source Code:* [GitHub Repository](GITHUB LINK TO THE REPO)
- *Additional Resources:* [Other Relevant Links](ANY OTHER RELEVANT LINKS)



# Medical Chatbot

This project implements a chatbot powered by a medical dataset. The chatbot is designed to provide medical information and assistance based on the data it has been trained on. It is a conversational AI that interacts with users, answering their medical queries and guiding them based on the knowledge embedded in the dataset.

## Features

- **Medical Knowledge**: The chatbot is trained on a comprehensive medical dataset, allowing it to answer a wide range of medical questions.
- **Interactive Conversations**: The bot engages users in meaningful conversations, helping them find the information they need.
- **Local Deployment**: Run the chatbot on your local machine, providing a private and secure environment for interactions.

## Prerequisites

Before running the project locally, ensure you have the following installed on your machine:

- Python 3.7 or later
- Virtualenv (optional but recommended)
- Git

## Steps to Run the Project Locally

### 1. Clone the Repository

First, clone the repository to your local machine using Git:

```bash
git clone https://github.com/LeoAB03/AI-MODEL.git
cd RAG
```

### 2. Set Up a Virtual Environment (Optional)

It is recommended to use a virtual environment to manage your dependencies. You can create and activate a virtual environment using the following commands:

```bash
python3 -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### 3. Install Dependencies

Install the required Python packages by running:

```bash
pip install -r requirements.txt
```

### 4. Set Up the Dataset

Place the medical dataset in the appropriate directory (e.g., `data/`). Ensure that the dataset is properly formatted and ready for use by the chatbot.

### 5. Run the Chatbot

You can start the chatbot by running the main script:

```bash
python app.py
```

This will launch the chatbot, and you can interact with it through the terminal or a web interface, depending on how it's set up in `main.py`.

### 6. Access the Chatbot

If the chatbot is running through a web interface, open your browser and navigate to the local server address (usually `http://127.0.0.1:8000/`).

### 7. Deactivate the Virtual Environment (Optional)

After you're done, you can deactivate the virtual environment with:

```bash
deactivate
```
