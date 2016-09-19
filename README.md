Feature extractor for resnet50. Based on https://github.com/Lasagne/Recipes/blob/master/examples/resnet50/ImageNet%20Pretrained%20Network%20(ResNet-50).ipynb

Download the model weights from https://s3.amazonaws.com/lasagne/recipes/pretrained/imagenet/resnet50.pkl

Usage:
~~~~
python resnet_50_test.py -i image_path -m model_weight_pkl
~~~~

Following function can be used to get feature extractor for any layer.
~~~~
get_feature_extractor(pkl_model, layer_name)
~~~~
