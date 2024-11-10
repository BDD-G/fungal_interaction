# fungal_interaction

# Abstract
Fungi offer valuable solutions for various biotechnological applications, including enzymes for the food industry, bioactive metabolites for healthcare, and biocontrol organisms for agriculture. The current workflows for identifying biocontrol fungi typically rely on subjective visual observation of the strains’ performance, rendering the process time-consuming and challenging to reproduce. To tackle these challenges, we develop an AI-automated approach employing five deep learning models which are ViT, VGG16, ResNet50, DensNet121, and MobileNet-V2. Our approach is centered on analyzing standardized images of 96-well microtiter plates containing solid medium on which fungi-fungi challenge experiments are conducted. We use our approach to categorize the outcome of interactions between the plant pathogen *Fusarium graminarium* and individual isolates from a collection of 38,400 fungal strains. Our results strongly support the effectiveness of our approach, attaining a peak accuracy of 95.0% on the test data. Correspondingly, the macro average Precision, Recall, and F1-score during validation were and 92.4%, 94.1%, and 93.1%, respectively. To the best of our knowledge, this paper presents the first automated method for scoring *F. graminarium* – fungal interactions using deep learning, and the technique can easily be trained for other fungal species.



# Performance 
## Table
<img width="809" alt="table " src="https://github.com/user-attachments/assets/4ca6da72-e8cc-40a1-a9fd-bf24f40f7a87"> 

## Boxplot
![boxplot](https://github.com/user-attachments/assets/ec9a4e21-1cff-485f-ad7f-191a257e570a)

## Training Process of all models
![training_process1](https://github.com/user-attachments/assets/3c3d4784-ca75-4b0c-93cb-3ce89b3ccbe4)


## Software and Hardware
The code utilized in this study was implemented in Python and TensorFlow library version 2.15. The process of training the deep learning models was performed on Google Colab pro plus, using NVIDIA GPU A100-40G


