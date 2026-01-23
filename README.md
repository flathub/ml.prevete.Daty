# Daty

___Free Wikidata editor___

Daty is a free Wikidata editor adhering to GNOME Human Interface Guidelines, intended to enable a better editing workflow and faster deployment of requested user features for Wikidata.

Use Daty to search, select, read, batch edit items, script actions, share, visualize proposed changes and bots.

WARNING: This is a preview release, so entity editing is disabled.

---

## Manual Install and Run

Make sure you follow the [setup guide for your Linux distribution](https://flathub.org/en/setup) before installing.

```
flatpak install flathub ml.prevete.Daty
flatpak run ml.prevete.Daty
```

## Building

```
git clone git@github.com:flathub/ml.prevete.Daty.git
flatpak run org.flatpak.Builder build-dir --user --ccache --force-clean --install ml.prevete.Daty.json
```

