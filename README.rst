How to
======
::

    #In an Openerp Module:
    from oemetasl import OEMetaSL


    class oetest(osv.Model):
        __metaclass__ = OEMetaSL

    #Functions defined in OEMetaSL will be automatically added if they are not
    #implemented in the osv.Model class

