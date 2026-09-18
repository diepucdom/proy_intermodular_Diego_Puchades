# PROYECTO: COMIDA PARA LLEVAR

- Recompensas
- Misiones
- Amigos
- Recuento de cupones
- Raids a restaurantes por cupones
- Ubicación y countdown de raids y ofertas

# PESTAÑAS

## HOMEPAGE

- Iniciar sesión / Crear cuenta
- Remember me
- Icono cuenta*
- Icono amigos*
- Pedidos domicilio*
- Ofertas*
- Ubicaciones recientes
- Raids (redirección a página **RAIDS**)

## CUENTA

- Usuario
- Correo
- Cambiar contraseña
- Foto de perfil
- Lista de amigos
  - Popup
  - Eliminar amigo
  - Entrar en su perfil (página cuenta sin credenciales, solo nombre + foto)
- Tarjeta
  - Introducir contraseña → Stripe
- Cupones

## AMIGOS

- Searchbar
- Lista de amigos
  - Misma que en página **CUENTA**

## PEDIDOS

- Ofertas
- Pedir
  - Establecer punto de recogida
  - Cobrar (Stripe)
- Desglosar
  - Comida
  - Precio
  - Hora de llegada
- Una vez has pedido:
  - Se muestra mapa con ubicación en tiempo real (API Maps)
  - Hora estimada de llegada
  - Se suman cupones / se resta saldo

## RAIDS

- Restaurante
- Foto
- Ubicación (Maps)
- Countdown
  - Al acabar no se puede interactuar con nada
  - Sale como expirada
- Pedido necesario
- Precio
- Premio: cupones
- Al llegar:
  - El operador suma los cupones
  - Cobra con normalidad