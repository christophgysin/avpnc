# Aviatrix VPN client

A python implementation of the [Aviatrix VPN client](https://docs.aviatrix.com/Downloads/samlclient.html)

The VPN client opens a webbrowser to authenticate with SAML and create a
one-time password, which is then used to create a connection with openvpn.

# Requirements

- sudo
- openvpn

You also need a webbrowser that supports javascript.

# Usage

    $ ./avpnc profile.ovpn
