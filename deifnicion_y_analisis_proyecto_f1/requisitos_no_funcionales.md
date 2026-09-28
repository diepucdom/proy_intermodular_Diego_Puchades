## Requisitos no funcionales

1. **Seguridad**
   - Las contraseñas deben almacenarse de forma segura y nunca en texto plano.
   - Los datos sensibles de los usuarios deben estar protegidos.
   - Las credenciales del administrador deben mantenerse separadas del código del proyecto.
   - Las comunicaciones y los pagos deben realizarse mediante conexiones seguras.
   - La sesión del usuario debe caducar periódicamente para aumentar la seguridad.
   - El sistema debe controlar los permisos de cada tipo de usuario.

2. **Protección de datos**
   - Cada usuario solo podrá acceder a la información que le corresponda.
   - Los datos personales y de pago no deben ser visibles para otros usuarios.
   - El sistema debe cumplir con la normativa de protección de datos aplicable.
   - El usuario debe poder consultar las condiciones y permisos relacionados con el uso de sus datos.

3. **Rendimiento**
   - Las páginas deben cargar en un tiempo reducido.
   - Las búsquedas de usuarios, ofertas, restaurantes y pedidos deben responder rápidamente.
   - El sistema debe poder gestionar varios usuarios simultáneamente sin perder rendimiento.
   - Las funciones que utilicen mapas y ubicación deben funcionar de forma fluida.

4. **Disponibilidad y fiabilidad**
   - La aplicación debe estar disponible siempre que sea posible.
   - Los pagos deben realizarse mediante un servicio externo fiable.
   - Los pedidos y pagos deben evitar pérdidas o duplicaciones de información.
   - La base de datos debe disponer de copias de seguridad periódicas para evitar la pérdida de información.

5. **Mantenibilidad**
   - El código debe estar organizado y separado por funciones para facilitar su mantenimiento.
   - Las diferentes partes de la aplicación deben tener la menor dependencia posible entre ellas.
   - La aplicación debe poder ampliarse con nuevas funciones sin modificar grandes partes del sistema.
   - El código debe poder actualizarse para adaptarse a nuevos estándares y tecnologías.

6. **Escalabilidad**
   - La aplicación debe poder soportar un aumento de usuarios y pedidos.
   - La estructura debe permitir añadir nuevas funciones, ofertas, misiones, recompensas y tipos de usuario.
   - La base de datos debe estar preparada para aumentar la cantidad de información almacenada.

7. **Usabilidad y accesibilidad**
   - La interfaz debe ser clara, sencilla y fácil de utilizar.
   - Las funciones principales deben poder encontrarse fácilmente.
   - La aplicación debe mostrar mensajes claros cuando se produzca un error.
   - Los formularios deben indicar correctamente los campos obligatorios y los errores.

8. **Compatibilidad**
   - La aplicación debe funcionar correctamente en los principales navegadores web.
   - La interfaz debe adaptarse a ordenadores, tablets y dispositivos móviles.
   - Las funciones externas utilizadas, como mapas y pagos, deben ser compatibles con la aplicación.

9. **SEO**
   - Las páginas públicas deben estar estructuradas para facilitar su indexación por los buscadores.
   - El contenido debe utilizar una estructura correcta de títulos, textos y metadatos.
   - La aplicación debe optimizar los tiempos de carga para mejorar su posicionamiento.

10. **Copias de seguridad y recuperación**
   - La base de datos debe realizar copias de seguridad periódicas.
   - Las copias deben almacenarse de forma segura.
   - Debe existir un procedimiento para recuperar la información en caso de pérdida o fallo del sistema.