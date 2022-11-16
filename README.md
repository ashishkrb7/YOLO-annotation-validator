# Code to validate the YOLO annotation format

This codebase is basically design to validate the image annotation done on YOLO format

## Draw an bounding box in an image

> Draw bounding boxes

1. Put all of your raw images in [./raw_images/](./raw_images/) folder.
2. Put all of your annotation files(YOLO format txt) in [./labels/](./labels/) folder.
3. Write your class information into [classes.txt](classes.txt).
4. Run python [draw_box.py](draw_box.py) in your terminal.
5. Now you have the images with bounding boxes in the [./save_image/](./save_image/) folder.

> Extract the corresponding raw images

1. Put the images with incorrect boxes into [./wrong/](./wrong/) folder.
2. Clean up [./save_image/](./save_image/) folder.
3. Run python get_origin_image.py in your terminal.
4. Now you have the raw images which were annotated incorrectly in the [./save_image/](./save_image/) folder.

