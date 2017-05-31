# Disparity_image

Used to find out the disparity present between two image. 

## How to use:
```
cd /path/to/opencv-files
cd disparity_image
mkdir build && cd build
cmake ..
make
./Disparity /path/to/left-image.png /path/to/right-image.png
```

# Camera Calibration

Used to calibrate the camera i.e. find out the intrincis paramters of the camera along with the distortion factors.

## How to use:
```
cd /path/to/opencv-files
cd calibration
mkdir build && cd build
cmake ..
make
./calibration -w=4 -h=5 -s=0.025 -o=camera.yml -op -oe
```

# Good Practice
Run the `clean.sh` everytime before pushing your code to the git repo. 
