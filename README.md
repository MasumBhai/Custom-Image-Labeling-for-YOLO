# Custom Image Labeling for YOLO-v4 

### Build for Windows

```bash
conda install pyqt=5
conda install -c anaconda lxml
pyrcc5 -o libs/resources.py resources.qrc
python custom_label_img.py [IMAGE_FOLDER_PATH] [CLASS_FILE]
```