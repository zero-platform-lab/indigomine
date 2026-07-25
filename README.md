# Indigomine

An indigo (blue-violet) theme for **Redmine 6.x** — a modernized, recolored fork of
[Bleuclair](https://github.com/farend/redmine_theme_farend_bleuclair) (GPLv2).

No build step required: compiled CSS/JS are included. Just drop it into `themes/`.

## What's different from Bleuclair

- **Indigo / blue-violet recolor** — header gradient, links and accents.
- **Lavender highlights** — replaces the light‑yellow hover/box/card backgrounds.
- **Tracker‑colored issue ID tags** in issue lists (indigo‑family per tracker) and
  **colored status text**.
- **Two‑part "picker" chip** for the issue detail title (tracker + number, right‑pointed
  ribbon) — powered by the bundled `javascripts/theme.js`.
- **Modern font stack** (BIZ UDPGothic / system‑ui), rounded cards, lighter borders, row hover.
- The **Simple Gantt** plugin picks up the theme colors via CSS variables (`--sg-*`).

## Install (Redmine 6.x)

1. Clone into your Redmine `themes/` directory:

   ```bash
   cd /path/to/redmine/themes
   git clone https://github.com/zero-platform-lab/indigomine.git
   ```

2. Restart Redmine (Propshaft regenerates the theme assets on boot).
3. **Administration → Settings → Display → Theme → Indigomine → Save**.

## License & credits

Distributed under the **GNU General Public License v2.0 (GPLv2)**, inherited from Bleuclair.
See [`LICENSE`](LICENSE) and [`NOTICE`](NOTICE).

- Original theme: **Bleuclair** by Far End Technologies (farend).
- Recolor and layout modifications: zero-platform-lab.
- Upstream (includes the SCSS source): <https://github.com/farend/redmine_theme_farend_bleuclair>
