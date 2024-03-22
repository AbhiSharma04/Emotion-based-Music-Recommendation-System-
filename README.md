
# Emotion-based music recommendation system

This web application offers a unique music recommendation experience by harnessing the power of emotion recognition. Using advanced machine learning and image processing technologies, it personalizes music playlists in real-time based on the user's current emotional state.

# Features
Facial Expression Capture: Leverages OpenCV to accurately capture facial expressions through a webcam interface in real-time.
Emotion Analysis: Employs TensorFlow to run deep learning models, effectively predicting the user's current emotion from the captured facial expressions.
Personalized Recommendations: Integrates emotion analysis results to curate and suggest music that aligns with the user's emotional cues.
Web Application: Built with Django, the system provides a robust and user-friendly interface for interaction and displays the recommended playlist.
Feedback-Informed Iteration: Incorporates user feedback to refine recommendations and enhance the overall experience.

# How It Works

Expression Capture: The user engages with the web application's interface, which accesses their webcam to capture facial expressions.
Emotion Prediction: Captured expressions are fed into a TensorFlow-powered deep learning model that predicts the user's emotion with high accuracy.
Music Matching: Based on the emotion predicted, the system queries an extensive music database to select songs that match the emotional state.
Playlist Delivery: A personalized playlist is dynamically generated and presented to the user, offering a music listening experience tailored to their mood.


## Installation & Run

Create a new project in Pycharm and add the above files. After that open the terminal and run the following command. This will install all the modules needed to run this app. 

```bash
  pip install -r requirements.txt
```

To run the app, type the following command in the terminal. 
```bash
  streamlit run app.py
```

## Libraries

- Streamlit
- Opencv
- Numpy
- Pandas
- Tensorflow
- Keras



## Support

For support,Abhishek Sharma (http://www.linkedin.com/in/asharma04)

