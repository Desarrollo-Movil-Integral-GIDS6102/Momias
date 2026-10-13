# momias_guanajuato

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Learn Flutter](https://docs.flutter.dev/get-started/learn-flutter)
- [Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Flutter learning resources](https://docs.flutter.dev/reference/learning-resources)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

## Guía de Evidencias (Capturas de Pantalla Obligatorias por Ronda)

Para cada una de las rondas del desarrollo guiado por TDD, toma **dos capturas de pantalla** de la terminal ejecutando `flutter test`:

1. **ROJO:** La prueba escrita que falla (falla roja en la terminal).
2. **VERDE:** La prueba pasando de manera exitosa tras implementar el código mínimo (éxito verde en la terminal).

Las capturas que ya están en `assets/` se muestran a continuación. Las evidencias marcadas como **Pendiente** no se encontraron entre los archivos disponibles; agrega la captura correspondiente cuando la tengas.

### RONDA 1 — Colisión entre rectángulos (AABB)

- **1A — ROJO:** ![Captura de la ronda 1: prueba roja](assets/prueba1x.png)
- **1B — VERDE:** ![Captura de la ronda 1: prueba verde](assets/prueba1v.png)

### RONDA 2 — Gravedad y salto

- **2A — ROJO:** **Pendiente de agregar** (captura del fallo de `motor_fisica_test.dart`).
- **2B — VERDE:** ![Captura de la ronda 2: gravedad](assets/prueba2_0v.png)
- **2B — VERDE:** ![Captura de la ronda 2: salto](assets/prueba2_1v.png)
- **2B — VERDE:** ![Captura de la ronda 2: salto en el aire](assets/prueba2_2v.png)

### RONDA 3 — Aterrizar sobre una plataforma

- **3A — ROJO:** ![Captura de la ronda 3: fallo de colisión con plataforma](assets/prueba3_1x.png)
- **3B — VERDE:** ![Captura de la ronda 3: prueba de plataforma](assets/prueba3_2v.png)

### RONDA 4 — Movimiento horizontal con límites del nivel

- **4A — ROJO:** **Pendiente de agregar** (captura de las pruebas de `moverHorizontal` fallando).
- **4B — VERDE:** ![Captura de la ronda 4: movimiento horizontal](assets/prueba4_1v.png)
- **4B — VERDE:** ![Captura de la ronda 4: límite derecho](assets/prueba4_2v.png)
- **4B — VERDE:** ![Captura de la ronda 4: límite izquierdo](assets/prueba4_3v.png)

### RONDA 5 — La momia patrulla entre dos límites

- **5A — ROJO:** **Pendiente de agregar** (captura de `momia_test.dart` fallando).
- **5B — VERDE:** ![Captura de la ronda 5: pruebas de patrulla](assets/prueba5_1v.png)
- **5B — VERDE:** ![Captura de la ronda 5: momia derrotada](assets/prueba5_2v.png)

### RONDA 6 — Combate: saltar encima derrota, chocar de lado golpea

- **6A — ROJO:** ![Captura de la ronda 6: prueba de combate fallida](assets/prueba6.png)
- **6B — VERDE:** La misma captura muestra también el resultado exitoso de la colisión lateral; **pendiente de agregar** una captura verde completa de `motor_combate_test.dart`.

### RONDA 7 — Recolectar calaveritas

- **7A — ROJO:** **Pendiente de agregar** (captura del test de recolección fallando).
- **7B — VERDE:** ![Captura de la ronda 7: recolección de calaveritas](assets/prueba7.png)

### RONDA 8 — Detectar la meta (el Callejón del Beso)

- **8A — ROJO:** **Pendiente de agregar** (captura del test de meta fallando).
- **8B — VERDE:** ![Captura de la ronda 8: meta alcanzada](assets/prueba8.png)

### RONDA 9 & 10 — Vidas, Game Over y MotorJuego Integrado

- **9A — ROJO:** **Pendiente de agregar** (captura de las pruebas de pérdida de vidas y Game Over fallando).
- **9B — VERDE:** **Pendiente de agregar** una captura de terminal con la ejecución completa de `flutter test` y todas las pruebas pasando.

### RONDA 11 — Ejecución del juego en interfaz gráfica (Flutter Run)

- **Captura del juego en ejecución:** ![Juego en ejecución: vidas, puntaje, plataformas, momias, personaje y controles](assets/juego_inicial_3vidas_0puntaje.jpg)
- **Captura durante una partida:** ![Partida en curso](assets/mitadjuego_2vida_50puntos.jpg)
- **Captura al llegar a la meta:** ![Victoria en el Callejón del Beso](assets/finjuego_llagada_callejon.jpg)
