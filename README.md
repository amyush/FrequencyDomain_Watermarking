# Watermarking
**_Hiding the image in another image file. Frequency domain - DCT is used in this project_**

# Pre-requisite
-   Git-Hub account
-   Python 3
-   pip

# Inputs
  -   **Cover Filename / Carrier image filename** - This takes the name of the file alongwith the extension where the message is to be encoded(hidden). This file is taken from the gitHub repository. Any other file, if to be used, should be uploaded to the the same repository. For any sub-folders, relative path from the .ipynb file should be provided.
  -   **Key** - This is the secret key which is used to encode the message. Here, key is used to decide the bits where the message bits are to be encoded.
  -   **Watermark logo filename** - This is the message which is to be hidden in the audio.

# How-to-run
  - Step-1 Open the watermarking.ipynb file in colab or jupyter notebook.
      Link to the .ipynb file - 
      https://github.com/amyush/FrequencyDomain_Watermarking.git
      
      - To open the file in colab, copy the above link and in colab page, paste it in the git-hub url.
      ![image](https://user-images.githubusercontent.com/19607227/152243765-94d85a11-0d91-40f6-bf91-d7faea74c10a.png)
      - **OR**
      Open the below link to colab -
      https://drive.google.com/drive/folders/1oNN2ku6rTFCS8mmXBnQaLaGagYy5Zb9X?usp=sharing
      
  - Step-2 Once open, run all the cells from the beginning.
  - Step-3 Finally run the **result** segment to see the results of both encoding the message in the image file and extracting the watermarked logo from the image file.

    ![image](https://user-images.githubusercontent.com/19607227/152244074-fd2a37df-f18f-407e-a7db-c2f491753b90.png)

# Downloading the watermarked image
After running the hiding the image function, click on the panel and open the Files(local storage) in Colab. Go to root folder folder. The required file will be named as **waterMarkedImage.jpg**.
