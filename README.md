<h1> Face Detection App </h1>

<p> Welcome to SnapFace: Face Finder AI, the cutting-edge application that revolutionizes face detection using the power of artificial intelligence. Seamlessly designed to work with both front and rear cameras, SnapFace intelligently identifies and locates faces with unparalleled precision, making every snapshot a memorable experience. </p>

<a href="https://play.google.com/store/apps/details?id=com.ibrahimcanerdogan.facedetectionapp"><img width="90" height="90" src="https://img.icons8.com/?size=512&id=L1ws9zn2uD01&format=png"/></a>

<b><u><a href="https://medium.com/@ibrahimcanerdogan/face-detection-app-with-mlkit-android-696ce42d4be4" target="_blank"> MEDIUM </a></u></b>

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

<h2> LICENSE </h2>

````
MIT License

Copyright (c) 2023 İbrahim Can Erdoğan

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
