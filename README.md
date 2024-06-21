# Math Exercise Converter

Convert your math exercises into beautifully formatted images in a Word document.

Dieses Projekt konvertiert mathematische Funktionen in Bilder und fügt diese Bilder in ein Word-Dokument ein. Es verwendet `sympy`, um mathematische Ausdrücke zu generieren und `matplotlib`, um diese Ausdrücke in LaTeX zu rendern. Die gerenderten Bilder werden dann mithilfe von `python-docx` in ein Word-Dokument eingefügt.

##Anwendung

# Rational(p, q): Stellt die Potenz 
𝑝/𝑞 dar. Beispiel: 
7√x wird als x**Rational(1, 7) geschrieben.

# exp(x): Stellt die Exponentialfunktion 
e^√x dar. Beispiel: 
wird als exp(sqrt(x)) geschrieben.

# ln(x): Stellt den natürlichen Logarithmus 
ln(𝑥) dar. Beispiel: 
ln(𝑥^3) wird als ln(x**3) geschrieben.

# sin(x): Stellt die Sinusfunktion 
sin(x) dar. Beispiel: 
sin(ln(x^3)) wird als sin(ln(x**3)) geschrieben.

# sqrt(x): Stellt die Quadratwurzel 
𝑥 dar. Beispiel: 
√x wird als sqrt(x) geschrieben.

## Voraussetzungen

Stellen Sie sicher, dass Sie die folgenden Python-Bibliotheken installiert haben:

- `sympy`
- `matplotlib`
- `python-docx`

Installieren Sie diese Bibliotheken mit pip:

```sh
pip install sympy
pip install matplotlib
pip install python-docx
