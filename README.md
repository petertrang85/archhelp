# archhelp


tftp server
dnsmasq
/etc/dnsmasq.conf
enable-tftp
tftp-root=/srv/tftp
tftp-secure

systemctl enable/start

pacman downgrading

pacman -U /var/cache/pacman/pkg/

backup pkg

pacman -Qqe > pkglist.txt

install from backup

pacman -S - < pkglist.txt

