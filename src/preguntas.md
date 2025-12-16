- Como mejorarías la implementación de useFetch?
Soporte para métodos HTTP adicionales (POST, PUT, DELETE)
Capacidad de refrescar datos manualmente
Manejo de opciones de fetch personalizadas
Mejor separación de responsabilidades
- En el form de edición/creación de post, que hacemos para poder actualizar el estado de los datos de envio para no tener que manejar cada uno de los datos de manera individual?
Usar un useForm custom
En lugar de manejar cada campo individualmente, crea un hook personalizado que centralice la lógica:
