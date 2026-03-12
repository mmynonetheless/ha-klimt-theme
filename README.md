# 🎨 Gustav Klimt Theme for Home Assistant

Transform your Home Assistant dashboard into a work of art with this theme inspired by the **Golden Period** of Gustav Klimt (1862-1918), the legendary Austrian symbolist painter and co-founder of the Vienna Secession movement.

## 🖼️ About the Artist

**Gustav Klimt** is renowned for his highly decorative style, particularly his "Golden Phase" characterized by:
- **Gold leaf** applications (most famous in "The Kiss" and "Portrait of Adele Bloch-Bauer I")
- **Byzantine mosaic** influences
- **Art Nouveau** flowing lines and organic forms
- **Rich jewel tones** and warm earth colors
- **Symbolic and allegorical** content

This theme captures the essence of his Vienna workshop, where modern functionality meets timeless Art Nouveau beauty.

## ✨ Theme Features

| Element | Klimt Inspiration | Visual Effect |
|---------|-------------------|---------------|
| **Gold Primary** | "The Kiss" gold leaf backgrounds | Buttons and accents glow like precious metal |
| **Warm Brown Base** | Aged canvas and wood tones | Creates warmth like a vintage painting |
| **Geometric Patterns** | Byzantine mosaics and Stoclet Frieze | Subtle diagonal lines mimic mosaic tesserae |
| **Square Cards** | Klimt's 180×180cm square format | Balanced, iconic compositions |
| **Jewel Tone Accents** | Landscapes and floral patterns | Rich greens and oranges for charts |
| **Asymmetric Borders** | Art Nouveau flowing lines | Organic, non-rectilinear feel |
| **Patterned Backgrounds** | "The Kiss" textile patterns | Subtle texture behind cards |

## 🎨 Color Palette

| Color | Hex | Use | Klimt Reference |
|-------|-----|-----|-----------------|
| **Rich Gold** | `#d4af37` | Primary accents, buttons, active states | Gold leaf in "The Kiss" |
| **Dark Gold** | `#b8860b` | Secondary accents, icons, dividers | Deep gold backgrounds |
| **Ochre Brown** | `#2c1e0e` | Primary background | Aged canvas |
| **Warm Brown** | `#342113` | Card backgrounds | Wood panels |
| **Parchment** | `#f5e6d3` | Primary text | Aged paper |
| **Forest Green** | `#2e5c4b` | Success states, charts | Landscapes |
| **Terra Cotta** | `#9b5e3c` | Error/warning states | Earth tones |

## 📦 Installation

### HACS Installation (Recommended)

1. Make sure [HACS](https://hacs.xyz/) is installed
2. Go to **HACS → Frontend**
3. Click the three dots (top right) → **"Custom repositories"**
4. Add this repository URL with category **"Theme"**:
https://github.com/mmynonetheless/ha-klimt-theme

text
5. Click **"Explore & Download Repositories"**
6. Search for **"Klimt Theme"** and download
7. **Restart** Home Assistant

### Manual Installation

1. Download the `themes/klimt.yaml` file from the latest release
2. Place it in your Home Assistant `/config/themes/` directory
3. Add to your `configuration.yaml` (if not already present):
```yaml
frontend:
  themes: !include_dir_merge_named themes
