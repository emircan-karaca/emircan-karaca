<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a%2C100:1e3a5f&height=160&section=header&text=Emircan%20Karaca&fontSize=44&fontColor=e2e8f0&animation=fadeIn&fontAlignY=38&desc=systems%20%C2%B7%20networks%20%C2%B7%20self-hosted%20everything&descSize=16&descAlignY=60&descAlign=50">
  <img alt="Emircan Karaca — systems · networks · self-hosted everything" src="https://capsule-render.vercel.app/api?type=waving&color=0:e2e8f0,100:cbd5e1&height=160&section=header&text=Emircan%20Karaca&fontSize=44&fontColor=0f172a&animation=fadeIn&fontAlignY=38&desc=systems%20%C2%B7%20networks%20%C2%B7%20self-hosted%20everything&descSize=16&descAlignY=60&descAlign=50">
</picture>

<p align="center">
  Systems and network engineer at a public institution in Türkiye.<br>
  I write low-level tooling in Rust, Go and Swift, and keep the networks it runs on healthy.
</p>

<p align="center">
  <a href="mailto:emir@linux.com"><img alt="email" src="https://img.shields.io/badge/Email-emir%40linux.com-1e3a5f?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTIgNS41QTIuNSAyLjUgMCAwIDEgNC41IDNoMTVBMi41IDIuNSAwIDAgMSAyMiA1LjV2MTNhMi41IDIuNSAwIDAgMS0yLjUgMi41aC0xNUEyLjUgMi41IDAgMCAxIDIgMTguNXptMi4zLS41IDcuNyA1LjZMMTkuNyA1ek0yMCA3LjRsLTggNS44LTgtNS44djExLjFjMCAuMy4yLjUuNS41aDE1Yy4zIDAgLjUtLjIuNS0uNXoiLz48L3N2Zz4%3D"></a>
  <img alt="location" src="https://img.shields.io/badge/T%C3%BCrkiye-UTC%2B3-1e3a5f?style=flat-square">
</p>

## Hi, I'm Emircan

I keep infrastructure running for a public institution in Türkiye by day (systems, networks, the boxes nobody notices until they stop), and I run my own at home. Most of my code exists because something in that stack annoyed me enough to replace it.

Everything I build is private for now. I open things up when it is honest enough to be judged, not before.

### The stack I actually run

```text
┌─ hardware ───────────────────────────────────────┐
│  IT devices  ·  servers  ·  network gear         │
├─ os ─────────────────────────────────────────────┤
│  macOS  ·  Linux                                 │
├─ isolation ──────────────────────────────────────┤
│  Docker / OCI containers                         │
│  microVMs, one per container                     │
├─ services ───────────────────────────────────────┤
│  Nginx  ·  Supabase  ·  Go daemons               │
├─ network edge ───────────────────────────────────┤
│  mikrotik    routing · firewall · VLANs · Wi-Fi  │
│  fortigate   perimeter · policies                │
│  switches    port monitoring                     │
│  wifi        coverage                            │
└─ glue ───────────────────────────────────────────┘
   Git · Rust / Go / Swift / TypeScript / Python
```

### What I'm building

- **A daemonless container engine for macOS / Apple Silicon, in Rust.** No background daemon. Each container gets its own microVM, so the isolation boundary is the hypervisor, not a shared kernel. Aims for Docker CLI command parity so existing muscle memory keeps working.
- **A self-hosted Backend-as-a-Service, in TypeScript.** Auth, database, storage and functions on hardware I own — a self-hosted alternative to Supabase for my own projects.
- **Home infrastructure automation, in Go.** Declarative config for the services above, so a rebuild is a `git clone` away instead of an afternoon.
- **A network IP scanner and connect tool for macOS / iOS, in Swift.** Sweep a subnet, see what answers, connect in one tap. Built for people who live in switch consoles.
- **A couples' memories and special-days app, in Flutter + Supabase.** The one project on this list that is not about servers.
- **A document filing system, in Python.** Boring on purpose. Files go in, they come out named and sorted.

### Tools I reach for

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://skillicons.dev/icons?i=rust%2Cgo%2Cswift%2Cts%2Cpy%2Cflutter%2Cdocker%2Clinux%2Capple%2Csupabase%2Cnginx%2Cgit&perline=6&theme=dark">
    <img alt="Rust, Go, Swift, TypeScript, Python, Flutter, Docker, Linux, macOS, Supabase, Nginx, Git" src="https://skillicons.dev/icons?i=rust,go,swift,ts,py,flutter,docker,linux,apple,supabase,nginx,git&perline=6&theme=light">
  </picture>
  <br><br>
  <img alt="MikroTik RouterOS" src="https://img.shields.io/badge/MikroTik-RouterOS-4a5568?style=flat-square&logo=mikrotik&logoColor=white">
  <img alt="FortiGate FortiOS" src="https://img.shields.io/badge/FortiGate-FortiOS-EE3124?style=flat-square&logo=fortinet&logoColor=white">
  <br>
  <sub>Rust · Go · Swift · TypeScript · Python · Dart/Flutter · Docker · Linux · macOS · Supabase · MikroTik / FortiGate · Nginx · Git</sub>
</p>

### GitHub activity

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com/?user=emircan-karaca&theme=github-dark-blue&hide_border=true&background=00000000">
    <img alt="GitHub streak" src="https://streak-stats.demolab.com/?user=emircan-karaca&theme=default&hide_border=true&background=00000000">
  </picture>
  <br>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/emircan-karaca/emircan-karaca/output/github-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/emircan-karaca/emircan-karaca/output/github-snake.svg">
    <img alt="contribution snake" src="https://raw.githubusercontent.com/emircan-karaca/emircan-karaca/output/github-snake.svg">
  </picture>
</div>

<br>

<p align="center">
  <sub>Sağlıcakla kalın — stay well. Reach me at <a href="mailto:emir@linux.com">emir@linux.com</a>.</sub>
</p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://capsule-render.vercel.app/api?type=waving&color=0:1e3a5f%2C100:0f172a&height=100&section=footer">
  <img alt="" src="https://capsule-render.vercel.app/api?type=waving&color=0:cbd5e1,100:e2e8f0&height=100&section=footer">
</picture>
