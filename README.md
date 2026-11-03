# Dealerships and Reviews Application

## Capstone Project - IBM Full Stack Cloud Developer

A full-stack web application designed for a national car dealership network. The platform allows users to view dealerships across the United States, filter dealerships by state, read verified customer reviews with real-time sentiment analysis, and submit their own reviews for purchased vehicles.

### Architecture & Tech Stack
- **Frontend**: React.js, HTML5, CSS3, Bootstrap 5
- **Backend**: Django (Python 3), Django REST Framework
- **Microservices**:
  - Node.js & Express API with MongoDB for Dealership and Review services
  - Python Flask Microservice with NLTK for Review Sentiment Analysis
- **DevOps & Cloud**: Docker containers, GitHub Actions CI/CD pipeline, IBM Cloud Code Engine deployment

### Features
1. **User Authentication**: Sign-up, login, and session-based logout
2. **Dealer Directory**: Browse dealerships with dynamic filtering by state
3. **Sentiment Analysis**: Machine-learning driven polarity scoring (Positive, Neutral, Negative) for reviews
4. **Car Makes & Models**: Admin-managed vehicle inventories and models
5. **Add Reviews**: Authenticated users can post dealership reviews with car details
