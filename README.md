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

## Acknowledgement  
This code is based on the [TextAttack](https://github.com/QData/TextAttack) framework.
