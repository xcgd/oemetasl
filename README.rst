### README ###


###  Oemetaslfor Odoo/OpenERP ###


This module handles methods and MetaClass to modify OpenERP base methods.
For Exemple, we override copy method to restrict the copy in Odoo/OpenERP.
But you can implement the method you need.



How to
======
::

    # In an Openerp Module:
    from oemetasl import OEMetaSL


    class oetest(osv.Model):
        __metaclass__ = OEMetaSL

    # Functions defined in OEMetaSL will be automatically added if they are not
    # implemented in the osv.Model class

