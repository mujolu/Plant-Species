# Plant-Species

Step 3: Train the model

<img width="162" height="311" alt="Screenshot 2026-02-19 050831" src="https://github.com/user-attachments/assets/5c9bed74-727e-42ee-9071-493b07353a04" />


## Training Configuration

I trained the model using **40 epochs**, a **batch size of 16**, and a **learning rate of 0.001** to help it learn effectively from the images.

I chose 40 epochs so the model would have enough time to understand the patterns in the dataset without overtraining. A batch size of 16 allowed the model to process a small group of images at a time, which balanced accuracy and training speed. I set the learning rate to 0.001 to keep the learning process steady and controlled, allowing the model to improve without making large errors.

Overall, these settings helped me achieve good results for the image classification task.


Step  5: Under the Hood results

<img width="251" height="546" alt="Screenshot 2026-02-19 050839" src="https://github.com/user-attachments/assets/c45cc08b-1d34-404b-81ac-7a69c1b77470" />



10 Screenshots



<img width="631" height="909" alt="image" src="https://github.com/user-attachments/assets/55df5904-f4c7-4645-9da4-cdda2a0eb1db" />


<img width="725" height="926" alt="image" src="https://github.com/user-attachments/assets/3b92c41f-76c2-4dac-808b-7bdb0b554b47" />


<img width="433" height="865" alt="image" src="https://github.com/user-attachments/assets/e2a3047b-be60-4102-8217-06debacc9014" />


<img width="357" height="743" alt="image" src="https://github.com/user-attachments/assets/ef511324-b15d-4a92-98d1-a1ff5579c431" />




<img width="325" height="397" alt="Screenshot 2026-02-19 222948" src="https://github.com/user-attachments/assets/3dd7fb0b-993e-4865-b622-13eff0a24f13" /> <img width="314" height="429" alt="Screenshot 2026-02-19 222941" src="https://github.com/user-attachments/assets/5724fecd-fa6e-4632-96f2-e8da31db8002" />


<img width="554" height="895" alt="image" src="https://github.com/user-attachments/assets/c33304df-09e4-440f-9e92-a7657a3e5f3d" />


<img width="421" height="887" alt="image" src="https://github.com/user-attachments/assets/f108cb03-9384-4e47-a870-53c0ca65a5d8" />



<img width="272" height="916" alt="Screenshot 2026-02-19 052850" src="https://github.com/user-attachments/assets/d5c70207-edf9-4826-a354-7d07066aacca" />



<img width="1920" height="1080" alt="Screenshot 2026-02-19 052548" src="https://github.com/user-attachments/assets/d3d2857e-fff6-4821-ac7a-4996abf272c8" />



<img width="343" height="815" alt="image" src="https://github.com/user-attachments/assets/a3e978d7-e949-45ed-85b4-596c7cd74f2f" />























## Dataset:


<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/1e16908f-d282-4125-8b98-1483a95a5c15" />
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/a796b429-387f-4fc1-86b3-91425a2b95ff" />



##
## Google drive model link: https://drive.google.com/drive/folders/1IOXeNrjahQuxWS1qqtd17Pt9Twy0sAsr?usp=sharing

# Reflection Question

1. Some really achieved 100% accuracy and some were not able to fully recognize the plant especially on the angles that are most not common.
2. Hottentot. Usually, this plant look like braided hairs, there were so many stems. I come across this image where it was classified as the same plant but there were only two stems in total. The model misclassified it to the strings of heart and only the exact plant name has the lowest confidence score.
3. Changing the epochs, batch size, and learning rate affected how well the model learned from the plant images. Using 40 epochs gave the model enough time to understand patterns without overtraining, while a batch size of 16 balanced training speed and accuracy by processing a moderate number of images at a time. A learning rate of 0.001 allowed the model to learn steadily without making large errors. Together, these settings helped produce stable training and improved the model’s accuracy in recognizing different plant species.
4. Challenges I encounter were, having trouble were to get this massive load of images and when training the model, you have to finish the sesion of training and testing in it or it will restart the next time you come visit the site.
5. Changes will be how I will put all possible angles, colors and volume of the dataset itself, so when training the model, it will achieve high accuracy score and low confusion matrix.


# Documentation link: https://drive.google.com/drive/folders/1QWGmzQlNPCVfViDJbrpyfHsNvAmRIrwR?usp=sharing









