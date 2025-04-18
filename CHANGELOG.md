# 2.0.2
2025-04-17
**UPDATES**
- Removed: GCC compilation from source. Now it installs GCC form OS package manager (dnf, apt, pacman...).
| Changed: Hugepages calculation. Newer methods help get hugepages to optimal performance.
| Changed: We're compiling VeriConomy's veriumMiner 1.6, it's the only miner allowed in the network
+ Added: Destination folder is presented with a default and create if it doesn't exist.
= Pending: new 'Runme' generation, add wallet mining instructions with correct parameters for solominers

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
