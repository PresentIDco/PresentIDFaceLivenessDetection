### Face Liveness Detection

PresentID Facial liveness detection can recognize the person in front of the video is real or fake. It can detect if the user is physically present and prevents masks, photos, or video deepfakes to fool the system. We use the convolutional neural network (CNN) deep learning algorithms to prevent fraud.
In our solution, there are a client and server-side processes. Each side consists of several machine learning algorithms.

Our processes on the client side are done with our client SDK that is provided for IOS, Android, and Web. In the client SDK, we check that face should be in the camera all the time of the procedure and if we couldn’t find the face in all the frames then the process is stopped. Also, we check the gaze and head pose of the user in each frame. The gaze model is used to check eye closeness(if the user is asleep or not). Head pose checking is used to prevent the diversity of data. That helps our 3D liveness model to train better and easier. This gaze and pose detection don’t complicate the user act and on the other side keeps the system safer. Besides that, in the whole procedure, a user should fit his face on an oval. We generate the random oval in the random position of the screens. Showing random oval in random positions on the screen has two advantages. First, that prevents injection. Second, that movement makes bold some spoofing clues for attacks. Moreover, we collect 30 image frames from the client side.
On the server-side, our 3D face anti-spoofing model which is the convolutional model that has been trained based on our data uses 30 frames in the video and extracts a depth map that is able to detect the depth and is able to detect spoof attacks based on depth detection. Providing Data for the training models was the main challenge. Our team collects a large dataset from our first attendance app. Also, we have crawled social networks to collect a large video dataset and then clean and create spoof data from them.

![live-crop](https://user-images.githubusercontent.com/63470748/119773316-50bdd000-be75-11eb-9461-c4e501f0f14a.png)

**Face Liveness Detection Videos on Youtube**

- https://youtube.com/shorts/VUrcFRvrDdM?feature=share
- https://youtube.com/shorts/8DUtEdBQFaI?feature=share
- https://youtu.be/8jMVPDhZa18
- https://youtu.be/bZRAP8OAu5U
- https://youtu.be/Nia-5Npzsbg
- https://youtu.be/uJJRdUe7Gos

**Ability & Potentials:**
- We process video frames & it takes 2-5 seconds on the client-side & Less than 1.5 seconds on the server-side with a Core i7 CPU.
- CPU based server-side.
- Verify 3-Dimensionality.
- Verify identity.
- Great with glasses, makeup & beards
- For all modern smart devices & webcams.
- Support IOS, Android devices.
- Web client SDK & API.
- Easy integration with your app

**Use Cases:**
- Attendance systems
- Dating websites
- Digital banking
- Visitor identification
- Expedited service
- Access management
- Public safety
- Fraud prevention
- Know your customer
