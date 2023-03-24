# NLTK_News_Prediction_LSTM

There has been an outbreak of fake news as the world move into a pandemic era where the source of information for most people around the world was the internet. 
Fake news may include opinions, rumors and made up stories that can be masked in a way to make it look like real and legitimate news. For this very reason spreading fake news or misinformation around the world is a powerful tool given that fake news spreads faster than the truth. One of the very reasons why individuals with malicious intent leverage this tool is because of its faster transmittance.

In this repo, we will perform News_prediction using Natural Language Processing and LSTM with both Normal and Bidirectional approaches.

![image](https://user-images.githubusercontent.com/85514219/227405165-05f3e511-1aa1-4f3c-93da-9d05ba2f8dc0.png)


## LSTM

Long Short-Term Memory (LSTM) is an artificial neural network used in artificial intelligence and deep learning. 

Unlike standard feedforward neural networks, LSTMs have feedback connections. Such recurrent neural networks (RNNs) can process not only individual data points (such as images), but also entire data sequences (such as audio or video). This property makes LSTM networks ideal for data processing and prediction. For example, LSTM has been used for unsegmented connected handwriting recognition, speech recognition, machine translation, voice activity detection, robot control. It can be applied to tasks such as video games and healthcare.

LSTM is a special type of recurrent neural network. In particular, this architecture was introduced to solve the vanishing and exploding gradient problem. In addition, this type of network recognizes the relationship between the first and last values ​​of a sequence, making it suitable for maintaining long-distance connections.

LSTM models introduce expressions, especially gates. There are actually three types of gates:

      Forget Gate - Controls how much information the memory cell gets from the previous step's memory cell.
      Update (input) gate - Determines whether to update the memory cell. It also controls how much information the current memory cell potentially gets from the new memory cell.
      Exit Gate - Controls the value of the next hidden state
      
## Bidirectional LSTM

Bidirectional LSTM (BiLSTM) is a recurrent neural network used primarily on natural language processing. Unlike standard LSTM, the input flows in both directions, and it’s capable of utilizing information from both sides. It’s also a powerful tool for modeling the sequential dependencies between words and phrases in both directions of the sequence.

In summary, BiLSTM adds one more LSTM layer, which reverses the direction of information flow. Briefly, it means that the input sequence flows backward in the additional LSTM layer. Then we combine the outputs from both LSTM layers in several ways, such as average, sum, multiplication, or concatenation.

![image](https://user-images.githubusercontent.com/85514219/227406431-afb87aac-e0f9-45e8-86f0-e8e4a03d7309.png)

## NLTK

NLTK is the primary platform for building Python programs that work with human language data. Classification, tokenization, stemming, tagging, parsing, semantic reasoning, industry-grade wrappers around his NLP libraries, and an active discussion forum. NLTK has been called "a great tool for teaching and working with computational linguistics using Python" and "a great library for playing with natural languages". Natural Language Processing with Python is a hands-on introduction to language processing programming. Written by the NLTK developers, it guides the reader through the basics of writing Python programs, manipulating corpora, classifying text, and analyzing language structures.

## All the necessary scripts with all required dependencies are provided. Thank you :))
