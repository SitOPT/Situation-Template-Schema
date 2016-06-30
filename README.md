How to generate JAXB classes
--------------------------------

Steps to generate a Java data model from the XSD file (Java JDK has to be installed).

1) only once: Add C:/Program Files/Java/jdk../bin to system path variable

2) execute `xjc -d src/ -p situationtemplate.model situation_template.xsd` in the command line

(Optional: You can call "ant build" to export the JAXB classes to a jar file)
