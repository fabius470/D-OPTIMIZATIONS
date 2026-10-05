# D-OPTIMIZATIONS
in this folder there is exes created by claude, they baisically optimize your pc, but i need to test it first, maybe before trying, ask ai, to not have problems with the files. the files are python files. 
# D Optimizations Software Installation

🇬🇧 [English](#-english) | 🇮🇹 [Italiano](#-italiano)

*Made with Claude · Fatto con Claude*

---

## 🇬🇧 English

A Windows app written in **Python** (tkinter) that downloads and extracts, in one click,
the folder containing all the optimization files.

### How it works

1. Open `D Optimizations Software Installation.exe`.
2. Choose the destination folder with the **Sfoglia** (Browse) button.
3. Click **Scarica ZIP online** (Download ZIP online): the app downloads the zip from the Releases section of this repository.
4. If the option *Estrai lo zip dopo il download* (Extract the zip after download) is enabled, the files are extracted into the `Ottimizzazione` folder, which opens automatically when finished.

### Download

The zip with all the files is in the **Releases** section on the right side of this page.

### Requirements

- Windows 10 or Windows 11
- Internet connection (for the online download)

### For developers

The source code is in `main.py` and uses only the Python standard library.
To build the exe you need PyInstaller:

```
python -m pip install pyinstaller
python -m PyInstaller --onefile --noconsole --name "D Optimizations Software Installation" main.py
```

In the code, the `ZIP_URL` line contains the direct link to the zip in the Releases section.

### Warnings

Windows Defender or SmartScreen may flag the exe as unknown. This is a common
false positive for programs built with PyInstaller. Download and use the files
only if you trust the author.

### Credits

This app was created with the help of [Claude](https://claude.ai), the AI assistant by Anthropic.

---

## 🇮🇹 Italiano

App per Windows scritta in **Python** (tkinter) che scarica ed estrae in un clic
la cartella con tutti i file di ottimizzazione.

### Come funziona

1. Apri `D Optimizations Software Installation.exe`.
2. Scegli la cartella di destinazione con il pulsante **Sfoglia**.
3. Premi **Scarica ZIP online**: l'app scarica lo zip dalla sezione Releases di questo repository.
4. Se la casella *Estrai lo zip dopo il download* è attiva, i file vengono estratti nella cartella `Ottimizzazione`, che si apre in automatico a fine lavoro.

### Download

Lo zip con i file si trova nella sezione **Releases**, a destra di questa pagina.

### Requisiti

- Windows 10 o Windows 11
- Connessione a internet (per il download online)

### Per sviluppatori

Il codice sorgente è in `main.py` e usa solo la libreria standard di Python.
Per creare l'exe serve PyInstaller:

```
python -m pip install pyinstaller
python -m PyInstaller --onefile --noconsole --name "D Optimizations Software Installation" main.py
```

Nel codice, la riga `ZIP_URL` contiene il link diretto allo zip delle Releases.

### Avvertenze

Windows Defender o SmartScreen possono segnalare l'exe come sconosciuto: è un
falso positivo comune per i programmi creati con PyInstaller. Scarica e usa i
file solo se ti fidi dell'autore.

### Crediti

Questa app è stata creata con l'aiuto di [Claude](https://claude.ai), l'assistente AI di Anthropic.
