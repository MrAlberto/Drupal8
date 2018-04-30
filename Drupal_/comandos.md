# DRUPAL 8 

## Módulos

* Instalar módulos con composer:
`composer require drupal/nombremaquinadelmodulo`

* Actualizar módulos con composer:
`composer update drupal/nombremaquinadelmodulo`

* Instalar módulos con drupal console: moi (module install)
`drupal moi name`

* Desinstalar módulos con drupal console: mou (module uninstall)
`drupal mou name`

* Instalar dependencias de módulos 
`composer require drupal/modulename`

---
## Drush

* Activar modo mantenimiento (con drush)
`drush sset system.maintenance_mode 1`

* Desactivar modo mantenimiento (con drush)
`drush sset system.maintenance_mode 0`

* Limpiar cache (con drush)
`drush cr`

* Lista de actualizaciones disponibles (con drush
`drush ups`

* Actualizar base de datos si lo necesita (con drush)
`drush updb`

* Iniciar Compass Watch (cd web/themes/custom/socialfood/)
`compass watch`

> Clases para nodos ( [link](https://lohmeyer.rocks/blog/2016/05/09/0076-adding-node-class-body-html-tag-drupal-8) )
---
## Drupal Console

> Comandos de drupal Console ( [link](https://hechoendrupal.gitbooks.io/drupal-console/content/en/about/what-is-the-drupal-console.html) )

* Iniciar servidor local (con drupal console)
`drupal server`
    
---
## Composer

 - Instalar modulos:
   - $ composer require drupal/nombremaquinadelmodulo
    - Ej:
    - $ composer require drupal/admin_toolbar
 - Para una versión del módulo específica:
   - $ composer require drupal/admin_toolbar:1.16.0
 - Actualizar el core y todos los módulos:
   - $ composer update
 - Actualizar un módulo específico:
   - $ composer update drupal/admin_toolbar
 - Eliminar un módulo:
   - $ composer remove drupal/admin_toolbar
# GIT
## Crear commit
> Exportamos Primero la configuración desde /web
1. `git status`
> Paso opcional, solo para comprobar los archivos de configuración exportados
2. `Drush cex (sync)`
3. `git status`
> Con -A añadimos todos los archivos, podemos añadir los archivos uno por uno con `git add nombre`
4. `git add -A`
5. `git commit -m "nombredelcommmit"`

**Push**
`git push origin master`

**Pull**`git pull`

**Crear Rama**
`git checkout -b nombre`

**Importar configuración** 
`drush cim (sync)`

---
