# Custom KDE Panels

This is my first custom KDE panel.  I call it HUD and it just puts a
panel at 50% of screen size at the top of the screen.  I has the
following widgets:

* Kicker (Application Menu)
* Show Desktop
* Present Windows
* Application Title
* Spacer
* Virtual Desktop Bar
* Fokus
* System Tray
* Digital Clock
* User Switcher

# To install

```
kpackagetool5 -t Plasma/LayoutTemplate --install org.kde.plasma.desktop.hudPanel
```

# To remove

```
kpackagetool5 -t Plasma/LayoutTemplate -r org.kde.plasma.desktop.hudPanel
```
