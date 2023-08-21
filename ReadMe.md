# Transformavericks - Video Frame Prediction + Segmentation
Course Project for CSCI-GA - 2572. Uses the first 11 frames to predict the semantic segmentation for the next 11 frames.
Ranked at 7th best model out of 23 teams
# Instructions to reproduce our results
**IMPORTANT: Download these files and place it in Segmentation_Code Folder https://drive.google.com/drive/folders/1wqzivNuFtXJ4sDycgLebhqCY36IczRqW?usp=sharing**
1) This repo has two main models , one is Video Frame Prediction and Segmentation
2) First task is to train video frame Prediction model
3) To do that first navigate to "VideoPred" Folder
4) The instructions to setup the model and generate future frames is mentioned in [VideoPred/README.md](VideoPred/README.md)
5) Once the future frames for validation and hidden sets are generated using the code and instructions mentioned in [VideoPred/README.md](VideoPred/README.md), Next task is to do segmentation on predicted frames and calcualte Jaccardindex for validationset and generate future segmentation frames for hidden set
6) The code and instructions to do that is clearly documented in  [Segmentation_Code/Readme.Md](Segmentation_Code/Readme.Md) which is present in "Segmentation_Code" folder
7) Following the instructions in Readme of Segmentation folder , you can generate the segmentation masks for both validation and hidden sets and calculate JaccardIndex for the hidden set.
