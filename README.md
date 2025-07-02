# quantized_gradient_descent
This is an Open Ended Lab Project (OELP) done in my third semester of DS, along with Jeeva Jayaprakash. It's kinda experimental - we test various bit allocation methods and observe the tradeoff between accuracy and communication efficiency.

The whole project is explained well and concise in the ppt in this directory. Even the ipynb is well commented with enough text boxes as well to explain what our thought process was. Please refer to those for full details.

To be brief we basically generated an artificial datatset (refer to the ppt or the ipynb to see how exactly) and then added noise to it. Now we train on this data basically. We have made use of logloss function as our loss function for the same.

The point is to allocate different number of bits to different attributes and see how accuracy and communication efficiency alters during training. 

Why do this? Why quantize? Mainly to cut down on communication costs while keeping a decent enough accuracy of the data we send to a server.
