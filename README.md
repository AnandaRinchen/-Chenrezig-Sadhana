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

[View Live Site](https://<your-username>.github.io/chenrezig-sadhana/) · [Report an Issue](../../issues)

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
| V | **Prayer to the Six Realms** | རིགས་དྲུག་གི་སྨོན་ལམ། | Supplication to Chenrezig as Guru, Yidam, and Protector, followed by prayers for beings in each of the six realms. Attributed to **Gelong Pema Karpo** (Padma Karpo, 16th c.). |
| VI | **Mantra & Dedication** | སྔགས་དང་བསྔོ་བ། | Recitation of **Oṃ Maṇi Padme Hūṃ** (108, 1,000, or 10,000+ times), dissolution of the visualization, and dedication of merit. |
| VII | **Prayer for Dewachen** | བདེ་སྨོན། | The wondrous aspiration prayer for rebirth in Sukhāvatī (the Land of Bliss), invoking the triad of Amitābha, Avalokiteśvara, and Mahāsthāmaprāpta. |

---

## Features

- **Sacred Typography** — Noto Serif Tibetan, Cormorant Garamond, Crimson Pro, Noto Serif SC
- **Illuminated Design** — Parchment palette, saffron/maroon/gold, lotus mandala with HRĪḤ, Tibetan ornamental dividers
- **Six Mantra Jewels** — Interactive colored spheres in the five-wisdom colors
- **Thangka Art** — Four-Armed Chenrezig and Amitābha Pure Land paintings embedded
- **Author Attribution Cards** — Dignified portrait card for the compiler; historical cards for Gelongma Palmo and Gelong Pema Karpo
- **Floating Table of Contents** — Tap the ༄ button for quick navigation during practice sessions
- **Print-Ready** — Dedicated print stylesheet for shrine offerings
- **Single-File Deployment** — No build step, no frameworks, no dependencies

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
open index.html        # macOS
xdg-open index.html    # Linux
start index.html       # Windows
```

### 3. Deploy to GitHub Pages

1. Push to GitHub
2. Go to **Settings → Pages**
3. Under *Source*, select **Branch: `main`**, folder **`/ (root)`**, click **Save**
4. Live within ~60 seconds at: `https://<your-username>.github.io/chenrezig-sadhana/`

---

## File Structure

```
chenrezig-sadhana/
├── index.html                  # The complete digital pecha
├── khenpo-kunga-rinchen.jpg    # Compiler's portrait photo
├── chenrezig.png               # Thangka: Four-Armed Avalokiteśvara (§3)
├── dewachen.png                # Thangka: Amitābha Pure Land (§7)
├── README.md                   # This file
├── LICENSE                     # CC0 1.0 Universal
└── .gitignore                  # Git ignore rules
```

All files sit in the **same folder** — no subfolders needed. Upload everything to the repo root.

---

## Editing the Text

Each verse follows a simple four-div pattern:

```html
<div class="verse">
  <div class="bo">ཏིབེ་ཏན།</div>       <!-- Tibetan script -->
  <div class="ph">Phonetics</div>        <!-- Romanization -->
  <div class="en">English translation.</div>  <!-- English -->
  <div class="zh">中文译文。</div>        <!-- Chinese -->
</div>
```

To swap in a different lineage's recension, replace the text inside these divs — styling is automatic.

---

## Historical Authors

### Gelongma Palmo · དགེ་སློང་མ་དཔལ་མོ། · 比丘尼巴摩

The *bhikṣuṇī* Lakṣmī — an eleventh-century Kashmiri princess turned nun, revered as the founder of the Nyungne fasting practice. The Seven-Branch Prayer in §4 is her composition.

### Gelong Pema Karpo · དགེ་སློང་པདྨ་དཀར་པོ། · 比丘贝玛噶波

"White Lotus" — most notably the Fourth Gyalwang Drukpa (1527–1592), hierarch of the Drukpa Kagyü lineage. The Prayer to the Six Realms in §5 descends through the Chenrezig practice lineages.

---

## Translation Notes

- **Correction applied:** མཐུ་ཆེན་ཐོབ (*Thuchen-thob*) is **Mahāsthāmaprāpta** (大势至菩萨), not Vajrapāṇi.
- **Six Realms verses** follow the standard Karma Chagme / Thangtong Gyalpo lineage form.
- **Chinese** uses classical Buddhist register (佛经体) consistent with the Chinese Tripiṭaka.

---

## Contributing

Contributions welcome — translation corrections, lineage-specific recensions, accessibility improvements, additional languages. Open an [Issue](../../issues) first.

---

## Suggested Repository Settings

**Description:**
```
སྤྱན་རས་གཟིགས་ཀྱི་སྒྲུབ་ཐབས། A digital pecha of the Chenrezig (Avalokiteśvara) sadhana — four-line liturgical edition in Tibetan, phonetics, English, and Chinese. Edited by Khenpo Kunga Rinchen.
```

**Topics:**
```
buddhism, tibetan-buddhism, chenrezig, avalokiteshvara, sadhana, prayer, mantra, om-mani-padme-hum, dharma, meditation, pecha, liturgy, dewachen, sukhavati, tibetan-script, chinese-buddhism, translation
```

---

## License

Released under **CC0 1.0 Universal** — public domain. See [LICENSE](LICENSE).

---

<div align="center">

### སརྦ་མངྒ་ལཾ།
*Sarva Maṅgalaṃ*
#### 吉 祥 圆 满

*May all who encounter this text swiftly attain the state of Noble Avalokiteśvara,*
*and may every being without exception be established at that same ground.*

**ཨོཾ་མ་ཎི་པདྨེ་ཧཱུྃ།**

</div>
