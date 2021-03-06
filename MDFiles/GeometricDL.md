## Multi-view Geometry using Deep Learning
- [PoseNet: A Convolutional Network for Real-Time 6-DOF Camera Relocalization](https://arxiv.org/abs/1505.07427): Uses a naive loss function to regress 6DOF pose from an input RGB image. Needs excessive parameter tuning.

- [Geometric Loss Functions for Camera Pose Regression with Deep Learning](https://arxiv.org/abs/1704.00390):  Improvement of the PoseNet paper with better results a new theoretical loss functions based on multi-view geometry.

- [SfM-Net: Learning of Structure and Motion from Video](https://arxiv.org/abs/1704.07804): Outputs 3D scene depth, 6DOF camera pose between 2 images.

- [Unsupervised Learning of Depth and Ego-Motion from Video AKA SFMLearner](https://arxiv.org/abs/1704.07813): David Lowe's paper with Google to estimate depth from a single image and multi-view 6DOF pose.

- [UnDeepVO: Monocular Visual Odometry through Unsupervised Deep Learning](https://arxiv.org/abs/1709.06841): Monocular VO, estimates depth and 6DOF pose. Performs better than SfMLearner.

- [Alex Kendall's Blog](https://alexgkendall.com/computer_vision/Reprojection_losses_geometry_computer_vision/) Awesome curated list of papers which use deep learning to solve multi-view geometry problems.

- [LIFT: Learned Invariant Feature Transform](https://arxiv.org/abs/1603.09114) SIFT like matching using deep learning. Super robust and does not need RANSAC.

- [Unsupervised Deep Homography: A Fast and Robust Homography Estimation Model](https://arxiv.org/abs/1709.03966) Estimate robust homography using deep learning. Steven's and Shreas' paper.

- [End-to-End Learning of Geometry and Context for Deep Stereo Regression](https://arxiv.org/abs/1703.04309) Alex Kendall and Skidio's paper on obtaining stereo disparity using CNN. Takes 0.90s per pass. [<img src="../README/images/logo/tf.jpg" width="24" height="24" />](https://github.com/Jiankai-Sun/GC-Net) 

- [Pyramid Stereo Matching Network](https://arxiv.org/abs/1803.08669) Stereo disparity from CNN. Impressive results. Takes 0.41s per pass. [<img src="../README/images/logo/pytorch.jpg" width="24" height="24" />](https://github.com/JiaRenChang/PSMNet) 
