# 🧾 Validaciones de Datos

> Validación rápida y sencilla para formularios, registros y datos de usuarios.

Este proyecto contiene funciones útiles para verificar información básica antes de almacenarla o enviarla a un sistema.

## ✨ ¿Qué incluye?

- Cédula con 10 dígitos numéricos
- Nombre y apellido con letras válidas
- Correo electrónico con formato básico correcto

## 🔎 Reglas de validación

- Cédula: debe tener exactamente 10 caracteres numéricos.
- Nombre y apellido: no pueden estar vacíos y solo deben contener letras.
- Correo: debe incluir un `@` y un dominio con punto, por ejemplo `usuario@ejemplo.com`.

## 🚀 Uso rápido

```python
from validaciones import validar_cedula, validar_nombre_apellido, validar_correo

print(validar_cedula("0991234567"))
print(validar_nombre_apellido("Ana", "Pérez"))
print(validar_correo("ana@ejemplo.com"))
```

## 📌 Ejemplos de salida

```python
validar_cedula("0991234567")         # True
validar_nombre_apellido("Ana", "Pérez")  # True
validar_correo("ana@ejemplo.com")    # True
```

## 🧠 Importante

Estas funciones son una validación básica ideal para formularios simples. Si tu proyecto necesita reglas más estrictas, puedes ampliarlas con validaciones adicionales según tus requisitos.

## 🏷️ Estado

Proyecto ligero, fácil de entender y listo para usar en ejemplos o formularios básicos.
