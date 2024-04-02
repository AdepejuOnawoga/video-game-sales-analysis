markdown
Copy code
# video-game-sales-analysis using Python MYSQL and Python (Pandas)

## Introduction
This project consists of two parts: one utilizing Python with MYSQL and the other utilizing Python with Pandas library for data analysis. Both parts aim to analyze video game sales data.

## Getting Started -Python MYSQL Analysis

### Requirements
- Python 3.x
- pandas
- sqlalchemy
- pymysql

### Installation

1. Install required libraries using pip:
pip install pandas sqlalchemy pymysql

2. Clone the repository:
git clone https://github.com/yourusername/video-game-sales-analysis.git

3. Navigate to the project directory:
cd video-game-sales-analysis

## Running the analysis

### Breakdown of analysis

1.  **Python MYSQL Analysis:**
- Execute the Python script:
  ```bash
  python mysql_analysis.py
  ```
### Description

This part of the project focuses on analyzing video game sales data stored in a MYSQL database. It performs the following tasks:

>   Imports necessary libraries including pandas, sqlalchemy, and pymysql.

>   Connects to a MYSQL database named data1202.

>   Executes SQL queries to analyze the average global sales before and after the year 2005.

>   Prints the results and determines which period had higher average global sales.

2.   **Python Pandas Analysis:**

- Execute the Python script:
  ```bash
  python pandas_analysis.py
  ```

### Description

This part of the project utilizes the Pandas library to analyze video game sales data. It performs the following tasks:

>   Reads a CSV file containing video game sales data.

>   Calculates the average global sales before the year 2005.

>   Compares the average global sales before and after 2005 and prints the result.

## Conclusion

Both Python MYSQL and Python Pandas analyses provide insights into video game sales data, demonstrating different approaches to data analysis using Python.

## Deployment

### Local Deployment

To deploy this project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/video-game-sales-analysis.git```

-  Navigate to the project directory:

 ```bash
 cd video-game-sales-analysis
 ```
 
- Install the required dependencies:

```bash
pip install -r requirements.txt
```
- Run the Python scripts:

**For Python MYSQL Analysis:**
```bash
python mysql_analysis.py
```
**For Python Pandas Analysis:**
```bash
python pandas_analysis.py
```
### Deployment to server

If you want to deploy this project to a server, you can follow these general steps:

- Set up a server environment with the necessary software dependencies (Python, MySQL, etc.).

- Clone the repository onto the server.

- Install the required dependencies using pip.

- Configure the project settings and database connections for the server environment.

- Set up any necessary server configurations (e.g., firewall rules, domain settings).

- Run the Python scripts on the server.

Note: The specific deployment steps may vary depending on your server setup and requirements. It's recommended to consult with your server administrator or follow the deployment guidelines provided by your hosting provider.

## Author
The project was completed by group 4 members of DATA1202 class:
- Kelvin Okpala
- Sheila Odor
- Gabrielle Walters
- Adepeju Onawoga

## License
Include information about the license under which the project is released.

## Acknowledgement
Acknowlwgement goes to our Professor, Omar Al-Trad for seemlessly guiding us into having a high proficiency in data analysis tools. 

The journey wouldn't have been the same without you. Thank you.
