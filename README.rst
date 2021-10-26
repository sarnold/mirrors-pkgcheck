pkgcheck mirror
===============

Mirror of ``pkgcheck`` package for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For pkgcheck: see https://github.com/pkgcore/pkgcheck


Using pkgcheck with pre-commit
------------------------------

Add this to your ``.pre-commit-config.yaml``:

.. code-block:: yaml

    -   repo: https://github.com/pre-commit/mirrors-pkgcheck
        rev: ''  # Use the sha / tag you want to point at
        hooks:
        -   id: pkgcheck
