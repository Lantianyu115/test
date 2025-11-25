# Yelp Search & Analytics App
 
**Project Option:** NoSQL (Solo)  
**Author:** Zhengjia Zhou  

---

### Project Overview

This is a data-driven web application designed to help users explore local businesses, analyze market trends, and read customer reviews using the Yelp Open Dataset.


### Project Structure

* `app.py`: The main entry point for the Web Application. Contains the UI logic and integrates the custom parser/functions.
* `project.ipynb`: The development notebook containing the raw implementation, validation tests, and debugging of the parser/operations.
* `business.json`: Yelp Business dataset 
* `tip.json`: Yelp Tip dataset 
* `README.md`: Project documentation.


### Prerequisites

To run this project, you need:

1.  **Python** installed on your system.
2.  **Streamlit** library.
3.  **Yelp Dataset Files**: Ensure `business.json` and `tip.json` are present in the **root directory** of the project.


### Installation

1.  Open your terminal or command prompt (e.g., Anaconda Prompt).
2.  Navigate to the project directory:
    ```bash
    cd path/to/your/project_folder
    ```
3.  Install the required UI library:
    ```bash
    pip install streamlit
    ```
    

## How to Run the Application

1.  Ensure your terminal is inside the project folder.
2.  Run the application using the Streamlit command:
    ```bash
    streamlit run app.py
    ```
3.  The application will automatically open in your default web browser.


### Testing the Parser & Functions

If you wish to examine the underlying logic, algorithms, and unit tests for the parser and data operations, please refer to the Jupyter Notebook:

1.  Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
2.  Open **`project.ipynb`**.
3.  Run the cells sequentially to see demonstrations of:
    * Parsing logic tests (Handling Nested objects, Arrays, Booleans).
    * Individual function verification (`filtering`, `join_data`, etc.).


### Acknowledgments

* **Dataset**: Yelp Open Dataset.
* **Tech Stack**: Python (Core Logic), Streamlit (UI).
