# Client-side Acceptable Format Initiative

Stage: Proposal

This initiative hopes to improve the current situation of Proxy Client based on [User-Agent] detection format.

The initiative recommended use [Accept] http request header

[Accept]: https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Accept
[User-Agent]: https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/User-Agent

## Example

Request:

```http
GET /to/path HTTP/1.1
Accept: text/clash+yaml, text/surge
```

Response:

```http
HTTP/1.1 200 OK
Content-Type: text/clash+yaml
```

## Media Type Registry

| Media Type                                    | File Format                       |
| --------------------------------------------- | --------------------------------- |
| [text/surge][surge]                           | Surge format                      |
| [text/surge-proxies][surge-proxies]           | Surge Proxy Provider format       |
| [text/surge-ruleset][surge-ruleset]           | Surge Rule Provider format        |
| [text/surge-domain-set][surge-domain-set]     | Surge Domain Set format           |
| [text/clash+yaml][clash+yaml]                 | Clash format                      |
| [text/clash-proxies+yaml][clash-proxies+yaml] | Clash Proxy Provider format       |
| [text/clash-ruleset+yaml][clash-ruleset+yaml] | Clash Rule Provider format (YAML) |
| [text/clash-ruleset][clash-ruleset]           | Clash Rule Provider format (Text) |
| [text/sip008+json][sip008+json]               | Shadowsocks SIP008 format         |
| [text/uri-proxies][uri-proxies]               | URI Proxies format                |

[surge]: media-types/surge.md
[surge-proxies]: media-types/surge-proxies.md
[surge-ruleset]: media-types/surge-ruleset.md
[surge-domain-set]: media-types/surge-domain-set.md
[clash+yaml]: media-types/clash+yaml.md
[clash-proxies+yaml]: media-types/clash-proxies+yaml.md
[clash-ruleset+yaml]: media-types/clash-ruleset+yaml.md
[clash-ruleset]: media-types/clash-ruleset.md
[sip008+json]: media-types/sip008+json.md
[uri-proxies]: media-types/uri-proxies.md

## References

- [RFC 2046, section 4.1](https://datatracker.ietf.org/doc/html/rfc2046#section-4.1)
- [RFC 2048, section 2.1.4](https://datatracker.ietf.org/doc/html/rfc2048#section-2.1.4)
- [RFC 2483, section 5](https://datatracker.ietf.org/doc/html/rfc2483#section-5)
- [RFC 6839, section 3.1](https://datatracker.ietf.org/doc/html/rfc6839#section-3.1)
- [RFC 6648](https://datatracker.ietf.org/doc/html/rfc6648)
- [YAML Media Type, section 2.2](https://datatracker.ietf.org/doc/html/draft-ietf-httpapi-yaml-mediatypes-10#section-2.2)
- [List of Proxy URI scheme](uri-schemes.md)
