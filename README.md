# Eye to Space

A real-time animated ASCII-art visual made with **Python**, **Tkinter**, and **NumPy**.

The animation begins with a detailed eye, gradually zooms through the iris, and transforms into a star-filled space scene with a glowing heart-shaped nebula. The visuals are rendered using colored ASCII characters in a desktop window.

## Preview

Add a screenshot of the running application at `assets/preview.png`, then uncomment the image line below:

<!-- ![Eye to Space preview](assets/preview.png) -->

## Features

- Animated eye with blinking and subtle eye movement
- Detailed iris and lighting effects
- Smooth zoom transition into a space scene
- Animated stars, shooting stars, and a heart-shaped nebula
- Colored ASCII rendering in a Tkinter window
- Restart the animation without closing the app

## Requirements

- Python 3.10 or newer
- NumPy
- Tkinter (usually included with the standard Python installation on Windows)

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/eye-to-space.git
cd eye-to-space
```

### 2. (Optional) Create a virtual environment

**Windows (PowerShell or Command Prompt):**

```bash
python -m venv .venv
.venv\\Scripts\\activate
```

**macOS / Linux:**

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install dependencies

```bash
python -m pip install -r requirements.txt
```

### 4. Run the project

```bash
python eye_to_space.py
```

## Controls

| Key | Action |
|---|---|
| `R` | Restart the animation |
| `Esc` | Close the application |

## Project structure

```text
eye-to-space/
├── assets/
│   └── preview.png       # Add your application screenshot here
├── eye_to_space.py       # Main animation program
├── requirements.txt     # Python dependencies
├── .gitignore
├── LICENSE
└── README.md
```

## Troubleshooting

- **`ModuleNotFoundError: No module named 'numpy'`** — Run `python -m pip install -r requirements.txt`.
- **Tkinter is unavailable on Linux** — Install your distribution's Tkinter package (often named `python3-tk`), then run the program again.
- **The `python` command is not recognized on Windows** — Try `py eye_to_space.py` and `py -m pip install -r requirements.txt`.

## Contributing

Issues and pull requests are welcome. If you want to suggest an improvement, please open an issue describing the change.

## License

This project is released under the MIT License. See [LICENSE](LICENSE).

---

If you find this project interesting, consider giving the repository a ⭐.
