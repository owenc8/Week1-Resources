# Week1-Resources

Welcome to week 1 of Generative AI and Computational Creativity!

## Running python notebooks

### Option 1

If you are familiar with github, you can clone this repo and run the notebook in your IDE or tool of choice.

### Option 2

All of the provided notebooks will contain a link like this: <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>

Following the link will open the notebook in Google Colaboratory. Note, while this doesn't require any setup beyond having a google account, you will have to manually upload and download assets in the "files" tab on the left side of the page.

## Working with assets

In this repo you will find helpful resources and tutorials for working with your preferred modality. To start with, we're introducing `PIL` and `pretty-midi` for images and symbolic music respectively. If you're comfortable with python libraries, here is a list of suggestions for you to potentially check out:


- 2D Images:        [PIL (Pillow)](https://pillow.readthedocs.io/en/stable/index.html)
- Symbolic Music:   [pretty_midi](https://craffel.github.io/pretty-midi/)
- Audio:            [librosa](https://librosa.org/doc/latest/index.html)
- Video:            [MoviePy](https://zulko.github.io/moviepy/)
- Text:             [NLTK](https://www.nltk.org/)
- 3D Mesh:          [PyMesh](https://pymesh.readthedocs.io/en/latest/)
- Compute Shaders:  [Python Arcade](https://api.arcade.academy/en/stable/tutorials/compute_shader/index.html)

Some more general multi-media libraries

- [pygame](https://www.pygame.org/wiki/about): More established than aformentioned Python Arcade but no custom shaders
- [OpenCV](https://opencv.org/): Useful for images, video, etc. May be overkill in simple cases
- [torchvision](https://pytorch.org/vision/stable/index.html), [torchaudio](https://pytorch.org/audio/stable/index.html): Mostly for integrating with PyTorch models but may contain some useful GPU-accelerated functionality