# NBA-Pedict
Proyecto para predecir el MVP, DPOY, ROY, y Campeón de la temporada 2025-26 de la NBA.


Con la API de la NBA se obtuvieron los datos de jugadores y equipos de la temporada 2025-26.


# Organización de carpetas
nba_project/
│
├── data_raw/            ← datos originales desde API-NBA
├── data_clean/          ← datos limpios y transformados
├── notebooks/           ← Jupyters para análisis y ETL
├── src/
│   ├── extract/         ← scripts de descarga
│   ├── transform/       ← limpieza y features
│   └── model/           ← modelos ML
└── README.md


# Contenido del dataset limpio
| Player | Team | PTS | REB | AST | STL | BLK | PER | TEAM_WINS | TEAM_NET_RTG | SEASON |