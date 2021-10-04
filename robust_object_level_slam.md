# [ROLS : Robust Object-Level SLAM for Grape Counting](https://ieeexplore.ieee.org/document/9025552)

## Method
- Slam Pipeline
    1. **Mask R-CNN:** Segment grapes, leaves, branches
    2. **SVD:** Apply on point cloud to refine grapes, leaves, branches classification
    3. **Sphere fitting:** Landmarks for SLAM
    4. **SLAM:** Glue point clouds together using landmarks obtained from step 3
