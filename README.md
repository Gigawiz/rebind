# Rebind

Rebind is a tool that implements the multiple A record DNS rebinding attack. Although this tool was originally written to target home routers, it can be used to target any public (non RFC1918) IP address.

Rebind provides an external attacker access to a target router's internal Web interface. This tool works on routers that implement the weak end system model in their IP stack, have specifically configured firewall rules, and who bind their Web service to the router's WAN interface. Note that remote administration does not need to be enabled for this attack to work. All that is required is that a user inside the target network surf to a Web site that is controlled, or has been compromised, by the attacker. See docs/whitepaper.pdf for a detailed description of the attack.

--------------------------------------------------------------------------------------------------------------------------------
Automatically exported from code.google.com/p/rebind

This is simply a copy of the code from the official repo located at https://code.google.com/p/rebind/ to prevent it from being lost with google's removal of the google code service.

Nothing has been modified from that page, and this project will return to its creator if requested.
