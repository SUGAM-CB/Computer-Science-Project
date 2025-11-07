TITLE: Event-Connect: A Machine Learning-Based Event Recommendation System

Problem statement: In a city like Berlin, there are hundreds of things to do every single day from cultural festivals and art shows to tech conferences and business networking events. Users do not know where to look for events because the choice is overwhelming. Today's event websites present static lists and not intelligent suggestions. This lack of intelligent filtering renders the user less interactive and event exploration time-consuming and inefficient.


Proposed solution: The project proposes developing a Berlin Event Recommendation System utilizing machine learning and data-driven personalization to recommend events based on users' interests. Event data will be collected from public APIs or web scraping from sources such as Eventbrite, Meetup, or Berlin.de. The system will preprocess event data and use content-based filtering—applying TF-IDF vectorization and cosine similarity to match user interest with event descriptions and categories. A light-weighted Flask-based web application will serve as the user interface where the user will enter preferences (e.g., music, technology, art) and be recommended personalized events.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Project Goals:

-> To develop a personalized event recommendation system

-> To implement a content-based filtering model using TF-IDF and cosine similarity

-> To save users time by eliminating the need to manually browse through large event listings on different websites.

-> To encourage international students and newcomers to easily discover events aligned with their interests and networks.

-> To demonstrate how machine learning and web technologies can enhance smart city applications through personalization.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
#Tech Stack Overview:


-> Programming & Frameworks

     Python 3.10+ — Core development language

     Flask — Lightweight backend web framework for routing and user interaction

     Bootstrap 5 — For responsive and modern front-end design

-> Machine Learning & Data Handling

     scikit-learn — Used for TF-IDF vectorization and cosine-similarity calculations

     pandas and NumPy — For data cleaning, manipulation, and analysis

     pickle — For saving and loading trained TF-IDF models

-> Data & APIs

     Eventbrite API — Primary data source for event information in Berlin

     CSV files — Local storage of cleaned event datasets

-> Tools & Environment

     VS Code — Development environment

     Git / GitHub — Version control and project hosting

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Phase status:

   Development phase

-> abstract,introduction and related work defined

-> 


  
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Risk Concideration:

 This project involves several potential risks related to data, performance, and technical implementation

  -> risk related to data availability as public APIs have limited data access

  -> data quality could reduce the accuracy of recommendation as data may contain outdated or inconsistent information

  -> TF-IDF and cosine similarity calculations could become slower as the dataset grows

  -> New users with very limited input or uncommon interests may receive less relevant recommendations

  -> The current system is designed for a prototype-scale dataset; scaling to large, live event databases may require backend redesign or database integration
  

<img width="451" height="128" alt="image" src="https://github.com/user-attachments/assets/25c6d5e9-5032-4f1a-9cd0-4bde4019d942" />







