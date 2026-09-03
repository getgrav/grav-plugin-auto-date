# v1.0.4
## 09/03/2026

1. [](#bugfix)
    * Installing or updating on Grav 2 no longer fails on a dependency that cannot exist there. The plugin still asked for the Grav 1.7 admin plugin, so `bin/gpm install` stopped with a PHP error, and the Plugins page reported a failed update. On the testing release channel it could go further and install the old admin plugin alongside Admin 2 [getgrav/grav-premium-issues#618](https://github.com/getgrav/grav-premium-issues/issues/618)

# v1.0.3
## 05/01/2026

1. [](#improved)
    * Added 1.7|2.0 compatibility flags

# v1.0.2
##  05/29/2016

1. [](#bugfix)
    * Fixed links in blueprint

# v1.0.1
##  09/30/2016

1. [](#improved)
    * Fixed icon

# v1.0.0
##  09/30/2016

1. [](#new)
    * Initial Release
