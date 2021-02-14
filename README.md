# Astropet

Virtual pets over the [gemini](https://gemini.circumlunar.space/) protocol. A Fork of [Community Garden](https://github.com/michael-lazar/astrobotany) which itself is a fork of [jifunks/botany](https://github.com/jifunks/botany).

## WIP

This project is a WIP current version is still 100% the Astrobotany code.

## Getting Started

(requires python 3.7+)

```bash
# Setup a fresh virtual environment
git clone git@github.com:aaadonai/astropet.git
cd astropet
python -m virtualenv venv
source venv/bin/activate

# Install astrobotany in "edit" mode
pip install -e .

# Launch the gemini server
python main.py
```

## Art

### Playscii

The project uses a forked version of the playscii ASCII art program to generate the ``.psci`` files:

https://github.com/michael-lazar/playscii

Botany's original art files were imported using the following settings:

- palette: ``240-ansi`` (generated using [this script](scripts/build_palette.py))
- charset: ``dos`` (of which 7-bit US ASCII is a subset)

While colorizing the images, I maintained a few common colors between plants:

| Color Code | Usage |
| --- | --- |
| 0 | background |
| 80 | soil |
| 133 | primary flower color |
| 199 | secondary flower color |
