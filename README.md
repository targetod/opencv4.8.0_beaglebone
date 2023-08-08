# opencv4.8.0_beaglebone
compiled opencv for BBB

Built with flags
cmake -D CMAKE_BUILD_TYPE=RELEASE -D CMAKE_INSTALL_PREFIX=/usr/local \
-D WITH_CUDA=OFF -D WITH_CUFFT=OFF -D WITH_CUBLAS=OFF -D WITH_NVCUVID=OFF \
-D WITH_OPENCL=OFF -D WITH_OPENCLAMDFFT=OFF -D WITH_OPENCLAMDBLAS=OFF \ 
-D BUILD_opencv_apps=OFF -D BUILD_DOCS=OFF -D BUILD_PERF_TESTS=OFF \
-D BUILD_TESTS=OFF -D ENABLE_NEON=on -D BUILD_opencv_python3=OFF  \
-D BUILD_opencv_python2=OFF ..

lsb_release -a
Distributor ID:	Debian
Description:	Debian GNU/Linux 10 (buster)
Release:	10
Codename:	buster
