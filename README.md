# Fly appendage tracking
How does a brain control appendages? In this project, we activate single neurons in the 
fly brain and measure how that affects the position of the proboscis, the appendage the 
fly uses to consume food. Many neurons, when activated, affect the position of the proboscis.
https://user-images.githubusercontent.com/66529470/236931393-38aa833a-acf4-42bd-8bf2-6a2b757a8569.mp4
In this video, we activate a specific neuron using light (invisible to this IR camera), which causes the proboscis to extend.
To analyze this, we trained a deep convolutional network to mark positions of the proboscis. (Model training)
We labelled videos for each set of neurons we activated (Video analysis)
https://user-images.githubusercontent.com/66529470/236931541-a70d8e55-ba08-4e4e-9389-21abe0ea8a12.mp4
then analyzed this marked positions for each set of neurons (Tracking analysis).
We found that neurons near sensory input causes repeated proboscis extension and retraction,
while neurons closer to motor output cause extended proboscis extension. 

See https://joiezhouie.github.io/MCBhonorsposter/ for the poster that my undergraduate mentee, Joie Zhou, created to describe this project; she won best neuroscience poster in the University of California, Berkeley Molecular and Cellular department for this work.
