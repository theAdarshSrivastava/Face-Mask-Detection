# Face Mask Detection
After the new Coronavirus illness (COVID-19) case spread quickly in Wuhan-China in December 2019, World Health Organization (WHO) affirmed that this is a risky infection that can be spreading from one person to another through drops and airborne. Concerning the anticipation, wearing a face cover is basic while heading outside or meeting other people. Nonetheless, some flighty individuals will not wear a face mask for such countless reasons. The impact of the (Covid-19) has been devastating and as a result of this in addition to vaccination one has to always wear a mask in public and hence for entry into any public place now demands a “Mask on the Face”.
So the importance of this is that this will help the organisation to abide by the government norms as well as maintain the safety and security of the overall staff and hence prevent any further outbreak, curbing the covid cases somewhat. It can be used by any public enterprise be it from business to educational institution to admit entry on the basis of the results obtained from this project.

## Dataset
We have created three separate folder for each train, test as well as validation data directly without using train_test_split in 8-1-1 manner. In each of the folder we have two folders named as ‘WithMask’ and ‘WithoutMask’. In train folder we have 10000 images in which 5000 belongs to each category. In test folder we have a total 992 images from both categories. While in the validation folder we have 800 images in which 400 images belongs to each category.

The dataset maybe accessed <a href = "https://drive.google.com/drive/folders/1MaU49YgSFBqGbMVImh6k6f__q-_mowck?usp=sharing">here</a>.

## Model Architecture
<img src = "assets/model.png" height = 600px width = 400px>

The model in .h5 format may be downloaded from <a href = "https://drive.google.com/file/d/1qgXJ0eSur-Ezh_tmxxD920LJef-J4icT/view?usp=sharing">here</a>.

## Usage
Please download the trained <a href = "https://drive.google.com/file/d/1qgXJ0eSur-Ezh_tmxxD920LJef-J4icT/view?usp=sharing">model</a> and move it to a directory names *models*. Please ensure that the path to model is *"classify_model.h5"*.

- Cloning the Repository: 

        git clone https://github.com/am9964/Face_Mask_Detection
        
- Entering the directory: 

        cd Face_Mask_Detection
        
- Setting up the Python Environment with dependencies:

        pip install -r requirements.txt
        
- Entering the test directory: 

        cd test

- Running the file:

        python3 test.py
        
## Demonstration

https://user-images.githubusercontent.com/66861243/117566631-59708100-b0d5-11eb-81e6-94680115bd8c.mp4

## Result Analysis

- Confusion Matrix and ROC_Curve
<img src = "assets/Screenshot 2021-11-17 183734.jpg" align="center" height = 300px width = 600px>


## Contributors

- [Ankit Mathur](https://github.com/am9964)
- [Adarsh Srivastava](https://github.com/theAdarshSrivastava)
