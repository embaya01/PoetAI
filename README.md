## Project Title
Poet AI: Text Generation using LSTM Neural Networks

## Project Description
This project is aimed at generating new text using LSTM neural networks. LSTM networks are a type of recurrent neural network (RNN) that are capable of learning long-term dependencies. They are often used in natural language processing (NLP) tasks such as language translation, speech recognition, and text generation.

The dataset used for this project is a collection of text documents. The text is preprocessed, and then the LSTM network is trained on the processed text. Once trained, the network can be used to generate new text.

The project is implemented using Python and Keras, a high-level neural networks API. The project also makes use of the numpy and nltk libraries.

## Installation
To run this project, you need to have Python 3 installed. You can download Python from the official website: [https://www.python.org/downloads/](https://www.python.org/downloads/)

Once you have installed Python, you need to install the following libraries:
```bash
Keras
numpy
nltk
```
You can install these libraries using pip, the Python package installer. Open a command prompt or terminal window and run the following commands:
```python
pip install keras
pip install numpy
pip install nltk 
```
You also need to download the nltk data. Open a Python shell and run the following commands:

```python
import nltk
nltk.download('punkt')
```
## Usage
To use this project, follow these steps:

Download or clone the project from GitHub.

Navigate to the project directory.

Run the text_generation.py file using the following command:

```python
python text_generation.py
```
The program will train the LSTM network on the input data and generate new text.


## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## Credits
This project was created by Elisee Mbaya.

## License

[MIT](https://choosealicense.com/licenses/mit/)
