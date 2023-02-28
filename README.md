# is-ip-valid

Check if a string is a valid IP address

## Install

```sh
npm install is-ip
```

## API

### isIP(string)

Check if `string` is a valid IP (IPv4 or IPv6).

### isIPv6(string)

Check if `string` is valid IPv6.

### isIPv4(string)

Check if `string` is valid IPv4.

### ipVersion(string)

Returns `IPv6` if `string` is valid IPv6 or `IPv4` if `string` is valid IPv4, or `undefined` if `string` is neither.

## Usage

```js
import { isIP, isIPv4, isIPv6, getIPversion } from "is-ip-valid";

isIP("192.168.0.1");
> true

isIPv4("192.168.0.1");
> true

isIPv6("1:2:3:4:5:6:7:8");
> true

getIPVersion("192.168.0.1");
> IPv4
```
