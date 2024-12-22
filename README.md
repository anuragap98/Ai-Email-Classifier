![Compatibility](https://img.shields.io/badge/compatible%20with-python3.8.x-blue.svg)
# AI Email Classifier
[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)
[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)  


##### An AI Application for classifying emails into categories

### Features :octocat:  
* **Leverages both Machine Learning (ML) and Deep Learning (DL) models:**
	* Offers flexibility and the ability to choose the most suitable model for different datasets and classification tasks.
* **High Accuracy:** Demonstrates high accuracy on unseen datasets, ensuring reliable and effective email categorization.
* **User-Friendly Web Interface:** Provides a clean and intuitive interface for:
	* Training: Easily train and fine-tune the models using labeled email datasets.
	( Testing: Conveniently test the classifier with individual emails or batches of emails.
* **REST API Gateway:** Enables seamless integration with other applications:
	* Single Email Classification: Classifies a single email by sending its subject and body in a request.
	* Batch Email Classification: Efficiently classifies a large number of emails in a single API call.
 

### Prerequisites: :book:

* Git: If you haven't already, install Git from https://git-scm.com/downloads.
* Python 3.x: Download and install Python 3 from https://www.python.org/downloads/.

### Installation: :rocket:

1. Open a terminal or command prompt and navigate to your desired project directory. Then,
   * Run the following command to clone the Ai Email Classifier repository from GitHub:
	   ```bash
	   git clone https://github.com/TheThinker01/AiEmailClassifier.git
	   ```
   * Install Python `virtualenv`
	   ```bash
	   pip install virtualenv
	   ```
3. Create and Activate a Virtual Environment (Recommended):
	   ```bash
	   virtualenv env        # Create a virtual environment named 'env'
	   source env/bin/activate  # Activate the virtual environment (Linux/macOS)
	   ```
   * For Windows, activate the virtual environment using:
	   ```bash
	   env\Scripts\activate.bat # Activate the virtual environment (Windows)
	   ```

4. Install all the dependencies -
   ```bash
   pip install -r Requirements.txt
   ```
6. Run the Server - 
   ```bash
   python manage.py runserver 127.0.0.1:8000
   ```
7. Access the Application:
   * Open the specified URL (e.g., http://127.0.0.1:8000/ml) in your web browser. :tada:

> ### Requirements 
* All required packages and libraries are listed in the Requirements.txt file.


> ### Credits - Collaborative Effort by Team - AI200416
* Thanks to the following contributors: [Archisman Pathak](https://github.com/TheThinker01)
