🏏 IPL Score Predictor
🚀 Project Overview
The IPL Score Predictor is an AI-based project designed to predict the total score of a team in an IPL match. It analyzes match data such as venue, batting team, bowling team, striker, and bowler to estimate the score. Built using deep learning, the model uses a trained neural network and offers a simple interface for real-time predictions.

🌟 Features
🔹 Data Preprocessing
Handled missing values and cleaned the dataset.

Encoded categorical variables like teams and players.

Applied MinMaxScaler to normalize the feature set.

🔸 Model Training
Designed and trained a Neural Network model.

Used Dense Layers with ReLU activation.

Implemented Huber Loss and Adam Optimizer for better performance.

🔹 Interactive Prediction Interface
Developed using ipywidgets.

Allows users to input match details and get predicted scores instantly.

🔸 Model Evaluation
Evaluated model performance using:

Mean Absolute Error (MAE): 11.71

Mean Squared Error (MSE): 330.16

R² Score: 60.8%

📊 Dataset
The model was trained using historical IPL match data containing the following features:

Match venue

Batting team

Bowling team

Striker

Bowler

Final score of the batting team

🧠 AI Techniques
🏗️ Neural Network Architecture
Multiple dense layers for capturing complex data relationships.

ReLU activation function in hidden layers.

📉 Loss & Optimization
Used Huber Loss to handle outliers effectively.

Trained with Adam Optimizer for efficient learning.

🛠 Tech Stack & Tools

Category	Technologies Used
Programming	Python
Libraries	Pandas, NumPy, Scikit-learn, TensorFlow/Keras, ipywidgets
Platform	Google Colab, Visual Studio Code
🔥 Challenges Overcome
Model Optimization: Tuned hyperparameters to improve accuracy and reduce prediction error.

Interface Integration: Successfully linked the trained model with an interactive input tool using ipywidgets.

📈 Roadmap & Future Scope
🏆 Expand prediction support for other leagues like PSL.

🌦️ Include weather and pitch conditions for more accurate forecasts.

📱 Enhance the user interface for broader accessibility and better user experience.

👨‍💻 Team Members
M Attaullah (Leader) – Designed and trained the model, led the project, and evaluated model performance.

M Haris Nisar – Collected and cleaned data, performed preprocessing and analysis.

Abdul Rehman – Focused on model tuning, evaluation, and testing.

M Muqaddas Ali – Developed the interactive user interface using ipywidgets.

🤝 Get in Touch!
Passionate about AI, Cricket, and data-driven solutions? Let’s connect and share ideas!

M-Attaullah

Muhammad Attaullah

