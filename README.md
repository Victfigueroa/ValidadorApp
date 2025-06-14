## Análisis de Calidad de Código con SonarQube (cloud)

**Grupo 5**  
- Juan Villaman  
- Cristóbal Erazo  
- Victor Figueroa  

### Uso de Sonar Qube Cloud
Existieron algunos problemas al intentar instalar SonarQube directamente en nuestros sistemas. Para no retrasar el trabajo, decidimos usar SonarQube Cloud. Es una versión en la nube que funciona de manera muy similar, dándonos todas las herramientas necesarias para cumplir con los requisitos de la tarea sin contratiempos.

### ¿Qué tipo de errores detectó SonarQube que podrían haber pasado desapercibidos?
SonarQube identificó *code smells*, problemas de mantenibilidad y advertencias de seguridad como el uso de `System.out.println`, que no se detectan fácilmente en pruebas dinámicas.

### ¿Qué ventajas tiene el análisis estático respecto al dinámico?
El análisis estático permite identificar errores sin ejecutar el programa, lo que facilita la corrección temprana de problemas y mantiene estándares de calidad desde las primeras etapas de desarrollo.

### ¿Cómo impacta SonarQube en la calidad del software antes del despliegue?
Mejora significativamente la calidad del software al permitir identificar y corregir errores antes del despliegue. Esto reduce riesgos, mejora la mantenibilidad y asegura un producto más confiable.

### ¿Qué políticas o reglas personalizarías según el tipo de proyecto?
Para proyectos críticos se podrían aplicar reglas más estrictas de seguridad y cobertura. En proyectos pequeños, se puede permitir más flexibilidad para favorecer la velocidad sin comprometer la calidad base.

### Análisis final: ¿Qué detectamos? ¿Qué corregimos? ¿Cómo mejoró el resultado?
Detectamos errores como caracteres ilegales, el uso de `System.out.println` y ausencia de estructura de paquetes. Corregimos la clase `App.java`, aplicamos buenas prácticas y configuramos correctamente el análisis en SonarQube Cloud. Esto nos permitió obtener una calificación “A” en todas las métricas, mejorando la mantenibilidad y preparación del software para producción.

### Dashboard Sonarquebe con error (antes)
![SonarQube (Antes)](https://github.com/user-attachments/assets/74be1849-34ee-4bf5-bc54-c21a5ae7b0d5)

### Dashboard Sonarquebe sin error (despues)
![SonarQube (Despues)](https://github.com/user-attachments/assets/ffb29a2c-909f-4136-9ac2-effa665174d9)
