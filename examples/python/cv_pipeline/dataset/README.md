# Dataset
The file `paths_to_images_with_at_least_2_faces.txt` contains paths to the images suitable for experiments,
and it was generated by running `./find_images_with_faces.py ./dhd_traffic/images/test 500 2`.
The script finds images with at least 2 human faces via YOLO11 until there are 500 images or until all images have been checked.

Details:
- Dataset: [TJU-DHD](https://github.com/tjubiit/TJU-DHD)
- Chosen Subset: test set of TJU-DHD-traffic
- Model: [yolov11n-face.pt](https://github.com/akanametov/yolo-face)
