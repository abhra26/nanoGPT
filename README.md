# nanoGPT
In this coding project we trained a nanoGPT model from Andrej Karpathy’s  github project. The model was first trained on a dataset containing shakespeare text. We first trained a baby GPT model from scratch and then we fine tuned it. The fine tuned model was made from the checkpoint of a GPT2 model. The fine tuned model performed better than training from scratch because of the obvious reason that we had more optimised parameters and hyper parameters. Fine tuning exposed the model to a more extensive vocabulary and text patterns and hence produces better output. 

Using this GitHub as guidelines we prepared a dataset containing PG Wodehouse texts. We trained the nanoGPT on this dataset. For fine tuning we used gpt-2-simple library in python to fine tune a GPT2 model.

Results can be seen for PG Wodehouse by using the same terminal commands given in the reference GitHub, just replace. "shakespeare" to "wodehouse" or "Wodehouse" accordingly.
