# ROR2 Modding GUI

The ROR2 Modding GUI is a Tauri-based program that acts as a front end for the Command Line r2mod tool for Linux.

# DISCLAIMER:
### This is my first real project like this and it is nowhere near done so you probably shouldn't use it

# Building

Dependancies:
Rust
Tauri

1. Clone the repository
```bash
git clone https://github.com/Violets-puragtory/Ror2-Modding-Gui 
```

2. Install tauri-cli (if not already installed)
```bash
cargo install tauri-cli
``` 
3. Build
```bash
cd Ror2-Modding-Gui
cargo tauri build
```

# To-Do

- [x] Allow launching ROR2 with mods
- [x] Allow launching ROR2 without mods
- [ ] Implement mod search
- [ ] Implement GTK theme support
- [ ] Implement installation of mods
- [ ] eat a cookie