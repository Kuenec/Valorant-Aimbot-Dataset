---

# Valorant 10K+ Head-Only Class Dataset  
<img src="https://github.com/Kuenec/Valorant-Aimbot-Dataset/blob/main/Screenshot%202025-04-20%20190402.png" alt="YOLOv5 Training" width="600"/> 
## Overview  
This repository provides a dataset containing **10,000+ labeled head only class images** from Valorant, specifically designed for training AI aimbots. The dataset contains only head detection particularly for headshot focused aim only.   

## Download the Dataset  
You can download the dataset here:  
🔗 [Valorant 10K Head Only Class Dataset (Roboflow)](https://universe.roboflow.com/kuenec/valorant-10k-head-only-class-aimbot-ukzjf)  

## Usage  
1. **Download** the dataset from the provided link.  
2. **Train** your model using your preferred framework (e.g., YOLOv5, YOLOv8, Faster R-CNN).  
3. **Deploy** the trained model into the game through the use of torch CUDA and torch.load the .pt file you get after training.  

### Recommendations  
- I personally trained my model using **YOLOv5**, but it is compatible with most object detection frameworks.
- Augment (blur, flip, crop) some of the images, to prevent your bot from memeorizing the locations of heads, stunting progression of the bot.
- 🔗 [Yolov5](https://github.com/ultralytics/yolov5)

## Disclaimer  
This dataset is intended for **educational and research purposes only**. The use of AI aimbots in competitive games may violate the terms of service of the game. Use at your own risk.  

## Contributing  
If you'd like to contribute to expanding or improving this dataset, feel free to open an issue or submit a pull request.  

## Training Results  
<img src="https://github.com/Kuenec/Valorant-Aimbot-Dataset/blob/main/Screenshot%202025-04-20%20191045.png" alt="YOLOv5 Training" width="600"/> 
