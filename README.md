# EngineForAnimationCourse

### Graphic Engine based on Libigl



#### IK using OCC

uploaded the last update made 2 new functions isPossible which checks the distance between the origin point and the destination and prints out of reach, added the keycallbacks of t p d as in the assignment description, in update is where i do the CCD calculating the angle and the axis it should rotate on. pressing space you can still move the box around and itll update it even if the box goes out of reach the arm will not break and will still try to move towards the box(i thought of removing this but i thought if you are actually trying to animate thats ok).

*code is in ik basicScene.cpp
