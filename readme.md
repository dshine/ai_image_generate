# How to use

This repo generates images based on AI. Source images are stored in the source folder. Style images are stored in the style folder. These are combined to generate new images in the output folder.
Based on this tutorial: https://towardsdatascience.com/python-for-art-fast-neural-style-transfer-using-tensorflow-2-d5e7662061be

## Clone Repo
```
git clone https://github.com/dshine/ai_image_generate.git
```
## Create Virtual Env

```
python3 -m venv venv
```
```
source /venv/bin/activate
```
## Install Requirements
```
pip install -r requirements.txt
```

## Populate Source & Style
Grab some images and store them in the folders

## Run program
```
python run.py
```
## Example 
### Source Image
![Source Image](/source/birmingham-museums-trust-Ct2Q6q29xds-unsplash.jpg)
### Style/Pattern
![Source Image](/style/birmingham-museums-trust-_sn71oyTN4o-unsplash.jpg)
### Output
![Source Image](/output/1641315330.3137836.png)