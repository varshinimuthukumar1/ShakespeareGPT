An implementation of a decoder only auto-regressive transformer model trained on [Tiny Shakespeare Dataset](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://raw.githubusercontent.com/karpathy/char-rnn/master/data/tinyshakespeare/input.txt&ved=2ahUKEwjj7-mTk8CHAxWEBdsEHbQcAwIQFnoECBQQAQ&usg=AOvVaw1IimzpEutw_xJxKH0xyDb1).  It generates random verses of text modelled in Shakespearen style.  

It has the building block implementations of the self-attention and transformer, and an implementation from scratch.  It is following this tutorial, [Let's build GPT from scratch](https://www.youtube.com/watch?v=kCc8FmEb1nY) from Andrej Karpathy.


The model trained has 10M parameters.  The tokens are character level(not sub-word level like ChatGPT), and there are 65 unique tokens in this case.

## Model

|  Model             | n<sub>parameters</sub> | n<sub>tokens</sub> | 
|--------------------|------------------------|--------------------|
| GPT-3              | 175.0B                 | 300B               |
| Shakespeare-GPT    | 10M                    | 300000             |


## Demo

The model can generate Shakespeare like verses right now, although it does not make any sense yet.  Before improving the model architechture, I need to solve the issue of having a larger computing capacity.

![Demo](images/demo.gif)

