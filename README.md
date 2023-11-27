# Odoo Attrs replacer

### As Odoo changed the attrs to (no more attrs) in v17, I create this little script to help you replace all attrs in your XML files with corresponding attributes in the XML directly.

### How to use:

Simply install with pip beautifulsoup4 (or install -r requirements.txt)

Then launch the python script (python3 replace_attrs.py).

If will ask you the root directory to check for XML files. You can give a full project path.

If nothing is given, we will use "." (current directory).

The script will ask you, for each file, if you want to replace all attrs= with related attrs in the tag (for all tags at once).

Unless you chose in the begining 'y' for auto-replace (don't ask for each file)
