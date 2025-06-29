# Omnic Summer

Omnic Summer is a Python-based, menu-driven utility that lets you quickly apply a wide range of PC performance tweaks. With dedicated categories for Graphic Enhancement, Network & Latency Reduction, and RAM & CPU Optimization—each containing 30 customizable scripts—Omnic Summer empowers users to streamline and boost their Windows experience. Whether you’re a gamer, a power user, or just want your computer running at its best, Omnic Summer provides safe, scriptable tweaks in a convenient package.

---

## Features

- **Easy Menu System:** Select and run tweak categories or the full bundle from a single interface.
- **Three Major Tweak Sets:**  
  - **Graphic Enhancer:** Improve visuals and display performance.
  - **Network & Latency Reduction:** Optimize network settings for lower ping and faster browsing.
  - **RAM & CPU Optimization:** Free up memory and CPU resources for better responsiveness.
- **Modular Design:** Each tweak is a separate function—easy to review, customize, or expand.
- **Open Source:** Community contributions are welcome!

---

## How to Use

### 1. Download or Clone the Repository

**With Git:**
```bash
git clone https://github.com/YOUR_USERNAME/omnic-summer.git
cd omnic-summer
```

**Or download ZIP:**  
Click "Code" > "Download ZIP", then extract the folder.

---

### 2. Run the Program

Make sure you have Python 3 installed.  
Open a terminal in the project folder and run:

```bash
python omnic_summer.py
```

---

### 3. Follow the Menu

You’ll see options like:

```
========= Omnic Summer =========
1. Graphic Enhancer (30 tweaks)
2. Network & Latency Reduction (30 tweaks)
3. RAM & CPU Optimization (30 tweaks)
4. Run ALL Tweaks (Full Bundle)
0. Exit
Select an option:
```

Enter the number for the tweak set you want, or run the full bundle.

---

## Customizing Tweaks

Each tweak is a function in its respective `.py` file (`graphic_enhancer.py`, `network_latency.py`, `ram_cpu.py`).  
You can:
- Edit tweak functions to suit your system or needs.
- Add new tweaks by defining new functions and including them in the tweak list.
- Remove or comment out tweaks you don’t want.

---

## Contributing

1. Fork this repository.
2. Add or improve tweaks (please document changes!).
3. Submit a pull request with a clear description.

---

## Safety Notice

- **Review All Tweaks:** Before running on your main PC, read through the tweak functions to ensure you’re comfortable with the changes.
- Most tweaks are safe, but always **backup important data** before modifying system settings.
- Omnic Summer is provided as-is, without warranty.

---

## License

MIT License.  
See [LICENSE](LICENSE) for details.

---

Enjoy a faster, smoother PC with Omnic Summer!
