#placeholder.sh

Very thin command-line wrapper for [placehold.it](http://placehold.it). Accepts 3 arguments:

- Width
- Height
- Text (optional)

## Usage

```
placeholder.sh 300 200
```

This will create a file named [300x200.jpeg](http://placehold.it/300x200.jpeg) in your current directory.

If you specify the third argument, the image will have the text written on it and the file will be named after the argument, for example:

```
placeholder.sh 300 200 "Sample Text"
```

Will create a file called [Sample Text.jpeg](http://placehold.it/300x200.jpeg&text=Sample+Text) in your current directory.

## Installation

The project comes with a Makefile which copies ```placeholder.sh``` file to ```/usr/local/bin```.

Execute this:

```
make
```
