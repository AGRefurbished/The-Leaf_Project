from pathlib import Path

readme_content = """
# 🌿 The Leaf Project

A low-tech, sustainable water condensation system that turns **steam into usable water** using nothing more than synthetic leaves and gravity — no electricity or machines needed.

Inspired by nature and middle school science, **The Leaf Project** is part of a broader initiative to reduce AI’s environmental impact through creative, energy-free cooling methods.

---

## 🧠 Concept Sketch

![Concept Sketch of Condensation Chamber](schematic/concept_sketch_condensation_chamber.png)

*Steam rises into the chamber, condenses on angled synthetic leaves (made of heat-resistant silicone), and drips into a collection container. Excess pressure escapes via a relief valve.*

---

## 🌎 Why It Matters

- 🌊 **No freshwater required** — uses saltwater or wastewater
- ⚡ **No power draw** — relies on basic physics, not fans or chillers
- 🌀 **Closed-loop idea** — can cycle vapor locally or return to cooling loop
- 🧩 **Modular & Scalable** — ideal for pairing with AI data centers in remote or coastal areas

---


## 📚 Learn More
- [Google Cloud Skills Boost Profile](https://www.cloudskillsboost.google/public_profiles/a32749a5-8963-4278-99e4-f2266038458f)
- [Prompt Playground](https://github.com/AGRefurbished/prompt-playground)

---

## 💬 Contribute
Got improvements? 3D designs? Want to prototype?  
Feel free to fork the repo, open a pull request, or [reach out](mailto:mali198919@yahoo.com).

---

**“Simple ideas solve big problems.”**
"""

# Save the README to a file
readme_path = Path("/mnt/data/README.md")
readme_path.write_text(readme_content.strip())

readme_path
