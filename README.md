# mapstitch_data
Contains data for experimenting with map stitching.


To test stitching:
* Get repo into your workspace, hector members can do
    ```
    hector install mapstitch_data
    ```
    
* Run stitcher command line tool:
    ```
    roscd mapstitch_data/maps
    rosrun mapstitch mapstitch_tool tiz_01_mod/map.pgm tiz_02_rotated/map.pgm  -v -d 10
    ```
