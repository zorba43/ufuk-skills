# ufuk-skills

[🇹🇷 Türkçe](#türkçe) · [🇬🇧 English](#english)

---

## Türkçe

Bu repo bir **Claude Code eklenti pazarı (plugin marketplace)**. Seçtiğim eklentileri ve kendi skill'lerimi tek bir yerden kurmanızı sağlar.

### Kurulum

Claude Code içinde şu iki komutu çalıştırın:

```
/plugin marketplace add zorba43/ufuk-skills
/plugin install ufuk-skills@ufuk-skills
```

Kurulumdan sonra Claude Code'u yeniden başlatın (veya `/reload-plugins` çalıştırın).

### Eklentiler

| Eklenti | Açıklama |
|---|---|
| `ufuk-skills` | Planlama, hata ayıklama, TDD ve kod incelemesi için iş akışı skill'leri. Jesse Vincent'ın Superpowers eklentisine dayanır (skill'ler `/superpowers:...` adıyla görünür). Doğrudan [obra/superpowers](https://github.com/obra/superpowers) reposundan kurulur. |

Kendi skill'lerim ileride `plugins/` klasörüne eklenecek.

### Güncelleme

```
/plugin marketplace update ufuk-skills
```

---

## English

This repo is a **Claude Code plugin marketplace**. It lets you install plugins I've picked, plus my own skills, from one place.

### Install

Run these two commands inside Claude Code:

```
/plugin marketplace add zorba43/ufuk-skills
/plugin install ufuk-skills@ufuk-skills
```

Restart Claude Code afterwards (or run `/reload-plugins`).

### Plugins

| Plugin | Description |
|---|---|
| `ufuk-skills` | Workflow skills for planning, debugging, TDD and code review. Based on Superpowers by Jesse Vincent (skills appear as `/superpowers:...`). Installed directly from [obra/superpowers](https://github.com/obra/superpowers). |

My own skills will be added under `plugins/` later.

### Updating

```
/plugin marketplace update ufuk-skills
```

---

## Credits / Teşekkürler

Third-party plugins are not copied into this repo; the marketplace points to the original repositories, so you always get the author's own code.
Üçüncü taraf eklentiler bu repoya kopyalanmaz; pazar doğrudan orijinal repolara yönlendirir.

| Plugin | Author / Yazar | Repository | License / Lisans |
|---|---|---|---|
| ufuk-skills (Superpowers) | Jesse Vincent ([@obra](https://github.com/obra)) | https://github.com/obra/superpowers | MIT |
