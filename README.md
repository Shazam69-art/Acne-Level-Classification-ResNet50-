# Acne-Level-Classification-ResNet50-
An Acne Level Classification model which can predict three levels of classification ( ["Level_0", "Level_1", "Level_2"]).

Link to download the .pth file: https://drive.google.com/file/d/1MBh-06iknEFGZUot339X4ZlU7vIY2Z01/view?usp=sharing.

Make sure the class names are set properly : "Level_0", "Level_1", "Level_2". The model was trained on these classes, so, the names must be exact.


One of the most important libraries to load this .pth file: 
import torch
from torchvision import transforms
from torchvision.models import resnet50
