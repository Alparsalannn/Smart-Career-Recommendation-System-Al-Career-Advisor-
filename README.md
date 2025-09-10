# Smart-Career-Recommendation-System-Al-Career-Advisor-
An AI-powered career guidance system that helps students and professionals choose the right career path based on their skills, interests, and academic background.  This project combines data science, machine learning, and web deployment to provide personalized career recommendations, job matches, and learning resources.

Features

Data Pipeline – Cleans and processes job/education data

Skill Extraction – Identifies key skills from job descriptions

Recommendation Engine – Suggests relevant jobs using content-based filtering (TF-IDF + cosine similarity)

ML Classifier – Predicts best-fit career paths using a Random Forest Classifier

Learning Resources – Provides curated courses & materials for upskilling

Web Application – Simple UI (Flask + HTML) for users to input skills and get recommendations

Deployment Ready – Dockerized for easy deployment

├── app.py                  # Flask API
├── data_pipeline.py        # Data cleaning & feature extraction
├── recommend.py            # Content-based recommendation
├── train_models.py         # Career classifier training
├── frontend/index.html     # Simple demo frontend
├── data/raw/jobs_sample.csv # Sample dataset
├── models/learning_resources.json # Resource mapping
├── requirements.txt        # Dependencies
├── Dockerfile              # Docker setup
├── docker-compose.yml      # Compose for deployment
└── README.md


How It Works

Input: User enters skills & interests

Processing: System analyzes inputs against job market data

Prediction: ML model predicts career category

Output: Career recommendation, job suggestions, and learning resources
