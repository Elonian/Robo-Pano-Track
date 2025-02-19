# RoboPan

Orientation Tracking and Panorama Stitching

Accurate estimation of sensor orientation is critical for various applications in robotics, navigation, and computer
vision. This problem focuses on leveraging data from an Inertial
Measurement Unit (IMU) and cameras to refine angular velocity
measurements and improve orientation estimation of a sensor
setup. By fusing IMU and visual data, a rotation matrix is computed, representing the sensor’s orientation. This rotation matrix
is then mapped into the world coordinate frame using projections,
ensuring accurate spatial representation. The projected images
are subsequently stitched together to create a composite image
that aligns with the calculated pixel values, preserving geometric
consistency. The proposed methodology enhances the precision
of orientation estimation and image reconstruction, contributing
to improved sensor fusion techniques for real-world applications
such as SLAM, augmented reality, and autonomous navigation.
