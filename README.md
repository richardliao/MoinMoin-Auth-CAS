MoinMoin-Auth-CAS
=================

This auth module adds the ability to authenticate MoinMoin 1.9.x users using a Jasig CAS server.

For MoinMoin 1.8.x, see::

    http://moinmo.in/RichardLiao/CasAuthentication

Installation
------------

Put cas.py into the MoinMoin configuration directory (or any other directory in python path).

Add it to the wikiconfig.py configuration file:

    class Config(...):
        import cas
        auth = [cas.CASAuth("https://sso.example.com/cas")]



