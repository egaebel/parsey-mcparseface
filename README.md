First time setup
================

When first pulling this repo create a virtualenv workspace in the current directory.
After virtualenv is setup and the activate script has been run, run the pip command:

pip install -r requirements.txt

this will install all the packages necessary for Parsey McParseface.

Once these packages have been installed, clone Parsey McParseface into the src directory:

git clone https://github.com/tensorflow/models.git

Finally, patch conll2tree.py by running (from the src directory):

cp conll2tree.py models/syntaxnet/syntaxnet/conll2tree.py

Build Parsey McParseFace by following the instructions here:

https://github.com/tensorflow/models/tree/master/syntaxnet
