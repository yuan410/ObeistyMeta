# System Requirements
## Hardware requirements
To run the entire script a computer with >14.8 GB RAM is needed to support the in-memory operations.
## Software requirements
### OS Requirements
The script can be run on Windows, macOS and Linux. The package has been tested on Ubuntu 23.04 and Windows 10.0.22631.
### Python Dependencies
numpy
scipy
matplotlib
scikit-learn
pandas
seaborn
statistics
# Pull image from Dockerhub and run: 
  - open a commond line, make a directory if you like, then:
  - `docker pull yueyu445/obesity_jupyter_image`
  - `docker run -it -p 8888:8888 yueyu445/obesity_jupyter_image`
  - Then copy the url it generates (e.g.`http://(0de284ecf0cd or 127.0.0.1):8888/?token=e5a2541812d85e20026b1d04983dc8380055f2d16c28a6ad`) to your local browser.
  - Upon successful Dockerhub entrance: Navigate to the file notebooks/MockedDataResults.ipynb, then click Run > Run All Cells to execute the code script.
### Run Time estimation:
2 hours approximately (run via the Docker Container as described above)
