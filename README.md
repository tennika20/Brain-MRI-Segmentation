# Brain-MRI-Segmentation-Using-Unet



## Cloning the Repository

	`git clone {project_url}`

## Requirements for setting up the environment

1. python 3.6 or higher

2. `pip install PyQt5`

3. `pip install numpy`

4. `pip install pandas`

5. `pip install matplotlib`

6. `pip install opencv-python`

7. `pip install tqdm`

8. `pip install scikit-image`

9. `pip install sklearn`

10. `pip install scipy`



# Executing the Project

1) Python3 Final.py

<img width="945" alt="image" src="https://user-images.githubusercontent.com/19888725/206880287-14d2c8b4-9c97-445d-a035-f8c959c0dd89.png">



2) Upload the MRI Image File from "test_images" folder into the GUI.

   Naming Convention for mask: `MRI_Imagename_mask.tiff`

   The original mask is displayed beside the MRI image, if it is present in the current MRI image folder:

<img width="942" alt="image" src="https://user-images.githubusercontent.com/19888725/206880249-79a438ad-52b6-495f-a6e6-bb3cd426741c.png">




3) Click on "Submit" button.

   Final output with predicted segmentation is displayed in a new window:

<img width="1194" alt="image" src="https://user-images.githubusercontent.com/19888725/206880279-dafd9cee-fae3-48df-aae5-6d5fb56c2c6a.png">




# Model File: 
Download Unet Model File Here: https://drive.google.com/file/d/1HO86MnK74TcZCoEIxN9IAQEzdxS9VAGZ/view?usp=share_link
And place it in project root folder with rest of the files
