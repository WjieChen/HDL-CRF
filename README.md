# HDL-CRF

This is  a model for bacterial name entity recognition

you can train your own model through the train.py or use pre-trained model to predict 

the parameter file in model/config.py,you can adjust the parameter .
the model weights of ours in test file

1.Train your own model
  1) python build_data.py
  2) python train.py
  3) python evaluate.py
 
2. use pre-trained model
 1) python predict.py
 

3. evaluate the model of us

    python evaluate.py
    
    
  
references:

https://github.com/guillaumegenthial/sequence_tagging

