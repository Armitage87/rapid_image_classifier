# rapid_image_classifier
One shot image classifier, enter categories and hit play
Idea came from Silicon Valley TV show, hot dog or not hot dog, what if you needed quick one shot low error classifier, and you're not bothered to write one? 
Enter rapid classifier!
All you need to do is define model to use as transfer learning, and pick keywords (categories) you need to classify. 
After that, run each cell and on the other end of it get a model that can infer categories with ~98% accuracy!
Learning rate, loss rate and error rates are adjusted based on model performance and validation set is created with 20 images only by default, you can specify more if needed.
As a bonus, this is Google Colabs script so it can be ran in Colabs and take finished model for further needs/experimentation
