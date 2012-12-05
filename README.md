Codeigniter Helper ChileAtiende
====================

Helper para consumir las fichas de chileatiende con Codeigniter, necesitas tener tu <a href="https://www.chileatiende.cl/desarrolladores/access_token" target="_blank">access_token</a>

### Como Configurar

* editar y agregar al archivo autoload.php

```php
$autoload['helper'] = array('consumidor');
```

* editar y agregar al archivo config.php

```php
$config['chileatiende_api_access_token'] = "TU_ACCESS_TOKEN";
$config['chileatiende_api_url'] = "https://www.chileatiende.cl/api/";
```

### Como usar

```php
$servicio = APIServicio($idServicio);
echo $servicio->servicio->nombre
```

eso es todo :)

### Licencia

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/3.0/deed.es_CL"><img alt="Licencia Creative Commons" style="border-width:0" src="http://i.creativecommons.org/l/by-nc-sa/3.0/88x31.png" /></a><br />Este obra está bajo una <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/3.0/deed.es_CL">Licencia Creative Commons Atribución-NoComercial-CompartirIgual 3.0 Unported</a>.