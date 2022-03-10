# kaggle
Projects from Kaggle

Visit Profile: https://www.kaggle.com/alexteboul

![competition](https://road-to-kaggle-grandmaster.vercel.app/api/badges/alexteboul/competition/light)
![dataset](https://road-to-kaggle-grandmaster.vercel.app/api/badges/alexteboul/dataset/light)
![notebook](https://road-to-kaggle-grandmaster.vercel.app/api/badges/alexteboul/notebook/light)
![discussion](https://road-to-kaggle-grandmaster.vercel.app/api/badges/alexteboul/discussion/light)


## [pawpularity-contest](https://github.com/AlexTeboul/kaggle/tree/main/pawpularity-contest): Predicting Shelter Pet Popularity Based on Pet Images
TLDR: In this competition we were tasked with predicting shelter pet popularity based on images of the animals. 
Metadata was provided that had human generated feature information about the images - 
like if the pet was in focus and not occluded. Unfortunately, not much signal could be obtained. 
The target variable was the Pawpularity score, a proprietary click-rate score from PetFinder.my that was not well explained by the images or human-generated metadata.
Only improvements over guessing the mean Pawpularity score involved applying transfer learning to predict pet breed of cat and dog, then training models to infer pawpularity based on breed. 
Some breeds were preferred over others in terms of click-rate on the website. 
