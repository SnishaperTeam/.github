# SnishaperTeam

Building comprehensive, freely combinable software for flexible network traffic manipulation.

SnishaperTeam is a development organization dedicated to creating tools that enable users to navigate and operate within complex network environments. Our work centers on the principle of composability: each component is designed to function independently while integrating seamlessly with others, giving users the freedom to combine options according to their specific needs.

The organization was established as a continuation of the original SniShaper project and has carried forward active development and maintenance, expanding the project's scope across multiple platforms and techniques.

Our primary focus areas include:

- **SNI-based blocking circumvention** — Supporting multiple bypass methods including TLS fragmentation, domain fronting, Encrypted Client Hello (ECH), QUIC direct connection, and dynamic reverse proxy relay
- **Cross-platform proxy tooling** — Bringing Clash-style proxy functionality to Android, HarmonyOS and desktop platforms
- **Composable architecture** — Designing software with modular, freely combinable components that allow flexible traffic operation strategies

---

## SniShaper

A desktop application supporting multiple methods to bypass SNI blocking, designed for complex network environments. It supports techniques such as TLS fragmentation, domain fronting, ECH, MITM and CDN-based approaches, with a full-featured direct-connection variant and a native Android companion client.

<div align="center">
<table>
<tr>
<td width="50%">

[![SniShaper](https://githubcard.com/SnishaperTeam/SniShaper.svg)](https://githubcard.com/SnishaperTeam/SniShaper/card?utm_source=github&utm_medium=readme)

</td>
<td width="50%">

[![Snishaper-Droid](https://githubcard.com/SnishaperTeam/Snishaper-Droid.svg)](https://githubcard.com/SnishaperTeam/Snishaper-Droid/card?utm_source=github&utm_medium=readme)

</td>
</tr>
</table>

**[SniShaper-Fast](https://github.com/SnishaperTeam/SniShaper-Fast)** — private repository, team members only

</div>

## FlowWeaver & snishaper-core

[FlowWeaver](https://github.com/SnishaperTeam/FlowWeaver) is the full-featured local proxy client and gateway: Clash subscription support, multi-protocol nodes (Shadowsocks, VMess, VLESS, Trojan, TUIC, Hysteria2, WireGuard, SOCKS5, HTTP), UDP relay and TUN virtual adapter integration. Both SniShaper and FlowWeaver take their proxy engine from the standalone [snishaper-core](https://github.com/SnishaperTeam/snishaper-core) library: proxy server, rule engine, DoH resolver, certificate manager and TUN dataplane in one reusable Go module.

<div align="center">
<table>
<tr>
<td width="50%">

[![FlowWeaver](https://githubcard.com/SnishaperTeam/FlowWeaver.svg)](https://githubcard.com/SnishaperTeam/FlowWeaver/card?utm_source=github&utm_medium=readme)

</td>
<td width="50%">

[![snishaper-core](https://githubcard.com/SnishaperTeam/snishaper-core.svg)](https://githubcard.com/SnishaperTeam/snishaper-core/card?utm_source=github&utm_medium=readme)

</td>
</tr>
</table>
</div>

## lumine

Clash-style network proxy implementations across multiple platforms, bringing familiar Clash-style proxy functionality to mobile platforms with a consistent user experience across ecosystems.

<div align="center">
<table>
<tr>
<td width="50%">

[![lumine-for-harmonyos](https://githubcard.com/SnishaperTeam/lumine-for-harmonyos.svg)](https://githubcard.com/SnishaperTeam/lumine-for-harmonyos/card?utm_source=github&utm_medium=readme)

</td>
<td width="50%">

[![lumine-for-android](https://githubcard.com/SnishaperTeam/lumine-for-android.svg)](https://githubcard.com/SnishaperTeam/lumine-for-android/card?utm_source=github&utm_medium=readme)

</td>
</tr>
</table>
</div>

## Related Tools

<div align="center">
<table>
<tr>
<td width="33%">

[![sniproxy-tls-rf](https://githubcard.com/Snishaper/sniproxy-tls-rf.svg)](https://githubcard.com/Snishaper/sniproxy-tls-rf/card?utm_source=github&utm_medium=readme)

</td>
<td width="33%">

[![blindtls-vercel](https://githubcard.com/Snishaper/blindtls-vercel.svg)](https://githubcard.com/Snishaper/blindtls-vercel/card?utm_source=github&utm_medium=readme)

</td>
<td width="33%">

[![Optidown](https://githubcard.com/Snishaper/Optidown.svg)](https://githubcard.com/Snishaper/Optidown/card?utm_source=github&utm_medium=readme)

</td>
</tr>
</table>
</div>

---

## Technology Stack

- **Go** — Core proxy and networking applications (SniShaper, FlowWeaver, SniShaper-Fast, snishaper-core, lumine-for-android, server-side tooling)
- **C++ / ArkTS / ArkUI** — HarmonyOS native development (lumine-for-harmonyos)
- **Kotlin + Jetpack Compose** — Android client (Snishaper-Droid)
- **TypeScript / React** — Frontend and web presence

---

## Contact

- Website: [jetcpp.ccwu.cc](https://jetcpp.ccwu.cc)
- Matrix: [Snishaper and FlowWeaver building](https://matrix.to/#/!j7cXGinN6v1-6-FyjGKxAfoZrVjzQWRgrOmc3l6zxj4?via=matrix.org)

---

SnishaperTeam — Build freely, combine flexibly.
