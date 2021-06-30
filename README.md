# Alzheimers-Class
Demented and nondemented MRI image classification with [fastai](https://docs.fast.ai/)

MRI image training notebook: [Colab-image](https://colab.research.google.com/drive/11snVT2nD5pEVjU41OqDAaaQxTyoHm53l?usp=sharing)

[Medium](https://dechawatarty.medium.com/ai-%E0%B8%81%E0%B9%87%E0%B8%8A%E0%B9%88%E0%B8%A7%E0%B8%A2%E0%B8%8A%E0%B8%B5%E0%B8%A7%E0%B8%B4%E0%B8%95%E0%B8%84%E0%B8%99%E0%B9%84%E0%B8%94%E0%B9%89-%E0%B8%AA%E0%B8%A3%E0%B9%89%E0%B8%B2%E0%B8%87%E0%B9%82%E0%B8%A1%E0%B9%80%E0%B8%94%E0%B8%A5%E0%B8%8A%E0%B9%88%E0%B8%A7%E0%B8%A2%E0%B8%97%E0%B8%B3%E0%B8%99%E0%B8%B2%E0%B8%A2%E0%B9%82%E0%B8%A3%E0%B8%84-alzheimers-%E0%B8%88%E0%B8%B2%E0%B8%81%E0%B8%A0%E0%B8%B2%E0%B8%9E-mri-%E0%B8%94%E0%B9%89%E0%B8%A7%E0%B8%A2-fastai-87001f755a97)

Machine learning nowadays has been developing to solve our problems from daily life to national-level issues. Moreover, it would be remarkable when ML can be applied to medical fields and enhance our health!

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
