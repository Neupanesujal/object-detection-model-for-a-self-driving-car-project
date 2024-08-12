Regarding the qualification task: ML(Computer Vision) Internship - Treeleaf Technologies Pvt Ltd

I am detecting object for a self driving car.
For this the object to be detected are street light, pedestrian, traffic signs and vehicles

At first i did transfer learning in MobileNet : 1. MobileNet object detection

I think i need better architecture to capture the details so i fine tuned ResNet in google collab: 2. ResNet object detection Google Collab

I tuned my hyper parameters and then trained in my laptop : 3. Final  ResNet object detection

My model shows strong precision at 0.96, indicating it correctly identifies most of the positive predictions. 
However, the recall of 0.6692 suggests it misses some positive instances. 
The F1 score of 0.7549 balances precision and recall, indicating a good overall performance. 
Training and validation accuracies are close (0.87 and 0.86), suggesting the model generalizes well to new data.
