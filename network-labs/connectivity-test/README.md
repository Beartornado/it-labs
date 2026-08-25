# Basic Network Connectivity Test

## Goal

Practice basic Windows network diagnostic commands and document the results.

## Commands

- `ipconfig`
- `ping`
- `tracert`
- `nslookup`


## Test Results

### Loopback Test

Command:

`ping 127.0.0.1`

Result:

The loopback address responded successfully with no packet loss.

#### Interpretation

A successful response confirms that TCP/IP is functioning locally on the computer.


### Default Gateway Test

Command:

`ping 192.168.0.1`

Result:

The default gateway responded successfully with no packet loss.

#### Interpretation

A successful response confirms that the computer can communicate with the router on the local network.


### DNS Resolution Test

Command:

`nslookup github.com`

Result:

The DNS lookup successfully returned IP addresses for GitHub.

#### Interpretation

The successful lookup confirms that the computer can contact a DNS server and resolve a domain name to an IP address.
