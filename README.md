# Slang Emulator

At its core, a GPT model that can take a text file from anywhere on the internet or from local files and imitate the linguistic style of the text


The program makes use of multi-head attention, feedforwards, dropouts, transformer blocks, layer norms, and residual layers.
It also has the ability to run on a GPU with CUDA capabilities. It uses the Adam optimizer and of course, bigram model.

This repository has 2 versions of a GPT model. The more newer version is the gpt-model.py file, which runs in about 15 min.
The older version is the prototype.py file, which contains a simpler, non fine-tuned version that runs in 1 min. The input.txt
file contains most of J. Cole's published lyrics (which was originally parsed from the internet), and is used as a default input.

**DISCLAIMER: MAY HAVE MISSING OR OUTDATED PARTS**
