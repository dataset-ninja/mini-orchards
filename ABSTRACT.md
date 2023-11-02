**Mini-Orchards** is an object detection dataset comprising 492 images and 3124 labeled objects, all pertaining to a single class — *apple*. Created within a specific laboratory, these images portray apples suspended by string against a background resembling a genuine orchard. Most images offer a clear view of apples without obstruction, though some instances exhibit apples obstructed by others, adding a touch of complexity. This dataset serves as a valuable resource for object detection in computer vision and agricultural research.

Mini-Orchards Dataset is a logical continuation of __Simulated-Orchards Dataset__ [(available on DatasetNinja)](https://datasetninja.com/simulated-orchards). You can check the specifics of simulating apples on the Unity engine in this dataset.

Mini-Orchards is a dataset created within authors' lab and consists of images of apples suspended by string from a frame. The apples hanging in front of a background emulate a real orchard. The nature of the images makes it a rather simple dataset, since apples are visible mostly without obstruction from branches and leaves. There are however cases where apples are obstructed by other apples. The camera was placed at a fixed distance from the frame holding the apples. RGBD images were taken using a ZED Stereolabs stereo camera. However, since this research focuses on RGB data, the depth channel was discarded. The resulting images have a 1920x1080 resolution.

Mini-Orchards has 500 images that are divided into a *train*, *val*, and *test* set. The train set contains 300 images, while the validation and test sets each have 100 images. The complete dataset has roughly 3000 apples that are annotated with bounding boxes.

In the original images, too much of the surrounding environment is visible in the frame of the camera. Objects like the grid structure holding the apples can be seen in the images. Authors cropped the images to discard the irrelevant background section of the images and used these cropped images for authors' experiments. Figure below shows an example of a cropped and uncropped image from the dataset. The cropped images have a resolution of 1920x576.

<img src="https://github.com/dataset-ninja/mini-orchards/assets/123257559/c43aabb1-e813-4870-b48a-babf0aec907f" alt="image" width="800">

<span style="font-size: smaller; font-style: italic;">Example of (a) original and (b) cropped image from the Mini-Orchards dataset.</span>
