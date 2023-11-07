# AGWS
This repository contains the code of the paper: Adaptive Gradient-based Word Sailency for Adversarial Text Attacks

## Usage  
unzip AGWS_code.zip

cd AGWS_code

pip install -e.
_____________________________________________________________________________________________________________________

The AGWS can be easily tested by the command line in the TextAttack framework:  
`textattack attack --recipe agws --model bert-base-uncased-mr --num-examples 1000`  
This will attack BERT model on MR dataset using the AGWS.  

Notice that, for the shield model, due to the author only provide the OpenAttack-supported model.
Therefor, you should turn the weight to .bin in order to adjust textattack libraries.
Or, you can E-mail qiyupeng0714@163.com, I can provide the Textattack-supported model type.

#,# Acknowledgement  
This code is based on the [TextAttack](https://github.com/QData/TextAttack) framework.
