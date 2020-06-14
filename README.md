# Cronjob for sniffer tool.

***net_sniffer*** is shell tool for control/operating net sniffer.

Developed in bash code: ***100%***.

The README is used to introduce the tool and provide instructions on
how to install the tool, any machine dependencies it may have and any
other information that should be provided before the tool is installed.

[![GitHub issues open](https://img.shields.io/github/issues/vroncevic/net_sniffer.svg)](https://github.com/vroncevic/net_sniffer/issues)
 [![GitHub contributors](https://img.shields.io/github/contributors/vroncevic/net_sniffer.svg)](https://github.com/vroncevic/net_sniffer/graphs/contributors)

<!-- START doctoc -->
**Table of Contents**

- [Installation](https://github.com/vroncevic/net_sniffer#installation)
- [Usage](https://github.com/vroncevic/net_sniffer#usage)
- [Dependencies](https://github.com/vroncevic/net_sniffer#dependencies)
- [Shell tool structure](https://github.com/vroncevic/net_sniffer#shell-tool-structure)
- [Docs](https://github.com/vroncevic/net_sniffer#docs)
- [Copyright and Licence](https://github.com/vroncevic/net_sniffer#copyright-and-licence)
<!-- END doctoc -->

### INSTALLATION

Navigate to release [page](https://github.com/vroncevic/net_sniffer/releases) download and extract release archive.

To install modules type the following:

```
tar xvzf net_sniffer-x.y.z.tar.gz
cd net_sniffer-x.y.z
cp -R ~/sh_tool/bin/   /root/scripts/net_sniffer/ver.1.0/
cp -R ~/sh_tool/conf/  /root/scripts/net_sniffer/ver.1.0/
cp -R ~/sh_tool/log/   /root/scripts/net_sniffer/ver.1.0/
```

![alt tag](https://raw.githubusercontent.com/vroncevic/net_sniffer/dev/docs/setup_tree.png)

Or You can use docker to create image/container.

### USAGE

```
# Create symlink for shell tool
ln -s /root/scripts/net_sniffer/ver.1.0/bin/net_sniffer.sh /root/bin/net_sniffer

# Setting PATH
export PATH=${PATH}:/root/bin/

# Control/operating net sniffer
net_sniffer
```

### DEPENDENCIES

This tool requires these other modules and libraries:

* None

### SHELL TOOL STRUCTURE

***net_sniffer*** is based on MOP.

Shell tool structure:
```
.
├── bin/
│   ├── net_dumper.sh
│   ├── net_ipsniffer.sh
│   └── net_params.sh
├── conf/
│   └── net_sniffer.cfg
└── log/
    └── net_sniffer.log
```

### DOCS

[![Documentation Status](https://readthedocs.org/projects/net_sniffer/badge/?version=latest)](https://net_sniffer.readthedocs.io/projects/net_sniffer/en/latest/?badge=latest)

More documentation and info at:

* https://net_sniffer.readthedocs.io/en/latest/

### COPYRIGHT AND LICENCE

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0) [![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

Copyright (C) 2018 by https://vroncevic.github.io/net_sniffer

This tool is free software; you can redistribute it and/or modify
it under the same terms as Bash itself, either Bash version 4.2.47 or,
at your option, any later version of Bash 4 you may have available.

