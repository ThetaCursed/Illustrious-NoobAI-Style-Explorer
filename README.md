# Illustrious XL & NoobAI-XL Style Explorer 🎨

<p align="center">
  <img src="images/Illustrious XL & NoobAI-XL Style Explorer.png" alt="Illustrious XL &amp; NoobAI-XL Style Explorer Banner" width="800">
</p>
<p align="center">
  <img src="images/Illustrious XL & NoobAI-XL Style Explorer - Favorites Tab.png" alt="Illustrious XL &amp; NoobAI-XL Style Explorer - Favorites Tab" width="800">
</p>
<p align="center">
  <img src="images/Illustrious XL & NoobAI-XL Style Explorer - Swipe-mode.png" alt="Illustrious XL &amp; NoobAI-XL Style Explorer Swipe Mode" width="800">
</p>

## 🚀 Overview

The **Illustrious XL & NoobAI-XL Style Explorer** is a high-performance interactive visual library created specifically for AI artists and prompt engineers working with **Illustrious XL** (by OnomaAI Research) and **NoobAI-XL** (by Laxhar Lab).

It gives you instant visual previews of over **16,000+ Danbooru artist tags**, dataset strength indicators, and one-click optimized artist tags that work **perfectly in both models**. No more guessing — see exactly how each artist style renders before you generate.

Every style in this explorer is 100% compatible between Illustrious XL and NoobAI-XL, giving you maximum flexibility whether you prefer the community-favorite base model or the advanced V-Prediction fine-tune.

## 🛠️ Key Features
*   **Visual Search & Filtering:**  
    Instantly search 16,000+ artist styles by name. Jump to artists by dataset size (`Works`) or **Uniqueness Rank**.

*   **Advanced Sorting:**  
    Sort alphabetically, by number of training images, by stylistic uniqueness, or randomize to discover hidden gems.

*   **Favorites & Folder System:**  
    Save favorites with one click (stored locally in IndexedDB). Organize into custom folders with drag-and-drop and multi-select (`Ctrl+Click`).

*   **Import / Export:**  
    Export favorites as `.json` or simple `.txt` lists of artist names. Import previously saved collections.

*   **Customizable Gallery:**  
    Adjustable grid from 4 to 10 columns (slider + hotkeys `4`-`0`).

*   **One-Click Prompt Copy:**  
    Click any card to instantly copy the exact artist name ready for Stable Diffusion, ComfyUI, or Forge.

*   **Focused Swipe Mode:**  
    Distraction-free full-screen browsing. Automatically skips already-favorited artists. Hotkeys: `←` `→` (navigate), `C` (copy), `↓` (favorite), `Esc` (close). Start from any card with middle-click.

*   **High Performance & Fully Offline:**  
    Lightweight Vanilla JS + optimized WebP images. The entire ~900 MB app runs completely offline after download.

## 💾 Offline Usage
Run the explorer locally on any computer — no internet required.

1. **Download the project:**
   - **Direct ZIP:** [Download latest release](https://github.com/ThetaCursed/Illustrious-NoobAI-Style-Explorer/archive/refs/heads/main.zip)
   - **Git clone:** `git clone https://github.com/ThetaCursed/Illustrious-NoobAI-Style-Explorer.git`

2. Unzip (if needed).

3. Open `index.html` in any modern browser.

## 💻 Technical Stack
- **Core Models:** **Illustrious XL** (OnomaAI) + **NoobAI-XL** (Laxhar Lab)
- **Tagging System:** Normalized Danbooru tags (fully compatible with both models)
- **Frontend:** HTML5, CSS3 (Flexbox + Grid), Vanilla JavaScript
- **Storage:** IndexedDB (favorites & folders saved locally)

## 🤝 Acknowledgments
- **OnomaAI Research** — creators of the massively popular **Illustrious XL**
- **Laxhar Lab** — developers of the powerful **NoobAI-XL** fine-tune
- The entire **Danbooru** community for the incredible tagging ecosystem

## 📄 License
This project is open-source and provided as a free visual reference tool for educational and artistic purposes.