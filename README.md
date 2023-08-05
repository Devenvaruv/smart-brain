# Face Recognition App

This is a Face Recognition App built using React.js and the Clarifai API for face detection. The app allows users to register, sign in, and use a facial recognition feature to detect faces in images.

# Features
Sign In and Register: Users can create accounts or sign in to their existing accounts.
Face Recognition: After signing in, users can enter an image URL in the input field and click the 'Detect' button to detect faces in the image. The app will highlight the detected faces with bounding boxes.

# App Components
The app is composed of the following components:

App: The main component that handles the app's state and logic.

FaceRecognition: Renders the image with detected faces highlighted.
Navigation: Displays navigation options based on user authentication status.
Signin: Provides a form for users to sign in to their accounts.
Register: Provides a form for new users to register.
Logo: Renders the logo of the app.
ImageLinkForm: Allows users to input an image URL and submit it for face detection.
Rank: Displays the user's name and rank based on their number of entries.
