# Step CV-Pipeline: model_train

This CV-Pipeline component is intended for configuring model training and starting model training

Input data for step CV-Pipeline: model_train
- **coco_train_dataset**     
Training dataset
- **coco_eval_dataset**     
Validation dataset
- **yolox_pth_pretrain_weights**     
Predtraining weights

The output of this step CV-Pipeline is
- **obj_detect_inference_files**     
Saved weights of the trained model (weights of the last epoch and with the best achieved metrics), configuration files

## How to run a step CV-Pipeline: model_train

### clone the repository: model_train
```
git clone --recurse-submodules https://github.com/4-DS/obj_detect_binary-model_train.git
cd obj_detect_binary-model_train
```  

### run step CV-Pipeline:model_train
```
python step.dev.py
```  
or
```
step.prod.py
``` 

