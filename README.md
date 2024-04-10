# Gesture Recognition Assignment

## Table of Contents
* [Problem Statement](#problem-statement)
* [Objectives](#objectives)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)
* [Contributors](#contributors)

<!-- You can include any other section that is pertinent to your problem -->

## Problem Statement
Imagine you are working as a data scientist at a home electronics company which manufactures state of the art smart televisions. You want to develop a cool feature in the smart-TV that can recognise five different gestures performed by the user which will help users control the TV without using a remote.

The gestures are continuously monitored by the webcam mounted on the TV. Each gesture corresponds to a specific command:
 
| Gesture | Corresponding Action |
| --- | --- | 
| Thumbs Up | Increase the volume. |
| Thumbs Down | Decrease the volume. |
| Left Swipe | 'Jump' backwards 10 seconds. |
| Right Swipe | 'Jump' forward 10 seconds. |
| Stop | Pause the movie. |

Each video is a sequence of 30 frames (or images).

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Objectives:
1. **Generator**:  The generator should be able to take a batch of videos as input without any error. Steps like cropping, resizing and normalization should be performed successfully.

2. **Model**: Develop a model that is able to train without any errors which will be judged on the total number of parameters (as the inference(prediction) time should be less) and the accuracy achieved. As suggested by Snehansu, start training on a small amount of data and then proceed further.

3. **Write up**: This should contain the detailed procedure followed in choosing the final model. The write up should start with the reason for choosing the base model, then highlight the reasons and metrics taken into consideration to modify and experiment to arrive at the final model.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Numpy - version 1.23.5
- Pandas - version 1.5.3
- Matplotlib - version 3.7.1
- Seaborn - version 0.12.2
- TensorFlow - version 2.15.0
- keras - version 2.15.0
- OpenCV - 4.9.0.8

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Giving credits here.
- This project was inspired by [UpGrad](https://ww2.upgrad.com/?_gl=1*1a6yjvu*_ga*MTY4NTk0NDA2Ny4xNjk4MDg2ODEw*_ga_HVXPGHVCS0*MTY5ODA4NjgwOS4xLjAuMTY5ODA4NjgwOS42MC4wLjA.&user_uuid=478408e8-483a-4336-8184-9025c279e0af&combination_id=2) and [IIIT Banglore](https://www.iiitb.ac.in/)


## Contributors
- [@Ritam_Kishore](https://github.com/dk2302)
- [@Dhyanesh_Parekh](https://github.com/dhyanesh-parekh)


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
