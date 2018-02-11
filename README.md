#  Turku AI Week 2018 Machine Learning Workshop

## Resources

TODO.

## Setup

**Note!** You can skip these if you are using [Anaconda](https://www.anaconda.com/download/).

```
# Install Python 2 or Python 3
# Setup virtual environment if you wish and activate it.

pip install -r requirements.txt

# If you are using Python 2 version:
pip install -r python2/requirements.txt

# If you are using Python 3 version:
pip install -r python3/requirements.txt

jupyter notebook
# Web browser should start automatically, open "Machine Learning Workshop Tutorial" notebook in there.
```

## Adding or Removing Dependencies

```
# Edit ./requirements.in
pip install pip-tools
pip-compile --output-file=requirements.txt requirements.in
pip install -r requirements.txt
```

```
# Edit ./python2/requirements.in
pip install pip-tools
pip-compile --output-file=python2/requirements.txt python2/requirements.in
pip install -r python2/requirements.txt
```

```
# Edit ./python3/requirements.in
pip install pip-tools
pip-compile --output-file=python3/requirements.txt python3/requirements.in
pip install -r python3/requirements.txt
```

## License

TODO.