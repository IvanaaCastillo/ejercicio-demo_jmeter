# 🧪 Ejercicio Demo JMeter

Pruebas de rendimiento con **Apache JMeter** sobre una aplicación web sencilla, ideal para practicar conceptos básicos de carga y estrés.

---

## 📋 Descripción

Este repositorio contiene un entorno mínimo para ejecutar pruebas de rendimiento utilizando Apache JMeter. Incluye:

- Una aplicación web dummy (`dummy-app`)  
- Planes de prueba `.jmx` para simular múltiples usuarios  
- Uso de Docker para facilitar la configuración  
- Ejecución local o integración con CI/CD  

---

## 🚀 Cómo ejecutar

1. Clona el repositorio:
   ```bash
   git clone https://github.com/IvanaaCastillo/ejercicio-demo_jmeter.git
   cd ejercicio-demo_jmeter

2. Levanta la aplicación dummy con Docker:
   ```bash
   docker compose up

3. Abre Apache JMeter y carga el plan de prueba (test-plan.jmx).
4. Ejecuta la prueba y analiza los resultados.

---

# 🛠️ Tecnologías usadas

- Apache JMeter
- Docker
- Aplicación dummy en Node.js (opcional para pruebas locales)
- Git

---
