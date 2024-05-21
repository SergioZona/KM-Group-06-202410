# KM - Choucair Academy

## Integrantes del Proyecto
- Brenda Catalina Barahona Pinilla - 201812721
- Juan Diego González Gómez - 201911031
- Sergio Julián Zona Moreno - 201914936

## Instalación

1. El primer paso es instalar las dependencias necesarias:

```bash
!pip install -q -U google-generativeai
!pip install graphviz
```
2. Para el segundo paso es necesario crear una cuenta en [Gemini](https://ai.google.dev/pricing?hl=es-419) y luego solicitar el API Key. Este API Key posteriormente debe ingresarse en la celda que contiene: `API_KEY_HERE`.

## Uso
Una vez se haya instalado las dependencias y configurado el API Key de Gemini, se puede ejecutar el script, explorar los ejemplos y las soluciones que proporciona el árbol de decisión.

Es importante destacar que, para que un problema funcione correctamente, debe incluir información sobre:

- Tipo de Aplicación
- Tipo de Problema
- Etapa del Ciclo de Vida del Desarrollo del Software
- Complejidad del Sistema o Módulo Bajo Prueba
  
Gemini automáticamente extrae los parámetros necesarios para que funcione. En caso de que algún parámetro no se lea adecuadamente, aparecerá el siguiente mensaje:

`
"No se encontró información que se ajuste al dominio de conocimiento. Por favor detalle: el tipo, el problema, la etapa y la complejidad que afectan la aplicación."
`
