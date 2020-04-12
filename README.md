# ibus-keyboards
Extra keyboard layouts for IBUS

# Summary
`.mim` files define IMEs for ibus-m17n. Ibus did not have support for Icelandic so I created my own. My primary resource for creating these files was https://www.nongnu.org/m17n/manual-en/m17nDBTutorial.html

# Currently Implemented
- [x] Standard keys
- [x] Long Vowel Accent keys
- [x] Umlaut and `å` keys
- [ ] Alt-Gr keys

# Manual Installation
There are two options for installing these layouts.

### Installing for a single user
Copy the `.mim` file into `~/.m17n.d` and restart ibus (`ibus-daemon -rdx`)

### Installing system-wide (requires root)
Copy the `.mim` file into `/usr/share/m17n` and restart ibus (`ibus-daemon -rdx`)

# Conclusion
That's it! It's fairly simple. One last request: I'm not sure how these mappings behave on non-US keyboards, so please reach out to me if there are problems.
