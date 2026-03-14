# Sistema de Reserva de Canchas

Proyecto base para modelar la **lógica de reserva de canchas**.

---

## 👥 Equipo

**Los Piratas Dev**

---

## 📌 Descripción

Este proyecto define el flujo principal que sigue una persona usuaria para reservar una cancha deportiva desde una vista de disponibilidad.

El objetivo es organizar el proceso de reserva de forma clara, simple y ordenada.

---

## 🧭 Flujo de reserva (usuario)

1. **Seleccionar cancha**  
   La persona usuaria elige una cancha en la vista de canchas disponibles.

2. **Elegir fecha**  
   Selecciona el día en el que desea alquilar, entre las opciones habilitadas.

3. **Elegir horario**  
   El sistema muestra los horarios disponibles y la persona usuaria selecciona el que prefiera.

4. **Confirmar reserva**  
   Se registra la reserva de la cancha con la fecha y horario elegidos.

---

## ✅ Reglas funcionales sugeridas

- Solo se deben mostrar **canchas disponibles**.
- Solo se deben habilitar **fechas válidas** para reserva.
- Los horarios deben actualizarse según cancha y fecha seleccionadas.
- No se puede confirmar una reserva si el horario ya fue tomado.

---

## 🚀 Próximos pasos recomendados

- Agregar autenticación de usuarios.
- Implementar historial de reservas.
- Incorporar cancelaciones y reprogramaciones.
- Añadir notificaciones de confirmación (correo o mensaje).

---

## 🛠️ Estado del proyecto

En definición inicial de lógica y flujo funcional.
