# Virtual-pen-and-eraser
It is project which uses opencv for accessing camera, numpy for mathematical calculations, and mediapipe for hand detection i.e. capturing the motion of hand. In this project, user can draw, write, sketch, and can do many more with his/her index finger. Here index finger acts as a pen and eraser, depending on your choice.

<b> Requirements </b>
1. Python 3.12.1 , numpy , opencv, mediapipe installed on your system.
2. Pycharm 2021.3.2 IDE for development (recommended for better experience)

<b> Algorithm </b>
1. Start reading the frames and convert the captured frames to HSV colour space.(Easy for colour detection)
2. Prepare the canvas frame and put the respective ink buttons on it.
3. Adjust the values of the mediapipe intialization to detect one hand only.
4. Detect the landmarks by passing the RGB frame to the mediapipe hand detector
5. Detect the landmarks, find the forefinger coordinates and keep storing them in the array for successive frames .(Arrays for drawing points on canvas)
6. Finally draw the points stored in array on the frames and canvas .

<b> Output pictures </b>
    <img src="https://github.com/itz-mahekbhartiya/Virtual-pen-and-eraser/blob/9d89f3b1640db5badf0c8c9a7a63a2b258da647d/Outputs/Output%2001.png">
    Drawing symbols
    <img src="https://github.com/itz-mahekbhartiya/Virtual-pen-and-eraser/blob/9d89f3b1640db5badf0c8c9a7a63a2b258da647d/Outputs/Output%2002.png">
    <img src="https://github.com/itz-mahekbhartiya/Virtual-pen-and-eraser/blob/9d89f3b1640db5badf0c8c9a7a63a2b258da647d/Outputs/Output%2003.png">
    Writing "Hello world !"
    <img src="https://github.com/itz-mahekbhartiya/Virtual-pen-and-eraser/blob/9d89f3b1640db5badf0c8c9a7a63a2b258da647d/Outputs/Output%2004.png">

<b> Team members </b>
1. Mahek Bhartiya
 >  Linkedin: [mahek-bhartiya](www.linkedin.com/in/mahek-bhartiya-513012233)
2. Ayush Gawai
 >  Linkedin: [ayush-gawai](www.linkedin.com/in/ayush-gawai-864682262/)
2. Aditya Kulkarni
 >  Linkedin: [aditya-kulkarni](www.linkedin.com/in/aditya-kulkarni-93063a218/)
2. Pavan Gadave
 >  Linkedin: [pavan-gadave](www.linkedin.com/in/pavan-gadave/)
2. Sumit Shedage
 >  Linkedin: [sumit-shedage](www.linkedin.com/in/sumit-shedage-11306825b/)
