# DS3000-RealVsDeepfake-Final-Project Instructions

## Option 1:

1. Clone this repo
2. Download our dataset through https://www.kaggle.com/datasets/abdallamohamed312/in-the-wild-audio-deepfake?resource=download-directory&select=release_in_the_wild
    - The big black download button does not work. Instead scroll down and select the "release_in_the_wild" folder and use the download button there
    - Extract zip
    - Take out real and fake folders from file and make sure the path is correct in the first line of the notebook
          real_folder = "real"
          fake_folder = "fake"
          ^^ something like this
    - Ensure n_of_files is either 1000 for like a 10-20 min run time or None for reading all files (around 40 mins) depends on hardware

## Option 2:

1. Access our google drive folder at https://drive.google.com/drive/folders/1b9a1Cm7z-4biGDWGU7rpe3ntqdG-zyuA
2. Ensure your file path matches our code: /content/drive/MyDrive/DS 3000 Project/{real/fake}
   - you can insert this folder into your main drive by clicking the 3 dots of the folder, click "organize", then create a shortcut to connect to "mydrive"
3. Uncomment block 2 to allow your drive to be mounted 
   
