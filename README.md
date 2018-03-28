# FaceExpressionDetection
The purpose of this project is to write an OPENCV project which can detect a winking face or a “shush” expression on different images.
  To run, put the image folders and the source code in the same folder and run
“python DetectShush.py ShushImages” or “python DetectWink.py WinkImages”.
  If the image folder is missing, the python code will run in video mode which can detect those expressions on live video.
  The main approach generally can be divided into three steps:
1.	Convert the image to its gray image to be easily modified.
2.	Locate the human face in the gray image.
3.	Apply mouth.xml or eye.xml to find out expression in specified area in the face.
