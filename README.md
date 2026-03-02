# nuvem-semana1-ana-faller

# Semana 1 - Deploy estatico (GitHub Pages)

##Links
- Repositorio:https://github.com/FallerAnaa/nuvem-semana1-ana-faller
- Site (GitHub Pages): https://falleranaa.github.io/nuvem-semana1-ana-faller/

## O que foi feito
- Criei index.html, style.css e script.js pelo navegador
- Ativei GitHub Pages (main / root)

##Dificuldades
- Me perdi um pouco na interface do GitHub, pois fazia algum tempo que não o utilizava, mas nada que me impediu de cumprir com a atividade.

# Semana 2 - HTTP + Fetch no GitHub Pages

## O que foi feito
-   Modifiquei index.html e script.js pelo navegador
-   Adicionei requisições: Get + Post

## Mini-evidência
- Get: {
  "fonte": "open-meteo.com",
  "temperatura": 24,
  "vento": 15.6,
  "unidade_temp": "°C",
  "unidade_vento": "km/h",
  "bruto": {
    "latitude": -24.375,
    "longitude": -53.875,
    "generationtime_ms": 0.042319297790527344,
    "utc_offset_seconds": 0,
    "timezone": "GMT",
    "timezone_abbreviation": "GMT",
    "elevation": 329,
    "current_units": {
      "time": "iso8601",
      "interval": "seconds",
      "temperature_2m": "°C",
      "wind_speed_10m": "km/h"
    },
    "current": {
      "time": "2026-03-02T11:45",
      "interval": 900,
      "temperature_2m": 24,
      "wind_speed_10m": 15.6
    }
  }
}

- Post: {
  "fonte": "jsonplaceholder.typicode.com",
  "resposta": {
    "turma": "Serviços em Nuvem",
    "atividade": "Semana 2",
    "timestamp": "2026-03-02T11:47:58.724Z",
    "id": 101
  }
}
