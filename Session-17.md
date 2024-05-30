# Package Management-
- Package Management is the method of installing and maintaining the package/software.
- Package management in Linux refers to the process of installing, updating, configuring, and removing software packages
- In Linux, software is available in the form of packages (packages are the collection of programs).
- And installing the packages means simply extracting the files from the archive and put it on the system.

# Repositories-
- Centralized location where software packages are stored and maintain that are made available for installation

# Dependencies-
- Some package requires shared library, or another package, called dependency.
- Dependency refers to a software component or library that another piece of software relies on in order to function correctly.

## Low-level Utilities-
- Low-level tool manages package files installation, update and uninstallation of package without their dependencies.
## High-level Utilities-
- high-level tool can install the package with their dependencies. 

| Linux Family | Low-level Tool | High-level Tool |
|--------------|----------------|-----------------|
| Red Hat      | rpm            | yum             |
| Debian       | dpkg           | apt-get         |

* Red Hat Based OS- Ubantu, Linux, Kali-Linux
* Debian Based OS- Fedora, CentOS, Rhel
