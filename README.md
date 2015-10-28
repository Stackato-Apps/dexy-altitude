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

To push to a HPE Helion Stackato PaaS:

    stackato push -n

[1]: http://www.dexy.it/
[2]: http://html5templates.com
[3]: https://github.com/ananelson/dexy-templates

