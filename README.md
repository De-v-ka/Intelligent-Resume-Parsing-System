# Intelligent Resume Parsing System with SBERT & TF-IDF



## Overview
An AI-powered resume parsing system that:
- Automatically categorizes resumes into job categories with **98% accuracy**
- Computes ATS compatibility scores when Job Descriptions (JDs) are provided
- Ranks resumes by relevance to specific job openings
- Combines SBERT embeddings with TF-IDF features for optimal performance

## Key Features

### Core Capabilities
- **Resume Categorization**: Predicts job categories (Engineering, Marketing, Healthcare, etc.)
- **ATS Scoring**: Evaluates resume-JD compatibility using semantic matching
- **Ranking System**: Prioritizes resumes by relevance to job requirements
- **Multi-Format Support**: Processes PDF, DOCX, and TXT resume formats

### Technical Highlights
- **Hybrid Model Architecture**:
  - SBERT (Sentence-BERT) for semantic understanding
  - TF-IDF for keyword-based features
  - Ensemble classifier (98% accuracy on test set)
