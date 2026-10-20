# Google's structured method learns depth and ego-motion from monocular video

- **Date:** 2018-11-27
- **Who:** Google Research
- **Type:** research

Google described an unsupervised method that learns depth and camera motion from a single camera. It models the scene in 3D, with moving objects and the camera each given their own motion. On the KITTI and Cityscapes driving datasets it beat earlier unsupervised methods and approached methods that use stereo supervision, and it added an online refinement step for transfer between datasets. It mattered for robots and cars that must judge distance without a stereo rig.

## Sources
- https://research.google/blog/a-structured-approach-to-unsupervised-depth-learning-from-monocular-videos/
