# 3D Visualizing Body Pose Landmarks 

This repository provides demonstration of how to visualize body pose landmarks both for real-time video and static images. We utilized library Plotly to visualize body landmarks for static image. Compared to static case, real time detection pose significant issue with jitter. There are many smoothing techniques to remove jittering; however for real-time jitter removal 1euro-noise-filtering is ideal choice. To visualize body landmark in real-time Open3D will be implemented. The repo deployed in jupyter notebook and do following:
* implement 1euro-noise-filtering to make smooth visualization
* static 3D visualization with Plotly
* real-time 3D visualization with open3D

## Acknowledgements

Usefull resources
* [SmoothNet: A Plug-and-Play Network for Refining Human Poses in Videos][1] 
* [Towards a more applicative Pose Estimation][2]
* [Detection of 3D Human Posture Based on Improved Mediapipe][3]

[1]: https://arxiv.org/pdf/2112.13715v2 
[2]: https://towardsdatascience.com/towards-a-more-applicative-pose-estimation-bf18bc311228
[3]: https://www.researchgate.net/publication/368864097_Detection_of_3D_Human_Posture_Based_on_Improved_Mediapipe 

## Demo (Click to view video)
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/iJvPCGDfUqs/0.jpg)](https://www.youtube.com/watch?v=iJvPCGDfUqs)


## Further Work
* Motion Capture using only one camera
* Character/avatar movement control with camera
## License

[MIT](https://choosealicense.com/licenses/mit/)

