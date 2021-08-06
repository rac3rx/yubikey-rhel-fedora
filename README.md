# yubikey-rhel-fedora

sudo dnf install u2f-hidraw-policy    # new and easy way

#
# OLD WAY (REF: https://gist.github.com/fntlnz/a4513162960e1e9fdb99)
#
#wget -O /etc/udev/rules.d/70-u2f.rules https://raw.githubusercontent.com/Yubico/libu2f-host/master/70-u2f.rules
#udevadm trigger
