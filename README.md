# AndroidNDK
Learn using c++ code in android

//task 1: openface draw threshold form an image
  1 clone openface c++ library from https://github.com/aybassiouny/OpenFaceCpp.git
  2 build c++ project
    1 install cmake
      1 add cmake bin path to environment variant Path
      2 proxy setting in envrionment variants http_proxy & https_proxy(since in university newtwork)
    2 download dlib & tinyxml2 lib
    3 build dlib and tinyxml2 project with cmake.//maybe not need to build
  3 copy parse tinyxml2d.dll to vs .sln folder
  
task 1: openface draw threshold form an image(use another repository)
  1 download openface c++ source code from https://github.com/aybassiouny/OpenFaceCpp.git
  2 open sln & run in release mode without debugger(Ctrl+F5)
  # Resource:  1 VS 2015(already in my computer)
              2 OpenFace C++ source code
  
  
task 2: get sample FaceLandMarkImg to work on Android
  1 Compile openface library for Android
  2 Write the C++ wrapper for openFace library
  3 Configure gradle to package up library
  4 Test from Java
