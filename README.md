# DD-IX Route Server Deployment

This deployment configures the route servers of the DD-IX peering lan.

## Important Files

- [/etc/bird.confl](templates/bird/bird.conf.j2) - bird configuration
- [/etc/ifstate/config.yml](templates/ifstate/config.yml.j2) - network configuration
- [/etc/nftables.peering.nft](templates/nftables/nftables.nft.j2) - firewall rules for the peering lan
