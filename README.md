# Adaptive-DDoS-Attack-Recognition-Using-Advanced-Machine-Learning-Classifiers-
Adaptive DDoS Attack Recognition Using Advanced Machine Learning Classifiers is a cybersecurity project that detects both known and new DDoS attacks. It uses Reciprocal Points Learning for Open-Set Recognition and machine learning models like Passive Aggressive, Random Forest, and Decision Tree. 

This repository contains the implementation of the Adaptive DDoS Attack Recognition system, which leverages advanced machine learning classifiers to detect known and unknown Distributed Denial of Service (DDoS) attacks. The project introduces a novel Reciprocal Points Learning framework tailored for Open-Set Recognition, enabling robust detection of both traditional and evolving attack patterns.

The system is designed with a user-friendly web interface, allowing users to upload network traffic data in CSV format for analysis. The framework applies machine learning algorithms such as Passive Aggressive Classifier, Random Forest, and Decision Tree to distinguish between normal and malicious network behavior effectively.
Features

    Detection of Unknown Attacks
        Implements Reciprocal Points Learning for Open-Set Recognition, targeting new and unforeseen DDoS attack patterns.

    Machine Learning Models
        Utilizes Passive Aggressive Classifier, Random Forest, and Decision Tree for traffic analysis and classification.

    Web Interface
        Includes a registration and login system.
        Allows CSV file uploads for network traffic analysis.
        Provides clear results on whether the data indicates a DDoS attack.

    Extensive Dataset Support
        Trained and validated on diverse datasets, including CIC NIDS datasets (IDS2017, IDS2018, etc.).

Objectives

    Enhance detection of both known and unknown DDoS attacks using advanced machine learning techniques.
    Adapt to dynamic network environments and emerging attack patterns.
    Validate the framework through extensive testing on real-world datasets.

Outcomes

    Significant improvement in the accuracy of detecting DDoS attacks.
    Reliable performance in dynamic and real-world scenarios.
    High adaptability to new and unforeseen network threats.

Installation and Setup
Prerequisites

    Python 3.8 or higher
    Required libraries: pandas, numpy, scikit-learn, flask, matplotlib

Steps to Run

    Clone the repository:

git clone https://github.com/yourusername/adaptive-ddos-detection.git  
cd adaptive-ddos-detection  

Install dependencies:

pip install -r requirements.txt  

Run the application:

    python app.py  

    Access the web interface at http://localhost:5000.

File Structure

    app.py: Main Flask application file.
    models/: Contains the machine learning models.
    data/: Example datasets for testing.
    static/: Static files (CSS, JS).
    templates/: HTML templates for the web interface.
    requirements.txt: List of required Python libraries.

Usage

    Register or log in through the web interface.
    Upload a CSV file containing network traffic data.
    View the analysis results to determine if the data contains DDoS attacks.

Contribution

Contributions are welcome! Please create a pull request with your proposed changes.
License

This project is licensed under the MIT License.
