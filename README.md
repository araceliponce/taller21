# Taller21 | Demo19Angular

guards

- CanActivate -> true|false permite la navegacion a una ruta dependiendo de si el usuario esta autenticado. se ejecuta antes de que cargue el componente

en home/ ves   login y post[disabled]


en post/ ves     post y logout



ng g s services/autenticacion
ng g guard canactivate (y escogemos esa opcion)
ng g c principal/login