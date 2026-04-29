# m2e-code-quality
Eclipse m2e-code-quality P2 Update Site - adopted to be used within Oomph setup projects.

## Info
This is a fork of the original m2e-code-quality update site.
The content of the `p2site` folder is an original copy of the repo [m2e-code-quality-p2-site](https://github.com/m2e-code-quality/m2e-code-quality-p2-site).

## Note
There was modification required for each particular `m2e-code-quality\*\content.jar` file.<br>
The original `content.jar/content.xml` files contain references to the update sites of the according code style checker implementations.<br>
=> These referenced update sites will break Oomph installations of deviating Eclipse platform versions,
since it will lead to interfering or conflicting P2 repo lookups of P2 directory runs of Oomph installer.

## Update Site
This repos [p2site](../../tree/main/p2site) content is cleaned up to not contain any other update site reference anymore.
This adapted content is being provided via Update site URL https://p2site.github.io/p2.m2e-code-quality/.
