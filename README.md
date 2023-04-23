Download Link: https://assignmentchef.com/product/solved-ae4317-assignment-autonomous-drone-racing
<br>
<h1> autonomous drone racing</h1>

Artificial Intelligence is a disruptive technology that can profoundly change aspects of our society. Since 2012 there has been great progress in AI, thanks to the rapid developments in “deep neural networks”. The world champion in chess was beaten by IBM’s Deep Blue in 1997, humans were beaten at Jeopardy by IBM’s Walter in 2011, in Go by Google Deepmind’s AlphaGo in 2016, and in StarCraft II in 2019. In aerospace, the next achievement may consist of beating human drone race pilots with an autonomous drone.




<strong>Figure 1:</strong> The AIRR racing drone, it has an Inertial Measurement Unit (IMU), a downward pointing laser ranger, 4 high-resolution cameras, and an NVidia Xavier board: 512-Core Volta GPU with Tensor Cores, 8-Core ARM v8.2 64-Bit CPU, 8 MB L2 + 4 MB L3., 16 GB 256-Bit LPDDR4x Memory., 32 GB eMMC 5.1 Flash Storage.

In 2019, the first AI Robotic Racing competition was organized. The goal was to (1) have autonomous drones race together utilizing different approaches to AI and drone racing, and (2) have the winner compete with one of the world’s best human drone race pilots, Gab707. 424 teams from 81 countries participated in the competition. At the end, 9 teams competed against each other in 3 seasonal races and 1 world championship race. The TU Delft team became 1<sup>st</sup> in the championship but lost against the human pilot. For more details: <a href="http://mavlab.tudelft.nl/mavlab-wins-the-alpha-pilot-challenge/">http://mavlab.tudelft.nl/mavlab</a><a href="http://mavlab.tudelft.nl/mavlab-wins-the-alpha-pilot-challenge/">–</a><a href="http://mavlab.tudelft.nl/mavlab-wins-the-alpha-pilot-challenge/">wins</a><a href="http://mavlab.tudelft.nl/mavlab-wins-the-alpha-pilot-challenge/">–</a><a href="http://mavlab.tudelft.nl/mavlab-wins-the-alpha-pilot-challenge/">the</a><a href="http://mavlab.tudelft.nl/mavlab-wins-the-alpha-pilot-challenge/">–</a><a href="http://mavlab.tudelft.nl/mavlab-wins-the-alpha-pilot-challenge/">alpha</a><a href="http://mavlab.tudelft.nl/mavlab-wins-the-alpha-pilot-challenge/">–</a><a href="http://mavlab.tudelft.nl/mavlab-wins-the-alpha-pilot-challenge/">pilot</a><a href="http://mavlab.tudelft.nl/mavlab-wins-the-alpha-pilot-challenge/">–</a><a href="http://mavlab.tudelft.nl/mavlab-wins-the-alpha-pilot-challenge/">challenge/</a>

<h1>Assignment specification</h1>

In the AIRR races, the drone had to pass through large gates designed by the competition organizers, the Drone Racing League and Lockheed Martin. Detecting these gates in the images from the drone’s cameras was a vital task for the competition.

<strong>The assignment’s goal is to design an automatic gate detection method. </strong>A relevant data set with images from an autonomous drone race and labels for the gates in the images will be provided on Brightspace.<strong> Please note that the code for this assignment can be Python / MATLAB only! </strong>In contrast to the group assignment, here it is not expected that you actually implement the method on embedded hardware.

The <strong>product</strong> of the assignment is a <strong>3-4 page report</strong>, in which the student describes:

<ol>

 <li>The choice for a specific object detection algorithm. The student is free to choose any object detection method, e.g., a method based on SIFT-feature matching to a gate template image or a deep neural network method, as long as the choice is motivated in the context of autonomous drone racing.</li>

 <li>Explanation of the detection algorithm. If the choice fell on a machine learning algorithm, there should be an explanation of the learning process (What part of the data set was used for learning? What were the learning parameters? What was the learning progress?)</li>

 <li>An analysis of the computational effort spent by the algorithm. What kind of processing hardware do you think is necessary for the algorithm, and how will it affect the weight / safety of the drone? Can you show a relation between parameters of the algorithm and the resulting computation time? Where is the “sweet spot” according to you?</li>

 <li>Validation of the algorithm, both qualitative (show the resulting detections in images) and quantitative (generate a ROC curve on the basis of the test set, and, e.g., evaluate mean Average Precision or Intersection over Union).</li>

 <li>A link to (private or public) github with the student’s code. <strong>IMPORTANT: do NOT put the dataset on your personal github.</strong> Share a private github with the following users: guidoAI, JuSquare and dewagter.</li>

</ol>