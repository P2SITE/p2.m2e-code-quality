# m2e-code-quality
Eclipse m2e-code-quality Update Site

## Info
This is a fork of the original m2e-code-quality update site.

## Note
There was modification required for most of the `m2e-code-quality\*\content.jar` files.<br>
Those original content.jar/content.xml files contain a references to the update sites of the according code style checker implementations.<br>
=> This will break Oomph installations of deviating Eclipse platform versions, since it will lead to interfering or conflicting P2 repo lookups of P2 directory runs of Oomph installer.

## Update Site
This repos [p2site](../../tree/main/p2site) content is provided via update site URL https://p2site.github.io/p2.m2e-code-quality/
