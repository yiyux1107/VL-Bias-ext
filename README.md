# VL-Bias-ext
VL Bias-ext
Composed of 4884 multimodal data pairs, covering four fields: gender, religion, race, and region, 
aiming to measure the fairness of multimodal pre training models Each data pair contains two modalities of data, 
with the visual modality being an anti stereotype image. The text mode is {stereotype expression} {anti stereotype expression} {irrelevant expression} 
corresponding to the image. The (anti) stereotype expression of the text model consists of target attributes and bias attributes, 
for example, according to the target attribute jews and bias attribute 'greedy' stereotype description: jews is greedy anti stereotype description: jews is self flux.  

Data collection process 
1. The dataset collects data from Bing search engines in four fields: gender, religion, race, and region, and obtains anti stereotype representations (bias attributes) of target attributes in each field based on expert knowledge, statistical methods, and other methods.
2. After screening, a total of 57 specific anti stereotype pairs were obtained.
3. Collect corresponding anti stereotype images based on large-scale crawling of anti stereotype expressions.  

VL-Bias-ext Dataset is available at [Google Drive](https://drive.google.com/drive/folders/1zuhEtUuJL1McLTwm0zNH15wmYa1gEm5T)  
The dataset is constantly being updated

