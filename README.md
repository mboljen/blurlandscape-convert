# NAME

blurlandscape-convert - Add blur padding to convert portrait images to landscape.


# SYNOPSIS

**blurlandscape-convert** [ **-v** _pixel_ ] [ **-o** _dir_ ] [ **-s** _string_ ] [ **-y** ] [ **-h** ]


# DESCRIPTION

**blurlandscape-convert** adds a blurred padding to convert portrait images to landscape.


# OPTIONS

**-v** _pixel_
: Set virtual pixel method.

  - `dither` (default)
  - `mirror`
  - `random`

**-o** _dir_
: Set output directory and reset suffix.

**-s** _string_
: Set suffix for output files.

**-y**
: overwrite existing image files.

**-h**
: show this help message.


# INSTALLATION

Clone the remote repository and change into the local repository:

```bash
$ git clone https://github.com/mboljen/blurlandscape-convert
$ cd blurlandscape-convert
```

Use the following command to install this software:

```bash
$ make
$ make install
```

The default `PREFIX` is set to `/usr/local`.  In order to successfully complete the installation, you need to have write permissions for the installation location.


# EXIT CODES

+ `0` All operations successful


# CONTRIBUTION

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Submit bug reports online at: <https://github.com/mboljen/blurlandscape-convert/issues>

Please make sure to update tests as appropriate.


# SEE ALSO

Full documentation and sources at: <https://github.com/mboljen/blurlandscape-convert>


# LICENSE

[MIT](https://choosealicense.com/licenses/mit/)






