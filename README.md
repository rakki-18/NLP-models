Building a Deep Learning NLP  model( embedding layer + LSTM + hidden layers) that classifies IMDB reviews as positive or negative.
# References
https://www.coursera.org/learn/natural-language-processing-tensorflow<br>
[LSTM](https://www.youtube.com/watch?v=9TFnjJkfqmA&t=29s)<br>
Read about tokenization from [here](https://nlp.stanford.edu/IR-book/html/htmledition/tokenization-1.html)<br>
Read about word embeddings from [here](https://machinelearningmastery.com/what-are-word-embeddings)<br>

# Viewing Embedding Projections
- Go to [projector.tensorflow.org](http://projector.tensorflow.org/)
- Click on 'Load Data' 
- Click on 'Choose File' and then select the vectors.csv file
- Click on 'Choose File' and then select the words.csv file
- Check Spherize data
You should get something similar to this.
https://user-images.githubusercontent.com/55957545/97743369-8bdc6880-1b0b-11eb-93d5-20d3d640ce75.png
Notice how 'bad' and 'vampires' are clustered together :P
