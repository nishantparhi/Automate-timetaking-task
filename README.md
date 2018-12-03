# Route VPN using Ansible


This ansible roles help to Route VPN using ansoble roles.

Working:
1) Install iptables-persistent
2) Then it configures port-forwarding
3) Gets the iptable rules
4) If the rule is absent then it sets it up

To use this role, open up a terminal and type
`ansible-playbook mark1.yml -K` to run it.

#### Proof: https://asciinema.org/a/k2Y9tXaLxUElBcC8loGZRIoYE

As you see in the proof there are 2 diffrent IP(Internet Protocol) addresses in the case, and 2 different speed before and after the VPN(Virtual Private Network) gets connected.

****This example serves to automate a time taking task.**


