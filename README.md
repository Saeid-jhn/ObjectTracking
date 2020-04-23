# ObjectTracking #
Object Tracking based on Color detection using [OpenCV](https://opencv.org/) library and [Python](https://www.python.org/) - Raspberry Pi

## About ##
This project is build for tracking ball-shaped object based on its color. The project could be run on [Raspberry Pi](https://www.raspberrypi.org/) using Pi camera. For more detail please visit [Pyimagesearch](https://www.pyimagesearch.com/2015/09/21/opencv-track-object-movement/) webpage.

## Installing ##
The following packages are required to run the project:

* Python 3.8.2
* imutils 0.5.3
* OpenCV 4.2.0

1. Install python from the [www.python.org](https://www.python.org/downloads/) or use [Anaconda](https://www.anaconda.com/distribution/).
2. Install [imutils](https://pypi.org/project/imutils/) using Pip or Conda:
    * Pip `pip install imutils`
    * Conda `conda install -c conda-forge imutils`
3. Instal [OpenCV](https://opencv.org/) using Pip or Conda.
    * Pip `pip install opencv-contrib-python`
    * Conda `conda install -c anaconda opencv`
## Run ##
* In order to use Raspberry Pi camera, simply run [ball_tracking.py](https://github.com/Saeid-jhn/ObjectTracking/blob/master/ball_tracking.py).
* To use your local machine (PC or Raspberry Pi) video, use following script in terminal and give your video file path:
`python ball_tracking.py --video ball_tracking_example.mp4`

## Support ##
If you find this repository helpful, please star and fork it to support me.

## Contact ##
For questions, please contact Adrian Rosebrock in [pyimagesearch](https://www.pyimagesearch.com/2015/09/21/opencv-track-object-movement/).

## Reference
OpenCV Track Object Movement by Adrian Rosebrock on September 21, 2015 [[link]](https://www.pyimagesearch.com/2015/09/21/opencv-track-object-movement/)

## License ##
This project is distributed under [MIT License](https://github.com/Saeid-jhn/ObjectTracking/blob/master/LICENSE)
