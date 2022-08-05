# Custom Image Labeling for YOLO 

### Installation

1. Clone this repository 
```bash
https://github.com/MasumBhai/Custom-Image-Labeling-for-YOLO.git
```
2. Requirements installation

```bash
pip3 install -r requirements.txt
```

### How to Download custom images

use <a href="https://chrome.google.com/webstore/detail/image-downloader/cnpniohnfphhjihaiiggeabnkjhpaldj" target="_blank">"image downloader"</a> extension of chrome, to download batch images.

### How to label those custom images

*note: downloaded image folder & this project folder path should be different for image labelling. <br/><br/>
Now, inside the project directory, create a virtual environment & edit the classes.txt file per your image class.<br/><br/>
Run these command in terminal: 

```bash
conda install pyqt=5
conda install -c anaconda lxml
pyrcc5 -o libs/resources.py resources.qrc
python custom_label_img.py [IMAGE_FOLDER_PATH] [CLASS_FILE] [SAVE_DIR]
```

#### Acknowledgement
#### <a href="https://github.com/tzutalin/labelImg.git" target="_blank">This awesome repository</a>


### Feedback

If you have any feedback, please reach out to me at abdullahmasum6035@gmail.com

| <a href="https://github.com/MasumBhai"><img alt="Abdullah Al Masum's Github Stats" src="https://github-readme-stats.vercel.app/api?username=masumBhai&show_icons=true&count_private=true&theme=great-gatsby" width=500></a> | <a href="https://github.com/MasumBhai"><img alt="Abdullah Al Masum's Github Streak" src="https://github-readme-streak-stats.herokuapp.com?user=MasumBhai&theme=vision-friendly-dark&fire=DD2727&sideNums=CD5CDD" width=500></a> |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
