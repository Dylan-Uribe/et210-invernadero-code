# Sistema Automatizado de Plantas 🌱

[![TecnoUPSA 2023](https://img.shields.io/badge/TecnoUPSA%202023-Ganador-gold)](https://github.com/Dylan-Uribe/sistema-automatizado-de-plantas)
[![Arduino](https://img.shields.io/badge/Arduino-IDE-blue)](https://www.arduino.cc/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## 📋 Descripción

Proyecto ganador de la **TecnoUPSA 2023** en la materia de **Sistemas Digitales**. Este sistema automatizado de invernadero utiliza Arduino para monitorear y controlar las condiciones ambientales de las plantas, incluyendo temperatura, humedad del aire y humedad del suelo.

## 🛠️ Tecnologías y Componentes Utilizados

### Hardware
- **Arduino** (Microcontrolador principal)
- **Sensor DHT11** - Medición de temperatura y humedad del aire
- **Sensor de humedad de suelo** - Monitoreo de humedad del sustrato
- **Pantalla OLED SSD1306** (128x64) - Interfaz de usuario
- **Teclado matricial 4x4** - Control de navegación
- **Módulo RTC DS3231** - Reloj en tiempo real
- **Potenciómetro** - Configuración de parámetros
- **Relés para control de:**
  - Bomba de agua
  - Ventilador
  - Luces LED

### Software y Librerías
```cpp
#include <EEPROM.h>          // Almacenamiento persistente
#include <Keypad.h>          // Control del teclado matricial
#include <Adafruit_GFX.h>    // Gráficos para pantalla OLED
#include <Adafruit_SSD1306.h> // Control de pantalla OLED
#include <Wire.h>            // Comunicación I2C
#include <RTClib.h>          // Manejo del módulo RTC
#include <Adafruit_Sensor.h> // Librería base para sensores
#include <DHT.h>             // Control del sensor DHT11
```

## ⚙️ Funcionalidades Principales

### 🖥️ Sistema de Menú Interactivo
- **Menú Principal**: Navegación con teclado matricial
- **Visualización de Datos**: Temperatura, humedad y humedad del suelo en tiempo real
- **Configuración Personalizada**: Ajuste de parámetros de operación
- **Sistema de Registros**: Almacenamiento y visualización de eventos

### 🌡️ Control Automático
- **Ventilador**: Se activa automáticamente cuando la temperatura supera el umbral configurado
- **Bomba de Agua**: Riega cuando la humedad del suelo está por debajo del mínimo configurado
- **Luces LED**: Se encienden cuando la temperatura es inferior al umbral configurado

### 📊 Monitoreo y Registro
- **Registro de Eventos**: Almacena en EEPROM fecha, hora y tipo de evento
- **Visualización Histórica**: Navega por registros anteriores
- **Borrado de Registros**: Función para limpiar el historial

## 🚀 Instalación y Uso

### Prerrequisitos
- Arduino IDE
- Librerías mencionadas anteriormente instaladas

### Configuración Inicial
1. **Conexión del Hardware**: Conecta todos los componentes según el esquema de pines
2. **Carga del Código**: Sube el código `Invernadero Arduino.txt` a tu Arduino
3. **Configuración del RTC**: Al primer uso, descomenta la línea de ajuste de fecha/hora
4. **Calibración**: Ajusta los parámetros según tus necesidades específicas

### Uso del Sistema
1. **Navegación**: Usa el teclado matricial para navegar por los menús
2. **Visualización**: Selecciona "Mostrar" para ver datos en tiempo real
3. **Configuración**: Usa "Personalizar" para ajustar umbrales
4. **Registros**: Accede al historial de eventos del sistema

## 📈 Parámetros por Defecto

- **Bomba de Agua**: 
  - Mínimo: 25% humedad de suelo
  - Máximo: 50% humedad de suelo
- **Ventilador/LED**: 
  - Activación: 25°C

## 🏆 Reconocimientos

Este proyecto fue **ganador** en la **TecnoUPSA 2023** en la categoría de **Sistemas Digitales**, destacando por su innovación en automatización agrícola y su implementación técnica.

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - consulta el archivo [LICENSE](LICENSE) para más detalles.
