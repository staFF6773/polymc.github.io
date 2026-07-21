---
title: Download PolyMC for macOS
eleventyNavigation:
  key: <i class="fa fa-apple" aria-hidden="true"></i> macOS 
  order: 2
---

<div class="download-content">
    <div class="row">
    <div class="column">
      <div>
        <h1>macOS Download</h1>
        <br>
        <p><strong>Note:</strong> The current build is Apple Silicon (aarch64) only. For Intel Macs, use the Legacy build below.</p>
        <a class="button is-big" href="https://github.com/PolyMC/PolyMC/releases/download/{{ version.current }}/PolyMC-macOS-{{ version.current }}.tar.gz">Download (aarch64)</a>
        <a class="button is-big" href="https://github.com/PolyMC/PolyMC/releases/download/{{ version.current }}/PolyMC-macOS-Legacy-{{ version.current }}.tar.gz">Download Legacy (Universal)</a>
      </div>
    </div>
    <div class="column">
      {% image "Modpack Installer", "./src/img/screenshots/mac/LauncherLight.png", "./src/img/screenshots/mac/LauncherDark.png" %}
    </div>
  </div>
</div>

<div class="infobox top">

## Advanced MacOS install options

### Homebrew Package (community-maintained)

#### Installation instructions

```bash
brew install --cask polymc
```

### MacPorts Package (community-maintained)

#### Installation instructions

```bash
sudo port install PolyMC
```
  
</div>
