SET(TARGET_SRC osgviewer.cpp )

SET(TARGET_COMMON_LIBRARIES
    OpenThreads
    osg 
    osgDB
    osgGA
    osgViewer
    EGL
)

SETUP_APPLICATION(osgviewer)
