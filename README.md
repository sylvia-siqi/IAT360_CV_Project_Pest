# IAT360_CV_Pest_Detection (project Plan v2)

 ## Project Idea
 Our project aims to detect five crop pests, supporting pest identification to reduce crop
 damage. With the model, a farmer can quickly identify which pest is affecting their crops
 just by taking a picture, without needing detailed pest maps. Agricultural students can
 also use it to learn about pests in the field.
 This is considered important, as crop pests interfere with the growth of healthy crops,
 leading to decreased supply and higher food prices, negatively affecting agricultural
 workers and consumers alike.
 ## Type of Computer Vision problem
 The problem we are tackling is a supervised detection task.
 ## Data Preparation
 ● We will require labelled images of the target pests, and annotaion of the bounding boxes of the pests 
 ● Our primary data sources will include a labelled crop pest dataset from Kaggle. We will also gather more images from Google and label them ourselves. To ensure the model generalizes well, we will collect images that vary in lighting, angles, backgrounds, and pest sizes.
 ● We will annoate the images from the dataset to get the corrdinates of the bounding boxes
 ### The model will recognize five types of pests, with the following class labels:
 ■ Ricestem borer
 ■ Greenleafhopper
 ■ Planthopper
 ■ Ricebug
 ■ Riceleaf roller

 Potential Bias or Ethical Issues
 ● Bias or ethical issues may arise if our dataset does not encompass diverse
 farming conditions across various regions and methods, which could cause bad
 generalization of the model. To mitigate this, we will actively seek diverse
 datasets and ensure our image collection reflects various agricultural practices.
 ● Additionally, there is a risk of misclassifying non-harmful insects as pests, which
 could misinform farmers and lead to unnecessary pesticide use.
## Timeline
 ● Oct. 20- Oct. 25
 ○ Sylvia: Github Repository Setup
 ○ Dataset collection
    - Jenna: Collect 35 images fpr green leaf hopper and 50 images for plant hopper
    - Sylvia: Annotate images from the Kaggle dataset and the new images Jenna collected
 ● Oct. 26- Nov. 2 (Data Preprocessing and Training)
 ○ Sylvia: Load all data, make the bounding box display works
 ○ Jenna: Data Cleaning
 ○ Together: 
      Meet on Monday: 
         1. Integrate our custom dataset into YOLO framework +
         2. Fine-tuning YOLO model with our dataset + 
         3. Adjusting model’s parameters
 +    Save the fine-tuned model + evaluation results
 ● Nov. 3-Nov. 6 (Final report)
 ○ Jenna: Problem introduction + Dataset report
 ○ Sylvia: Model analysis + Challenges

## References
 ● Crop pest dataset: https://www.kaggle.com/datasets/pialghosh/crop-pest-dataset
 ● Image Annotation tool: https://www.makesense.ai/ 
