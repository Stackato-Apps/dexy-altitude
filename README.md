Dexy Static Website
===================

A static website generated and served by [Dexy][1] using the altitude template
from [HTML5 Templates][2]. Excerpted from the [dexy-templates][3] repository. 


Running locally
---------------

Requires Python 2.7. Install [dexy][1] from source or using 'pip'/'pypm'.

After you generate the site by running 'dexy' in the base directory, you can
preview your site by running 'dexy serve' which will launch a simple web server
built into Python.  For more information run 'dexy help -on serve'.

Pushing to Stackato
-------------------

To push to a Stackato PaaS:

  stackato push -n

All the configuration necessary is in the stackato.yml file. On Stackato 3.x
systems, the 'framework' key trigger the Legacy Buildpack (2.10.x
compatibility). If you prefer to use the new Python buildpack, override this
with the --buildpack option:

  stackato push --buildpack https://github.com/ActiveState/stackato-buildpack-python.git


[1]: http://www.dexy.it/
[2]: http://html5templates.com
[3]: https://github.com/ananelson/dexy-templates

