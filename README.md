# Alzheimers-Class
Demented and nondemented MRI image classification with fastai

MRI image training notebook: [Colab-image](https://colab.research.google.com/drive/11snVT2nD5pEVjU41OqDAaaQxTyoHm53l?usp=sharing)

[Medium]

# Respository Structure

```
- images
    - train
        - NonDemented (2560 images)
        - VeryMildDemented (1792 images)
        - MildDemented (717 images)
        - ModerateDemented (52 images)
    - test
        - NonDemented (640 images)
        - VeryMildDemented (448 images)
        - MildDemented (179 images)
        - ModerateDemented (12 images)
        
- notebooks
    - Image_train_ฺbaseline.ipynb; train the baseline model
    - Image_train_class.ipynb; train the model
    - McNemars_image_test.ipynb; test the model significance
   
- models
    - Image_ResNet34_1e-3.pth
    - Image_ResNet50_3e-2.pkl/pth
```
