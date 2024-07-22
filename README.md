# Survey-tool-for-collecting-participants-data

# Income Spending Survey Tool

This project involves developing a survey tool to collect participants' data on income and spending in preparation for a new product launch in the healthcare industry. The tool is developed using Flask for web development, MongoDB for data storage, and Python for data processing and visualization.

## Project Structure

- `app.py`: The main Flask application file that handles web requests and renders the HTML form.
- `templates/`: Contains the HTML template for the survey form.
- `static/`: Contains static files such as CSS and JavaScript.
- `data/`: Contains the CSV file generated from the collected data.
- `notebooks/`: Contains the Jupyter notebook for data visualization.

## Setup Instructions

### Prerequisites

- Python 3.7+
- Flask
- MongoDB
- pandas
- Jupyter Notebook
- matplotlib (for visualization)
- AWS account (for deployment)

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/income-spending-survey.git
    cd income-spending-survey
    ```

2. Create a virtual environment and activate it:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

4. Ensure MongoDB is installed and running on your local machine or connect to a MongoDB Atlas cluster.

### Running the Application

1. Start the Flask application:
    ```sh
    python app.py
    ```

2. Open your web browser and navigate to `http://127.0.0.1:5000` to access the survey form.

3. Fill in the survey form and submit the data.

### Data Processing and Visualization

1. After collecting the data, run the Jupyter notebook to process and visualize the data.

2. Navigate to the `notebooks/` directory:
    ```sh
    cd notebooks
    ```

3. Start Jupyter Notebook:
    ```sh
    jupyter notebook
    ```

4. Open the notebook and run the cells to load the data from the CSV file, process it, and generate the visualizations.

## Data

Here is a sample of the dummy dataset used for testing:

| Age | Gender | Total Income | Utilities | Entertainment | School Fees | Shopping | Healthcare |
|-----|--------|--------------|-----------|---------------|-------------|----------|------------|
| 25  | Male   | 50000        | 200       | 150           | 0           | 100      | 75         |
| 30  | Female | 60000        | 220       | 180           | 0           | 130      | 85         |
| 22  | Female | 45000        | 190       | 120           | 0           | 90       | 65         |
| 28  | Male   | 52000        | 210       | 170           | 0           | 110      | 80         |
| 35  | Female | 70000        | 250       | 200           | 100         | 150      | 100        |
| 40  | Male   | 80000        | 270       | 220           | 120         | 180      | 120        |
| 27  | Female | 55000        | 200       | 160           | 0           | 100      | 75         |
| 32  | Male   | 62000        | 230       | 190           | 0           | 140      | 90         |
| 29  | Female | 57000        | 210       | 170           | 0           | 120      | 85         |
| 31  | Male   | 64000        | 240       | 200           | 0           | 150      | 95         |

## Deployment on AWS

1. Create an AWS account and set up a new EC2 instance.

2. Install necessary packages on the EC2 instance (Python, Flask, etc.).

3. Clone the repository on the EC2 instance.

4. Run the Flask application on the EC2 instance and ensure it is accessible via the public IP address.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgements

- Flask documentation: https://flask.palletsprojects.com/
- MongoDB documentation: https://docs.mongodb.com/
- pandas documentation: https://pandas.pydata.org/docs/
- matplotlib documentation: https://matplotlib.org/stable/contents.html
