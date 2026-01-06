In order to configure the router via CLI, use the following commands to activate configuration mode

- Router> enable
- Router# configure terminal

Once in configuration mode, you will configure the two router ports that connect to each LAN, not the switch ports.

To configure LAN1, do the following commands

- Router(config)# interface Gig0/0
- Router(config-if)# ip address 192.168.1.1 255.255.255.0
- Router(config-if)# no shutdown  (even if the port seems on, always run this)
- Router(config-if)# exit

To configure LAN2, do the following commands

- Router(config)# interface Gig0/1
- Router(config-if)# ip address 192.168.2.1 255.255.255.0
- Router(config-if)# no shutdown  (even if the port seems on, always run this)
- Router(config-if)# exit

If everything is correctly configured, ping a PC from one LAN to another in simulation mode.
You should receive a successful reply, confirming that both LANs are now connected through the router.
