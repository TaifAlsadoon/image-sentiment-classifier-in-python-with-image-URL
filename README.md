# image-sentiment-classifier-in-python-with-image-URL


The goal of this code is to create a simple image sentiment classifier that can determine whether an image has a positive, neutral, or negative sentiment based on the image's visual features.










The key goals of this code are:


1.Load and preprocess the image: The code takes an image URL as input and uses the requests library to fetch the image data. It then preprocesses the image by converting it to grayscale and applying edge detection using OpenCV.



2.Extract a visual feature: The preprocessed image data is then used to calculate the total number of edge pixels in the image, which is used as a visual feature to represent the image.




3.Classify the image sentiment: The code uses a simple rule-based sentiment classifier to determine the sentiment of the image based on the total number of edge pixels. If the edge pixel count is below 10,000, the image is classified as "Positive"; if it's between 10,000 and 20,000, it's classified as "Neutral"; and if it's above 20,000, it's classified as "Negative".



4.Provide the classified sentiment: The code maps the numerical classification result to the corresponding sentiment class (Positive, Neutral, or Negative) and returns the classified sentiment.

<img width="1440" alt="Screenshot 1446-02-15 at 1 19 36 PM" src="https://github.com/user-attachments/assets/d4627849-9d77-41a2-aa55-cdd935b82fb2">
<img width="1440" alt="Screenshot 1446-02-15 at 1 21 09 PM" src="https://github.com/user-attachments/assets/9286a4ec-6e66-42f5-9631-1f2bcc8d5631">
<img width="1440" alt="Screenshot 1446-02-15 at 1 21 20 PM" src="https://github.com/user-attachments/assets/50b02ddd-9803-469f-b4ad-a88bb880accd">
![Image 15-02-1446 AH at 2 18 PM](https://github.com/user-attachments/assets/75ee1585-6322-49b7-857f-bd63998a9833)
