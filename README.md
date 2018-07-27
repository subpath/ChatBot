# ChatBot
ChatBot with seq2seq Neural Network

Here you can find ChatBot made with seq2seq architecture and trained on [Cornell Movie - Dialogs Corpus](https://www.cs.cornell.edu/~cristian/Cornell_Movie-Dialogs_Corpus.html).

You can start using this chat bot by importing it from **ChatBot.py** file:

```python
from Chatbot import ChatBot
bot = ChatBot()
```
method .reply takes string as an input and returns predicted string
```bash
bot.reply('Where are you from?')
>> "no , i really do n't know . i 'm sorry ...""
```

If you wanna retrain bot on a different data or with different parameters, then file **ChatBot_trainig.py** contains everything you need

Medium article: https://medium.com/cindicator/building-chatbot-weekend-of-a-data-scientist-8388d99db093

