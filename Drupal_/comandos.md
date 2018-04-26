# GIT
## Crear commit
1. Git status
2. Drush cex (sync) ### Exportamos Primero la configuración desde /web
3. Git status #Paso opcional
4. Git add -A #con -A añadimos todos los archivos
5. Git commit -m "nombredelcommmit"

**Push** ---> [ `git push origin master` ]

**Pull** --> [ `git pull` ]

**Crear Rama** ---> [ `git checkout -b nombre` ]

#Importar configuración ---> [ git cim (sync) ]

--------------------------------------------------------------------------------------------


## DRUPAL 8 

### Módulos

* Instalar módulos con drupal console: moi (module install) ---> [ `drupal moi name` ]

* Desinstalar módulos con drupal console: mou (module uninstall) ---> [ `drupal mou name` ]

* Instalar dependencias de módulos ---> [ `composer require drupal/modulename` ]

----------------------------------------------------------------------------------------------

> Comandos de drupal Console ( [link](https://hechoendrupal.gitbooks.io/drupal-console/content/en/about/what-is-the-drupal-console.html) )

#Activar modo mantenimiento (con drush) ---> [ `drush sset system.maintenance_mode 1` ]

#Desactivar modo mantenimiento (con drush) ---> [ `drush sset system.maintenance_mode 0` ]

#Limpiar cache (con drush) ---> [ `drush cr` ]

#Lista de actualizaciones disponibles (con drush) ---> [ `drush ups` ]

#Actualizar base de datos si lo necesita (con drush) ---> [ `drush updb` ]

#Iniciar servidor local (con drupal console) ---> [ `drupal server`]

#Iniciar servidor local (con php) ---> [ `php -S localhost:8080`]  

#Iniciar Compass Watch (cd web/themes/custom/socialfood/) ---> [ `compass watch` ]

> Clases para nodos ( [link](https://lohmeyer.rocks/blog/2016/05/09/0076-adding-node-class-body-html-tag-drupal-8) )

    
---------------------------------------------------------------------------------------------
