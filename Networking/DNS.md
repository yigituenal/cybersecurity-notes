# DNS (Domain Name System)

## What is DNS?

DNS (Domain Name System) translates domain names into IP addresses.

Example:

google.com → 142.250.x.x

Without DNS, users would have to remember IP addresses instead of domain names.

---

## Why is DNS Important?

- Makes websites easy to access.
- Converts domain names into IP addresses.
- Saves users from memorizing IP addresses.

---

## Default Ports

| Protocol | Port | Usage |
|----------|------|-------|
| UDP | 53 | Standard DNS queries |
| TCP | 53 | Zone transfers and large responses |

---

## How DNS Works

1. User enters a domain name.
2. The computer sends a DNS query.
3. The DNS server searches for the IP address.
4. The DNS server returns the IP address.
5. The browser connects to the web server.

---

## Example

User:

```
www.google.com
```

DNS Response:

```
142.250.x.x
```

Browser connects to:

```
142.250.x.x
```

---

## Common DNS Record Types

| Record | Purpose |
|--------|---------|
| A | Maps a domain to an IPv4 address |
| AAAA | Maps a domain to an IPv6 address |
| CNAME | Alias for another domain |
| MX | Mail server record |
| NS | Name server record |
| TXT | Stores text information (verification, SPF, etc.) |

---

## Security Notes

- DNS is a common target for attackers.
- DNS spoofing can redirect users to fake websites.
- DNS tunneling can be used to hide malicious traffic.

---

## Key Points

- DNS = Domain Name System
- Converts domain names to IP addresses
- Default Port: UDP 53
- TCP 53 is used for zone transfers and large responses
- Without DNS, users would need to remember IP addresses

---

## Example Commands

### Windows

```cmd
nslookup google.com
```

### Linux

```bash
dig google.com

# or

nslookup google.com
```

---

## TryHackMe Notes

- Learned how DNS resolves domain names.
- Practiced using `nslookup`.
- Understood why DNS is one of the core Internet services.

---

## Author

Yiğit Ünal

Cybersecurity Learning Journey
