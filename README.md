# Script_Generator

Two small scripts that will quickly create bash/python scripts (with the filenames
that were specified) that are blank except for the first '#!....' line.

Then, after the script is created, nano will open it and have the cursor set at the
bottom of the script, ready for you to start typing.

Both scripts also have the --chmod option which will, at the end, chmod +x the script
after you exit nano.

INSTALL:
	copy both newpy and newsh files into your bin directory

USAGE:
	newpy/newsh [FILENAME]

	use --help option for more information
