# Anti Spoofing Replay Dataset
1. [ About the dataset ](#about)
2. [ Distributions ](#dist)
3. [ Content ](#cont)
4. [ Get the Dataset ](#getdat)
5. [ Links ](#link)

<a name="about"></a>
# About the dataset
We introduce a large image dataset Anti Spoofing Replay for training a neural network to repel various attacks on biometric access systems. The dataset consists replay attacks - videos from `Antispoofing Real Dataset` (https://github.com/trainingdata-pro/Anti-Spoofing-Real-Dataset/tree/main) filmed on the phone. `Anti Spoofing Replay Dataset` solves the tasks of training algorithms to distinguish real users from scammers, who use videos of people in order to pass the identification procedure. Proposed dataset allows to build identity recognition systems, which can be used to develop anti-spoofing solutions, such as countermeasures and system configurations that can help make authentication systems more secure.

The dataset consists of 26,591 videos of replay attacks from 24,000+ unique people from 157 countries. The data for the dataset is still gathering, so the number of videos and photos is getting bigger!

### Data in the dataset
- People from 18 to 80 age old are presented in the dataset.
- For each person in the dataset the following data is presented:
  - **video_extension** - extension of the video
  - **phone_shot** - model of the phone on which the video is shot
  - **phone_replay** - phone model on which the video is played
  - **assignment_id** - unique identifier of the file
  - **worker_id** - unique identifier of the person
  - **age** - ahe of the person
  - **unique** - whether the person is unique
  - **country** - person's country
  - **region** - region of the person
  - **gender** - person's gender
- The data was mostly (approximately **90%**) collected indoor, however there are also original  videos made outdoors.
- The lighting is artificial in **80%** of cases,  **5%** natural daily lightning, **5%** evening outdoor lighting, **10%** - dark indoor lighting.
- On the played video people turn their heads, videos and photos are filmed so that the head takes up at least 1/2 of the frame.
- On the attack video there is a gradual zoom on the phone screen with a selfie video.

### People in the dataset
![Desktop - 1 (1)](https://github.com/trainingdata-pro/Anti-Spoofing-Replay-Dataset/assets/113421352/c8fb7c56-616c-41b6-8c71-5db9795216fe)

<a name="dist"></a>
# Distributions

### Gender of people in the dataset

![image](https://github.com/trainingdata-pro/Anti-Spoofing-Replay-Dataset/assets/113421352/a746259e-7076-404c-b811-66bbbb133839)

### Age of people in the dataset

![image](https://github.com/trainingdata-pro/Anti-Spoofing-Replay-Dataset/assets/113421352/92d71265-7c4e-4825-8168-3b59531a1973)


### Extensions of files in the dataset

![image](https://github.com/trainingdata-pro/Anti-Spoofing-Replay-Dataset/assets/113421352/08e7a3b9-1968-4e3c-bfe4-1379da1c920a)


<a name="cont"></a>
# Content
### The folder **"samples"** includes 30 folders:
- corresponding to each person in the sample
- containing of selfie and video of the individual

### File with the extension .csv
includes the following information for each media file:
- **live_video_id**: the unique identifier of the "Antispoofing Live" video
- **phone**: the device used to capture the replay video,
- **link**: the URL to access the replay video,
- **phone_video_payback**: the device used to play the "Antispoofing Live" video,
- **worker_id**: the identifier of the person who provided the media file,

<a name="getdat"></a>
# Get the Dataset
This is just an example of the data. If you need access to the entire dataset, contact us via [sales@trainingdata.pro](mailto:sales@trainingdata.pro) or leave a request on **https://trainingdata.pro/data-market?utm_source=github**

![Untitled (2) (1) (1)](https://github.com/trainingdata-pro/Anti-Spoofing-Replay-Dataset/assets/113421352/c15814f4-3f34-4913-afa9-e7042c1bc0fe)


<a name="link"></a>
# Links
| Resource | Link |
| --- | --- |
| TrainingData.pro | https://trainingdata.pro/data-market?utm_source=github |
| TrainingData.solutions | https://trainingdata.solutions/data-market?utm_source=github |
| Kaggle | https://www.kaggle.com/trainingdatapro |
| HuggingFace | https://huggingface.co/TrainingDataPro |

