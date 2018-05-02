Source:

  https://github.com/jazzsaxmafia/video_to_sequence


Using:

--python3.5

--VGG/19[in preprocessing and CNN_util.py]

  http://www.robots.ox.ac.uk/~vgg/software/very_deep/caffe/VGG_ILSVRC_19_layers.caffemodel
  
--vgg16[in model.py]

  https://github.com/ry/tensorflow-vgg16 (vgg16-20160129.tfmodel.torrent)



modified:

  [in preprocessing.py:]  cropped_frame_list = np.array(list(map(lambda x: preprocess_frame(x), frame_list)))


