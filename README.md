# java-ee-app
## Archivtypen
Ordnerstrukturen sind durch die Spezifikation festgelegt.
* **EAR** (Enterprise Archive): Java-EE-Anwendungen, die den gesamten Java-EE-Umfang benötigen (*Full Profile*)
* **WAR** (Web Archive): Java-EE-Anwendungen, die nur den Umfang des *Web Profile* benötigen
  * /
    * .jsf, .jsp etc.
    * WEB-INF
      * classes (Beans, Servlets, etc.)
      * lib (JARs, die nicht vom Applicationserver bereitgestellt werden)
      * \[templates\] (Facelet-Templates)
      * web.xml, beans.xml, faces-config.xml, etc.
    * META-INF
    * [resources]
      * .css, .html, .ttf, etc.
