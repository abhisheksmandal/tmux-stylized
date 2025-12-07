# 🌟 TMUX CONFIGURATION --- STYLIZED README

A clean, powerful, and modern tmux configuration with intuitive shortcuts, improved navigation, and full mouse + clipboard support.

---

## 🚀 Features

✔ 256-color support  
✔ Intuitive pane/window navigation  
✔ Vim-style copy mode with system clipboard  
✔ Beautiful status bar  
✔ Mouse mode enabled  
✔ Sessionizer integration  
✔ Smart keybindings for productivity

---

## 🔧 Installation

Save this configuration as your `~/.tmux.conf` file:

```bash
cp tmux.conf ~/.tmux.conf
tmux source-file ~/.tmux.conf
```

---

## 🎮 Keybindings Overview

### 🧠 Prefix Keys

- **Main Prefix:** `Ctrl + j`
- **Secondary Prefix:** `Ctrl + f`

---

### 🔲 Pane Navigation (No Prefix Needed)

| Action           | Keys      |
|------------------|-----------|
| Focus left pane  | `Alt + ←` |
| Focus right pane | `Alt + →` |
| Focus upper pane | `Alt + ↑` |
| Focus lower pane | `Alt + ↓` |

---

### ➗ Split Windows

| Action             | Keys         |
|--------------------|--------------|
| Split vertically   | `Prefix + v` |
| Split horizontally | `Prefix + h` |

---

### 🔀 Window Navigation

| Action          | Keys        |
|-----------------|-------------|
| Previous window | `Shift + ←` |
| Next window     | `Shift + →` |

---

### 🔃 Reorder Windows

| Action            | Keys                |
|-------------------|---------------------|
| Move window left  | `Ctrl + Shift + ←` |
| Move window right | `Ctrl + Shift + →` |

---

### 📡 Synchronize Panes

```
Prefix + y
```

---

### 🔄 Reload Configuration

```
Prefix + r
```

---

### 🧹 Clear Scrollback

```
Shift + L
```

---

## 📋 Copy / Paste

### Inside Copy Mode (Vim keys)

- Start selection → `v`
- Copy to clipboard → `y`
- Paste → `p`
- Mouse drag → auto copy

---

## 🐁 Mouse Mode

- Click to switch panes
- Scroll to enter copy-mode
- Drag to resize
- Mouse selection copies via xclip

---

## 🎨 Status Bar

**Left side shows:**
```
💻 HOSTNAME [SESSION]
```

**Right side shows:**
```
🕔 HH:MM
```

---

## 🧰 Sessionizer

Open with:
```
Prefix + f
```
or
```
Ctrl + f
```

---

## 📝 License

MIT --- Feel free to use, modify, or share.

---

## ❤️ Credits

Created with a focus on productivity and aesthetics.
