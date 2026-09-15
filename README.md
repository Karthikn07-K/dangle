# 🧵 Dangle

> **A tiny charm for your desktop. A little motion for your day.**

[![Windows](https://img.shields.io/badge/Windows-10%2F11-0078D4?logo=windows&logoColor=white)]
[![Download Dangle](https://img.shields.io/badge/Download-Dangle%20for%20Windows-0078D4?logo=windows&logoColor=white)](https://github.com/Karthikn07-K/Dangle/releases/download/Dangle/Dangle.exe)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](#-license)

**Dangle** is an open-source Windows desktop companion that hangs from
the top of your screen, swings with pendulum physics, reacts to your
mouse, and lets you make the charm---and even the rope---your own.

It is deliberately small in spirit: no dashboard, no feed, no noise.

Just a little object that **moves when you move**.

------------------------------------------------------------------------

## ✨ The idea

Your desktop is where you spend hours every day.

Dangle adds one tiny thing to it:

``` text
                    🪢
                    │
                    │
                    │
                  ╲ │
                   ╲│
                    ⭐
                 ~~~~~~~
```

Move your mouse near it.

**It wiggles.**

Grab it.

**It swings.**

Flick it.

**It carries the momentum.**

Then leave it alone.

**It settles.**

Dangle is built around that simple interaction.

------------------------------------------------------------------------

## 🎬 What makes it different?

Dangle isn't just a static desktop widget.

### 🧵 The rope is part of the charm

Choose a built-in rope style or use your own transparent PNG.

Your rope can have its own:

-   Texture
-   Thickness
-   Length
-   Visual style
-   Curvature while swinging

The rope follows the pendulum motion instead of behaving like a fixed
line.

### 🖱️ It notices you

Move your mouse close to Dangle and it reacts with a subtle wiggle.

Drag it and the charm follows.

Flick it and the motion becomes a real swing.

### 🎨 Make it yours

Use built-in charms or create your own.

Custom charms can use your own artwork and optional sounds.

### 📦 Take your charms with you

Custom charms can be exported/imported as shareable `.luckycharm`
bundles.

A charm can become a tiny portable creation rather than a setting locked
to one installation.

------------------------------------------------------------------------

# 🌟 Features

  Feature                                
  -------------------------------------- ----
  🧵 Physics-driven hanging rope          ✅
  🪢 Custom rope PNG                      ✅
  🎨 Built-in rope presets                ✅
  🖼️ Custom PNG charms                    ✅
  🖱️ Drag & flick interaction             ✅
  ✨ Mouse-proximity wiggle               ✅
  🖥️ Multi-monitor support                ✅
  📍 Left / center / right positioning    ✅
  📏 Adjustable rope length               ✅
  🎛️ Physics controls                     ✅
  🔊 Custom charm sounds                  ✅
  📚 Custom charm library                 ✅
  📦 `.luckycharm` import/export          ✅
  ⭐ Favorites & random charm             ✅
  🔔 System tray controls                 ✅
  ⌨️ Global show/hide shortcut            ✅
  🔗 `dangle://` interaction              ✅
  🌙 Reduce-motion mode                   ✅
  🚀 Windows standalone EXE               ✅

------------------------------------------------------------------------

# 🪄 Built-in charm collection

Dangle includes a collection of original procedural charms such as:

**⭐ Lucky Star · 💎 Crystal · 🪙 Tiny Coin · 🐱 Lucky Cat · 👁️ Lucky
Eye · 🪷 Lotus · 🌙 Moon · 🔔 Bell · 🐉 Dragon · ☁️ Cloud · ❤️ Heart**

And because the charm system supports custom artwork, the collection
doesn't have to stop there.

------------------------------------------------------------------------

# 🧵 Make your own rope

Have a rope texture you love?

Use it.

### Recommended PNG

-   Transparent background
-   Vertical orientation
-   Rope centered in the image
-   Good contrast against your desktop
-   PNG with alpha transparency

Dangle processes the visible rope area so large transparent margins
don't turn your rope into a tiny line.

### Example

``` text
      PNG
       │
       ▼
┌──────────────┐
│              │
│      ║       │
│      ║       │
│      ║       │
│      ║       │
│              │
└──────────────┘
       │
       ▼
  Dangle crops
  the transparent
  margins
       │
       ▼
  curved rope
  follows physics
```

------------------------------------------------------------------------

# 🖥️ Download

## Windows

Download the latest **`dangle.exe`** from the GitHub Releases page.

### Portable version

Dangle is designed to run as a standalone Windows application.

1.  Download `dangle.exe`
2.  Place it somewhere convenient
3.  Run it
4.  Use the system tray icon to open Settings

### Desktop shortcut

If you use the Windows installer, choose the Desktop shortcut option
during installation.

For a portable EXE, you can also right-click `dangle.exe` → **Send to →
Desktop (create shortcut)**.

------------------------------------------------------------------------

# ⚡ Quick start

Launch Dangle and look near the top of your screen.

Then:

**Move close** → it wiggles\
**Click** → it reacts\
**Drag** → it follows\
**Flick** → it swings\
**Release** → physics takes over

Right-click the tray icon for the main controls.

------------------------------------------------------------------------

# ⚙️ Customize everything

Open **Settings** to tune the experience.

### Position

Choose:

-   Left
-   Top Center
-   Right
-   Custom

### Appearance

Adjust:

-   Charm size
-   Window opacity
-   Interaction message
-   Click particles

### Behavior

Adjust:

-   Gravity
-   Damping
-   Rope length
-   Maximum swing angle
-   Mouse-proximity wiggle
-   Proximity radius
-   Wiggle strength
-   Rope style
-   Custom rope PNG

### Audio

Control:

-   Master sound toggle
-   Volume
-   Per-charm click/bless sounds

### Performance

Use reduce-motion mode when you want a calmer, lighter experience.

------------------------------------------------------------------------

# 🧠 Designed around real motion

Dangle uses pendulum-style simulation rather than simply moving an image
from side to side.

Conceptually:

``` text
          anchor
             ●
             │\
             │ \
             │  \
             │   \
             │    ●
             │   charm
             │
        gravity ↓
```

The charm has:

-   Angle
-   Angular velocity
-   Gravity
-   Damping
-   Rope length
-   Maximum swing angle

Mouse movement can inject momentum into the system, creating a
natural-looking swing.

# 🧪 Project status

Dangle is an actively evolving open-source project.

The current Windows release focuses on:

-   Desktop interaction
-   Physics
-   Custom charms
-   Custom rope rendering
-   Lightweight system-tray behavior
-   Personalization

Future ideas include:

-   🧩 A community charm gallery
-   😀 Emoji charms
-   🧵 More rope materials
-   🖼️ More visual effects
-   🎭 Per-charm interaction styles
-   📱 Android companion
-   🍎 macOS support
-   🐧 Linux support
-   🛠️ A no-code charm/rope creator
-   🌐 Community-created charm packs

# 💙 Inspired by a simple idea

There is something satisfying about objects that react to the physical
world.

A hanging object swings.

A rope has tension.

Momentum carries motion.

And sometimes a tiny interaction is enough to make a desktop feel a
little more alive.

Dangle takes that idea and turns it into an open-source desktop toy that
you can modify, customize, share, and build upon.

**No productivity system.**

**No complicated dashboard.**

**Just a little thing hanging from your screen.**

------------------------------------------------------------------------

## ⭐ If you like Dangle

If Dangle makes your desktop a little more fun, consider:

⭐ **Star the repository**

🐛 **Report bugs**

💡 **Suggest ideas**

🧵 **Share a rope texture**

🎨 **Create a charm**

🤝 **Contribute**

------------------------------------------------------------------------

::: {align="center"}
### 🧵 Dangle

**Hang anything. Swing everything.**

Built with ❤️ by **Inspired.KN**
:::
