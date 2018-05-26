# Datasets de preciosclaros.gob.ar

Este repositorio contiene datasets de toda la información provista por el portal [Precios Claros](https://www.preciosclaros.gob.ar) de la Dirección Nacional de Defensa del Consumidor, dependendiente de la Secretaría de Comercio,
con relevamientos semanales entre el 20 de abril de hasta el 22 de mayo de 2018.

Es decir, contiene los precios antes, durante y después de la devaluación ([de alrededor del 25%](https://invst.ly/7ij15))  para todos los productos de venta minorista, para cada sucursal de supermercado de las cadenas que proveen información a este portal.


** ATENCION **

Por las limitaciones de ancho de banda del servicio LFS de Github,
estamos subiendo los archivos acá

http://lab.nqnwebs.com/descargas/datasets_preciosclaros.tar.gz


Una version Sqlite (a partir de [modelos django](https://github.com/mgaitan/datasets_preciosclaros/blob/master/to_sqlite.ipynb)) de estos datos está en http://lab.nqnwebs.com/descargas/db.sqlite.gz


```
$md5sum datasets_preciosclaros.tar.gz
ab8fa12caf36c778c4d728e5f399d617  datasets_preciosclaros.tar.gz
$ md5sum db.sqlite.gz
ec3a3bc816d3d0ee1547bd3a3a0f8670  db.sqlite.gz
```




La extracción está basada en un scraper, cuyo código es libre y [se encuentra disponible](https://github.com/mgaitan/preciosa/tree/develop/tools/scrappers/preciosclaros) en como parte del proyecto [Preciosa](https://github.com/mgaitan/preciosa). El scraper está basado en Scrapy y se ejecutó en la plataforma [Scrapinghub](http://scrapinghub.com).


Los contenidos de Precios Claros están bajo licencia [Creative Commons Reconocimiento 2.5 Argentina License](https://creativecommons.org/licenses/by/2.5/ar/)