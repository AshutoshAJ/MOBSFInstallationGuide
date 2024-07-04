## Installing and Running MobSF for Local Analysis

#### MobSF (Mobile Security Framework) is an automated, all-in-one mobile application
(Android/iOS/Windows) pen-testing, malware analysis, and security assessment framework. Running MobSF locally ensures that your analysis results remain private.

##  Steps to Install and Run MobSF
#### Clone the Repository First, clone the MobSF repository from GitHub: 
``git clone https://github.com/MobSF/Mobile-Security-Framework-MobSF.git``  
Then,  
``cd Mobile-Security-Framework-MobSF``

### 1. Install Python 3.11

Make sure you have Python 3.11 installed on your machine. You can download it from the [official Python website](https://www.python.org/downloads/).  
Or if use brew:  
``brew install python@3.11``

### 2. Create a Virtual Environment

Create a virtual environment to manage dependencies and avoid conflicts:  
``python3.11 -m venv venv source venv/bin/activate``  

### 3. Install `wkhtmltopdf` (pdfkit)

Install `wkhtmltopdf`, which is required for generating PDF reports:  
``brew install wkhtmltopdf``  

### 4. Run the Setup Script

Run the MobSF setup script to install all necessary dependencies:  
``./setup.sh``  

### 5. Start MobSF

Start MobSF by running the following command:  
``./run.sh``  

### 6. Access the MobSF Web Interface

Open your web browser and navigate to `http://localhost:8000/` to access the MobSF web interface. Here, you can start analyzing your mobile applications locally.
