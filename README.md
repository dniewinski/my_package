Download this into a workspace, then build and source that workspace 

Export your urdf extras with:

    export JACKAL_URDF_EXTRAS=$(catkin_find my_package urdf/sensors.urdf.xacro --first-only)
