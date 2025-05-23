# Simulacion Medico de Software
## Erika Aristizabal y  Matias Baeza (sección 1)

### Corrección de diagramas
Diagrama de caso de uso
1- El estudiante no debería tener la facultad de ver el historial de OTRAS personas.
2- La "notificación del cambio por correo" no debería heredar de "Aprobar reserva".
3-Falta la implementación de <<include>> y <<extend>> en el diagrama.
![ab53ee95-e4ee-4ce1-816e-86a0871b5f87](https://github.com/user-attachments/assets/cd1cf610-75a0-4327-a5a7-835f8835d013)

Diagrama de Clases 

1-"reserva" aparece sin relación con otras clases y en minúscula, además de estar duplicado con "SistemaReserva"
2-Los métodos están sin sus respectivos parámetros o (). 
3-No se muestra el acceso (+ / -) de los atributos 
4-Falta el motivoCancelación en "SistemaReserva"
![11af8e30-6661-48bc-9c5f-a81c90dd6f02](https://github.com/user-attachments/assets/fbbc129a-ef27-4a9f-9a43-4769127121df)


Diagrama de implementación
1-La "Base de datos Central" no está dentro de "sistema Académico Externo"
2-El "Módulo de Historial" que está en "Navegador del Estudiante" debería estar implementado con el patrón Singleton ya que el "Sistema de Gestión de Reservas" hace una solicitud al la base de datos y se "duplica" esta acción

![f6e10862-3096-4f66-b0d6-05ad513f21e0](https://github.com/user-attachments/assets/56c2980e-2ca4-4b60-994a-65855b6e5aef)

