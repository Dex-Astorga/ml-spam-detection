# TEXT MESSAGE SPAM DETECTION MACHINE LEARNING PROJECT
This project is a retrospective on our machine learning capstone projects during the first semester of our senior year in college. Back in early 2023, spam messaging was rampant in the Philippines. It was a significant social issue that the country was grappling with, to the extent that an act needed to be passed to address this problem—the Sim Registration Act. During the peak of malicious spamming in the Philippines, our group decided to create a machine learning model for classifying text messages as spam or not. 
This GitHub project serves as a reflection on that undertaking, along with the decisions and changes I would have considered if I could go back in time, including project organization and clean code practices.

### Table of Contents:
#### Project Overview
#### Installation
#### Full Documentation File
#### Model Architecture
#### Technologies Used
#### Contributing
#### License


### Project Description:
This project focuses on finding the optimal model for text message spam classification through a detailed process:

1. **Dataset Partitions**: The ham-spam dataset is divided into three partitions, all representing "ham to spam" ratios: 70-30, 60-40, and 50-50. These partitions are used for training and testing machine learning models, independent of each other.

2. **Model Selection in Each Partition**: Out of 11 different classification algorithms, the best model was identified by training all the models using default parameters and cross validating the results, (hold out validation was done but not considered in selecting best model because of bias).

3. **Model Optimization**: All the best models from each partition were further optimized to enhance their performance.

4. **Model Comparison**: After optimization, I compared the performance of these models to select the best-performing one among them.

5. **Interactive Terminal App**: The selected best-performing model is integrated into a simple interactive terminal app named -- app.py. This app allows users to test the model's spam classification capabilities.


### Installation:
This project includes all of the datasets and notebooks that are used in the entire project. To make this interactive, I created a simple terminal app to accompany the project.
To use this Text Message Spam Detection App on your local machine, follow these steps:

1. **Clone the Repository:** Begin by cloning the project repostory using Git.
2. **Navigate to the Project Directory:** Go to the project directory using your command prompt or terminal.
3. **Create a Virtual Environment (Optional but Recommended):** For a cleaner setup, consider creating a virtual environment:
   - python -m venv venv

   - Activate the virtual environment based on your operating system:
   - On Windows:
     venv\Scripts\activate

   - On macOS and Linux:
     source venv/bin/activate

4. **Install Required Packages:** Install the necessary Python packages for the project:
   - pip install -r requirements.txt

5. **Run the Application:** Launch the interactive Text Message Spam Detection application:
   python app.py

This will start the application, allowing you to input text messages for spam classification. You can now explore and assess the performance of the spam detection model, with a focus on handling imbalanced data.

<br>

### Full Documentation File:
 
This [document](https://github.com/Dex-Astorga/coffee-shop-ecom/blob/main/design_guide_coffee_shop.pdf) is a thorough walk through of everything you need to know to use this project. 

<br>

### Database Schema:

![Project Architecture](https://github.com/Dex-Astorga/coffee-shop-ecom/blob/main/online_store_coffee_shop.png?raw=true)

<br>

### Technologies Used:

- **Machine Learning Framework:** Scikit-Learn
- **Data Analysis:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Model Serialization:** Joblib
- **Version Control:** Git
- **Development Tool:** Visual Studio Code
- **Notebook Environment:** Jupyter Notebooks
- **ERD Development Tool:** Lucidchart

<br>

### Contributing:

#### Reporting Issues

If you encounter a bug or have an idea for improvement:

1. **Submit an Issue:** Visit the [issue tracker](https://github.com/Dex-Astorga/coffee-shop-ecom/issues) and create a new issue.
2. **Provide Details:** Clearly describe the problem or feature request.
3. **Stay Engaged:** Check for updates on your issue.

#### Code Contributions

Interested in contributing code? Follow these steps:

1. **Fork & Clone:** Fork the repository and clone it to your machine.
2. **Create a Branch:** Make a new branch for your changes.
3. **Code:** Write your code, adhering to any guidelines if available.
4. **Test:** Ensure your changes work and add tests if relevant.
5. **Pull Request:** Open a pull request from your branch.

#### Contribution Guidelines

- Maintain a polite and collaborative tone in discussions.
- Align contributions with project goals and your vision.

Feel free to reach out with questions or concerns codex1727@gmail.com

<br>

### License:

This project is licensed under the MIT License.

MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

