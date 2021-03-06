---
layout: page
title: Home
---

{{ site.product_name }} is a speedrun tool for the *popular* PC game [{{ site.game_name }}](https://en.wikipedia.org/wiki/Martian_Gothic:_Unification){:target="_blank" rel="noopener"}.

{% if site.posts.size > 0 %}
*Last Update: {% assign post = site.posts | first %} {{ post.date | date: "%F" }} ([Changelog](changelog.html))*.
{% endif %}

<img align="right" width="216" height="493" src="assets/srt_window_detailed.png" alt="{{ site.product_name }} main window">

## Installation

1. Download and extract the latest version of **[SRT Host](https://www.neonblu.com/SRT/){:target="_blank" rel="noopener"}**.
2. Download the latest **[{{ site.product_name }} Plugin Pack {{ site.github.latest_release.name }}]({% assign asset = site.github.latest_release.assets | first %}{{ asset.browser_download_url }})**.
3. Extract the Plugin Pack contents to SRT Host **plugins** folder.
4. Run **SRTHost32.exe** and start {{ site.game_name }}.

## Features

* Player health.
* Poison status.
* Caution/danger status.
* Enemy health.
* In-game timer.
* DirectX overlay.
* Customizable interface.
* JSON HTTP Server via **[SRTPluginUIJSON](https://github.com/Squirrelies/SRTPluginUIJSON/){:target="_blank" rel="noopener"}**.

### Planned

* Inventory display.
* Equipped item.
