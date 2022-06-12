# Neural-Algorithm-for-Artistic-Style

Source: [A Neural Algorithm of Artistic Style](https://arxiv.org/pdf/1508.06576.pdf)
</br> Authors: Leon A. Gatys, Alexander S. Ecker, Matthias Bethge.

The pytorch implementation of the classic Neural Style transfer paper(provided in the above link). The paper aims at taking a reference image and transfering it's artistic style to target image. This is achieved by defining a optimization on pixels of the image with the objective containing content and style similarity. The content and style similarity are defined with the help of the representation obtained by a pre-trained network. Further details are available in the notebook.

## Results

## Requirements
* Python 3.6
* PyTorch <= 0.4
* Matplotlib
