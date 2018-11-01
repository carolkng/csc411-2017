# CSC411 Project 1

Original project available [here][1]

## Setup

### Data harvest

To download the required facescrub data, modify the `acts` list in
[`./data/get_data.py`](./data/get_data.py) and create the directory `data/uncropped`. This will put the
downloaded, uncropped images into the directory for further processing.

Note: the script appears to hang if the `data/uncropped` directory is not
present.
