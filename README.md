# Crop Yield Predictor: Making Agriculture Data-Driven

*A Simple Linear Regression approach to predicting harvest based on rainfall.*


## The Big Idea
Agriculture is the backbone of the economy, but it’s often a gamble based on the weather. For my **Bring Your Own Project (BYOP)** capstone, I wanted to build something that takes the "guesswork" out of farming. 

This project uses **Linear Regression**—a core concept from our course—to analyze how annual rainfall (mm) affects total crop yield (kg/hectare). By looking at historical patterns, this tool helps provide a realistic estimate of what a harvest might look like, helping farmers plan their resources and finances better.


##  Why this fits our Course
I’ve designed this project to demonstrate the concepts we covered across **Modules 1 through 5**:

* **Intelligent Agents (Module 1):** The predictor acts as a *Problem Solving Agent* that perceives environmental data (rainfall) and acts on it to provide a rational prediction.
* **Statistical Foundations (Module 3):** Before modeling, the code calculates the **Mean and Variance** of the dataset to ensure the data is balanced and reliable.
* **Machine Learning Logic (Module 4):** This is the heart of the project. I implemented a **Simple Linear Regression** model and used an **80/20 Train-Test Split** to validate that the model actually learns and doesn't just "memorize" the data (preventing overfitting).
* **Real-world Application (Module 5):** It follows the industry workflow of data representation, feature learning, and practical deployment.

---

## The Mathematics Behind It
The model finds the "Line of Best Fit" using the classic linear equation:

y = mx + c

* **y**: The Predicted Yield (what we want to find).
* **x**: The Rainfall input (what we already know).
* **m**: The Slope (how much the yield changes per unit of rain).
* **c**: The Intercept (the baseline yield).


## Tech Stack
* **Language:** Python 3
* **Libraries:** * `Pandas`: For handling the CSV data.
    * `Scikit-Learn`: For the Linear Regression engine.
    * `Matplotlib`: To visualize the results with a clear scatter plot.

---

##  How to Run It
1.  **Clone the Repo:**
    
https://github.com/Akkshat-0307/Crop-Yield-Predictor.git
    
2.  **Install Dependencies:**
    
    pip install pandas matplotlib scikit-learn
    
3.  **Launch the Predictor:**
    
    python predictor.py
    
4.  **Get a Prediction:** Enter any rainfall value (e.g., `750`) when prompted to see the estimated yield!


**Author:** Akkshat Goel (25BAI11134)
**Course:** Fundamentals of AI and ML

![p3](https://github.com/user-attachments/assets/8576c00e-94b6-4523-bc2e-b16e18b8b9ea)
![p2](https://github.com/user-attachments/assets/f8dd76e1-b8b6-4a0a-85db-b3a837805d6e)
![p1](https://github.com/user-attachments/assets/2b931ffd-25b2-42af-9be4-e5cfa47d5db1)
![p4](https://github.com/user-attachments/assets/04cbc327-1242-4ce8-a39d-f0af4b15193b)

