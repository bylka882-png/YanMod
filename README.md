# 🔪 YanMod

🌐 [English] | 🇷🇺 [Русский](README.RU.md)

**A mod repository for Yandere Simulator.** All modifications are packed into `.7z` archives, include `.webp` screenshots, and are available in the [Releases](../../releases) section.

---

### 📦 Archive Structure and Manifest

The releases contain **`.7z`** archives, while the repository hosts demonstration **`.webp`** images and the `info.yaml` manifest file:

```yaml
id: "Unique_ID"
name: "Mod name"
by: "Mod author"
credits: "Link to the author's social media"
v: "Mod version"
gameV: "Game version"
description: "Mod description"
DL_url: "Direct download link for the archive"
type: "Mod type"
affected_files:
  - "Files to be replaced (for tracking conflicts)"
dependencies:
  - "Dependencies"
```

---

### 📉 Supported Game Version Formats (`gameV`)

* **`<=`** / **`>=`** — less than/equal to or greater than/equal to the specified version.
* **`yyyy.mm.dd-yyyy.mm.dd`** — build period (from and to).
* **`U4`** / **`U5`** / **`U17`** / **`U19`** / **`U20`** / **`U6`** — specific Unity engine version.
* **`own`** — for standalone custom game builds.

---

### 🗂️ Supported Mod Types (`type`)

* **`Mod`** — standard mod.
* **`PM`** — Pose Mod modification.
* **`TR`** — texture replacement.
* **`ML`** — mod loader.
* **`Build`** — standalone game build.
* **`Plugin`** — BepInEx plugin.
* **`Translate`** — game localization/translation.

---

### 📥 How to Download

1. Go to **[Releases](../../releases)**.
2. Choose the required **`.7z`** archive.
3. Verify compatibility using the manifest and download the file.
