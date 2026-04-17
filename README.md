# Enumeraciones
# 📌 Sistema de Gestión de Solicitudes con Enum en C#

## 📖 Descripción del proyecto
Este proyecto consiste en una aplicación de consola desarrollada en C# para la gestión de solicitudes de clientes en una empresa de servicios tecnológicos.

El sistema fue diseñado para resolver problemas de inconsistencia en los estados de las solicitudes, los cuales anteriormente se manejaban como texto libre, generando errores como:
- Estados mal escritos (ej: "pendient", "done")
- Falta de uniformidad en los reportes
- Dificultad para validar procesos

Para solucionar esto, se implementa el uso de un **enumerador (enum)** que estandariza los estados.

## 🎯 Objetivo de la actividad
Aplicar el uso de enumeradores (`enum`) para representar valores constantes y mejorar la organización y claridad del código en un sistema real.

## 🧠 Implementación del Enum
Se creó el enumerador:

```csharp
public enum EstadoSolicitud
{
    Pendiente = 1,
    EnProceso,
    Completada,
    Cancelada
}
```  

---
1.
<img width="289" height="187" alt="image" src="https://github.com/user-attachments/assets/2e660191-ccad-4a48-b477-5e5aca01aba8" />

2.
<img width="259" height="229" alt="image" src="https://github.com/user-attachments/assets/edc35710-5885-4c8a-bc06-73cb0c94a637" />

3.
<img width="297" height="263" alt="image" src="https://github.com/user-attachments/assets/8be479b5-aa64-4696-b697-71bb047d93a1" />

4.
<img width="265" height="247" alt="image" src="https://github.com/user-attachments/assets/bf890542-8866-41ab-aa41-26af76b79673" />

5.
<img width="944" height="277" alt="image" src="https://github.com/user-attachments/assets/0d753b2a-b1f6-4114-b841-06d0d19f57d3" />
