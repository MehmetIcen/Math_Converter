# Math Exercise Converter

Convert your math exercises into beautifully formatted images in a Word document.

Dieses Projekt konvertiert mathematische Funktionen in Bilder und fügt diese Bilder in ein Word-Dokument ein. Es verwendet `sympy`, um mathematische Ausdrücke zu generieren und `matplotlib`, um diese Ausdrücke in LaTeX zu rendern. Die gerenderten Bilder werden dann mithilfe von `python-docx` in ein Word-Dokument eingefügt.

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
