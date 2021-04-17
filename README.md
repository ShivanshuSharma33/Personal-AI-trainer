# Personal-AI-trainer

This project uses MediaPipe framework for Pose Estimation that identifies 33 landmarks of the body for Pose Estimation. We have identified only those landmarks that are reponsible for counting dumbbell curls in correct posture. 


<h3>Steps:</h3></br>

1.Create a Pose Estimation Module that identifies 33 landmarks on the body.</br>
2.Create Aitrainer.py file that will call Pose Estimation Module and identifies only those landmarks that are reponsible for our project.</br>
3.Use openCV to find the angle between desired landmarks and if the angle meets the desired correct posture angle that dumbbell curl count will be positive else throw an error "Incorrct Posture".</br>
4.One can use other set of landmarks to identify different exercises in correct posture respectively.</br>
