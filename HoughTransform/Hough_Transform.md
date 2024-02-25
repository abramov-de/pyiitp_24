## How to use it?

To use the program, write the following command in the terminal:

```commandline
python HoughTransform.py -image .\test_image\building.jpg
```
Also you can use some ***optional parameters***:
```commandline
python HoughTransform.py -image .\test_image\building.jpg 
                         --edge_pixel_threshold 255 
                         --lower_canny_threshold 300 
                         --upper_canny_threshold 400 
                         --line_select_threshold 180
```
where:
```commandline
-image - Path to source image
--edge_pixel_threshold - Threshold for defined edges pixels and them locations (default=255)
--lower_canny_threshold - Lower threshold for Canny() function from OpenCV (default=300)
--upper_canny_threshold - Upper threshold for Canny() function from OpenCV (default=400)
--line_select_threshold - Threshold for selecting some emergency values and then drawing lines (default=180)                            
```


Examples of how the algorithm works (all these images are in the folders "Input images" and "Output images"):

![Lines example](/result_image/lines_result.png)

![Square example](/result_image/square_result.png)

![Building example](/result_image/building_result.png)

![Road example](/result_image/road_result.png)

![Parking example](/result_image/parking_result.png)

