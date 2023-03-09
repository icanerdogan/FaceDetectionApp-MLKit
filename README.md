<h1> Face Detection App </h1>
<p> With ML Kit's face detection API, you can detect faces in an image, identify key facial features, and get the contours of detected faces. Note that the API detects faces, it does not recognize people .

With face detection, you can get the information you need to perform tasks like embellishing selfies and portraits, or generating avatars from a user's photo. Because ML Kit can perform face detection in real time, you can use it in applications like video chat or games that respond to the player's expressions. </p>

<h2> Key capabilities </h2>
<ul>
<li>Recognize and locate facial features Get the coordinates of the eyes, ears, cheeks, nose, and mouth of every face detected.</li>
<li>Get the contours of facial features Get the contours of detected faces and their eyes, eyebrows, lips, and nose.</li>
<li>Recognize facial expressions Determine whether a person is smiling or has their eyes closed.</li>
<li>Track faces across video frames Get an identifier for each unique detected face. The identifier is consistent across invocations, so you can perform image manipulation on a particular person in a video stream.</li>
<li>Process video frames in real time Face detection is performed on the device, and is fast enough to be used in real-time applications, such as video manipulation.</li>
</ul>

<img src="https://raw.githubusercontent.com/icanerdogan/FaceDetectionApp-MLKit/master/documents/Face%20Detect.PNG">

<h2> Face detection concepts </h2>

<p> Face detection locates human faces in visual media such as digital images or video. When a face is detected it has an associated position, size, and orientation; and it can be searched for landmarks such as the eyes and nose.

Here are some of the terms that we use regarding the face detection feature of ML Kit: </p>

<ul>
<li>Face tracking extends face detection to video sequences. Any face that appears in a video for any length of time can be tracked from frame to frame. This means a face detected in consecutive video frames can be identified as being the same person. Note that this isn't a form of face recognition; face tracking only makes inferences based on the position and motion of the faces in a video sequence.</li>
<li>A landmark is a point of interest within a face. The left eye, right eye, and base of the nose are all examples of landmarks. ML Kit provides the ability to find landmarks on a detected face.</li>
<li>A contour is a set of points that follow the shape of a facial feature. ML Kit provides the ability to find the contours of a face.</li>
<li>Classification determines whether a certain facial characteristic is present. For example, a face can be classified by whether its eyes are open or closed, or if the face is smiling or not.</li>
</ul>

<h2> Face Detection App Preview </h2>

Front Camera       |  Rear Camera
:-------------------------:|:-------------------------:
![](https://raw.githubusercontent.com/icanerdogan/FaceDetectionApp-MLKit/master/documents/Front%20Camera.png)  |  ![](https://raw.githubusercontent.com/icanerdogan/FaceDetectionApp-MLKit/master/documents/Rear%20Camera.png)
