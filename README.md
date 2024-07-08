# Minimal Clock
A simple and versatile clock skin for [Rainmeter](https://www.rainmeter.net/).

![Preview_1](https://github.com/Gamba04/Minimal-Clock/assets/63524957/e05bea9c-73d2-4ef3-9bed-280e98fc0d60 "Preview 1")
![Preview_2](https://github.com/Gamba04/Minimal-Clock/assets/63524957/676bf965-1952-4ac6-bb61-2f2ff78359e1 "Preview 2")

# Setup
**Minimal Clock** has a series of variables designed for easy configuration.

```
[Variables]
Color="FFFFFF"
Font="Segoe UI"
ShowSeconds=0
ShowDate=1
Size=2
Spacing=(6 * #Size#)
BigFontSize=(45 * #Size#)
MediumFontSize=(18 * #Size#)
SmallFontSize=(12 * #Size#)
```

## Color
```
Color="FFFFFF"
```

Changes the $\textsf{{\color[rgb]{1.0, 0.47, 0.34}c}{\color[rgb]{1.0, 0.52, 0.32}o}{\color[rgb]{1.0, 0.57, 0.29}l}{\color[rgb]{1.0, 0.62, 0.27}o}{\color[rgb]{1.0, 0.68, 0.24}r}}$ of the clock.

**Possible values:**
- **RRGGBB** $\textcolor{Gray}{\textsf{(hex value)}}$
- **RRGGBBAA** $\textcolor{Gray}{\textsf{(hex value with alpha)}}$
- **R, G, B** $\textcolor{Gray}{\textsf{(decimal value from 0-255)}}$
- **R, G, B, A** $\textcolor{Gray}{\textsf{(decimal value from 0-255 with alpha)}}$

## Font
```
Font="Segoe UI"
```

Changes the font of the clock.

## Show Seconds/Date
```
ShowSeconds=1
ShowDate=1
```

Shows or hides the seconds or the date.

**Possible values:**
- **0** $\textcolor{Gray}{\textsf{(hidden)}}$
- **1** $\textcolor{Gray}{\textsf{(visible)}}$

## Size
```
Size=2
```

Changes the size of the entire clock.

> [!NOTE]
> This will affect the centering. To align the skin centered horizontally in a position, calculate: $\textcolor{Gray}{\textsf{DesiredPosition - (Width * Size) / 2}}$

## Spacing
```
Spacing=(6 * #Size#)
```

Changes the distance between the main text and the other components.

## Font Sizes
```
BigFontSize=(45 * #Size#)
MediumFontSize=(18 * #Size#)
SmallFontSize=(12 * #Size#)
```

Changes the different font sizes in the clock.

> [!WARNING]
> For values that include `* #Size#`, only change the number. The rest is needed in order to scale correctly.
