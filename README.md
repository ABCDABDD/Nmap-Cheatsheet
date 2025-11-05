# Nmap Enumeration Guide Repository 🌊  
**by:** [@blindma1den](https://github.com/blindma1den)

A practical, hands-on Nmap enumeration guide — packed with copy-paste commands, workflows, AD tips, and cheat-sheets for authorized pentesting.

---

## What this repo contains
This repo contains a comprehensive Nmap guide (`Nmap_Enumeration_Guide_by_blindma1den.md`), a one-page cheatsheet, example scan scripts, and helper utilities for parsing Nmap outputs. Everything is organized so you can quickly reference commands during labs or in the field.

---

## Quick start
1. Clone the repo:
```bash
git clone https://github.com/<your-username>/nmap-enum-guide.git
cd nmap-enum-guide
```

2. Read the full guide:
- `Nmap_Enumeration_Guide_by_blindma1den.md` — full, detailed guide for Nmap enumeration.

3. Use the `examples/` scripts to run quick scans (edit targets and rates before running):
```bash
bash examples/quick_recon.sh <target>
bash examples/full_tcp_scan.sh <target>
```

---

## Files & structure
```
nmap-enum-guide/
├─ README.md                       # this file
├─ Nmap_Enumeration_Guide_by_blindma1den.md  # full guide
├─ CHEATSHEET.md                   # quick reference (one-pager)
├─ examples/                       # ready-to-run example scripts
├─ scripts/                        # parsing and helper scripts
└─ resources/                      # notes, NSE tips, references
```

---

## Usage notes & safety
- This content is for **educational purposes and authorized testing only**. Do not scan machines you do not own or have explicit written permission to test.  
- Adjust timing (`-T`) and rate (`--min-rate`) to avoid disrupting production systems.  
- Review NSE scripts with `nmap --script-help <script>` before running them.

---

## Contributing
Pull requests welcome. If you add scripts or resources, include clear documentation and safe defaults. Keep examples non-destructive and lab-focused.

---

## License
This repo is provided under the MIT License — see `LICENSE` for details.

---

## Contact
Questions or suggestions? Open an issue or reach out via GitHub: [@blindma1den](https://github.com/blindma1den).
Feel free to contact me if you can add something useful!
Happy hacking!

By: @blindma1den

---

