# Source:

  https://github.com/jazzsaxmafia/video_to_sequence


# Using:

--Anaconda conda created an environment "activate caffe" to import caffe

--python3.5

--caffe

--Tensorflow

--VGG_ILSVRC_19   

  [in preprocessing and CNN_util.py]  	http://www.robots.ox.ac.uk/~vgg/software/very_deep/caffe/VGG_ILSVRC_19_layers.caffemodel
  
--vgg16    

  [in model.py]		https://github.com/ry/tensorflow-vgg16 (vgg16-20160129.tfmodel.torrent)



# Modified:

  [in preprocessing.py:]  cropped_frame_list = np.array(list(map(lambda x: preprocess_frame(x), frame_list)))


