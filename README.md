## WEATHER DASHBOARD

**Description:** Building a weather data collection system using AWS S3 and OpenWeather API  
Source: Day 1 of 30 days DevOps Challenge

---

### Project Overview
This project combines:  
a. External API Integration (Open Weather API)  
b. AWS S3  
c. IaaC  
d. Version Control (Git)  
e. Python Development  
f. Error/Bug fixing  
g. Environment Management  

---

### Features
- Fetches real-time weather data for multiple cities (focused on Seattle, New York, and Philadelphia)
- Displays temperature in °F, humidity, and weather conditions
- Automatically stores weather data in AWS S3
- Supports weather tracking for multiple cities
- Timestamps all data for historical tracking

---

### Technical Architecture
- **Language:** Python 3.x  
- **Cloud Provider:** AWS  
- **External API:** OpenWeather API  
- **Dependencies:**
  - boto3 (AWS SDK)
  - python-dotenv
  - requests

### Project Structure
weather-dashboard/ ├── src/ │ ├── init.py │ ├── weather_dashboard.py ├── tests/ ├── data/ ├── .env ├── .gitignore └── requirements.txt

## Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Debby77/weather-dashboard.git

2. **Navigate to the project directory:**
   ```bash
   cd weather-dashboard
   
3. **Install dependencies:**
   First off, Verify Python Installation: Run the following command to check if Python is installed:
   ```bash
   python --version
   
   Or
   
   python3 --version
    
4. **If Python is not installed, download and install it from python.org**

5. **Ensure Pip is Installed: If Python is installed but pip is not, install it using:**
   ```bash
    python -m ensurepip --upgrade
 Alternatively:
                    
    python -m pip install --upgrade pip

6. **Install Requirements: Run the following command to install project dependencies:**
       ```bash


       pip install -r requirements.txt
   **OR**
   **On macOS, you may need to use:**

    ```bash
   python3 -m pip install -r requirements.txt

7. **Configure your environment variables:**
   **Create a .env file in the root directory.**
   **Add your OpenWeather API key and AWS credentials to the file:**

    ```bash
   OPENWEATHER_API_KEY=your_api_key
   AWS_ACCESS_KEY_ID=your_access_key
   AWS_SECRET_ACCESS_KEY=your_secret_key
   AWS_BUCKET_NAME=your_bucket_name
   AWS_REGION=your_region
 8. **Run the application: Execute the following command to start the application:**

    ```bash

    python src/weather_dashboard.py


### Project Reactions!
This was the result of this Project. I am elated and excited to have completed Day 1 of the 30 Days DevOps Challenge. Looking forward to more!
![image](https://github.com/user-attachments/assets/c1beb522-0df1-4ba6-a636-c4089ecc4b20)


What I Learned in this project    
1. AWS S3 bucket creation and management    
2. Environment variable management for secure API keys    
3. Python best practices for API integration    
4. Git workflow for project development    
5. Error handling in distributed systems    
6. Cloud resource management    

Possible Future Enhancements:    
1. Add weather forecasting    
2. Implement data visualization    
3. Add more cities    
4. Create automated testing    
5. Set up CI/CD pipeline
