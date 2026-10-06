# Borozdov Blueline

A theme from the Borozdov collection. Two faces — light **Setsquare**, graphite pencil on
warm vellum, and dark **Erasure**, the same page rubbed down to a graphite ground with the
pencil marks left standing. Hairline rules, drafted right-angle corners, and inversion as
the only accent.

![Borozdov Blueline in light mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/blueline/main/screenshots/light.png)

![Borozdov Blueline in dark mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/blueline/main/screenshots/dark.png)

## Principles

- **No hue at all.** Every surface, border and label is graphite or vellum. State is never
  carried by colour — only by weight, a hairline and the one place the theme inverts.
- **Line weight over fill.** A hairline draws every rule, card edge and table frame; nothing
  is shaded to imply depth, the way a drafting sheet never shades what a line already says.
- **Drafted corners.** Callouts, code panes, buttons and popovers share the same sharp 2px
  radius — a setsquare's edge, never a soft card.
- **One inversion.** Graphite fill on Setsquare, vellum fill on Erasure, reserved for the
  filled button, the checked box and the caret — the single moment the whole page flips.
- **One serif flourish.** The note's own title and its first heading borrow a system serif;
  every other heading and all body text stay on the platform's own sans, so the flourish
  reads as punctuation, not decoration.

## Features

- Light and dark modes, following Settings → Appearance → Base color scheme
- Callouts, code blocks, tables and popovers drawn as the same hairline-rimmed panel
- Tags and property pills as flat, square badges that invert under the pointer
- Quiet editing: no focus ring around the note, its title or form fields while you type;
  property names read as labels, not boxed fields
- A toggle thumb tuned per face so it never disappears against its own track
- Text colours meet WCAG contrast on both faces
- The phone layout keeps the same colours and shapes
- No embedded fonts: the platform's own sans and a system serif carry everything, so the
  theme stays around 12 KB
- No `!important`: every rule can be overridden with a CSS snippet

## Installation

**From the community directory, as a variant:** this theme ships inside **Borozdov
Utility**. Install Borozdov Utility under Settings → Appearance → Themes → Manage, then
the [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin, and
choose **Blueline** under Style Settings → Borozdov Utility → Variant. The variant brings
this theme's palette, type and corners; its own layout, and its embedded font if it has
one, come with the full theme below.

**The full theme, by hand:** download `manifest.json` and `theme.css` from the
[latest release](https://github.com/borozdov-obsidian-themes/blueline/releases/latest) into
`<vault>/.obsidian/themes/Borozdov Blueline/`, then choose Borozdov Blueline under
Settings → Appearance → Themes.

## License

MIT — see [LICENSE](LICENSE).

---

**По-русски.** Тема из коллекции Borozdov. Два лика: светлый «Setsquare» — графитовый
карандаш на тёплом веленевом листе, и тёмный «Erasure» — тот же лист, стёртый до графитовой
основы, с оставшимся карандашным штрихом. Тонкие линии, чертёжные прямые углы и инверсия как
единственный акцент. Шрифты не встроены. В каталоге тема живёт вариантом Borozdov Utility: установите Borozdov Utility и плагин Style Settings, затем выберите Blueline в Style Settings → Borozdov Utility → Variant. Целиком, со своей вёрсткой, тема ставится вручную из последнего релиза репозитория.
