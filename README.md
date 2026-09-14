# SnishaperTeam

Building comprehensive, freely combinable software for flexible network traffic manipulation.

SnishaperTeam is a development organization dedicated to creating tools that enable users to navigate and operate within complex network environments. Our work centers on the principle of composability: each component is designed to function independently while integrating seamlessly with others, giving users the freedom to combine options according to their specific needs.

The organization was established as a continuation of the original SniShaper project. After the departure of the original developer, the team has carried forward active development and maintenance, expanding the project's scope across multiple platforms and techniques.

Our primary focus areas include:

- **SNI-based blocking circumvention** -- Supporting multiple bypass methods including TLS fragmentation, domain fronting, Encrypted Client Hello (ECH), QUIC direct connection, and dynamic reverse proxy relay
- **Cross-platform proxy tooling** -- Bringing Clash-style proxy functionality to Android, HarmonyOS, and desktop platforms
- **Composable architecture** -- Designing software with modular, freely combinable components that allow flexible traffic operation strategies

---

## Core Members

| Member | Role |
|--------|------|
| [dongzheyu](https://github.com/dongzheyu) (dongle / JetCPPTeam) | Lead developer, core maintainer |
| [Snishaper](https://github.com/Snishaper) | Developer, continuing updates following the departure of the original author |

---

## Projects

### SniShaper

A desktop application supporting multiple methods to bypass SNI blocking, designed for complex network environments. SniShaper is the flagship project of SnishaperTeam, providing a full-featured platform for network traffic manipulation with an emphasis on reliability and flexibility. It supports techniques such as TLS fragmentation, domain fronting, ECH, MITM, and CDN-based approaches.

Topics: cdn, cloudflare, domain-fronting, dpi, dpi-bypass, ech, gfw, golang, mitm, privacy, proxy, sni, tls

| Repository | Language | Description |
|------------|----------|-------------|
| [SniShaper](https://github.com/SnishaperTeam/SniShaper) | Go | Main desktop application |
| [SniShaper-Fast](https://github.com/SnishaperTeam/SniShaper-Fast) | Go | Lightweight proxy tool with passthrough, domain fronting, ECH, TLS fragmentation, QUIC direct, and dynamic reverse relay -- the full-featured direct-connection platform |
| [SniShaperWeb](https://github.com/dongzheyu/SniShaperWeb) | TypeScript | Official project website |

### lumine

Clash-style network proxy implementations across multiple platforms. lumine brings familiar Clash-style proxy functionality to mobile and embedded platforms, providing consistent user experience across ecosystems.

| Repository | Platform | Language | Description |
|------------|----------|----------|-------------|
| [lumine-for-harmonyos](https://github.com/SnishaperTeam/lumine-for-harmonyos) | HarmonyOS | C++ | Clash-style implementation of lumine on HarmonyOS, built with ArkTS and ArkUI |
| [lumine-for-android](https://github.com/Snishaper/lumine-for-android) | Android | Go | Clash-style implementation of lumine on Android |

### Related Tools

| Repository | Language | Description |
|------------|----------|-------------|
| [sniproxy-tls-rf](https://github.com/Snishaper/sniproxy-tls-rf) | Go | Simple implementation for SniShaper tls-rf mode custom upstream |
| [blindtls-vercel](https://github.com/Snishaper/blindtls-vercel) | Go | BlindTLS server implementation on Vercel |
| [Optidown](https://github.com/Snishaper/Optidown) | -- | Optimized proxy and download manager using pre-speed testing to accelerate most download tasks (Planned) |

---

## Technology Stack

- **Go** -- Core proxy and networking applications (SniShaper, SniShaper-Fast, lumine-for-android, server-side tooling)
- **C++** -- Platform-specific native implementations (lumine-for-harmonyos, system utilities)
- **TypeScript** -- Web presence and frontend tooling (SniShaperWeb)
- **ArkTS / ArkUI** -- HarmonyOS application development (lumine-for-harmonyos)

---

## Contact

- Website: [jetcpp.ccwu.cc](https://jetcpp.ccwu.cc)

---

SnishaperTeam -- Build freely, combine flexibly.