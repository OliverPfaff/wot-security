# WoT Security and Privacy
Github repository of the W3C Web of Things Security and Privacy Task Force to manage cross-cutting security and privacy considerations.

* [References](wot-security-references.md):
  List of both normative and informative source material.
* [WoT Security and Privacy Guidelines](index.html):
  A unified set of informative recommendations for security and privacy in a Web of Things system.
  Includes a threat model. This is work in progress.
    * The latest stable version can be found [here](https://rawgit.com/w3c/wot-security/master/index.html).
    * A "rendered" form of the latest stable version can be found [here](https://w3c.github.io/wot-security/).
      This compiles out the complex JavaScript implementing the ReSpec system,
      making it faster to view and more compatible with a wider range of browsers.
      However, there may a small delay before it gets updated when the master changes.
    * A working "unstable" version is also available [here](https://rawgit.com/w3c/wot-security/working/index.html)
      but has not yet been validated and may have errors.
      It is also not "compiled" and so may be slow to display (or display with issues) on some broswers.
* You may also be interested in the 
  [WoT Security Best Practices document](https://github.com/w3c/wot-security-best-practices).
  The Guidelines describe general principles and establish foundational definitions.
  The Best Practices document provides specific recommendatons for building and testing
  systems with current technology.

If you wish to make a contribution,
please be aware that since the master is being linked from other WoT documents
we want to keep it as stable as possible and are staging commits through
the "working" branch.
Issues and pull requests should be made to that branch, not master.
Conversely, if you want to see the latest (unstable) version,
checkout the "working" branch.
Issues should be filed against the working branch and will be closed when
updates are released to the master branch.

Older material has been moved to an `archive` subdirectory.
This material has mostly already been incorporated into the 
main guidelines or best-practices documents.
