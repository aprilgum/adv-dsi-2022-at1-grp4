# UTS Advanced Data Science for Innovation 2022-11

## Team repository of AT Group 4

* Hitoshi Fukuda
* April Nommesen

## Project 1: NBA Career Prediction

### Clone this repository
Use this command in the Terminal:

cd /<wherever>/project     (example)

git clone git@github.com:aprilgum/adv-dsi-2022-at1-grp4.git 

### Build and run the jupyter/scipy-notebook image for Python 3.8
Use this command in the Terminal:   docker run  -dit --rm --name adv-dsi-2022-at1-grp4 -p 8888:8888 -e JUPYTER_ENABLE_LAB=yes -v ${PWD}:/home/jovyan/work jupyter/scipy-notebook:python-3.8.1


### Launch Jupyter Lab
Copy one of URLs found from the logs.  Use this command in the Terminal:   docker logs --tail 50 adv-dsi-2022-at1-grp4
Paste in a browser to launch Jupyter Lab


