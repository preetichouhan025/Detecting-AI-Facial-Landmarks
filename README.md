# Detecting-AI-Facial-Landmarks

### Detecting AI Facial Landmarks using Tensorflow.js

Open http://itspreeti25.github.io/Detecting-AI-Facial-Landmarks to view it in the browser. (Please give it 10 seconds to render)

This is a small JavaScript React.JS based application to detect Facial Landmarks in real-time using Tensorflow.js pre-trained model. Tensorflow.js's Face Landmark Detection predict 486 3D facial landmarks to baiscally infer the geometrical surface of human face i.e. detecting the coordinates representing eyes, nose, cheeks, mouth etc. and drawing a mesh identifying them all.  

You move your face, the mesh moves along. Face not in the frame, then no mesh. 

- More Information is available here: https://github.com/tensorflow/tfjs-models/tree/master/face-landmarks-detection

- Canvas API is used to dar the mesh over the face using JavaScript and HTML element: https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API


A Facemesh is created detecting human faces.

![Image](https://github.com/itspreeti25/Detecting-AI-Facial-Landmarks/blob/main/src/facemesh.jpeg)

