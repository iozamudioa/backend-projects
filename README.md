# 🧠 Portafolio Backend – Java Edition

> Portafolio backend con enfoque en resolver problemas reales mediante arquitectura clara y código mantenible.  
> Refleja mi forma de pensar: práctica, estructurada y detallista.

---

## 🚀 ¿Qué encontrarás aquí?

Este repositorio reúne una serie de proyectos backend desarrollados con un enfoque riguroso y obsesivo en:

- ✅ Diseño limpio y mantenible
- ✅ Resolución de casos de uso reales
- ✅ Separación de responsabilidades como si fueran cuartos en una casa japonesa (cada uno hace lo suyo, y lo hace bien)
- ✅ Arquitectura hexagonal (porque no todo es controladores y servicios: el dominio manda)
- ✅ Patrones de diseño aplicados cuando son útiles, no por deporte
- ✅ Principios SOLID seguidos como mandamientos backend
- ✅ Estilo de código con aroma a espresso bien calibrado, no frappé revuelto

---

## 🛠️ Stack Tecnológico

| Categoría            | Herramientas / Tecnologías                                         |
|----------------------|--------------------------------------------------------------------|
| Lenguaje             | Java 17+                                                           |
| Framework base       | Spring Boot                                                        |
| Arquitectura         | Hexagonal (Ports and Adapters), Monolitos limpios, Microservicios |
| Seguridad            | JWT, Spring Security                                               |
| Persistencia         | Spring Data JPA, PostgreSQL, MongoDB (según el caso)              |
| Procesos batch       | Spring Batch, Jobs configurables                                   |
| Comunicación         | RESTful APIs, HTTP clients                                         |
| Testing              | JUnit 5, Mockito, Testcontainers                                   |
| Documentación        | Swagger / OpenAPI                                                  |
| Despliegue           | Docker, Render, Railway                                            |
| Automatización       | Maven / Gradle, GitHub Actions                                     |

---

## 🧱 Fundamentos

Cada proyecto está construido sobre estos pilares:

### 🔹 Arquitectura Hexagonal
Separación entre dominio, casos de uso y tecnología.  
Como si el sistema fuera una cebolla que no hace llorar.

```
┌────────────────────────────┐
│     Adaptadores Externos   │ ← Web, DB, Security
└────────────────────────────┘
            ▲
        Casos de Uso
            ▲
       Lógica de Dominio
```

### 🔸 Principios SOLID (más sólidos que una piedra de Tetris)

- **S**: Cada clase hace una sola cosa, y la hace bien.
- **O**: Extensible como Lego, sin romper lo que ya funciona.
- **L**: Si una subclase no respeta el contrato, fuera.
- **I**: Interfaces pequeñas, no menús de fonda con 80 platillos.
- **D**: El código depende de abstracciones, no implementaciones concretas (como debería ser una buena taza de café: no importa la cafetera, sino el grano).

---

## 📂 Estructura General

Cada proyecto en este repo incluye:

- 📦 Arquitectura clara por capas (o por puertos/adaptadores si es hexagonal)
- 🧪 Pruebas unitarias e integración
- 🛡️ Seguridad con JWT (si aplica)
- 🔁 Control de errores global
- 📚 Documentación con Swagger
- 🐳 Dockerfile para despliegue local
- ✍️ Bitácora técnica del proceso de desarrollo

---

## 🧠 Filosofía

> "El buen código es como una conversación clara:  
> directo, sin gritos, sin rodeos, y con pausas donde toca respirar."

Este portafolio no es solo una colección de proyectos, es un reflejo de cómo abordo problemas, diseño soluciones y estructuro software que no colapsa a la primera refactorización.

---

## 📌 Proyectos incluidos

- 📋 `api-tareas`: CRUD de tareas con autenticación JWT y arquitectura hexagonal
- 🔒 `auth-service`: sistema de autenticación con roles y tokens
- ⏱️ `job-runner`: ejecución de procesos batch controlados por configuración
- 📦 `api-productos`: servicio modular con DTOs, filtros y relaciones
- 🧭 (y más próximamente...)

---

## 🤝 Contribuciones y conexión

Si alguna de estas ideas te sirve, te inspira o quieres discutir sobre DDD, arquitectura o simplemente lo desquiciado que es inyectar `EntityManager` directamente en el dominio...  
¡Abre una issue, o conéctate!

---

## ☕ Última analogía para cerrar

> Si el código fuera café, aquí lo servimos fuerte, sin azúcar y sin excepciones no controladas.  
> Lo que ves es lo que puedes probar, documentar y desplegar.

---
