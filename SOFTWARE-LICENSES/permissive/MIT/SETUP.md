# MIT License - Setup Instructions

## Quick Start

### Option 1: Automated Copy
```bash
# Copy to your project root
cp LICENSE.txt ../../../LICENSE
```

### Option 2: Manual Setup

1. **Create a LICENSE file** in your repository root (no extension)
2. **Copy the text** from `LICENSE.txt`
3. **Update the copyright line** with your name and year:
   ```
   Copyright (c) 2026 Your Company
   ```
4. **Commit to git**:
   ```bash
   git add LICENSE
   git commit -m "Add MIT License"
   ```

---

## Verify Installation

Your repository should have:
```
your-repo/
├── LICENSE                 # MIT License text
├── README.md
└── ...
```

To verify the license is readable:
```bash
head -5 LICENSE
# Should show: MIT License
#              Copyright (c) 2026 Your Company
```

---

## What to Modify

Only change **this line**:
```
Copyright (c) 2026 Sistema Global de Licencias Terrestres
```

To:
```
Copyright (c) [YEAR] [YOUR NAME OR ORGANIZATION]
```

**Everything else stays the same.**

---

## Common Questions

**Q: Do I need to include the license in every file?**  
A: No. Just include the LICENSE file in your repository root. Optional: add a header comment to source files.

**Q: Can I use this for commercial projects?**  
A: Yes. The MIT License explicitly permits commercial use.

**Q: Do I need to share my source code?**  
A: No. The MIT License is permissive. You can distribute binaries only if you want.

---

## Need Help?

- See `README.md` for a complete overview
- See `manifest.json` for machine-readable license data
- Visit [OpenSource.org](https://opensource.org/licenses/MIT) for official details
