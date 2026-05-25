# EmergIA
sistema con IA en la notificacion de alertas tempranas 


EmergIA
Sistema inteligente de alerta temprana para emergencias médicas usando IA local, automatización clínica y análisis en tiempo real.



Descripción
EmergIA automatiza el proceso inicial de atención de emergencias médicas mediante:

- Validación automática de pólizas
- Análisis de historial médico
- Clasificación de urgencia
- Triage automatizado
- Recomendación hospitalaria
- Notificaciones automáticas
- IA local ejecutándose con Ollama



Tecnologías utilizadas
n8n
Ollama
Phi3 Mini
Docker
REST API
JSON
Postman



## Arquitectura

text
Postman/API-Webhook n8n-Validación póliza-Historial médico-IA Local (Ollama + Phi3)-Clasificación de urgencia-Asignación hospitalaria-Notificaciones hospital y seguro-Respuesta JSON estructurada


## Request de ejemplo

```json
{
  "insurance_id": "A12345",
  "symptoms": "dolor de pecho y dificultad para respirar",
  "hospital": "Hospital Central"
}
```

## Respuesta de ejemplo

```json
{
  "urgency": "CRITICAL",
  "triage_color": "RED",
  "specialty": "Cardiología",
  "hospital": "Hospital Central"
}
```



## IA Local

EmergIA utiliza IA ejecutándose localmente mediante:

- Ollama
- Phi3 Mini

Beneficios:

- privacidad médica
- cero dependencia cloud
- menor costo operativo
- procesamiento rápido

---

## Autor

Marco_Jimenez
Paul_Cisneros
Fernando_Roldan
