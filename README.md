# fmo-cpp
FMO detection (demo version)

Prerequisites:
1. opencv 
2. boost

To compile:
1. mkdir build
2. cd build
3. cmake ..
4. make
5. sudo make install

To run real-time on a camera:
1. fmo-desktop --camera 0 --utiademo
2. fmo-desktop --camera 0 --demo
3. fmo-desktop --camera 0 --tutdemo
4. fmo-desktop --camera 0 --removal

To run for a specific video:
1. fmo-desktop --input <path> --demo
  
Parameters: 

Help:
1. fmo-desktop --help
