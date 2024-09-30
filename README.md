# System Requirements
## Hardware requirements
To run the enire code script a computer with >14.8 GB RAM to support the in-memory operations.
## Software requirements
### OS Requirements
The code script can be on Windows, macOS and Linux.  The package has been tested on Ubuntu 23.04 and Windows 10.0.22631
### Python Dependencies
numpy
scipy
matplotlib
scikit-learn
pandas
seaborn
statistics
# Pull image from Dockerhub and run: 
  - opem a commond line, make a directory if you like, then:
  - `docker pull yueyu445/obesity_jupyter_image`
  - `docker run -it -p 8888:8888 yueyu445/obesity_jupyter_image`
  -  Then copy the url it generates (e.g.`http://(0de284ecf0cd or 127.0.0.1):8888/?token=e5a2541812d85e20026b1d04983dc8380055f2d16c28a6ad`)
  - Edit this: `(0de284ecf0cd or 127.0.0.1)` to: `127.0.0.1`, in the above link and open it in your browser
  - Navigate to the file notebooks/MockedDataResults.ipynb, then click Run > Run All Cells to execute the code script. 
