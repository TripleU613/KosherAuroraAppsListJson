

# 📱 Kosher Aurora Apps List

Welcome! This repository powers the **Kosher Aurora Store** – a filtered and privacy-focused version of Aurora Store tailored for safe, kosher-friendly usage. The store fetches a dynamic app list from this repo, ensuring that only approved apps are available—no updates to the app itself are needed.

---

## 🔍 What’s Different?

You may remember the older **Aurora Updater**—it worked, but this is better:

* ✅ Uses the **latest version** of the Aurora Store
* ✅ Supports **direct app downloads**
* ✅ Dynamically syncs with this JSON list
* ✅ Can install via **root**, **Aurora Services**, or even standard **Package Installer**
* ✅ Tries to **block access to default app settings**, but if users find a way, [please report it](https://github.com/TripleU613/KosherAuroraAppsListJson/issues)

---

## 📁 JSON-Controlled App List

All app visibility is controlled by a single file: [`apps_list.json`](apps_list.json)

* **No coding required** to contribute—it's like editing a text file.
* Hosted on GitHub, so anyone can help maintain the list.
* Used live by the store to update its allowed apps.

### ✅ Allowed Apps

The rules are simple:

* ❌ No social media
* ❌ No apps with embedded browsers
* ✅ Everything else that's useful or age-appropriate:

  * File managers
  * Utility tools
  * Kid-safe games

---

## ✍️ How to Contribute

Want to help maintain or suggest apps? It's easy:

1. **Fork the Repository**
   Click the **Fork** button in the top right of this page.

2. **Edit `apps_list.json`**
   Find the category that fits, and add the app’s package name.
   If no suitable category exists, create a new one.

3. **Submit a Pull Request**
   Include a brief explanation of what the app does and why it fits the kosher criteria.

All pull requests will be reviewed for suitability.

Feel like this is too advanced for you? It isn't. Check this guide out on how to contribute:
https://forums.jtechforums.org/t/guide-how-to-contribute-to-tripleus-kosher-aurora-store/3890

---

## 🧾 JSON Format

Here’s what the format looks like:

```json
{
  "categories": [
    {
      "title": "File Managers",
      "packages": [
        "com.example.files",
        "com.example.manager"
      ]
    },
    {
      "title": "Educational Games",
      "packages": [
        "com.kidsgame.mathfun"
      ]
    }
  ]
}
```

---

## ⚙️ Installation Notes

* **Rooted device?** Enable root install in settings.
* **Aurora Services installed?** It can use that too.
* **No extras?** It will install using the regular Android package installer.
* **Anonymous login only** — that's the only mode allowed in this fork.

---

## 🧪 Still Experimental

A lot of effort went into blocking access to app settings and preventing workarounds—but nothing’s perfect. If you discover a bypass, please [open an issue](https://github.com/TripleU613/KosherAuroraAppsListJson/issues) so it can be fixed.

---

## 📥 Download

➡️ [Get the latest release here](https://github.com/TripleU613/KosherAuroraAppsListJson/releases)

---

Thank you for helping make the **Kosher Aurora Store** safe, useful, and community-driven!


