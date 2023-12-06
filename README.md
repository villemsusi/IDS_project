# IDS_project

## Analysis of image classification models for use on low-resource computing units

## Train setup - NOT FUNCTIONAL!
* Download dataset from [https://www.robots.ox.ac.uk/~vgg/data/pets/, Oxford III-t Pet Dataset]
* Setup Conda environment
* Install CUDA and cudNN
* Setup CUDA on Conda environment
* Run setup.sh
* 
* 
* Run train.py with proper arguments (python ./train.py oxford-iiit-pet/images --model convnext_tiny.fb_in22k --sched cosine --epochs 10 --warmup-epochs 5 --lr 0.4 --reprob 0.5 --remode pixel --batch-size 64)