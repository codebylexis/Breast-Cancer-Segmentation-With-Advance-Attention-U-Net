# Breast Cancer Segmentation With Advance Attention U-Net

<p align="center">
</p>   
<img src="https://www.yourhealth.net.au/wp-content/uploads/2017/09/pink-ribbon-for-breast-cancer-awareness.jpg" width="1000" height="550">
<p>Breast cancer is the most common cancer diagnosed in women, accounting for more than 1 in 10 new cancer diagnoses each year. It is the second most common cause of death from cancer among women in the world. This project introduces an advanced Attention U-Net segmentation model designed to accurately identify and segment breast cancer-affected regions in ultrasound images. Traditional U-Net models often miss tiny, yet critical, cancerous tissues. The attention mechanism integrated into this model enhances its ability to focus on these subtle areas, improving segmentation accuracy. By enabling more precise identification, this model reduces the time radiologists spend analyzing images, accelerating the breast cancer detection process. 
</p>
<h2>Libraries Used</h2>
<ul>
  <li>Tensorflow</li>
  <li>Numpy</li>
  <li>Pandas </li>
  <li>Matplotlib</li>
  <li>Seaborn</li>
  <li>Sklearn</li>
</ul>
<h2>Data Visualization</h2>
<p align="center"> 
<img src="https://github.com/user-attachments/assets/19506247-f23c-48e6-9b4b-2b51e976d8a1" width="750" height="500">
</p>
<p align="center"> 
<img src="https://github.com/user-attachments/assets/fbc14d50-f97a-4d65-b631-2d074ae2a6d8" width="750" height="500">
</p>
<h2>Methodology</h2>
<p>I have developed an advanced attention U-Net architecture, specifically designed for high-precision image segmentation tasks. This model enhances the traditional U-Net framework by incorporating an innovative attention mechanism, inspired by natural language processing techniques. These attention mechanisms are seamlessly integrated into the skip connections, allowing the model to dynamically prioritize and focus on specific regions of the image during the segmentation process. This selective attention capability enables the U-Net to more accurately identify and delineate target objects within complex images.</p>
<p>The architecture begins with a series of encoder blocks, which progressively capture and condense spatial information through convolutional layers, reducing the image dimensions while increasing feature depth. This is followed by corresponding decoder blocks, which reconstruct the spatial dimensions while leveraging the enriched feature representations. The attention gates, placed at the skip connections between the encoder and decoder blocks, adjust the flow of information, emphasizing critical regions that contribute most to the accurate segmentation of the image.</p>
<p>The model was meticulously trained over 20 epochs, utilizing binary cross-entropy as the loss function and the Adam optimizer for weight adjustments. This rigorous training process has resulted in a robust and accurate segmentation tool, capable of handling complex image data with high precision. This U-Net variant, with its attention-enhanced skip connections, represents a significant advancement in image segmentation technology, particularly in applications where detailed and accurate object delineation is critical.</p>
<p align="center"> 
<img src="https://github.com/user-attachments/assets/9032293c-b98f-4589-b3c9-1a6d46897c9c">
</p>
<h2>Model Training</h2>   
<h4>Model Loss:</h4>   
<p align="center"> 
<img src="https://github.com/user-attachments/assets/53468827-bcb9-48a6-a3f8-a8736261fe95" width="700" height="400">
</p>
<h4>Model Accuracy:</h4>  
<p align="center"> 
<img src="https://github.com/user-attachments/assets/d63f1b33-35ac-4afc-8127-6f8ef786e149" width="700" height="400">
</p>
<h4>Model IOU:</h4>  
<p align="center"> 
<img src="https://github.com/user-attachments/assets/a52d8d1a-27bc-4605-a0b6-31e537154ddc " width="700" height="400">
</p>
<h2>Model Prediction</h2>
<p align="center">
<img src="https://github.com/user-attachments/assets/56bf71af-47e6-4a4f-8552-3b95e1b31d16" width="800" height="1200">
</p>
<h2>Conclusion</h2>  
<p>In this project, I have created an Advance Attention U-Net model for correctly segmenting breast cancer from ultrasound images.</p> 
