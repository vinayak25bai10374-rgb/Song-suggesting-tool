# Song Recommendation System (Machine Learning from Scratch)

This project is a simple song recommendation system built using Python. It uses a basic machine learning approach implemented from scratch to suggest songs based on user-selected genres.

The goal of this project is to understand the core concepts of machine learning, including data preprocessing, model training, and optimization, without relying on high-level libraries like sklearn.

---

## Project Overview

The system recommends songs by analyzing a dataset containing song names, genres, and popularity scores. It trains a simple linear model using gradient descent and ranks songs accordingly.

---

## How It Works

1. Load a real-world Spotify dataset from an online source  
2. Clean and preprocess the dataset  
3. Convert categorical genres into numerical values  
4. Train a linear regression model using gradient descent  
5. Run training for 40 epochs  
6. Plot the loss curve to visualize learning  
7. Recommend top songs based on the selected genre  

---

## Features

- Uses a real-world dataset  
- Machine learning model implemented from scratch  
- No use of sklearn or advanced ML libraries  
- Gradient descent optimization  
- Loss visualization using Matplotlib  
- Handles user input in any format (uppercase or lowercase)  
- Simple and beginner-friendly implementation  

---

## Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  

---

## Dataset Source

The dataset is loaded directly from the following link:

---

## How to Run

1. Open Google Colab or any Python environment  
2. Copy and paste the full code into a cell  
3. Run the program  
4. Enter a genre when prompted  
5. View recommended songs based on the trained model  

---


---

## Output

- The model trains over 40 epochs  
- Loss decreases over time  
- A graph is displayed showing the learning curve  
- Top songs are recommended based on genre and predicted score  

---

## Future Improvements

- Add more features such as danceability, energy, and tempo  
- Improve recommendation accuracy using multiple inputs  
- Build a user interface using Streamlit  
- Integrate with real-time APIs like Spotify  

---

## Conclusion

This project demonstrates how a basic recommendation system can be built using fundamental machine learning concepts. It is ideal for beginners who want to understand how models work internally without relying on external libraries.
