# edid-sh

A small utility for reading and writing EDID data via i2c.

# Usage

Read EDID form an i2c bus:

`./edid-sh -d -b BUS read_edid`

Write file with EDID data to an i2c bus:

`./edid-sh -d -b BUS write_edid FILE`

The file is comprised of characters '0-9a-fA-F', newlines and whitespace are removed.
