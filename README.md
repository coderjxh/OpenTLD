# OpenTLD
from https://github.com/alantrrs/OpenTLD

# Windows

	$ git clone git@github.com:kyokyojiang/OpenTLD.git
  	$ git branch origin/windows
	$ git pull

# Ubuntu

	$ emacs /etc/profile
	  # add
	  OpenCV_DIR=/home/install/opencv2.4.12.1
	  LD_LIBRARY_PATH=$OpenCV_DIR/lib:$LD_LIBRARY_PATH
	  export OpenCV_DIR LD_LIBRARY_PATH
	$ source /etc/profile
	$ git clone git@github.com:kyokyojiang/OpenTLD.git
	$ git branch origin/ubuntu
	$ git pull
