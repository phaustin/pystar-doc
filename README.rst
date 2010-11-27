repository for gh-pages
+++++++++++++++++++++++

+ gh-pages branch in this repository has
  documentation for the pystar project

+ updates are done automatically using the
  gh-pages.py script developed by 
  `Fernando Perez  <http://www.mail-archive.com/numpy-discussion@scipy.org/msg28272.html>`_
  for the `datarray-doc <https://github.com/fperez/datarray-doc/blob/master/readme.rst>`_

+ to modify these pages:

  - git clone git@github.com:phaustin/pystar.git
 
  - git clone git@github.com:phaustin/pystar-doc.git

  - cd pystar/doc  and edit rst files

  - from pystar/doc run::

      python gh-pages.py version_number

    to build the html pages and copy them to pystar-doc

  - if pages look ok, push pystar-doc back to github

+ view the web pages at http://phaustin.github.com/pystar-doc



