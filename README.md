![Project Status](https://img.shields.io/badge/status-in_progress-yellow)

# Multithreaded-URL-Checker 🚀  

**Multithreaded URL Checker** is a Python tool designed to fetch public API URLs, check their availability using **multithreading**, and log the results in a **CSV file**. This helps improve efficiency and speed in checking multiple URLs concurrently.  

## 📌 Features  
✅ Fetches and checks multiple URLs concurrently using **multithreading**.  
✅ Logs results in a structured **CSV file**.  
✅ Handles **timeouts, connection failures**, and logs errors efficiently.  

## 📜 Initial Design  
Below is the initial design of the project, which includes the core components and their interactions:  

![image](https://github.com/user-attachments/assets/c42a8763-6618-4d73-ae63-037cc0ee4f47)


### **Core Components**  
- **`URLChecker`** → Manages the overall process of checking URLs.  
- **`URLTask`** → Runs individual URL checks using HTTP requests.  
- **`APIHandler`** → Fetches the list of URLs to be checked.  
- **`CSVWriter`** → Writes the results into a CSV file.  
- **`Logger`** → Logs errors, timeouts, and connection failures for debugging.  

⚠️ **Note:** This is the **initial design**, and modifications may be made as the project evolves.  

## 📦 Installation  
