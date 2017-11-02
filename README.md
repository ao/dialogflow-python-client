DialogFlow: Python SDK for `DialogFlow <http://dialogflow.com>`_
=========================

[<img src="https://badge.fury.io/py/apiai.svg">](http://badge.fury.io/py/apiai) [<img src="https://travis-ci.org/api-ai/api-ai-python.svg">](https://travis-ci.org/api-ai/api-ai-python)

Overview
--------

The DialogFlow Python SDK makes it easy to integrate speech recognition with DialogFlow natural language processing DialogFlow allows using voice commands and integration with dialog scenarios defined for a particular agent in DialogFlow.

Prerequsites
--------

Create a `DialogFlow account <http://dialogflow.com>`_.


Running examples
--------

1. Find examples from 'examples' path.
2. Insert API key.

.. code-block:: python

    >>> CLIENT_ACCESS_TOKEN = '<YOUR_CLIENT_ACCESS_TOKEN>'
    ...

Features
--------

- Speech Recognition.
- Voice Activity Detection.
- Natural Language Processing.

Installation
------------

To install DialogFlow/api.ai, simply:

.. code-block:: bash

    $ pip install apiai

or install it from repo:

.. code-block:: bash

    $ pip install https://github.com/dialogflow/dialogflow-python-client.git

You might run into problems because some dependencies in your python environment are missing. You need to install numpy (which is available in almost all package managers). For running the examples you also need python audio.

In ubuntu the following will do the job:

.. code-block:: bash

    $ apt-get install python-pyaudio python-numpy
    $ pip install apiai

Documentation
-------------

Documentation is available at http://dialogflow.com.

## How to make contributions?
Please read and follow the steps in the [CONTRIBUTING.md](CONTRIBUTING.md).

## License
See [LICENSE](LICENSE).

## Terms
Your use of this sample is subject to, and by using or downloading the sample files you agree to comply with, the [Google APIs Terms of Service](https://developers.google.com/terms/).

This is not an official Google product.
