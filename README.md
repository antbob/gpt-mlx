## Building a GPT (Apple MLX version)

Companion notebook to the [Let's build GPT: from scratch, in code, spelled out](https://www.youtube.com/watch?v=kCc8FmEb1nY) video.

[The original version of the notebook](https://colab.research.google.com/drive/1JMLa53HDuA-i7ZBmqV7ZnA3c_fvtXnx-?usp=sharing) is using PyTorch. While Apple MLX is fairly similar API wise, it has some fundamental differences with PyTorch. The idea for this port was to stay as close to the original version as possible while keeping MLX specifics and differences to a minimum so it is easy to follow along and experiment on a Mac when watching the video.

This allows the final, larger model from the video to be trained on M-series Mac in reasonable time e.g. just under an hour on a M4 Pro Mac mini.