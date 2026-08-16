<div align="center">

<h1>Hide widget header</h1>

<p>
developed and maintained by
<a href="https://www.initmax.com"><img alt="initMAX" src="./.readme/logo/initmax-logo-framed.svg" height="22" valign="middle"></a>
and community
</p>

<p><strong>Takes the title bar off the widgets that do not need one - until you go to edit the board.</strong><br>
A clock, a logo or a single big number reads better without a header above it; the header comes straight back the moment you switch the dashboard to edit mode, so nothing becomes unconfigurable.</p>

<p>
<img src="./.readme/badge/zabbix.svg" alt="Zabbix 6.0-7.4">
<img src="./.readme/badge/version.svg" alt="version 2.0.3">
<img src="./.readme/badge/php.svg" alt="PHP 7.4+">
<img src="./.readme/badge/free.svg" alt="FREE AGPLv3">
<img src="./.readme/badge/gpg.svg" alt="GPG signed">
</p>

<p>
<a href="#what-you-can-build"><strong>Features</strong></a> &nbsp;·&nbsp;
<a href="#examples"><strong>Examples</strong></a> &nbsp;·&nbsp;
<a href="#install"><strong>Install</strong></a> &nbsp;·&nbsp;
<a href="#free-vs-pro"><strong>FREE vs PRO</strong></a> &nbsp;·&nbsp;
<a href="https://portal.initmax.com"><strong>Portal</strong></a> &nbsp;·&nbsp;
<a href="https://www.initmax.com/wiki/hide-widget-header/"><strong>Docs</strong></a>
</p>

<br>

<img src="./.readme/screen/01-overview.png" width="880" alt="Hide widget header on a Zabbix dashboard">

</div>

---

## Why Hide widget header

Zabbix already lets you mark a widget "hide header", but it still reserves the bar and shows it on hover - which is the right call while you are building a dashboard and noise once the board is on a wall.

**Hide widget header** takes those headers away completely while the dashboard is being VIEWED, and puts them back the moment you switch to edit mode - so every widget stays as configurable as it was. It applies only to widgets you have already marked as hidden-header; everything else looks exactly as before. There is nothing to configure: install it, enable it, done. The module ships a stylesheet and nothing else, so turning it off restores Zabbix exactly.

## What you can build

<table>
<tr>
<td width="50%" valign="top">

**Clean widgets on the wall**

Widget headers disappear outside dashboard edit mode, so a NOC screen shows only the data.

</td>
<td width="50%" valign="top">

**Headers back while editing**

Enter edit mode and every header is there again - move, resize and configure as usual.

</td>
</tr>
<tr>
<td width="50%" valign="top">

**Nothing to configure**

Install, enable, and every dashboard follows the rule for every user.

</td>
<td width="50%" valign="top">

**Stylesheet only**

Disable the module and Zabbix looks exactly as before.

</td>
</tr>
</table>

## Examples

<table>
<tr>
<td width="50%" align="center" valign="top"><img src="./.readme/screen/02-view-mode.png" alt="View mode"><br><small><b>View mode</b> - view mode</small></td>
<td width="50%" align="center" valign="top"><img src="./.readme/screen/03-edit-mode.png" alt="Edit mode"><br><small><b>Edit mode</b> - edit mode</small></td>
</tr>
</table>

## Configuration

There is nothing to configure - install it, enable it, done.

## Install

**FREE** ships as **GPG-signed `deb` / `rpm` packages** from the initMAX repository - `apt` / `dnf` installs them and keeps them updated.

### Easiest way - the guided installer on the Portal

Open the product page, pick your **OS** and **edition**, and copy the ready-made command. FREE is fully public (no login); PRO fills in your token once you sign in. There's a feedback box right there too.

<div align="center">
<a href="https://portal.initmax.com/catalog/zabbix-hidewidgetheader#how-to-install"><img src="./.readme/screen/portal-installer.png" width="100%" alt="Guided installer on the initMAX Portal - click to open"></a>
</div>

<p align="center"><a href="https://portal.initmax.com/catalog/zabbix-hidewidgetheader#how-to-install"><strong>→ Open the installer on the Portal</strong></a></p>

Prefer a plain archive? Every release also ships as a **ZIP** [straight from the repo](https://repo.initmax.com/zabbix/free/zip/hidewidgetheader/) - handy for offline or manual installs.

The module is enabled automatically during the package installation - verify it in **Administration → General → Modules**. Done.

## FREE vs PRO

There is no paid edition - everything below is in the one package.

| Feature | FREE |
| ---------------------------------------------------------- | :----: |
| Hide widget header outside dashboard edit mode | ✅ |
| Localised into all 25 Zabbix display languages | ✅ |
| High availability ready | ✅ |
| Licence | AGPLv3 |

## Requirements

|              |                                                              |
| ------------ | ------------------------------------------------------------ |
| **Zabbix**   | 6.0 · 6.2 · 6.4 · 7.0 · 7.2 · 7.4 - one package covers all    |
| **PHP**      | 7.4 or newer                                                 |
| **OS**       | Debian/Ubuntu · RHEL/Rocky/Alma/Oracle/Amazon · SUSE         |
| **Editions** | FREE (public repo) - there is no paid edition                  |
| **Languages** | All 25 Zabbix display languages - the module follows each user's own language setting |
| **High availability** | Ready. A stylesheet only - no server-side component and no local state; install it on every frontend node of an HA cluster and any node can serve it |

One package covers the whole range. Zabbix renamed the widget header element in 7.0 and changed its module API at 6.4, and the package carries what each frontend needs, so the same install works on 6.0 and on 7.4.

## Support &amp; links

- **[Documentation / Wiki](https://www.initmax.com/wiki/hide-widget-header/)**
- **[Product page](https://www.initmax.com/product/hide-widget-header/)**
- **[Portal](https://portal.initmax.com)** - downloads, tokens, support tickets
- **Source code (FREE, AGPLv3)** - included in every package and published as a [source archive](https://repo.initmax.com/zabbix/free/zip/hidewidgetheader/) on repo.initmax.com
- **[support@initmax.com](mailto:support@initmax.com)**

---

<div align="center">
<sub>FREE: <a href="https://www.gnu.org/licenses/agpl-3.0.html">AGPLv3</a> &nbsp;·&nbsp; © 2021–2026 initMAX s.r.o.</sub>
</div>
