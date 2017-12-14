=============
ckanext-sdgdata - SDG Data Hub extension
=============

This is an extension for CKAN that provides specific customizations for the SDG Data Hub project.
   
Other extensions that are used in the SDG Data Hub configuration include: ckanext-showcase

------------
Requirements
------------

Developed against CKAN 2.5.7.

------------
Installation
------------

.. Add any additional install steps to the list below.
   For example installing any non-Python dependencies or adding any required
   config settings.

To install ckanext-sdgdata:

1. Activate your CKAN virtual environment, for example::

     . /usr/lib/ckan/default/bin/activate

2. Install the ckanext-sdgdata Python package into your virtual environment::

     cd ckanext-sdgdata
     python setup.py install

3. Add ``sdgdata`` to the ``ckan.plugins`` setting in your CKAN
   config file (by default the config file is located at
   ``/etc/ckan/default/default.ini``).

4. Restart CKAN. For example if you've deployed CKAN with Apache on Ubuntu::

     sudo service apache2 reload

------------------------
Development Installation
------------------------

To install ckanext-sdgdata for development, activate your CKAN virtualenv and
do::

    git clone https://github.com//ckanext-sdgdata.git
    cd ckanext-sdgdata
    python setup.py develop
    pip install -r dev-requirements.txt
