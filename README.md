A custom listen attend and spell implementation.
================================
This code is a custom made speech transducer using its own attention mechanism.
However the tensor-flow default should be used for better performance.

This repository functions as an archive of my master thesis work, it is not under active development.

See also the original LAS paper by Chan et al.:
https://arxiv.org/abs/1508.01211

For an in depth discussion of the LAS-architecture including relevant background information
you could take a look at my thesis text:
https://github.com/v0lta/masterThesis/blob/master/thesis.pdf .
The figures and plots of the text are available at:
https://github.com/v0lta/masterThesis

And please consider using the tensorflow default attention code instead of this project:
The relevant part of the new Tensorflow 1.0 API are:
https://www.tensorflow.org/api_docs/python/tf/contrib/seq2seq

My code is not yet using the default code, because it became available towards the end of my thesis
project.
An implementation using the new Tensorflow API is available at:
https://github.com/vrenkens/nabu
