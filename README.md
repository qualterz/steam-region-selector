# Steam Region Selector

A desktop Windows application to select server regions in Steam games.

## Use-cases

- Play only on Australian servers.
- Don't play with Russians.
- Feel what is ping 100+ like.
- Allow only the best servers.

## Underhood

- It adds firewall rules leveraging `netsh` command to block traffic from game servers.
- It uses Steam Web API to get game servers addresses and games information.
