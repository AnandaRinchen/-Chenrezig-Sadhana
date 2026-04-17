<div align="center">

# ཨོཾ་མ་ཎི་པདྨེ་ཧཱུྃ།

# The Practice of Noble Avalokiteśvara
### སྤྱན་རས་གཟིགས་ཀྱི་སྒྲུབ་ཐབས། · 四臂观音修持仪轨

**A Digital Pecha — Four-Line Liturgical Edition**

*Tibetan · Phonetics · English · Chinese*

---

**Edited & Finalized by Khenpo Kunga Rinchen**<br>
མཁན་པོ་ཀུན་དགའ་རིན་ཆེན་གྱིས་རྩོམ་སྒྲིག་དང་ཞུས་ཆེན་བགྱིས།<br>
贡噶·仁钦堪布 编校

---

[View Live Site](https://<your-username>.github.io/chenrezig-sadhana/) · [Download PDF](#printing) · [Report an Issue](../../issues)

</div>

---

## About This Project

This is a **digital pecha** (དཔེ་ཆ) — a web-based illuminated manuscript presenting the complete Chenrezig (Avalokiteśvara) sadhana in a four-line parallel format designed for daily practice, study, and reference.

Every verse is rendered in four layers:

| Layer | Script | Purpose |
|-------|--------|---------|
| **Line 1** | **Tibetan** (བོད་ཡིག) | Root liturgical text in Noto Serif Tibetan |
| **Line 2** | *Phonetics* | THL-style romanization for chanting |
| **Line 3** | English | Refined liturgical translation |
| **Line 4** | 中文 | Classical Buddhist Chinese (佛经体) |

This format allows practitioners of any background — Tibetan readers, Western students using phonetics, Chinese Buddhist communities, or scholars — to follow the practice side by side in a single, elegant page.

---

## Contents of the Practice

| § | Section | Tibetan | Description |
|---|---------|---------|-------------|
| I | **Refuge & Bodhicitta** | སྐྱབས་འགྲོ་སེམས་བསྐྱེད། | Taking refuge in the Three Jewels and generating the mind of enlightenment. Recited 3×. |
| II | **The Four Immeasurables** | ཚད་མེད་བཞི། | Loving-kindness (བྱམས་པ), compassion (སྙིང་རྗེ), sympathetic joy (དགའ་བ), and equanimity (བཏང་སྙོམས). The four *brahmavihāras*. Recited 3×. |
| III | **Deity Visualization** | ལྷ་བསྐྱེད། | Visualizing Four-Armed Avalokiteśvara arising from the seed syllable HRĪḤ upon a white lotus and moon disc — radiant white, adorned with silks and jewels, crowned by Amitābha. |
| IV | **Seven-Branch Prayer** | ཡན་ལག་བདུན་པ། | Prostration, offering, confession, rejoicing, requesting the turning of the Dharma wheel, beseeching not to pass into nirvāṇa, and dedication. Composed by **Gelongma Palmo** (Bhikṣuṇī Lakṣmī, 11th c. Kashmir). |
| V | **Prayer to the Six Realms** | རིགས་དྲུག་གི་སྨོན་ལམ། | Supplication to Chenrezig as Guru, Yidam, and Protector, followed by prayers for beings in each of the six realms — gods (pride), demigods (jealousy), humans (desire), animals (ignorance), hungry ghosts (avarice), and hell beings (hatred). Attributed to **Gelong Pema Karpo** (Padma Karpo, 16th c.). |
| VI | **Mantra & Dedication** | སྔགས་དང་བསྔོ་བ། | Recitation of **Oṃ Maṇi Padme Hūṃ** (108, 1,000, or 10,000+ times), dissolution of the visualization, and dedication of merit. |
| VII | **Prayer for Dewachen** | བདེ་སྨོན། | The wondrous aspiration prayer for rebirth in Sukhāvatī (the Land of Bliss), invoking the triad of Amitābha, Avalokiteśvara, and Mahāsthāmaprāpta. |

---

## Features

**Sacred Typography**
- Tibetan script rendered in *Noto Serif Tibetan* at generous size for readability
- English display headings in *Cormorant Garamond*; body in *Crimson Pro*
- Chinese in *Noto Serif SC* with classical Buddhist register and spacing

**Illuminated Design**
- Warm parchment palette with monastic saffron, deep maroon, and burnished gold
- Central lotus mandala with slowly rotating outer petals and HRĪḤ seed syllable
- Gold Tibetan ornamental dividers (༄༅ · ❀) between sections
- Subtle paper-grain texture overlay for manuscript feel

**Six Mantra Jewels**
- Oṃ Maṇi Padme Hūṃ rendered as six interactive spheres in the traditional five-wisdom colors: white, green, yellow, blue, red, and dark — each corresponding to the purification of one of the six afflictions

**Author Attribution Cards**
- Dignified portrait-style card for the compiler with circular photo
- Historical author cards for Gelongma Palmo and Gelong Pema Karpo with contextual notes

**Practice-Ready**
- Floating Table of Contents (tap the ༄ button) for quick navigation during sessions
- Clear rubric instructions ("Recite three times," "Recite 108 times…")
- Print stylesheet for clean paper output suitable for shrine offerings

**Image Slots**
- Two bordered thangka frames (§3 and §7) with SVG placeholders — swap your own sacred art with a single `<img>` tag

**GitHub Pages Ready**
- Single-file deployment — no build step, no frameworks, no dependencies
- Google Fonts load from CDN; all decorative art is inline SVG
- Responsive from mobile phones to wide desktop monitors

---

## Quick Start

### 1. Clone the Repository

```bash
git clone https://github.com/<your-username>/chenrezig-sadhana.git
cd chenrezig-sadhana
```

### 2. View Locally

Simply open `index.html` in any browser — no server needed:

```bash
# macOS
open index.html

# Linux
xdg-open index.html

# Windows
start index.html
```

### 3. Deploy to GitHub Pages

1. Push to GitHub:
   ```bash
   git add .
   git commit -m "Initial commit: Chenrezig Sadhana digital pecha"
   git push origin main
   ```
2. Go to **Settings → Pages**
3. Under *Source*, select **Branch: `main`**, folder **`/ (root)`**, then click **Save**
4. Your site will be live within ~60 seconds at:
   ```
   https://<your-username>.github.io/chenrezig-sadhana/
   ```

---

## File Structure

```
chenrezig-sadhana/
├── index.html                  # The complete digital pecha (single-file)
├── khenpo-kunga-rinchen.jpg    # Compiler's portrait photo
├── README.md                   # This file
├── LICENSE                     # CC0 1.0 Universal
├── .gitignore                  # Git ignore rules
└── images/                     # (Optional) Your own thangka images
    ├── chenrezig.jpg           #   → Four-Armed Avalokiteśvara (§3)
    └── dewachen.jpg            #   → Amitābha / Sukhāvatī (§7)
```

---

## Adding Your Own Thangka Images

Two image frames are built into the page — one in §3 (Deity Visualization) and one in §7 (Dewachen Prayer). They currently display elegant SVG lotus placeholders.

### Steps

1. **Create** an `images/` folder in the repo root
2. **Add** your images (recommended: **600 × 800 px**, 3:4 ratio, JPG or PNG)
3. **Open** `index.html` and search for `<!-- <img src=`
4. **Uncomment** the `<img>` tag by removing `<!-- ` and ` -->`:

```html
<!-- Before -->
<!-- <img src="images/chenrezig-thangka.jpg" alt="Four-armed Chenrezig thangka"> -->

<!-- After -->
<img src="images/chenrezig-thangka.jpg" alt="Four-armed Chenrezig thangka">
```

The SVG placeholder automatically hides when your image loads.

### Where to Find Public-Domain Thangkas

| Source | Notes |
|--------|-------|
| [Wikimedia Commons — Avalokiteshvara](https://commons.wikimedia.org/wiki/Category:Avalokiteshvara) | Many CC-licensed thangka images |
| [Wikimedia Commons — Amitābha](https://commons.wikimedia.org/wiki/Category:Amit%C4%81bha) | Pure Land imagery |
| [Rubin Museum Collection](https://rubinmuseum.org/collection) | High-quality; check licensing per image |
| [Himalayan Art Resources](https://www.himalayanart.org) | Scholarly reference; request permission |

---

## Editing the Text

All liturgical content lives directly in `index.html` with clearly labeled section markers:

```html
<!-- ═══════════════════════════════════════════════ -->
<!-- SECTION 4: SEVEN-BRANCH PRAYER                   -->
<!-- ═══════════════════════════════════════════════ -->
```

Each verse follows a simple four-div pattern:

```html
<div class="verse">
  <div class="bo">ཏིབེ་ཏན།</div>       <!-- Tibetan script -->
  <div class="ph">Phonetics</div>        <!-- Romanization -->
  <div class="en">English translation.</div>  <!-- English -->
  <div class="zh">中文译文。</div>        <!-- Chinese -->
</div>
```

To swap in a different lineage's recension (Mindrolling, Drikung, Karma Kagyü, etc.), simply replace the text inside these four divs — all styling is applied automatically.

### CSS Classes Reference

| Class | Purpose |
|-------|---------|
| `.bo` | Tibetan script (Noto Serif Tibetan, maroon) |
| `.ph` | Phonetics (Cormorant Garamond italic, muted) |
| `.en` | English translation (Crimson Pro, dark ink) |
| `.zh` | Chinese translation (Noto Serif SC, maroon) |
| `.verse` | Single verse block with left saffron border |
| `.verse-group` | Group of verses under a sub-heading |
| `.rubric` | Stage direction / practice instruction (italic saffron) |
| `.author-card` | Historical author attribution with ornamental corners |
| `.compiler-card` | Compiler attribution with portrait photo |
| `.image-frame` | Thangka image placeholder with maroon/saffron border |
| `.mantra-display` | Mantra section with colored syllable jewels |
| `.section-header` | Section title block (number + English + Tibetan + Chinese) |

---

## Printing

The page includes a dedicated **print stylesheet**. To create a physical copy:

1. Open the page in your browser
2. Press `Ctrl+P` (or `Cmd+P` on Mac)
3. Set margins to *Minimum* or *None*
4. Enable *Background Graphics* for the gold ornaments and saffron borders
5. Print or *Save as PDF*

The floating TOC button and navigation are automatically hidden in print.

---

## Translation & Editorial Notes

- **Phonetics** follow a standardized THL-style (Tibetan & Himalayan Library) romanization, lightly adjusted for ease of chanting by non-Tibetan speakers.
- **English** has been carefully smoothed for liturgical rhythm — the goal is a translation that *sounds* like a prayer when read aloud, while remaining faithful to the Tibetan line-by-line.
- **Chinese** has been refined toward classical Buddhist register (佛经体), using terminology consistent with the Chinese Tripiṭaka tradition: 观自在 for Avalokiteśvara, 无量光 for Amitābha, 大势至 for Mahāsthāmaprāpta.
- **Correction applied:** In §7 (Dewachen Prayer), མཐུ་ཆེན་ཐོབ (*Thuchen-thob*) is correctly identified as **Mahāsthāmaprāpta** (大势至菩萨), not Vajrapāṇi. The Dewachen triad is Amitābha flanked by Avalokiteśvara and Mahāsthāmaprāpta, as per the *Sukhāvatīvyūha* sūtras.
- **Six Realms verses** (§5) follow the standard Karma Chagme / Thangtong Gyalpo lineage form.

---

## Historical Authors

### Gelongma Palmo · དགེ་སློང་མ་དཔལ་མོ། · 比丘尼巴摩

The *bhikṣuṇī* Lakṣmī — known in Tibetan as Gelongma Palmo — was an eleventh-century **Kashmiri princess** turned nun. Stricken with leprosy, she retreated to solitary practice and attained direct realization of Avalokiteśvara through unbroken devotion. She is revered as the **founder of the Nyungne (སྙུང་གནས) fasting practice**, one of the most widely observed purification rituals in Tibetan Buddhism. The Seven-Branch Prayer in §4 is her composition.

### Gelong Pema Karpo · དགེ་སློང་པདྨ་དཀར་པོ། · 比丘贝玛噶波

"White Lotus" (Padma Karpo) — a name borne by several eminent masters. The most renowned is the **Fourth Gyalwang Drukpa (1527–1592)**, hierarch of the Drukpa Kagyü lineage and one of Tibet's most prolific authors. The Prayer to the Six Realms in §5 descends through the Chenrezig practice lineages, invoking the Great Compassionate One to deliver beings from each realm to the pure land of Potala.

---

## Contributing

Contributions are welcome, especially:

- **Translation corrections** — if you spot a Tibetan–English or Tibetan–Chinese discrepancy
- **Lineage-specific recensions** — variant verse texts from Nyingma, Sakya, Gelug, or other Kagyü sub-schools
- **Accessibility improvements** — screen reader support, high-contrast mode, etc.
- **Additional languages** — Korean, Japanese, Vietnamese, or other Buddhist translation traditions

Please open an [Issue](../../issues) to discuss before submitting a Pull Request. For textual changes, cite your source edition if possible.

---

## Suggested Repository Settings

When setting up this repo on GitHub, consider the following:

**Repository Description:**
```
སྤྱན་རས་གཟིགས་ཀྱི་སྒྲུབ་ཐབས། A digital pecha of the Chenrezig (Avalokiteśvara) sadhana — four-line liturgical edition in Tibetan, phonetics, English, and Chinese. Edited by Khenpo Kunga Rinchen.
```

**Topics / Tags:**
```
buddhism, tibetan-buddhism, chenrezig, avalokiteshvara, sadhana, prayer, mantra,
om-mani-padme-hum, dharma, meditation, pecha, liturgy, four-immeasurables,
dewachen, sukhavati, tibetan-script, chinese-buddhism, translation
```

**Website URL:**
```
https://<your-username>.github.io/chenrezig-sadhana/
```

---

## License

The liturgical content is part of a living Buddhist tradition and freely offered to all practitioners and sentient beings. The web design, compiled translations, and editorial work are released under **CC0 1.0 Universal** — free for use, modification, and distribution worldwide without restriction.

See [LICENSE](LICENSE) for full text.

---

## Acknowledgments

- **Khenpo Kunga Rinchen** (མཁན་པོ་ཀུན་དགའ་རིན་ཆེན།) for compiling, editing, and finalizing this four-line edition
- **Gelongma Palmo** and **Gelong Pema Karpo** for the original compositions
- The countless lineage holders who transmitted and preserved these prayers across centuries
- [Google Fonts](https://fonts.google.com/) for *Noto Serif Tibetan*, *Noto Serif SC*, *Cormorant Garamond*, and *Crimson Pro*
- All sentient beings, for whom this practice is undertaken

---

<div align="center">

### སརྦ་མངྒ་ལཾ།
*Sarva Maṅgalaṃ*
#### 吉 祥 圆 满

*May all who encounter this text swiftly attain the state of Noble Avalokiteśvara,*
*and may every being without exception be established at that same ground.*

---

**ཨོཾ་མ་ཎི་པདྨེ་ཧཱུྃ།**

</div>
