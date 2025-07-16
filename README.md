=>>Predicting Customer Decisions with a Decision Tree
In this project, I explored real-world  **Bank marketing data** from a Portuguese bank to predict whether a customer will subscribe to a **term deposit**. I used a **Decision Tree Classifier** and visualized the model in a way that's both informative and easy to understand.

All of this was done using **Jupyter Notebook**, making the process interactive, beginner-friendly, and transparent.

-> Project Goal
> *“Based on a customer’s profile and past interactions, can we predict if they’ll say ‘yes’ to a term deposit offer?”*

This is done by:
* Preprocessing and encoding the dataset
* Splitting the data into training and test sets
* Training a **Decision Tree Classifier**
* Visualizing the decision tree to see how predictions are made

 ->Dataset Overview
* **Dataset Name:** `bank-additional-full.csv`
* **Separator:** `;`
* **Target Variable:** `y` (whether the client subscribed to a term deposit: yes/no)

-> Features include:
* Age, Job, Marital Status, Education
* Contact method (cellular, telephone)
* Previous marketing outcomes
* Duration and frequency of contact
* Economic indicators (like employment variation rate)

-> Tools & Technologies
* **Language:** Python
* **IDE:** Jupyter Notebook
* **Libraries:**
  * `pandas` – for data manipulation
  * `scikit-learn` – for model building
  * `matplotlib` – for decision tree visualization

-> How to Run the Project
1. Make sure the file `bank-additional-full.csv` is in your project folder.
2. Open the Jupyter Notebook.
3. Run each cell step-by-step.
4. A **decision tree diagram** will be generated showing how the model makes predictions.

 ->What You'll See in the Output
The final output is a **decision tree plot** that:
* Highlights the most important features
* Shows how data splits at each node
* Clearly visualizes when the model predicts “yes” or “no”

-> Why Use a Decision Tree?
* It’s easy to **interpret**
* Great for **visual storytelling**
* Helps in understanding **what factors matter most** in customer decisions
