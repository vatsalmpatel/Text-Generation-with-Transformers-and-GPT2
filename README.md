# Text Generation using Hugging Face 🤗 Transformers and GPT2

In thie example are going to look at Text Generation using the GPT2 model and Hugging Face 🤗. Using this model, we can generate paragraphs of text by just using a starting sentence.

# How to run the notebook, you might ask ❓

To that I would say, a very good question. In order to run the notebook, you need to install some dependencies first, and enable some `developer' features within `Windows`, in order to load the model from Hugging Face 🤗.

First, lets install some dependencies. In order to do so, you need to create an environment using Anaconda or any other environment manager you perfer (I prefer Anaconda) and do the following:

```Bash
conda create -n new_env_name
```

After you have created the encironment, activate it using

```Bash
conda activavte new_env_name
```

After this you need to install all the dependencies from the `requirements.txt` file:

```Bash
pip install -r requirements.txt
```

Once this is done, you also need to enable developer inside windows, to do that you need to search `Developer` in Windows Search and then go to `Developer Settings`. Enable the option and restart your computer. Once this is enabled, if you are using `Jupyter Notebook` you need to open the command prompt as `Administrator` and then run Jupyter Notebook.

# Introduction to the Notebook 📓

▶ `Imports` importing important libraries to use the GPT2 model with the Huggin Face 🤗 transformer.

▶ `Loading the GPT2 model`, this will help in loading the GPT model from Hugging Face. We use the inbuilt GPT2 Tokenizer to tokenize the starting sentence so that it can be passed to model for next sentence generation. 

Link to the model: https://huggingface.co/gpt2

▶ `Generate and Decode text`, we use the model that we created and use that to generate paragraphs from a starting sentence. We can set the `max_length` parameter to any number of words that you want to generate. Finally you decode the output to get human-readable words that the model has generated.

---

### And just like that, we created a Text Generation script by using the GPT2 model and Huggin Face Transformers. It is that easy by using the pre-trained models to generate paragraphs of text, that look as if some person 🧑 wrote that piece of text ✅🏁. 
