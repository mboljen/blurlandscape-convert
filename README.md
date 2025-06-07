# blurlandscape-convert

Add blur padding to convert portrait images to landscape


## Synopsis

```console
$ blurlandscape-convert [OPTION]...
```


## Description

This script adds a blurred padding to convert portrait images to landscape.


## Options

+ `-m`, `--method` _pixel_

  Set virtual pixel method:

  - `dither` (default)
  - `mirror`
  - `random`

+ `-d`, `--directory` _value_

  Set default output directory (default: `none`)

+ `-n`, `--name` _value_

  Set default output filename suffix (default: `none`)

+ `-y`, `--yes`

  Overwrite existing files

+ `-h`

  Show this help message


## Exit codes

+ `0` All operations successful


## Installation

Clone the remote repository and change into the local repository:

```console
$ git clone https://github.com/mboljen/blurlandscape-convert
$ cd blurlandscape-convert
```

Use the following command to install this software:

```console
$ make
$ make install
```

The default `PREFIX` is set to `/usr/local`.  In order to successfully complete the installation, you need to have write permissions for the installation location.


## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.


## License

[MIT](https://choosealicense.com/licenses/mit/)
