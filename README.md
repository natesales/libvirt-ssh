# libvirt-ssh

[![Go Report](https://goreportcard.com/badge/github.com/natesales/libvirt-sshd?style=for-the-badge)](https://goreportcard.com/report/github.com/natesales/libvirt-sshd) 
[![License](https://img.shields.io/github/license/natesales/libvirt-sshd?style=for-the-badge)](hhttps://github.com/natesales/libvirt-sshd/blob/main/LICENSE) 
[![Release](https://img.shields.io/github/v/release/natesales/libvirt-sshd?style=for-the-badge)](https://github.com/natesales/libvirt-sshd/releases) 

SSH into a libvirt qemu VM serial console

### Installation

libvirt-sshd is available as a debian package and x86 binary in the releases section of this repo. It's also available as an APT package by adding `deb [trusted=yes] https://apt.fury.io/natesales/ /` to your /etc/apt/source.list file.

### Usage

```
Usage for libvirt-sshd (dev) https://github.com/natesales/libvirt-sshd:
  -l string
        Listen <host:port> (default ":2222")
  -p string
        Path to virsh binary (default "virhs")
  -v    Enable verbose logging
```
