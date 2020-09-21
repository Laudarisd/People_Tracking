Framework
============

Intallation
============


Before running th training, we need to install follwing packages:

```
Cython
matplotlib>=3.2.2
numpy>=1.18.5
opencv-python>=4.1.2
pillow
PyYAML>=5.3
scipy>=1.4.1
tensorboard>=2.2
torch>=1.6.0
torchvision>=0.7.0
tqdm>=4.41.0
```

or 

run the following command on ubuntu terminal:


```
$ pip install -r requirements.txt   ## pip == pip3
```

In my case, I used `docker`. Installing `docker` will install all of the above packages.


`.xml` to `.txt`
================

We need to convert all `xml` files to `txt` format and move them to `custom/labels/`.
 To convert th `txt` [use this code](https://github.com/Laudarisd/People_Tracking/blob/master/Framework/custom/convert_xml_to_txt.py)


Train & Val
============

Separate all images to `train.txt` and `val.txt` files by using this [file](https://github.com/Laudarisd/People_Tracking/blob/master/Framework/custom/split.py) and move to `custom` folder.

Edit `train.py` file
=====================







