# INTCATCH-BoatUserManual-HTML

To build the manual, we use the Sphinx documentation generator: http://www.sphinx-doc.org/en/stable/contents.html.

1. Follow the directions to install Sphinx.
1. Clone the repo.
1. Temporarily move conf.py and index.rst to another folder.
1. Run sphinx-quickstart in the repo directory, use all default answers.
1. Move the original conf.py and index.rst that you copied back into the repo folder.
1. Obtain a copy of the "\_static" folder, which is not included in this repository, and move it into the repo folder.
1. run "make clean" and then "make html" to rebuild the documents.
1. Inspect the built HTML in the build folder.