# Custom Image Labeling for YOLO-v4 

### How to Download custom images

use <a href="https://chrome.google.com/webstore/detail/image-downloader/cnpniohnfphhjihaiiggeabnkjhpaldj" target="_blank">"image downloader"</a> extension of chrome, to download batch images.
### How to label those custom images
*note: downloaded image folder & this project folder path should be different for image labeling. <br/><br/>
Now, inside the project directory, create a virtual environment & edit the classes.txt file per your image class.<br/><br/>
Run these command in terminal: 

```bash
conda install pyqt=5
conda install -c anaconda lxml
pyrcc5 -o libs/resources.py resources.qrc
python custom_label_img.py [IMAGE_FOLDER_PATH] [CLASS_FILE] [SAVE_DIR]
```

### Acknowledgement
<a href="https://github.com/tzutalin/labelImg.git" target="_blank">this awesome repository</a> 