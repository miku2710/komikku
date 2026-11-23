#Modificacion del kernel Linux para Binder

##Descripcion
se inicio la modificacio del kernel Linux para habilitar el soporte binder necesario para la comunicaion entre los componentes del sistema android y el entorno Linux

##problema identificado
la configuracion inicial de kernel utilizaba Rust Binder y no tenia habilitado el controlador Binder clasico, lo que ocasioaba problemas al iniciar el administrado de servicios de waydroid

##actividades realizada 
-investigacion de los requisitos del kernel para waydroid.
-obtencion del codigo fuente y PKGBUILD oficial de Arch Linux.
-preparacion del entorno de copilacion.
-modificacion de opciones de configuracion relacionadas con bider.
-desactivacion de Rust Binder en la configuracion propuesta.
-inicio de la compilacion personalizada del kernel.

##estado actual
la compilacion del kernel esta en proceso, todavia falta instalarlo, iniciar el sistema con el y comprobar si waydroid funciona correctamete.

##objetivo
conseguir que el kernel proporcione el soporte Bider requerido para ejecutar Android mediante waydroid

