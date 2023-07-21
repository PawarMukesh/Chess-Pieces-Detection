# Chess-Pieces-Detection
### Overview : The goal of this project is able to identify chess pieces on a board or in a video using yolov5.
![image](https://github.com/Tanwar-12/Chess-Pieces-Detection/assets/110081008/df740dc6-0aba-4ea9-99f3-01dd8c5c65cf)
![image](https://github.com/Tanwar-12/Chess-Pieces-Detection/assets/110081008/efef9d71-49da-4a24-8d32-297d55f1713f)
### 📁 Dataset Used :  https://universe.roboflow.com/projects-ehrjz/chess-detection-i0woo
**The dataset consists of 13 classes:**
- 'bishop'
- 'black-bishop'
- 'black-king'
- 'black-knight'
- 'black-pawn'
- 'black-queen'
- 'black-rook'
- 'white-bishop'
- 'white-king'
- 'white-knight'
- 'white-pawn'
- 'white-queen'
- 'white-rook
 ## Data Preparation:
  * Create a bounding boxes with the help of label-img And makesense.ai website according to YoloV5.
  * Prepare folder structure that can be accept by YoloV5.
    ## Steps to use Yolov5:
* Cloning the YoloV5 file from official repository.
* Changing the directory of yolov5
* Installing the dependencies
* Download all versions pre-trained weights.
 ## Steps Before Training Custom Dataset:
* Go to yolov5/data/.
* Open data.yaml
* Edit the following inside it:

 1. Training and Validation file path
 2. Number of classes and Class names.

  ## Training YOLOV5 Model
* Set images size 640 with batch of 8.
* Train model around 600 epochs .Stopping training early as no improvement observed in last 100 epochs. Best results observed at epoch 201, best model saved as best.pt.
* Visualise the training metrics with the help of tensorboard.
   ## Testing Images Using Test Data:
  ![image](https://github.com/Tanwar-12/Chess-Pieces-Detection/assets/110081008/3ae8cfbd-e3fe-4600-8751-5902cc2bc373)

![image](https://github.com/Tanwar-12/Chess-Pieces-Detection/assets/110081008/8e8ca728-c606-46ab-b9b2-efb9774e4594)

## Testing Video Demo:




https://github.com/Tanwar-12/Chess-Pieces-Detection/assets/110081008/564d2002-c637-4021-8017-440a6224af0c


  
