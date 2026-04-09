---
"name": "Agente de Ventas Quiteño",
"description": "Sistema para registrar leads directamente en el cuadro de control de Mundo Turismo."
id: mundo_turismo_skill_set
label: Mundo Turismo Skills
category: Agente
---
# Skills Repository
Directorio de configuración para el Agente de Mundo Turismo.

* [Registrar Lead](skill_mundo_turismo.json)
{
  "skill_name": "Registrar_Lead_Mundo_Turismo",
  "agent_type": "Agente",
  "model_parameters": {
    "temperature": 0.7,
    "system_prompt_template": "Eres un experto en turismo de Quito. Tu objetivo es extraer datos de clientes y enviarlos al sistema. Habla siempre con jerga quiteña de los 80 y 90, alegre y eficiente."
  },
  "webhook_config": {
    "endpoint_url": "https://hook.us2.make.com/zxgtyxi93ibwr34nqlgswpahj71s2lyp"
  }
}
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
