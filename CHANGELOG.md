# 2.0.1
2023-04-27
**UPDATES**
| Changed: Warning text for obsolete GCC8 in systems that run GCC9 already
| Changed: We're downloading/compiling VeriConomy's veriumMiner: 1.6 compiling, 1.5 downlaoding
+ Added: Folders will get chown'd to the user in sudo instead of being property of root.


# 2.0.0

**UPDATES**
- **Addon** - centos7 support added
- **Change** - readme updated
- **Improvement** - adding additional option, --api-bind, when building RunMe
- **Improvement** - adding version output when running the script and passing -v, --version, or version

**BUGFIX**
- **HugePages** - multiple run's of the vMinstaller_linux script adds a new line to /etc/sysctl.conf
