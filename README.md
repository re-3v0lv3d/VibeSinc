# VibeSinc
Una app para Android que monitorea el nivel de ruido ambiental y ajusta automáticamente el volumen del dispositivo. 

## Características
- Monitoreo en tiempo real del nivel de ruido ambiental
- Ajuste automático del volumen según el nivel de ruido detectado:
  - Muy silencioso (< 60 dB): 60% del volumen
  - Silencioso (60-75 dB): 70% del volumen
  - Normal (75-80 dB): 80% del volumen
  - Ruidoso (80-90 dB): 90% del volumen
  - Muy ruidoso (> 90 dB): 100% del volumen
- Notificación persistente con el nivel de ruido actual
- Funciona en segundo plano
- Interfaz simple e intuitiva

## Requisitos
- Android 6.0 (API 23) o superior
- Permisos de micrófono
- Permisos de notificación (Android 13+)

## Tecnologías utilizadas
- Kotlin
- MediaRecorder para captura de audio
- Servicios en primer plano
- NotificationManager
- BroadcastReceiver
