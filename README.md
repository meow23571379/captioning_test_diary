Using:

python3.5

in preprocessing and CNN_util.py

VGG/19

http://www.robots.ox.ac.uk/~vgg/software/very_deep/caffe/VGG_ILSVRC_19_layers.caffemodel

modified:

in preprocessing.py:

cropped_frame_list = np.array(list(map(lambda x: preprocess_frame(x), frame_list)))

in model.py

vgg16

https://github.com/ry/tensorflow-vgg16 (vgg16-20160129.tfmodel.torrent)

