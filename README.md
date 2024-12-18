# Actividad 1 - Diseño y Operaciones CRUD en Bases de Datos NoSQL

#### Video: [Video de la actividad](https://drive.google.com/file/d/1neK9saOuELlWiK5vE-2L4I4UJ5Id0aSS/view?usp=sharing)

## Presentado por:  
- Cristian Leandro Pérez Peláez  
- Natalia Sierra Salamando  

### Corporación Universitaria Iberoamericana  
**Facultad de Ingeniería**  

**Curso:** Bases de Datos Avanzadas  
**Profesor:** Jorge Castañeda  
**Fecha:** Domingo, 17 de noviembre de 2024  

---

## Descripción de la Actividad  

Esta actividad consiste en diseñar y ejecutar operaciones CRUD en una base de datos NoSQL para modelar un torneo de fútbol bajo las siguientes reglas y requisitos.

### 1. Requisitos para la Creación de la Base de Datos  

#### Formato del Torneo de Fútbol y sus Reglas:  
- **Equipos Participantes:** 20 equipos.  
- **Jugadores por Equipo:** Entre 15 y 25 jugadores.  
- **Formato de Competencia:** Todos los equipos se enfrentan una vez.  
- **Puntaje por Resultado:**
  - Victoria: 3 puntos.
  - Empate: 1 punto.
  - Derrota: 0 puntos.  
- **Tabla de Posiciones:** Los equipos se ordenan según los puntos obtenidos.  

#### Datos Importantes del Torneo:  

1. **Jugadores:**
   - Información: Nombre, edad, posición, goles, asistencias, tarjetas amarillas, tarjetas rojas, equipo al que pertenecen.  

2. **Entrenadores:**  
   - Información: Nombre, edad, experiencia, estrategia, equipo asignado.  

3. **Árbitros:**  
   - Información: Nombre, edad, experiencia, partidos asignados.  
   - Asignación: Distribuidos aleatoriamente a los encuentros.  

4. **Equipos:**  
   - Información: Nombre, ciudad, entrenador, jugadores, puntos, victorias, derrotas, empates, goles a favor, goles en contra, diferencia de goles.  

5. **Partidos:**  
   - Información: Fecha, lugar, equipo local, equipo visitante, árbitro, resultado, goles del equipo local, goles del equipo visitante, ganador, estadísticas (posesión local y visitante, tarjetas amarillas, tarjetas rojas).  

---

### 2. Informes Requeridos  

1. **Tabla de Posiciones Actualizada:**  
   - Visualización de los equipos ordenados según puntos, incluyendo estadísticas clave.  

2. **Detalles de los Encuentros:**  
   - Información de cada partido con resultados y estadísticas detalladas.  

3. **Estadísticas Individuales por Jugador:**  
   - Seguimiento de métricas como goles, asistencias, tarjetas, etc.  

4. **Histórico de Partidos por Equipo:**  
   - Registro de victorias, derrotas y empates por equipo.  

---

## Alcance y Objetivos  

- Modelar correctamente la estructura de datos para reflejar los elementos del torneo.  
- Implementar operaciones CRUD para gestionar la información de los equipos, jugadores, entrenadores, árbitros y partidos.  
- Generar informes precisos que respalden el análisis y seguimiento del torneo.  

**Nota:** Este diseño utiliza principios avanzados de modelado NoSQL para garantizar eficiencia en las consultas y escalabilidad del sistema.
