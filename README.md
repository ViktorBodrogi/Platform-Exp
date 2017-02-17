# Platform

A highly customized [DokuWiki](https://github.com/splitbrain/dokuwiki) with many additional addons, plugins and templates.
It contains mostly submodules, and build, test, deploy scripts and environment.
Submodules are managed with `.gitmodules` files.

To init submodules:

    git submodule add https://github.com/ViktorBodrogi/dokuwiki
    git subtree add --prefix=dokuwiki/lib/tpl/bootstrap3 --squash https://github.com/LotarProject/dokuwiki-template-bootstrap3 master
