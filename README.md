# Fruit Detector — Teachable Machine Project

## Project overview
Fruit Detector is a browser-based image-classification website. It uses a model trained and hosted with Google Teachable Machine. Users can identify fruit in either of two ways:
1. Start a webcam and hold a fruit in front of it for live predictions.
2. Upload a picture of a fruit and click **Identify fruit**.

The page displays the class names and confidence percentages returned by the model.

## Existing model
This project uses the Teachable Machine model link supplied by the project creator:
https://teachablemachine.withgoogle.com/models/u6A7u-03t/

## Technologies used
- Google Teachable Machine
- TensorFlow.js
- HTML, CSS and JavaScript
- GitHub Pages

## How to use
1. Open the published website using Chrome or another modern browser.
2. Wait for the model to load.
3. Choose **Start webcam** and allow camera permission, OR choose an image file.
4. For an uploaded image, click **Identify fruit**.
5. Read the predicted fruit class and confidence percentages.
6. Stop the webcam when finished.

## Important notes
- Webcam access requires the user's permission and normally works on HTTPS or localhost. GitHub Pages sites are served over HTTPS.
- The model can only recognize the classes it was trained on. The exact fruit labels depend on the training data in the original Teachable Machine project.
- Predictions are estimates, not guarantees. Use clear images and good lighting.
- The page loads TensorFlow.js and the Teachable Machine image library from public CDNs, so an internet connection is required.

## GitHub Pages deployment
1. Create a public GitHub repository, for example `Teachable-Machine-Project`.
2. Upload `index.html` and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then save.
6. Wait for GitHub Pages to publish the site. Copy the website URL shown in the Pages settings.

## Project status
Website source code and documentation are prepared. Before submission, publish the repository and test both webcam and picture-upload modes with examples of the fruits included in the model's training classes.
