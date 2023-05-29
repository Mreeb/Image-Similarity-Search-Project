# Image-Similarity-Search-Project
It involves building a system to find similar images based on their visual features using techniques such as image preprocessing, feature extraction, and nearest neighbors search.
Here are some key components of your project:

Data Collection: Gathering image data from various sources, including URLs, and storing relevant attributes associated with each image.

Data Preprocessing: Downloading images from URLs, converting them to a consistent format, resizing them, and storing them for further processing. Additionally, handling error cases where images fail to download.

Feature Extraction: Utilizing computer vision techniques to extract meaningful features from the preprocessed images. In your case, you used a pre-trained model to extract features from images and represent them as vectors.

Nearest Neighbors Search: Building a model, such as the NearestNeighbors model, to efficiently search for similar images based on the extracted features. This involves fitting the model with the image vectors and performing queries to find the closest matches to a given query image.

Attribute Display: Displaying the attributes associated with the similar images to provide additional information to the user. You modified the code to include attributes like series title, issue number, issue comments, issue edition, published date, comic era, issue image, and issue image URL.

Model Persistence: Saving the trained model and image details to disk, allowing for future reuse without the need to retrain the model or preprocess the images again.
