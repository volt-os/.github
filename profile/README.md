<div align="center">

<img src="https://raw.githubusercontent.com/MohammadYehya/volt-os.github/main/gitassets/VoltOS_nobg.png" alt="VoltOS" width="200"/>
<br/>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com?font=Orbitron&weight=900&size=42&duration=1&pause=1000&color=58E1FF&center=true&vCenter=true&repeat=false&width=500&height=42&lines=VOLT+OS"/>
  <img src="https://readme-typing-svg.demolab.com?font=Orbitron&weight=900&size=42&duration=1&pause=1000&color=58E1FF&center=true&vCenter=true&repeat=false&width=500&height=42&lines=VOLT+OS"/>
</picture>

<sub><sup>L I N U X &nbsp;&nbsp; M A D E &nbsp;&nbsp; F A S T , &nbsp;&nbsp; F L U I D , &nbsp;&nbsp; A N D &nbsp;&nbsp; Y O U R S .</sup></sub>

[![Built on Arch](https://img.shields.io/badge/Built%20on-Arch%20Linux-1793D1?style=for-the-badge&logo=arch-linux&logoColor=white)](https://archlinux.org/)
[![Compositor](https://img.shields.io/badge/Compositor-Hyprland-58E1FF?style=for-the-badge&logo=wayland&logoColor=white)](https://hyprland.org/)
[![Shell](https://img.shields.io/badge/Shell-QuickShell-A6E3A1?style=for-the-badge&logo=quickshell)](https://quickshell.outfoxxed.me/)
[![Status](https://img.shields.io/badge/Status-Alpha-F9E2AF?style=for-the-badge)](https://github.com/MohammadYehya/volt-os.github/blob/main/profile)
[![License](https://img.shields.io/badge/License-GPL--3.0-F38BA8?style=for-the-badge&logo=gnu&logoColor=white)](https://github.com/MohammadYehya/volt-os.github/blob/main/profile/LICENSE)

</div>

---
<div align="center">
  
## 〔 The Vision 〕
</div>
<br/>

**VoltOS** is an Arch-based Linux distribution built around [Hyprland](https://hyprland.org/) and [QuickShell](https://quickshell.outfoxxed.me/). The goal is a desktop that starts fast, animates smoothly, and gives you full control over how it looks and behaves, without inheriting bloat from upstream defaults.

It's currently in alpha. The core stack is chosen and working, but the installer, marketplace, and configuration layer are still being built out. If you're here early, you're watching it take shape.

<div align="center">
  
## 〔 Core Pillars 〕
</div>
<table>
<tr>
<td width="33%" valign="top" align="center">

**SPEED**

Arch is a minimal base by design. VoltOS keeps it that way, no bundled services, no extras you didn't ask for. Less running means faster boot and launch times.

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

At its core, VoltOS pairs **Arch Linux** as the rolling-release base with **Hyprland** as its Wayland compositor, handling everything from tiling logic to the spring-physics animations the desktop is built around. The desktop shell itself is powered entirely by **QuickShell**, using <abbr title="Qt Modeling Language, a declarative language for designing user interfaces">QML</abbr> to give every surface of the UI a programmable, themeable identity.

Beyond that, decisions around the display manager, notification daemon, audio stack, and system tooling are being weighed carefully. The goal is coherence over comprehensiveness, every piece that ships will have a reason for being there.


<div align="center">
  
## 〔 The Marketplace 〕
</div>

After first boot, the Marketplace is the first thing you interact with. The base install has no launcher, no bar, no notification system. You pick what goes on your desktop and install it from here.\
The Marketplace operates on two tiers:\
**Verified**
:   Reviewed, tested, and approved by the VoltOS team. Guaranteed to integrate cleanly with the desktop and behave predictably.\
**Community**
:   Packages, themes, shell components, and extensions submitted by the community. Clearly marked as community-sourced, with ratings and open contribution.

> [!IMPORTANT]
> The Marketplace is in active design and has not shipped yet. If you have thoughts on how discovery, verification, or submission should work, open a [Discussion](https://github.com/MohammadYehya/volt-os.github/discussions). This is the right time to shape it.

<div align="center">

## 〔 Installation 〕
</div>

> [!WARNING]
> VoltOS does not have a stable installer or a bootable ISO yet. There is no supported installation path at this stage. Attempting to set it up from the current repository is possible, but expect rough edges, missing pieces, and things that change without notice.

When installation is ready, the experience will be straightforward, a script that takes a clean Arch base and lands you in a fully configured VoltOS desktop. A guided ISO installer is planned further down the line.

For now: watch the [Releases](https://github.com/MohammadYehya/volt-os.github/releases) page, or follow development in [Discussions](https://github.com/MohammadYehya/volt-os.github/discussions). Things are moving.

<div align="center">

## 〔 Roadmap 〕
</div>

VoltOS development is split into two primary phases: establishing the **Core Foundation** and building the **Modular Marketplace**. Our progress is tracked in detail, from base system configuration to user-facing plugins.

**Core**  -  *what the distro ships with by default*\
**Marketplace & Plugins**  -  *the extensibility layer*

[**View the full development roadmap →**](./ROADMAP.md)

<div align="center">

## 〔 Contributing 〕
</div>

VoltOS is an open project. Contributions are welcome at every level, code, design, documentation, bug reports, and feedback all move it forward.

The process is the standard GitHub fork-and-pull-request flow. If you're not sure where to start, check the open [Issues](https://github.com/MohammadYehya/volt-os.github/issues) or read through the [Discussions](https://github.com/MohammadYehya/volt-os.github/discussions) to get a feel for where things stand.

Contributions that aren't code are just as valuable. If you find the documentation lacking, fix it. If a bug is driving you mad, report it with enough context to reproduce it. If you've built something on top of VoltOS worth sharing, the community tab is for you.

<div align="center">

## 〔 License 〕
</div>

VoltOS is distributed under the **GNU General Public License v3.0**.

Free to use. Free to modify. Free to distribute, as long as it stays open.
See [LICENSE](./LICENSE) for the full terms.
