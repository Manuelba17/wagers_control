# wagers_control
Aplicación la cual requiere registrar un control de apuestas para cada usuario 

# Listado de entidades 

## Usuarios
- usuario_id **PK**
- nickname
- activision_id
- email
- telefono
- contraseña
- Nombre
- Apellidos

## wagers
- wagwer_id **PK**
- usuario_id FK
- rival1 
- rival2
- companero
- fecha
- resultado
- valor
- estado
