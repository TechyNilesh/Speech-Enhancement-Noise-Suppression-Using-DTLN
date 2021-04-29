# Speech Enhancement Noise Suppression Using DTLN
- **Speech Enhancement:**  Tensorflow 2.x implementation of the stacked dual-signal transformation LSTM network (DTLN) for  Noise Suppression.
- The code for training, inferring, and serving the DTLN model in Python is available in this repository. It also includes SavedModel, which contains pre-trained models that can be used as a starting point for your own projects.

## Model Running Instructions
1. First you need to install python latest verion of python 3 and pip module.
2. After that you just need to go working Directory and run: `pip run -r requirements.txt`
3.  After that you can run your **JUPYTER NOTEBOOK** and open file named: `Model File.ipynb`
4. All the model, training and testing instruction are given on that file.

## Sample
I am showing you sample file befor noise reduction and after noise reduction.

- Normal Audio With Noises: [Noisy Audio Input](https://github.com/TechyNilesh/Speech-Enhancement-Noise-Suppression-Using-DTLN/blob/main/data_test/input/noisy_input.wav "Noisy Audio Input")
- After Cleanig Noise: [Clean Audio Output](https://github.com/TechyNilesh/Speech-Enhancement-Noise-Suppression-Using-DTLN/blob/main/data_test/output/noisy_input.wav "Clean Audio Output")

## Refrences
- Paper : [Dual-Signal Transformation LSTM Network for Real-Time Noise Suppression](https://www.isca-speech.org/archive/Interspeech_2020/pdfs/2631.pdf "Dual-Signal Transformation LSTM Network for Real-Time Noise Suppression")
- Notes: [Paper Notes](https://github.com/TechyNilesh/Speech-Enhancement-Noise-Suppression-Using-DTLN/blob/main/Documents/paper%20notes.pptx "Paper Notes")
