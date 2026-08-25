# Entre Dioses y Atracciones

Web sobre parques de atracciones españoles, con **Coasterle**: un juego diario tipo Wordle para adivinar la montaña rusa del día.

**En vivo:** https://quiz-entrediosesyatracciones.web.app

## Tecnologías

- HTML5
- CSS3
- JavaScript (módulos ES)
- Firebase Firestore
- Autenticación con Google
- Firebase Hosting

## Qué tiene de particular

- Coasterle compara altura, parque, tipo y fabricante, con pistas por color y seis intentos.
- Ranking diario y racha de partidas, con inicio de sesión opcional: se puede jugar de forma anónima.
- **Reglas de Firestore** que impiden editar partidas ajenas y solo dejan que los contadores globales suban de uno en uno.
- Gestión de consentimiento de cookies con Cookiebot en modo de bloqueo automático, y política con tabla de cookies por proveedor, finalidad y duración.

## Estructura

```
firebase.json     Configuración de Firebase Hosting y cabeceras de caché
.firebaserc       A qué proyecto de Firebase se despliega
public/           Todo lo que se publica
```

## Cómo desplegarlo

```bash
firebase deploy
```

---

Hecho por **Marcos Martínez** — desarrollador web en Valencia.
