# IMAGE DEPTH ESTIMATION
## Description
Stereo Matching is a major problem in the field of Computer Vision, with the goal of reconstructing the real 3D structure from a pair of 2D images, known as stereo images. Stereo Matching is commonly applied in areas such as Autonomous Driving and Augmented Reality.

In this project, you will become familiar with the Stereo Matching problem by implementing several algorithms to compute the Disparity Map from a given stereo image pair. With the Disparity Map, you can obtain actual Depth Information.

## Installation

#### Running the Notebook on your computer

1. *Clone the repository:*
    ```sh
    git clone https://github.com/tranphuongtruc/IMAGE_DEPTH_ESTIMATION.git
    cd IMAGE_DEPTH_ESTIMATION
    ```

2. *(Optional)Create a virtual environment:*
   
    On Windows:
 
    ```sh
    python -m venv venv
    .\venv\Scripts\activate
    ```

    On macOS and Linux:

    ```sh
    python3 -m venv venv
    source venv/bin/activate
    ```

#### Running the Notebook on Google Colab

1. *Open Google Colab*

    Go to [Google Colab](https://colab.google/)

2. Upload Your Notebook

    Click on ***File*** -> ***Upload notebook***
    Choose the .ipynb file from your local machine.

3. *(optional) Mount Google Drive*

    If your notebook requires access to files stored in your Google Drive, you can mount it using the following code:

    ```sh
    from google.colab import drive
    drive.mount('/content/drive')
    ```

4. *NOTE*: If you cannot download the dataset, just use the **data** folder and modify the images' paths.
