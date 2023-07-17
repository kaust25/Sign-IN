# Sign IN

Sign IN is a sign language detection application that uses computer vision and deep learning techniques to recognize hand gestures and translate them into corresponding sign language words or phrases. The application consists of three code files: `Custom_Data_Capture.ipynb`, `CNN_Train_Code.ipynb`, and `Model_Gesture_Detection.ipynb`. Below is a brief description of each file and its functionalities.

## Custom_Data_Capture.ipynb

This Jupyter Notebook captures custom data for training the sign language detection model. It utilizes OpenCV to capture frames from a webcam, detect hand gestures, and save them as images for training. The captured images are stored in the specified directory.

## CNN_Train_Code.ipynb

This Jupyter Notebook trains a Convolutional Neural Network (CNN) model using the captured hand gesture images. It uses the Keras library with TensorFlow backend for building and training the model. The CNN model architecture consists of multiple convolutional and dense layers. The trained model is saved for future use.

## Model_Gesture_Detection.ipynb

This Jupyter Notebook uses the trained CNN model to detect hand gestures in real-time. It captures frames from a webcam, segments the hand region, and applies the trained model to recognize the corresponding sign language word or phrase. The detected word or phrase is displayed on the screen.

## Dependencies

The following dependencies are required to run the application:
- Python 3.x
- OpenCV
- NumPy
- TensorFlow
- Keras

Make sure to install these dependencies before running the application.

## How to Use

1. Run the `Custom_Data_Capture.ipynb` notebook to capture custom hand gesture images. Adjust your hand in the designated region of interest (ROI) and follow the on-screen instructions to capture images for different gestures.

2. Run the `CNN_Train_Code.ipynb` notebook to train the CNN model using the captured images. The model will be saved as `best_model_dataflair3.h5` for future use.

3. Finally, run the `Model_Gesture_Detection.ipynb` notebook to detect hand gestures in real-time. The notebook will open a webcam window displaying the captured frames with the recognized sign language word or phrase.

Note: Make sure to adjust the file paths in the code according to your system configuration.

## Community Benefits

Sign IN, the sign language detection application, brings several social benefits to the community, especially for individuals with hearing impairments or those who communicate using sign language. Here are some of the social benefits provided by Sign IN:

### Inclusive Communication:

Sign IN bridges the communication gap between individuals who use sign language and those who are not familiar with it. By translating sign language gestures into corresponding words or phrases, Sign IN enables effective communication between individuals with hearing impairments and the broader community.

### Independence and Empowerment:

Sign IN empowers individuals with hearing impairments by providing them with a tool to express themselves independently. It reduces their reliance on interpreters or third-party assistance in various social settings, enabling them to communicate more confidently and assertively.

### Accessibility to Information:

With Sign IN, individuals with hearing impairments can access and comprehend digital content more easily. They can interact with online platforms, educational resources, and digital media by using sign language, expanding their opportunities for learning, social engagement, and entertainment.

### Inclusive Education:

Sign IN supports inclusive education by facilitating communication between deaf or hard-of-hearing students and teachers. It enables teachers to understand and respond effectively to students' sign language communication, fostering a more inclusive and supportive learning environment.

### Employment Opportunities:

By enhancing communication abilities, Sign IN improves employment opportunities for individuals with hearing impairments. It enables them to participate more actively in job interviews, meetings, and workplace interactions, thereby promoting equal access to employment and career advancement.

### Social Integration and Awareness:

Sign IN promotes social integration by fostering understanding and acceptance of sign language within the wider community. It raises awareness about the unique needs and experiences of individuals with hearing impairments, encouraging empathy, inclusivity, and a more inclusive society as a whole.

By leveraging technology and deep learning, Sign IN contributes to creating a more inclusive and accessible society, where individuals with hearing impairments can actively participate, communicate, and be understood.

Feel free to explore and modify the code to suit your requirements. Enjoy using Sign IN!
