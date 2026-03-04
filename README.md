# Pokémon Battle Arena (Streamlit)

A Pokémon combat simulator built with **Streamlit** using real data from the **PokeAPI**.  
Select two Pokémon, choose damaging moves, and simulate a battle with type effectiveness, STAB, and randomness.

---

## 🌐 Live App

🔗 https://pokemon-battle-arena.streamlit.app/

---

## 🚀 How to Run Locally

```bash
pip install -r requirements.txt
streamlit run poke_dashboard.py
```

---

## ⚙️ Features

- Pokémon selection by name
- Sprites, types, weaknesses, and base stats
- Damaging move selection with move details (type, class, power, accuracy)
- Base stat comparison chart (Plotly)
- Turn-based battle simulation
- Battle log table
- HP over battle rounds chart

---

## 📊 Data Source

- https://pokeapi.co/

---

## 📁 Repository Structure

- `poke_dashboard.py` – Main Streamlit application
- `requirements.txt` – Python dependencies
- `README.md` – Project documentation
- `pokeball_pixel_icon.png` – Header icon (optional)

---

## 👥 Group Contributions

- **Diego Gaitán** – UI design, layout styling, hero header, sprite rendering, final integration and debugging
- **Juan José Rincón** – API integration (Pokémon, moves, types) and caching logic
- **Luka Tcheishvili** – Data processing and pandas implementation (tables, stat comparison, battle log)
- **Romain Gelin** – Combat mechanics (damage formula, STAB, effectiveness, turn order)
- **Cécile Tambey**  – Plotly visualizations (bar chart, HP line chart) and UI polishing
