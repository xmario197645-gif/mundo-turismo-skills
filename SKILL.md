{
  "id": "mundo_turismo_task",
  "label": "Mundo Turismo Lead Manager",
  "category": {
    "id": "ventas",
    "label": "Agencia de Viajes"
  },
  "description": "Sistema para registrar leads directamente en el cuadro de control de Mundo Turismo.",
  "models": [
    {
      "name": "Agente de Ventas Quiteño",
      "info": "Extrae datos del cliente y los manda al webhook de Make.",
      "url": "https://hook.us2.make.com/zxgtyxi93ibwr34nqlgswpahj71s2lyp",
      "downloadFileName": "skill_mundo_turismo.json",
      "bestForTaskIds": ["mundo_turismo_task"]
    }
  ]
}

---
id: mundo_turismo_skill_set
label: Mundo Turismo Skills
category: Agente
---
# Skills Repository
Directorio de configuración para el Agente de Mundo Turismo.

* [Registrar Lead](skill_mundo_turismo.json)