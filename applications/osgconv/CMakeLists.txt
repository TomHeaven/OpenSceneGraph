SET(TARGET_SRC
    OrientationConverter.cpp 
    osgconv.cpp
)
SET(TARGET_H
    OrientationConverter.h
)

SET(TARGET_COMMON_LIBRARIES
    OpenThreads
    osg 
    osgDB
    osgGA
    osgViewer
    EGL
)

SETUP_APPLICATION(osgconv)
