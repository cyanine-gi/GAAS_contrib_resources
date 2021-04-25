# Dependencies for GAAS_contrib:

## We need eigen-3.3.9 for cuda-ndt acceleration.

eigen-3.3.9 usage:

    cd eigen-3.3.9&&mkdir build&&cd build&&sudo make install&&sudo ldconfig -v

**You have to download and compile opencv-3.4.5 and pcl-1.8 manually.** Maybe some CMakeLists.txt need to be edited.


## **If you are using AGX Xavier:**  you need to copy vision opencv to GAAS_contrib/algorithms/src/. Just do:

    cp -r vision_opencv ~/GAAS_contrib/algorithms/src/


