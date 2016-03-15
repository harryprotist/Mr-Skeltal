Mr. Skeltal
---------------

A skeleton file tool that's high in calcium.  Keep a directory of skeleton
files and use the `skeltal` command to create a new file of any type and
even do some preprocessing on the file.

## Usage

`skeltal [-t type] [--spooky|-s] filename[.type]`

The file extension `.type` will be used in the case that you didn't provide
a `-t type` option. Use the spooky flag for spookier output.

This command will look for a file named `type.skel` in your `$SKELTAL_DIR`,
then copy it to `filename`.

## Setup

Add a line to your `.bashrc` (or whatever shell you use), with `export
SKELTAL_DIR="<directory of your skel directory>"`. Otherwise skeltal will
just look in the current directory for skel files.

Either add the directory containing the script `skeltal` to your `$PATH`
or move `skeltal` to a directory in your `$PATH`.
