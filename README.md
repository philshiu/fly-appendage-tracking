# Fly appendage tracking
How does a brain control appendages? In this project, we activate single neurons in the 
fly brain and measure how that affects the position of the proboscis, the appendage the 
fly uses to consume food. Many neurons, when activated, affect the position of the proboscis.
To analyze this, we trained a deep convolutional network to mark positions of the proboscis. (Model training)
We labelled videos for each set of neurons we activated (Video analysis)
then analyzed this marked positions for each set of neurons (Tracking analysis).
![Labelled video](https://github.com/philshiu/fly-appendage-tracking/blob/main/Readme%20Videos/87_labelled.gif?raw=true)
In this video, we activate a specific neuron using light (invisible to this IR camera), which causes the proboscis to extend. We tracked specific portions of the head and the eye, and measured aspects of the proboscis extension, such as extension distance, duration and extension angle.
We found that neurons near sensory input causes repeated proboscis extension and retraction,
while neurons closer to motor output cause extended proboscis extension. 

See https://joiezhouie.github.io/MCBhonorsposter/ for the poster that my undergraduate mentee, Joie Zhou, created to describe this project; she won best neuroscience poster in the University of California, Berkeley Molecular and Cellular department for this work.
