# Streetview_HouseNumber_Recognizer

**Objective**: Build a live camera app that can interpret number strings in real-world images.

<p>
<img src="https://lh3.googleusercontent.com/KYNMyzs3qlkIs11aDbnRqd86JgojF4Ha-215a7JM4rIsJBl33omWPj7aV19e4TTeePHzO_RaKe5KvGq6KdSBr_AiH4m9cFj855L28-BHdKvSRQc1swkj4MmkCinyXuFhY5UzIII9" alt="Camera" style="width: 20%"/> >>> 31 </p>


In this project, I will train a model that can decode sequences of digits from natural images, and create an app that prints the numbers it sees in real time. 

The solution is based on deep learning. After preprocessing data, we create and train a Convolutional neueal network to recognize digits in realworld images. We then save and reuse the model in our application (Native android or web based .. haven't decided yet).


### Setup

Python
NumPy, SciPy, iPython
TensorFlow

### Data
[Street View House Numbers (SVHN): A large-scale dataset of house numbers in Google Street View images.]
(http://ufldl.stanford.edu/housenumbers/)
