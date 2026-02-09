# Documentation of the Sentio Prober control

This is a private package.

## Instructions for building the documentation

The documentation needs to be build with MkDocs. The "material" theme is required to build the documentation.

```py -m pip install mkdocs mkdocstrings[python] mkdocs-material```

If you have done this you can create a local server to host the documentation:

 ```py -m mkdocs serve```

To view the documentation open a browser and input "http://localhost:8000/" in the address line. To build the html files for deployment execute the following command: 
 
 ```py -m mkdocs build```

The page will be put into the "site" folder.
