---
# Display name
title: Christina Sheckler

# Name pronunciation (optional)
#name_pronunciation: Chien Shiung Wu

# Full name (for SEO)
first_name: Christina
last_name: Sheckler

# Status emoji
status:
  icon: ☕️

# Is this the primary user of the site?
superuser: true

# Highlight the author in author lists? (true/false)
highlight_name: true

# Role/position/tagline
role: Student at the University of Michigan

# Organizations/Affiliations to display in Biography blox
organizations:
  - name: Neural Engineering in Epilepsy Lab
    url: https://sites.google.com/umich.edu/neural-engineering-in-epilepsy/home

# Social network links
# Need to use another icon? Simply download the SVG icon to your `assets/media/icons/` folder.
profiles:
  - icon: at-symbol
    url: 'mailto:ninashec@umich.edu'
    label: E-mail Me
  - icon: brands/github
    url: https://github.com/ninashec
  - icon: brands/linkedin
    url: https://www.linkedin.com/in/christinasheckler/

interests:
  - Artificial Intelligence
  - Computational Neuroscience
  - Human Computer Interaction
  - Machine Learning
  - Natural Language Processing

education:
  - area: B.S. Computer Science 
    institution: University of Michigan
    date_start: 2020-08-01
    date_end: 2025-05-01
    summary: |
      Courses included:
      - EECS 492 - Introduction to Artificial Intelligence
      - EECS 445 - Introduction to Machine Learning
      - EECS 487 - Introduction to Natural Language Processing
      - EECS 442 - Introduction to Computer Vision
  - area: B.S Cognitive Science - Computation concentration
    institution: University of Michigan
    date_start: 2020-08-01
    date_end: 2025-05-01
    summary: |
      Courses included:
      - Psych 230 - Introduction to Behavioral Neuroscience
      - Psych 336 - Drugs of Abuse
      - CMPLXSYS 511 - Theory of Complex Systems
      - EECS 281 - Data Structures and Algorithms
work:
  - position: Research Assistant
    company_name: University of Michigan Biomedical Engineering
    company_url: ''
    company_logo: ''
    date_start: 2023-05-01
    date_end: ''
    summary: |2-
      Under Dr. William Stacey
      -  Created an automated C++ text-parsing script that could extract relevant information from EEG comments file (.lay) and convert information to standard format used worldwide (BIDS format)
      - Created a computational toolbox and tutorial for generating synthetic EEG seizure data based on a mathematical model, enabling precise control over seizure onset and offset dynamics for use in developing seizure detection algorithms and training data analysis tools. Writing a manuscript on this work. 
      - Developed a seizure dynamotype classifier by creating a comprehensive preprocessing pipeline for EEG data, including high-pass and low-pass filtering, median filtering, sequence length normalization via cubic spline interpolation, and dimensionality reduction. Implemented data augmentation techniques such as series flipping to enhance model robustness. Applied sequence padding and data normalization to ensure consistent input shapes for neural networks. Constructed an LSTM neural network for classification of EEG signals, incorporating custom loss functions and evaluation metrics such as F1-score. Validated model performance through cross-validation and hyperparameter tuning, achieving improved accuracy on noisy and unbalanced EEG datasets. Created custom LSTM-GradCam to further understand the model classification.
      - Developed a sequence-to-sequence LSTM model in TensorFlow to remove white noise from EEG data. The model was trained on simulated EEG signals with white noise added at varying levels, then denoised to restore the original clean signals. Data preprocessing involved concatenating, reshaping, and padding the time-series data, followed by splitting it into training and testing sets. The model was optimized using mean squared error (MSE) to effectively filter out noise. The trained model demonstrated strong performance in removing white noise from the signals, improving data quality for subsequent analysis.

  - position: Research Assistant
    company_name: University of Michigan Psychology
    company_url: ''
    company_logo: ''
    date_start: 2023-05-01
    date_end: 2023-12-31
    summary: |
      Under Dr. Stephanie Preston
      - Assisted in Discomfort and Uncertainty in Autonomous Vehicles study exploring factors influencing passenger discomfort and trust in Autonomous Vehicles by measuring physiological stress responses and conducting post-ride surveys. 
      - Created and administered Qualtrics surveys to assess participant discomfort before and after riding in               autonomous vehicles.
      - Managed and assisted in a paid participant study, including physiological data collection (saliva samples, biometric monitoring) and analysis of survey responses.
      - Coordinated participant recruitment, scheduling, and compensation through the Prolific platform.

# Skills
# Add your own SVG icons to `assets/media/icons/`
skills:
  - name: Technical Skills
    items:
      - name: Python
        description: ''
        percent: 80
        icon: code-bracket
      - name: Data Science
        description: ''
        percent: 100
        icon: chart-bar
      - name: SQL
        description: ''
        percent: 40
        icon: circle-stack
  - name: Hobbies
    color: '#eeac02'
    color_border: '#f0bf23'
    items:
      - name: Figure Skating
        description: ''
        percent: 100
        icon: ⛸️
      - name: Cats
        description: ''
        percent: 100
        icon: 🐈 
      - name: Creative Writing
        description: ''
        percent: 100
        icon: 🖊️

languages:
  - name: English
    percent: 100
  - name: Spanish
    percent: 100

# Awards.
#   Add/remove as many awards below as you like.
#   Only `title`, `awarder`, and `date` are required.
#   Begin multi-line `summary` with YAML's `|` or `|2-` multi-line prefix and indent 2 spaces below.
awards:
  - title: Neural Networks and Deep Learning
    url: https://www.coursera.org/learn/neural-networks-deep-learning
    date: '2023-11-25'
    awarder: Coursera
    icon: coursera
    summary: |
      I studied the foundational concept of neural networks and deep learning. By the end, I was familiar with the significant technological trends driving the rise of deep learning; build, train, and apply fully connected deep neural networks; implement efficient (vectorized) neural networks; identify key parameters in a neural network’s architecture; and apply deep learning to your own applications.
  - title: Blockchain Fundamentals
    url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
    date: '2023-07-01'
    awarder: edX
    icon: edx
    summary: |
      Learned:
      - Synthesize your own blockchain solutions
      - Gain an in-depth understanding of the specific mechanics of Bitcoin
      - Understand Bitcoin’s real-life applications and learn how to attack and destroy Bitcoin, Ethereum, smart contracts and Dapps, and alternatives to Bitcoin’s Proof-of-Work consensus algorithm
  - title: 'Object-Oriented Programming in R'
    url: https://www.datacamp.com/courses/object-oriented-programming-with-s3-and-r6-in-r
    certificate_url: https://www.datacamp.com
    date: '2023-01-21'
    awarder: datacamp
    icon: datacamp
    summary: |
      Object-oriented programming (OOP) lets you specify relationships between functions and the objects that they can act on, helping you manage complexity in your code. This is an intermediate level course, providing an introduction to OOP, using the S3 and R6 systems. S3 is a great day-to-day R programming tool that simplifies some of the functions that you write. R6 is especially useful for industry-specific analyses, working with web APIs, and building GUIs.
---

## About Me

I am a student at the Univerity of Michigan studying Computer Science and Cognitive Science. My research interests include natural language processing, human computer interaction, machine learning, and artificial intelligence in the neurotechnology domain. I am apart of the Neural Engineering in Epilepsy Lab, where I develop seizure detection and classification algorithms, as well as toolboxes for mathmatical simulations.
