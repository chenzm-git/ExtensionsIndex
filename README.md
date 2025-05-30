# Slicer Extensions Index

## Overview

Think of the ExtensionsIndex as a repository containing a list of [extension description file][]s
(*.s4ext) used by the Slicer extensions build system to build, test, package and upload
extensions on an [extensions server][].

Once uploaded on an `extensions server`, within Slicer, extensions can be installed using the [extensions manager][].

A website referred to as the [extensions catalog][] provides Slicer users with a convenient way of finding and downloading extensions previously uploaded on the `extensions server`. The `extensions manager` in Slicer makes the catalog available directly in the application and allows extensions to be installed, updated, or uninstalled by a few clicks.

The following diagram depicts how `extensions catalog`, `extensions server`, [CDash][] and the
slicer factory interact.

<img width="80%" src="https://www.slicer.org/slicerWiki/images/a/ab/Extensions-Index-to-Catalog-cycle.png"/>

## Extension tiers

We accept extensions to 3D Slicer at various quality and maturity levels. To make it clear for users what they can expect from a particular extension, 3D Slicer maintainers assign each extension to a "tier":

- Tier 1: Experimental extensions.
- Tier 3: Community-supported extensions.
- Tier 5: Critically important extensions, supported by Slicer core developers.

Extension tier 2 and 4 are reserved for future use, to allow defining intermediate steps between the initially defined tiers without reclassifying every extension.

## Build instructions

See https://slicer.readthedocs.io/en/latest/developer_guide/extensions.html#extensions-build-system

## Contact

Questions regarding this project should be posted on 3D Slicer forum: https://discourse.slicer.org

## License

* [3D Slicer license](https://github.com/Slicer/Slicer/blob/main/License.txt)

[CDash]: https://slicer.cdash.org/index.php?project=SlicerPreview
[extensions manager]: https://slicer.readthedocs.io/en/latest/user_guide/extensions_manager.html
[extension description file]: https://slicer.readthedocs.io/en/latest/developer_guide/extensions.html#extension-description-file
[extensions catalog]: https://extensions.slicer.org/catalog/All/30117/win
[extensions server]: https://slicer.readthedocs.io/en/latest/developer_guide/extensions.html#extensions-server
