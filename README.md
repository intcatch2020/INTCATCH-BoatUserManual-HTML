# INTCATCH-BoatUserManual-HTML

To build the manual, we use the Sphinx documentation generator: http://www.sphinx-doc.org/en/stable/contents.html.

#. Follow the directions to install Sphinx.
#. Clone the repo.
#. Temporarily move conf.py and index.rst to another folder.
#. Run sphinx-quickstart in the repo directory, use all default answers.
#. Move the original conf.py and index.rst that you copied back into the repo folder.
#. Obtain a copy of the "\_static" folder, which is not included in this repository, and move it into the repo folder.
#. run "make clean" and then "make html" to rebuild the documents.
#. Inspect the built HTML in the build folder.