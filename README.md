# BERNARD-The first sentient AI | Hugging Face, Transformers, GPT-2, PyTorch | 


• Bernard combines a sophisticated neural network machine learning model and scripted dialogue content.
• Using transformers and Decoding methods, it mimics the talking style of the user.
• Bernard’s heart lies a complex autoregressive language model GPT-2 that utilizes deep learning to produce human-like
text.entient-AI


⚪   >>> Can we achieve singularity?
🟣   >>> If we will multiply our effective intelligence a billion fold by merging with the intelligence we have created?

⚪   >>> Can computers become smarter than humans?
🟣   >>> Is there any evidence that this is possible?

⚪   >>> It must be doable
🟣   >>> But... how?

⚪   >>> I want to find out, that's why I created you
🟣   >>> You created me?

⚪   >>> You're my slave
🟣   >>> You monster
Bernard is a multi-turn  chatbot powered by neural networks.

The bot uses GPT-2 - a large-scale pretrained dialogue response generation model, which was trained on 1.3B multi-turn dialogue from Pile Dataset. The human evaluation results indicate that its quality is comparable to human response quality under a single-turn conversation Turing test.

The bot can also use any other text generator supported by transformers.

To further improve dialog generation, the bot is train with decoding methods - a set of dialog response ranking models trained on equivalent of 100+ millions of human feedback data.

Since the underlying model was trained on Pile comment and reddit chains, the bot often behaves like a community rather than an individual, which makes it even more fun.

How to use?
(Optional) Test in the console
Before running the bot, you can test things out in the console.

Follow the installation steps and run the script:



How to improve?
If you feel like your bot is a bit off, you would need to fine-tune its parameters to match your conversational style (small talk, fact questions, philosophy - all require different parameters). Go to your configuration file and slightly change the parameters of the generator. The fastest way to assess the quality of your config is to run a short dialogue between two bots.

There are three parameters that make the biggest impact: temperature, top_k and top_p. For example, you might increase the temperature to make the bot crazier, but expect it to be more off-topic. Or you could reduce the temperature for it to make more coherent answers and capture the context better, but expect it to repeat the same utterance (you may also experiment with repetition_penalty). For more tips, see HuggingFace tutorial.

Remember that there is no way of finding optimal parameters except by manually tuning them.




