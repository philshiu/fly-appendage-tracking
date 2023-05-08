# Fly appendage tracking
How does a brain control appendages? In this project, we activate single neurons in the 
fly brain and measure how that affects the position of the proboscis, the appendage the 
fly uses to consume food. Many neurons, when activated, affect the position of the proboscis.


https://user-images.githubusercontent.com/66529470/236931718-64b92f8d-61bd-454b-b872-dded4f6eef54.mp4


In this video, we activate a specific neuron using light (invisible to this IR camera), which causes the proboscis to extend.
To analyze this, we trained a deep convolutional network to mark positions of the proboscis. (Model training)
We labelled videos for each set of neurons we activated (Video analysis)
then analyzed this marked positions for each set of neurons (Tracking analysis).


https://user-images.githubusercontent.com/66529470/236932069-92ef6dfa-5634-4e13-9fa9-3afcd7897b66.mp4


We found that neurons near sensory input causes repeated proboscis extension and retraction,
while neurons closer to motor output cause extended proboscis extension. 

See https://joiezhouie.github.io/MCBhonorsposter/ for the poster that my undergraduate mentee, Joie Zhou, created to describe this project; she won best neuroscience poster in the University of California, Berkeley Molecular and Cellular department for this work.
