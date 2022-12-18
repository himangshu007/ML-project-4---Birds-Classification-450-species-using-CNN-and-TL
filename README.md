# ML-project-4---Birds-Classification-450-species-using-CNN-and-TL

# 🦜Bird Classification using Deep Convolutional Neural Networks , mobilenet v2 and Transfer Learning


## 🔬Overview 
Wildlife conservation has been recently transformed by the application of artificial intelligence. AI helps researchers determine the location of animals, date of sighting, migration patterns, and even an animal social group. AI is used by conservationists to monitor and protect animals in their natural habitat.

There are an estimated 30,000 threatened species across the globe. Scientists are utilizing AI to understand what put these species at risk by offering information about where they are born, how many survive, where they go, and how far they go. Following are some advantages of AI in the conservation of animal species:

* AI facilitates the collection of vast and fascinating datasets and their analysis in no time.
* AI is helping wildlife researchers in studying the wild animal species collectively and making strategies to protect them.
* Artificial intelligence tracks wildlife patterns and predicts the extinction of endangered animal species.
* It helps conservationists to detect and stop wildlife poaching.
* It can provide information about the effects of climate change on wildlife and reducing its impact by designing a proper plan.
* AI assists in assessing the species population and see changes.
* It helps to stop illegal animal trade on social media.
* Artificial intelligence identifies and classifies animal species into various classes and provides detailed information about them.
* AI algorithms can conserve animal habitats by predicting animal migratory patterns.
[Source](https://aiworldschool.com/research/this-is-why-ai-in-wildlife-conservation-is-so-glorious/)

## ❗Author's Note:
Make sure to run the cells from top to bottom with a GPU accelerator. There are some linux commands present in some cells so this is important to take into account. Also, any suggestions, comments and recommendations to improve the notebook will be highly appreciated. Cheers!

## Steps Involved 
### 1  🏗️Import Necessary Libraries
### 2  🤙Create helper functions
### 3  📥Load and Transform Data
### 4  📅Placing data into a Dataframe
### 5  🔭Visualizing images from the dataset
### 6 Saving the model
### 7  ✔️Model Evaluation
### 8  📉Visualizing loss curves
### 9  🔮Making predictions on the Test Data
### 10 # 📊Plotting the Classification Reports


 ## MobileNetV2
![image](https://user-images.githubusercontent.com/64637562/208295257-5e008ac3-7277-446d-b670-2cd85eab3e3e.png)

In MobileNetV2, 
* there are two types of blocks. One is residual block with stride of 1. Another one is block with stride of 2 for downsizing.
* There are 3 layers for both types of blocks.
* This time, the first layer is 1×1 convolution with ReLU6.
* The second layer is the depthwise convolution.
* The third layer is another 1×1 convolution but without any non-linearity. It is claimed that if ReLU is used again, the deep networks only have the power of a linear classifier on the non-zero volume part of the output domain.
