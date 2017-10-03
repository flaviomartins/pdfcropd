# pdfcropd

Runs on the background to open newly downloaded PDFs automatically.
It generates a version of the PDF (e.g., double column scientific paper) with the margins cropped suitable for printing.
Your eyes will thank you for the larger font size.

### Usage

```
usage: pdfcropd [-h] [-d D [D ...]] [--margins MARGINS]

optional arguments:
  -h, --help         show this help message and exit
  -d D [D ...]       watch directories
  --margins MARGINS
```

### Installation

#### Dependencies

    $ sudo apt-get install python-pyinotify
    
    Note: pdfcrop needs to be installed (e.g., TeXLive LaTeX distribution)
    
#### User installation

    $ curl https://raw.githubusercontent.com/flaviomartins/pdfcropd/master/pdfcropd > ~/bin/pdfcropd
    $ chmod +x ~/bin/pdfcropd
    $ pdfcropd

Note: You need `~/bin` in your `$PATH` for this to work.

## How to use it?

1. Run pdfcropd

2. Download a PDF

3. Your cropped PDF opens automatically

## License

BSD-3-Clause