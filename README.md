# Use LLAMA

Llama 2 models:
1. 7B
2. 13B
3. 70B

use instruction tuning to turn the Llama 2 models into a chatbots.

Open source.

Code Llama is also available (7B/13B/34B)

PS: _Code Llama - python_ could be useful

Purple Llama is a responsible AI



## 1. Install Llama 2 locally
check [link](https://ai.meta.com/blog/5-steps-to-getting-started-with-llama-2/)

For me, I create a conda env to hold each package to run Llama2.

~~~
$ conda create -n llama2_env python=3.11
~~~


## 2. Download the model weights
Follow the step 2 to request the model [link](https://ai.meta.com/llama/) first 

I downloaded models:
* all (not code-llama)

But it is not working in two parts:

* Launch the download.sh script (_bash_ download.sh). When prompted, enter the presigned URL you receive in your email.
* Run cp ./tokenizer.model ./llama-2-7b-chat/tokenizer.model to create a copy to the tokenizer.

