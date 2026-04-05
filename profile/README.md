<div align="center">

<img src="https://raw.githubusercontent.com/MohammadYehya/volt-os.github/main/gitassets/VoltOS_nobg.png" alt="VoltOS" width="200"/>
<br/>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=Orbitron&weight=900&size=42&duration=1&pause=1000&color=58E1FF&center=true&vCenter=true&repeat=false&width=500&height=60&lines=VOLT+OS"/>
  <img src="https://readme-typing-svg.demolab.com?font=Orbitron&weight=900&size=42&duration=1&pause=1000&color=58E1FF&center=true&vCenter=true&repeat=false&width=500&height=60&lines=VOLT+OS"/>
</picture>

<sub><sup>L I N U X &nbsp;&nbsp; M A D E &nbsp;&nbsp; F A S T , &nbsp;&nbsp; F L U I D , &nbsp;&nbsp; A N D &nbsp;&nbsp; Y O U R S .</sup></sub>

[![Built on Arch](https://img.shields.io/badge/Built%20on-Arch%20Linux-1793D1?style=flat-square&logo=arch-linux&logoColor=white)](https://archlinux.org/)
&nbsp;
[![Compositor](https://img.shields.io/badge/Compositor-Hyprland-58E1FF?style=flat-square&logo=wayland&logoColor=white)](https://hyprland.org/)
&nbsp;
[![Shell](https://img.shields.io/badge/Shell-QuickShell-A6E3A1?style=flat-square)](https://quickshell.outfoxxed.me/)
&nbsp;
[![Status](https://img.shields.io/badge/Status-Alpha-F9E2AF?style=flat-square)]()
&nbsp;
[![License](https://img.shields.io/badge/License-GPL--3.0-F38BA8?style=flat-square&logo=gnu&logoColor=white)](./LICENSE)

</div>

---
<div align="center">
  
## 〔 The Vision 〕
</div>
<br/>

> **VoltOS** is not a reskin. It is a rethinking.
>
> Built on the bare metal of Arch Linux, animated by Hyprland, and fully expressed through QuickShell — VoltOS is a distribution designed around three uncompromising ideas: your system should launch before you blink, move like it has weight, and look exactly the way you want it to.
>
> No bloat inherited. No opinions forced. No ceiling on what you can build with it.

<div align="center">
  
## 〔 Core Pillars 〕
</div>
<table>
<tr>
<td width="33%" valign="top" align="center">

**SPEED**

VoltOS ships nothing it doesn't need. No redundant services, no background noise, no weight you didn't ask for. Arch gives us the leanest possible foundation — we keep it that way. Boot fast. Launch instantly. Stay out of your way.

</td>
<td width="33%" valign="top" align="center">

**FLUID ANIMATIONS**

Every window open, close, move, and workspace transition is deliberate. Hyprland's GPU-accelerated compositor makes spring physics and bezier curves first-class citizens. Nothing snaps. Everything flows.

</td>
<td width="33%" valign="top" align="center">

**CUSTOMIZABILITY**

QuickShell gives you QML, a real language, not a config file. Rewrite the bar. Rebuild the launcher. Redesign the lock screen from scratch. VoltOS hands you every component and says: *make it yours.*

</td>
</tr>
</table>

<div align="center">
  
## 〔 Under the Hood 〕
</div>

> [!NOTE]
> The technical foundation of VoltOS is still being finalized. What you see here reflects the current direction, not a locked-in decision. Some components are confirmed, others are under active evaluation.

At its core, VoltOS pairs **Arch Linux** as the rolling-release base with **Hyprland** as its Wayland compositor, handling everything from tiling logic to the spring-physics animations the desktop is built around. The desktop shell itself is powered entirely by **QuickShell**, using <abbr title="Qt Modeling Language — a declarative language for designing user interfaces">QML</abbr> to give every surface of the UI a programmable, themeable identity.

Beyond that, decisions around the display manager, notification daemon, audio stack, and system tooling are being weighed carefully. The goal is coherence over comprehensiveness, every piece that ships will have a reason for being there.


<div align="center">
  
## 〔 The Marketplace 〕
</div>

VoltOS ships with a curated base of software — everything needed to get started, nothing that wasn't asked for. But the real extensibility comes through the **VoltOS Marketplace**: a first-class, built-in application for discovering and installing everything beyond the defaults.

The Marketplace operates on two tiers:

<dl>
  <dt><strong>Verified Apps</strong></dt>
  <dd>Software reviewed, tested, and approved by the VoltOS team. These are guaranteed to integrate cleanly with the desktop, meet a baseline quality bar, and behave predictably. Install with confidence.</dd>
  <dt><strong>Community Apps</strong></dt>
  <dd>Packages, themes, shell components, and extensions submitted by the community. Clearly surfaced as community-sourced, with ratings, flags, and open contribution. The marketplace grows with the people who use it.</dd>
</dl>

> [!IMPORTANT]
> The Marketplace is in active design and has not shipped yet. If you have thoughts on how discovery, verification, or submission should work — open a [Discussion](https://github.com/MohammadYehya/volt-os.github/discussions). This is the right time to shape it.

<div align="center">

## 〔 Installation 〕
</div>

> [!WARNING]
> VoltOS does not have a stable installer or a bootable ISO yet. There is no supported installation path at this stage. Attempting to set it up from the current repository is possible, but expect rough edges, missing pieces, and things that change without notice.

When installation is ready, the experience will be straightforward — a script that takes a clean Arch base and lands you in a fully configured VoltOS desktop. A guided ISO installer is planned further down the line.

For now: watch the [Releases](https://github.com/MohammadYehya/volt-os.github/releases) page, or follow development in [Discussions](https://github.com/MohammadYehya/volt-os.github/discussions). Things are moving.

<div align="center">

## 〔 Roadmap 〕
</div>

Development is organized loosely into three phases. What's done is done. What's in progress is being actively worked. What's planned is real — just not yet.

**Foundation** &nbsp;—&nbsp; *in progress*

- [x] Hyprland base configuration
- [ ] QuickShell bar and system tray
- [ ] App launcher
- [ ] Lock screen
- [ ] Notification system

**Core** &nbsp;—&nbsp; *in progress*

- [ ] Automated install script
- [ ] NVIDIA compatibility
- [ ] VoltOS settings panel
- [ ] Stable, reproducible configuration layer

**Release** &nbsp;—&nbsp; *planned*

- [ ] Marketplace — first public release
- [ ] Verified app catalogue
- [ ] Community submission pipeline
- [ ] Bootable ISO with guided installer
- [ ] Custom GRUB theme

<div align="center">

## 〔 Contributing 〕
</div>

VoltOS is an open project. Contributions are welcome at every level — code, design, documentation, bug reports, and feedback all move it forward.

The process is the standard GitHub fork-and-pull-request flow. Fork the repository, create a branch, make your changes with clear commit messages, and open a PR. If you're not sure where to start, check the open [Issues](https://github.com/MohammadYehya/volt-os.github/issues) or read through the [Discussions](https://github.com/MohammadYehya/volt-os.github/discussions) to get a feel for where things stand.

Contributions that aren't code are just as valuable. If you find the documentation lacking, fix it. If a bug is driving you mad, report it with enough context to reproduce it. If you've built something on top of VoltOS worth sharing, the community tab is for you.

<div align="center">

## 〔 License 〕
</div>

VoltOS is distributed under the **GNU General Public License v3.0**.

Free to use. Free to modify. Free to distribute — as long as it stays open.
See [LICENSE](./LICENSE) for the full terms.

<div align="center">

[![Stars](https://img.shields.io/github/stars/MohammadYehya/volt-os.github?style=flat-square&color=FFD700)](https://github.com/MohammadYehya/volt-os.github/stargazers)
&nbsp;&nbsp;
[![Issues](https://img.shields.io/github/issues/MohammadYehya/volt-os.github?style=flat-square&color=F38BA8)](https://github.com/MohammadYehya/volt-os.github/issues)
&nbsp;&nbsp;
[![Forks](https://img.shields.io/github/forks/MohammadYehya/volt-os.github?style=flat-square&color=A6E3A1)](https://github.com/MohammadYehya/volt-os.github/fork)

<sub>Fast. Fluid. Yours.</sub>

</div>
