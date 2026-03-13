# Create new subdomain
This guide is performed in Hostinger's hPanel

## Domain -> DNS/Nameserver
### New A Nameserver
Type
```
A
```
Name
```
sub
```
*'sub' is subdomain name. example : 'sub.domain.com'*
Heading Toward
```
1.111.111
```
*'1.111.111' is server ip address*
Click add record to save
### New CNAME Nameserver
Type
```
CNAME
```
Name
```
www.sub
```
Heading Toward
```
sub.domain.com
```
Click add record to save


