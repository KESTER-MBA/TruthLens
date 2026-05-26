TruthLens: An Artificial Intelligence Platform for Fake News Detection

TruthLens is a web-based AI platform that detects and classifies news content as Real, Fake, Misleading, or Satire in real-time. It combines advanced language models with an intuitive interface to help users assess news credibility and combat misinformation.

Live Demo: <https://tlens.netlify.app/>

OVERVIEW

TruthLens provides real-time classification of news content across 4 categories using the Anthropic Claude API. The platform delivers explainable verdicts with confidence scores, a user-friendly interface, session analytics, and media literacy tools.

KEY FEATURES

AI-Powered Detection
Analyzes textual patterns, emotional language, source credibility, and factual consistency. Classifies news as Real, Fake, Misleading, or Satire with confidence scoring.

Explainable AI
Provides plain-language explanations of classification reasoning, extracted claims, and decision factors.

Responsive Design
Works on desktop and mobile. Single Page Application built with modern web technologies.

Session Analytics
Real-time statistics tracking total checked items, real, fake, and unsure counts. Calculates fake news rate.

Media Literacy Tools
Interactive quiz on spotting misinformation and News of the Day dashboard with live headlines.

TECHNOLOGIES USED

Frontend: HTML5, CSS3, JavaScript ES6+
AI Backend: Anthropic Claude API claude-sonnet-4
Deployment: Netlify CDN, Git/GitHub
Communication: HTTPS, REST API, JSON

GETTING STARTED

Access Live Version
Visit <https://tlens.netlify.app/> directly. No installation required.

Local Setup
Clone the repository: git clone <https://github.com/KESTER-MBA/TruthLens.git>
Open index.html in your browser

HOW TO USE

1. Submit news text, headline, or URL in the input field
1. Click Analyze to get classification results
1. View verdict with confidence score
1. Read AI explanation and extracted claims
1. Track session statistics and recent checks

SYSTEM ARCHITECTURE

Three-tier architecture:

Client Layer: HTML5, CSS3, JavaScript on Netlify CDN
Application Layer: Input validation, API communication, DOM management
AI Inference Layer: Anthropic Claude API for classification and reasoning

Privacy-first design: All session data stored locally in browser only. No remote database. No user tracking.

PROJECT OBJECTIVES

AI Detection Engine: Analyzes and classifies news across 4 categories
LLM Integration: Claude API as core inference engine with explainability
Web Interface: Responsive, accessible single-page application deployed live
Performance Evaluation: Tested with diverse news samples
Future Directions: Roadmap for multilingual support and multimodal detection

FUTURE ENHANCEMENTS

Multilingual Support for Nigerian languages, French, Spanish
Multimodal Detection for images, videos, and audio analysis
Browser Extension for inline fact-checking
Social Media Integration with Twitter/X, Facebook, WhatsApp
User Feedback Loop for continuous prompt refinement
Analytics Dashboard for misinformation trend tracking

WHY CLAUDE API

Initial RoBERTa approach failed because it misclassified credible sources and had no explainability. Migrated to Claude API for superior zero-shot reasoning, 4-class classification, native explainability, and better cross-domain generalization.

TEAM
 Project, Babcock University 2025/2026

Bamidele Felix Emmanuel
MBA Kester Jachimike 
Sulaiman Abdul-Qayyum 

CONTACT

Live Demo: <https://tlens.netlify.app/>
GitHub: <https://github.com/KESTER-MBA/TruthLens>
Email: [michealkester16@gmail.com](mailto:michealkester16@gmail.com)

LICENSE

Academic and research use. Part of Babcock University B.Sc. Information Technology program.

Citation: TruthLens: An Artificial Intelligence Platform for Fake News Detection. Final Year Project Defense, Babcock University, 2025/2026
