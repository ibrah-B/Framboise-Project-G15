# Stage Sense
Groupe 15 MI8
Membres du groupe:

Ibrahim Boubaya

Yassine Elmokhtari

Jules Decorps n0 21506930



Un accordeur (ou tuner, en anglais) est un dispositif — physique ou logiciel — permettant de déterminer la hauteur exacte d’un son musical afin d’ajuster un instrument pour qu’il produise les notes correctes. En d’autres termes, il aide les musiciens à s’assurer que chaque corde ou note émise correspond à la fréquence souhaitée.


Lorsqu’un instrument (comme une guitare, un violon ou une basse) joue une note, le son produit est une onde caractérisée par sa fréquence — mesurée en hertz (Hz).
L’accordeur capte ce son à l’aide d’un microphone ou d’un capteur de vibration, puis analyse le signal pour identifier :

- La fréquence fondamentale (la note principale jouée).

- L’écart entre cette fréquence et la fréquence de référence (par exemple, 440 Hz pour le La standard).

À partir de cette analyse, l’accordeur indique si la note est :

Trop basse (flat ou grave),

Trop haute (sharp ou aiguë),

Ou juste (in tune).

---------------------------
STRUCTURE DU REPO:
├── backend/          → Server-side logic (API + sound processing)
│   ├── app.py        → Main FastAPI entry point
│   ├── services/     → Core modules (tuner logic, instruments data)
│   ├── tests/        → All backend tests (pytest)
│   └── requirements.txt
│
├── frontend/         → Client-side web app (React)
│   ├── public/       → Static assets (icons, images)
│   ├── src/          → Main source files
│   │   ├── components/ → Reusable UI parts (TunerDisplay, etc.)
│   │   ├── pages/      → App pages (Home, Settings)
│   │   ├── services/   → API requests to backend
│   │   └── App.jsx     → Main app entry
│   └── package.json
│
└── README.md         → You are here