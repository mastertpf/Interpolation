# Lineær interpolation — klassisk opsætning + eksport til Word

> Denne README er genereret ud fra notebook'en *Interpolation_Lineaer.ipynb*. Den er tænkt som en klassisk, nøgtern vejledning til studerende.

## Åbn i Google Colab
Klik på badgen herunder (ret `<brugernavn>`, `<repo>` og stien til filen i dit GitHub).

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](
https://colab.research.google.com/github/<brugernavn>/<repo>/blob/main/Interpolation_Lineaer_clean.ipynb
)

> Alternativt: Åbn Colab → **File → Open notebook… → GitHub** og søg på dit repo.

## Krav
- Python 3.x i Colab (standard)
- Pakker der importeres i notebook'en:
```
from IPython.display import display, Markdown, clear_output
from docx import Document
from docx.shared import Inches
from ipywidgets import VBox, HBox, Text, FloatText, Checkbox, Button, Output, Layout, HTML
from math import isfinite
import ipywidgets # Corrected import statement
import matplotlib.pyplot as plt
import numpy as np
import os
```

## Sådan bruger du notebook'en
1. Kør cellerne i rækkefølge fra toppen (traditionel praksis).
2. Når du bliver bedt om input, følg formatkrav herunder.
3. Gem din egen kopi til Google Drive: **File → Save a copy in Drive**.

## Input og formatkrav
_Ingen tydelige dato/decimal-formatkrav fundet._

## Funktioner i notebook'en
_Ingen funktionsdefinitioner fundet i koden._

## Typiske fejl & løsninger
- **GitHub viser “Invalid Notebook … 'state' mangler i metadata.widgets”**  
  → Brug den rensede fil *Interpolation_Lineaer_clean.ipynb* (metadata er fjernet), eller åbn direkte i Colab.
- **Dato-fejl** (ValueError: time data ... does not match format)  
  → Sørg for at dine datoer matcher formatet angivet ovenfor.
- **Tal fortolkes forkert** (12,5 vs 12.5)  
  → Brug samme decimalseparator som koden forventer.

---

*Denne README er et udgangspunkt. Udfyld gerne konkrete eksempler på input og tilpas teksten til jeres undervisning.*
