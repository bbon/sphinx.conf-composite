# sphinx.conf-composite

## Summary

Config helps you easy and flexibly manage sphinx-engine settings for many servers.

## Install

Put the sphinx.conf (written in Perl) and sphinx.d (with *.inc files, symlinks possible) into any place, e.g.

    /home/myconfs/sphinx.conf
    /home/myconfs/sphinx.d/file1.inc
    /home/myconfs/sphinx.d/file2.inc
    /home/myconfs/sphinx.d/file3.inc
    ...

and:

```bash
cd /etc/sphinxsearch
ln -s /home/myconfs/sphinx.conf sphinx.conf
```

Enjoy!
