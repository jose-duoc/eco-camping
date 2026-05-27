¡Bienvenido al sistema de control de registros para **Eco-Camping 'Bosque Vivo'**! Este es un script interactivo desarrollado en **Python** diseñado para la administración eficiente y en tiempo real de la ocupación de sitios y vehículos dentro del camping. de libre uso.

El sistema permite supervisar la disponibilidad de espacios, registrar ingresos y salidas, y calcular métricas operativas clave para evitar la sobreocupación, promoviendo así un turismo sustentable y ordenado.

---

## 🚀 Características Principales

* **Control de Aforo en Tiempo Real:** Monitoreo constante basado en una capacidad máxima definida (15 sitios).
* **Menú Interactivo:** Navegación amigable a través de la terminal mediante opciones numéricas.
* **Validación de Datos Completa:** Manejo robusto de errores frente a entradas no válidas (letras, valores negativos o cantidades superiores al límite disponible).
* **Métricas de Ocupación:** Cálculo automático del porcentaje de capacidad utilizada en el ecosistema del camping.

---

## 🛠️ Tecnologías Utilizadas

* **Lenguaje:** Python 3.x
* **Paradigmas:** Programación estructurada, ciclos condicionales (`while`, `if-elif-else`) y control de excepciones (`try-except`).

---

## 📋 Funcionalidades del Menú

El script cuenta con 5 opciones fundamentales para la gestión del recinto:

1.  **Ver sitios disponibles:** Muestra de forma inmediata cuántos espacios quedan libres para recibir nuevos vehículos.
2.  **Registro de nuevos vehículos (Entrada):** Permite ingresar múltiples vehículos a la vez, validando que no se supere la capacidad máxima.
3.  **Registro de salida de vehículos (Salida):** Libera los sitios ocupados asegurando que no se retiren más vehículos de los que realmente existen en el sistema.
4.  **Estado actual del camping:** Presenta un resumen del total de sitios ocupados frente al límite total junto con el porcentaje exacto de ocupación.
5.  **Salir:** Finaliza de manera segura la ejecución del programa.

---

## 📦 Instrucciones de Uso

### Prerrequisitos
Tener instalado **Python 3** en tu equipo. Puedes verificarlo ejecutando:
```bash
python --version
Ejecución
Clona este repositorio o descarga el archivo fuente (por ejemplo, main.py).

Abre una terminal en la carpeta del archivo.

Ejecuta el script con el siguiente comando:

Bash
python main.py
💻 Ejemplo de Uso de la Interfaz
Plaintext
Gestión de Eco-Camping 'Bosque Vivo'

=== MENÚ DE CONTROL DE REGISTROS
1.- Ver sitios disponibles
2.- Registro de nuevos vehiculos en el sitio(Entrada)
3.- Registro de salida de vehículos(Salida)
4.- Estado actual del camping
5.- Salir

Seleccione una opción (1-5): 4

[ESTADO] Ocupación actual: 0/15 sitios
[ESTADO] El camping esta al 0.0% de su capacidad
🛡️ Robustez frente a Errores
El código implementa bloques try-except para capturar fallos de tipo ValueError, asegurando que si un usuario ingresa texto por accidente en campos numéricos, el programa no se detenga abruptamente, sino que le notifique el error amigablemente y le permita continuar con la navegación.
