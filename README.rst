=========
Pinocchio
=========

This is a clone of the `Pinocchio project <http://darcs.idyll.org/~t/projects/pinocchio/doc>`_, placed here because currently ``zc.buildout`` fails when trying to use the original url/`pypi submission <http://pypi.python.org/pypi/pinocchio/0.2>`_.

The following is a ``buildout.cfg`` example to help you use this version of ``pinocchio`` in your project::

    [buildout]
    ...
    versions = versions
    find-links =
        https://github.com/unpluggd/pinocchio/tarball/0.2#egg=pinocchio-0.2
    eggs = 
        pinocchio

    [versions]
    pinocchio=0.2

    ...
