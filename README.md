# human_pose_estimation
# Introduction 
The recent methods of estimating the human posture in two-dimensional space based on deep learning have shown better applicability and results than before. However, the problem also faced many different challenges such as in crowds, resolution, lighting, ... In this project, I analyze and evaluate pros and cons of the article “Pifpaf: Composite Fields For Human Pose Estimation ”, the author has focused on solving the challenge of occluded and low resolution. I analyze on different datasets: COCO dataset, in addition I analyze errors on 1000 MPII images, 2000 images of sports dataset collected by us. Thereby having a more general view of the article, and thereby giving directions to develop research to improve the article. 

This project based on paper : https://arxiv.org/abs/1903.06593 and code: https://github.com/vita-epfl/openpifpaf

I analyze and evaluate on datasets:4000 images COCO test-dev,2000 images sports,1000 images MPII datasets:

Because the author focused on solving the challenge on low resolution and obscuration. I resized the images to 3 different resolutions: 256px, 321px, 641px. The author have suggested that 321px is the best but I want to experiment with 256px more, then I can conclude that 321px is the best or not.

Dataset: https://drive.google.com/drive/folders/19xFqlgraUi7BZp9VgBUY_UfC6u4gYNyY?usp=sharing

# Result
Error(image) on 1000 images MPII
<img width="1440" alt="Screen Shot 2020-10-19 at 3 28 50 PM" src="https://user-images.githubusercontent.com/43095377/96420687-ffcf6480-121f-11eb-95d4-ccf3d1698819.png">



