svg2png
=======

Convert SVG files to PNG images. This tool leverages the great work of others to easily convert SVG files into PNG images using a docker container. Mount the folder containing your SVG file as `/svg` and then provide the name of the SVG file. For example:

    docker run --rm -v `pwd`:/svg burke/svg2png filename.svg`

For convenience, a `svg2png` script is provided to run the above docker command for you. Usage:

    svg2png filename.svg

See [svg2png-cli](https://www.npmjs.com/package/svg2png-cli) for command line options (e.g., `-w` to set width or `-s` to scale image).
