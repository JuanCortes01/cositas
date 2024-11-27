wafwoof
sql scann
bingoo

dork list de chatGPT  

Dorks generales para pruebas de seguridad

    Archivos sensibles expuestos:
        filetype:pdf intext:"sensitive" OR intext:"confidential"
        filetype:xls site:example.com
        filetype:sql "password"

    Directorios y configuraciones expuestos:
        intitle:"index of" "parent directory"
        intitle:"index of" "backup"
        intitle:"index of" "admin"

    Errores y logs públicos:
        inurl:"/error.log"
        inurl:"/phpinfo.php"
        intext:"Warning: mysql_connect()" "on line"

    Cámaras de seguridad expuestas:
        inurl:"/view/index.shtml"
        intitle:"Live View / - AXIS"
        intitle:"webcamXP 5"

    Páginas de inicio de sesión:
        inurl:admin/login
        intitle:"login" "admin"
        inurl:"/wp-admin/"

    Bases de datos expuestas:
        filetype:sql "INSERT INTO"
        inurl:"/phpMyAdmin/" "Welcome to phpMyAdmin"

    Contraseñas y credenciales:
        filetype:txt "username" "password"
        filetype:env DB_PASSWORD
        intext:"credentials" filetype:txt

Prácticas éticas al usar Google Dorks

    Obtén permiso antes de buscar información en sistemas que no te pertenecen.
    Úsalos en ambientes controlados como tu propia red o dominios donde tengas autorización.
    No almacenes, uses ni compartas datos confidenciales que encuentres accidentalmente.
    Documenta los hallazgos para mejorar las políticas de seguridad.

Recursos adicionales

    Sitios para aprender sobre pentesting ético, como Hack The Box y TryHackMe.
    Herramientas de automatización como Google Dork Searcher para generar dorks de forma masiva.


