# List of Proxy URI scheme

| Scheme       | Specification   | Description      |
| ------------ | --------------- | ---------------- |
| `http`       | [CURLOPT_PROXY] | HTTP             |
| `https`      | [CURLOPT_PROXY] | HTTPS            |
| `socks`      | [CURLOPT_PROXY] | SOCKS            |
| `socks4`     | [CURLOPT_PROXY] | SOCKSv4          |
| `socks5`     | [CURLOPT_PROXY] | SOCKSv5          |
| `socks5-tls` | ?               | SOCKSv5 over TLS |
| `ss`         | [SIP002]        | Shadowsocks      |
| `ssr`        | [ShadowsocksR]  | ShadowsocksR     |
| `trojan`     | [Trojan]        | Trojan           |
| `vmess`      | [v2rayN]        | VMess            |
| `vmess1`     | [v2ray#1569]    | VMess            |
| `vmess`      | [v2fly#2638]    | VMess            |
| `vmess`      | [Xray#716]      | VMess            |
| `vless`      | [Xray#716]      | VLESS            |
| `tuic`       | [DAE#182]       | TUIC             |
| `hysteria`   | [Hysteria]      | Hysteria 1       |
| `hysteria2`  | [Hysteria2]     | Hysteria 2       |
| `juicity`    | [Juicity]       | Juicity          |

[CURLOPT_PROXY]: https://curl.se/libcurl/c/CURLOPT_PROXY.html
[SIP002]: https://shadowsocks.org/doc/sip002.html
[ShadowsocksR]: https://github.com/shadowsocksr-backup/shadowsocks-rss/wiki/SSR-QRcode-scheme
[Trojan]: https://azadzadeh.github.io/trojan-go/en/developer/url/
[v2rayN]: https://github.com/2dust/v2rayN/wiki/分享链接格式说明(ver-2)
[v2ray#1569]: https://github.com/v2ray/v2ray-core/issues/1569
[v2fly#2638]: https://github.com/v2fly/v2ray-core/discussions/2638
[Xray#716]: https://github.com/XTLS/Xray-core/discussions/716
[DAE#182]: https://github.com/daeuniverse/dae/discussions/182
[Hysteria]: https://v1.hysteria.network/docs/uri-scheme/
[Hysteria2]: https://v2.hysteria.network/docs/developers/URI-Scheme/
[Juicity]: https://github.com/juicity/juicity
