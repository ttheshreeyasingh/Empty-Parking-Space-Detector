# Empty Parking Space Detector

## Brief Description

The goal of the project is to detect and count the number of empty spots, given an orthogonal and top-view of a car parking lot. The parking lots can also have shadows in them. 

### Objective

1. To capture and detect the existence of vehicles at the parking lot using image processing techniques.

2. Count, and display available parking spaces.

## Setup and Installation
- to install the required dependencies run `pip install -r requirements.txt`

- There are two approaches used. 
    - To run the first approach: Go to `src/Approach1/` then run `findSpace1.ipynb` then `mainImg1.ipynb`. similarly for image 2 replaing 1 with 2 in both files.
    - To run the second approach: Refer to the notebook `./src/Project.ipynb` and run all cells. 

- The data required for both approaches are present in the data folder.

### Built with - Python 3

### Modules used (latest versions):
1. numpy
2. opencv-python
3. matplotlib
4. pickle
5. cvzone (pip install cvzone)
6. os: for saving the images
7. collections: for queues

## Sample outputs

### Approach 1
Testcase 1 - 15/69 empty parking spaces
![test1](https://user-images.githubusercontent.com/82603720/204346941-55942e27-13f3-4f70-aafe-81d8d9c1c647.png)
[Output for video input captured from a drone](https://user-images.githubusercontent.com/82603720/204346229-1aa67039-7c39-4297-acb4-ba4a11af1868.webm)

Testcase 2 - 51/84 empty parking spaces
![test2](https://user-images.githubusercontent.com/82603720/204344879-5fa98a9e-d9b6-427f-a98f-3222e716666a.png)

### Approach 2
Testcase 1 - 15/18 empty parking spaces

![Screenshot from 2022-11-28 23-35-06](https://user-images.githubusercontent.com/82603720/204350406-ee52a349-9b52-4145-9988-b5f5a1313880.png)

Testcase 2 - 17/18 empty parking spaces

![Screenshot from 2022-11-28 23-34-48](https://user-images.githubusercontent.com/82603720/204350515-08fa346d-9e47-4576-872e-608aace0a4b5.png)

Testcase 3 - 39/40 empty parking spaces

![Screenshot from 2022-11-28 23-34-20](https://user-images.githubusercontent.com/82603720/204350565-22b03634-a1c0-4b42-9628-4efeee4e6c44.png)

Testcase 4 - Slant parking lot

![Screenshot from 2022-11-28 23-35-23](https://user-images.githubusercontent.com/82603720/204350670-f3fe0528-2d3c-4ff5-8364-ba3fbb3b767b.png)

## Team Information

### Team: Sesh

Smruti Biswal - 2020112011</br>
Eshika Khandelwal - 2020114018</br>
Srujana Vanka - 2020102005</br>
Shreeya Singh - 2020102011

### Contribution

Smruti and Srujana: Approach 1 </br>
Eshika and Shreeya: Approach 2 </br>

## Biblography:
1. Pickel documentation: Used to save positions of parking spaces in approach 1. [link](https://www.datacamp.com/tutorial/pickle-python-tutorial)
2. Pixel count to detect if the parking space is empty or not. [link](https://www.sciencedirect.com/topics/engineering/pixel-count)
3. Capturing mouse click events with Python and OpenCV - SetMouseCallBack documentation [link](https://pyimagesearch.com/2015/03/09/capturing-mouse-click-events-with-python-and-opencv/)
4. Adaptive Thresholding for detecting curves and edges. [link](https://pyimagesearch.com/2021/05/12/adaptive-thresholding-with-opencv-cv2-adaptivethreshold/)
5. Cvzone documentation: Used for displaying the pixel count over an image. [link](https://pypi.org/project/cvzone/)

## Citation (optional)

- Parking Space Detection Using Image Processing in MATLAB (https://www.irjet.net/archives/V5/i4/IRJET-V5I4287.pdf)
