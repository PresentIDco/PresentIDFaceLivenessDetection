# PresentIDFaceLivenessDetection
What is Liveness Detection?

PresentID Facial liveness detection can recognize the person in front of the video is real or fake. It can detect if the user is physically present and prevents masks,photos, or video deepfakes to fool the system.We use Convolutional Neural Network (CNN) deep learning algorithms to prevent fraud.

We use combination of bio-metric authentication algorithms such as face, voice, Eye , head detection & tracking to have a highest accuracy to prevent fraud.
PresentID Face Liveness Detection Demo Youtube Video
Ability & Potentials:

    Comparing the photo & Selfie, verifies if the person is real or fake.
    We do not store the user data at any part of the procedure.
    It recognizes all faces of people, not relies on their age, gender & region.
    It can be performed in any devices independent from the type of OS.

How to try it?

1- Record a Velfie (Video Selfie)
2- Upload file to API
3- See the result (JSON result is available)
PresentID Face Liveness Detection Tutorial Youtube Video
Record a video selfie (Velfie):

    Keep your hand in the about 40 cm distance. Put your face in the center of frame. Keep your head straight and fixed, with straight look. Now you can start recording. Then close the camera to your face, keeping same position and you can stop it when your face get fit the frame by sides.

Call API

As you can see in the sample code, the video file in multipart / Form-data format must be sent to the API. Note that do not send the file as base64in any way. Depending on the programming language you use, you can integrate with the service in the sample codes section.
