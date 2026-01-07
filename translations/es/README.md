<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "97a2c4bb6626355c73b9c3ee2b697a60",
  "translation_date": "2026-01-06T12:25:35+00:00",
  "source_file": "README.md",
  "language_code": "es"
}
-->
> Nota: Esta documentación se actualiza continuamente para reflejar los últimos cambios.

> ⚠️ Este repositorio es una demo creada para mostrar
> la localización automatizada de documentación usando Localizeflow.
>
> El contenido original se basa en
> el proyecto “AZD para Principiantes” de Microsoft.


# AZD Para Principiantes: Un Viaje de Aprendizaje Estructurado

![AZD-for-beginners](../../translated_images/azdbeginners.5527441dd9f74068.es.png) 

[![GitHub watchers](https://img.shields.io/github/watchers/microsoft/azd-for-beginners.svg?style=social&label=Watch)](https://GitHub.com/microsoft/azd-for-beginners/watchers/)
[![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/network/)
[![GitHub stars](https://img.shields.io/github/stars/microsoft/azd-for-beginners.svg?style=social&label=Star)](https://GitHub.com/microsoft/azd-for-beginners/stargazers/)

[![Azure Discord](https://dcbadge.limes.pink/api/server/https://discord.gg/microsoft-azure)](https://discord.gg/microsoft-azure)
[![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)

## Comenzando con Este Curso

Sigue estos pasos para iniciar tu viaje de aprendizaje con AZD:

1. **Haz Fork del Repositorio**: Haz clic en [![GitHub forks](https://img.shields.io/github/forks/microsoft/azd-for-beginners.svg?style=social&label=Fork)](https://GitHub.com/microsoft/azd-for-beginners/fork)
2. **Clona el Repositorio**: `git clone https://github.com/microsoft/azd-for-beginners.git`
3. **Únete a la Comunidad**: [Comunidades Discord de Azure](https://discord.com/invite/ByRwuEEgH4) para soporte experto
4. **Elige Tu Ruta de Aprendizaje**: Selecciona un capítulo a continuación que coincida con tu nivel de experiencia

### Soporte Multilenguaje

#### Traducciones Automatizadas (Siempre Actualizadas)

<!-- CO-OP TRANSLATOR LANGUAGES TABLE START -->
[Árabe](../ar/README.md) | [Bengalí](../bn/README.md) | [Búlgaro](../bg/README.md) | [Birmano (Myanmar)](../my/README.md) | [Chino (Simplificado)](../zh/README.md) | [Chino (Tradicional, Hong Kong)](../hk/README.md) | [Chino (Tradicional, Macao)](../mo/README.md) | [Chino (Tradicional, Taiwán)](../tw/README.md) | [Croata](../hr/README.md) | [Checo](../cs/README.md) | [Danés](../da/README.md) | [Neerlandés](../nl/README.md) | [Estonio](../et/README.md) | [Finlandés](../fi/README.md) | [Francés](../fr/README.md) | [Alemán](../de/README.md) | [Griego](../el/README.md) | [Hebreo](../he/README.md) | [Hindi](../hi/README.md) | [Húngaro](../hu/README.md) | [Indonesio](../id/README.md) | [Italiano](../it/README.md) | [Japonés](../ja/README.md) | [Kannada](../kn/README.md) | [Coreano](../ko/README.md) | [Lituano](../lt/README.md) | [Malayo](../ms/README.md) | [Malayalam](../ml/README.md) | [Marathi](../mr/README.md) | [Nepalí](../ne/README.md) | [Pidgin Nigeriano](../pcm/README.md) | [Noruego](../no/README.md) | [Persa (Farsi)](../fa/README.md) | [Polaco](../pl/README.md) | [Portugués (Brasil)](../br/README.md) | [Portugués (Portugal)](../pt/README.md) | [Punyabí (Gurmukhi)](../pa/README.md) | [Rumano](../ro/README.md) | [Ruso](../ru/README.md) | [Serbio (Cirílico)](../sr/README.md) | [Eslovaco](../sk/README.md) | [Esloveno](../sl/README.md) | [Español](./README.md) | [Swahili](../sw/README.md) | [Sueco](../sv/README.md) | [Tagalo (Filipino)](../tl/README.md) | [Tamil](../ta/README.md) | [Telugú](../te/README.md) | [Tailandés](../th/README.md) | [Turco](../tr/README.md) | [Ucraniano](../uk/README.md) | [Urdu](../ur/README.md) | [Vietnamita](../vi/README.md)

> **¿Prefieres Clonar Localmente?**

> Este repositorio incluye más de 50 traducciones que aumentan significativamente el tamaño de la descarga. Para clonar sin traducciones, usa checkout parcial (sparse checkout):
> ```bash
> git clone --filter=blob:none --sparse https://github.com/localizeflow/azd-for-beginners-localizeflow-demo.git
> cd azd-for-beginners-localizeflow-demo
> git sparse-checkout set --no-cone '/*' '!translations' '!translated_images'
> ```
> Esto te proporciona todo lo necesario para completar el curso con una descarga mucho más rápida.
<!-- CO-OP TRANSLATOR LANGUAGES TABLE END -->

## Descripción General del Curso

Domina Azure Developer CLI (azd) a través de capítulos estructurados diseñados para un aprendizaje progresivo. **Enfoque especial en el despliegue de aplicaciones de IA con integración de Microsoft Foundry.**

### Por Qué Este Curso es Esencial para Desarrolladores Modernos

Basado en insights de la comunidad Microsoft Foundry Discord, **el 45% de los desarrolladores desean usar AZD para cargas de trabajo de IA** pero enfrentan desafíos con:
- Arquitecturas de IA complejas con múltiples servicios
- Mejores prácticas para despliegue de IA en producción  
- Integración y configuración de servicios Azure AI
- Optimización de costos para cargas de IA
- Resolución de problemas específicos de despliegues de IA

### Objetivos de Aprendizaje

Al completar este curso estructurado, lograrás:
- **Dominar los Fundamentos de AZD**: Conceptos clave, instalación y configuración
- **Desplegar Aplicaciones de IA**: Usar AZD con servicios Microsoft Foundry
- **Implementar Infraestructura como Código**: Gestionar recursos Azure con plantillas Bicep
- **Solucionar Problemas de Despliegues**: Resolver incidencias comunes y depurar problemas
- **Optimizar para Producción**: Seguridad, escalabilidad, monitoreo y gestión de costos
- **Construir Soluciones Multi-Agente**: Desplegar arquitecturas complejas de IA

## 📚 Capítulos de Aprendizaje

*Selecciona tu ruta de aprendizaje según tu nivel de experiencia y objetivos*

### 🚀 Capítulo 1: Fundamentos y Primeros Pasos
**Requisitos**: Suscripción a Azure, conocimiento básico de línea de comandos  
**Duración**: 30-45 minutos  
**Complejidad**: ⭐

#### Qué Aprenderás
- Comprender los fundamentos del Azure Developer CLI
- Instalar AZD en tu plataforma
- Tu primer despliegue exitoso

#### Recursos de Aprendizaje
- **🎯 Comienza Aquí**: [¿Qué es Azure Developer CLI?](../..)
- **📖 Teoría**: [Conceptos Básicos de AZD](docs/getting-started/azd-basics.md) - Conceptos y terminología clave
- **⚙️ Configuración**: [Instalación y Configuración](docs/getting-started/installation.md) - Guías específicas por plataforma
- **🛠️ Práctica**: [Tu Primer Proyecto](docs/getting-started/first-project.md) - Tutorial paso a paso
- **📋 Referencia Rápida**: [Hoja de Comandos](resources/cheat-sheet.md)

#### Ejercicios Prácticos
```bash
# Comprobación rápida de instalación
azd version

# Despliega tu primera aplicación
azd init --template todo-nodejs-mongo
azd up
```

**💡 Resultado del Capítulo**: Desplegar con éxito una aplicación web simple en Azure usando AZD

**✅ Validación de Éxito:**
```bash
# Después de completar el Capítulo 1, deberías ser capaz de:
azd version              # Muestra la versión instalada
azd init --template todo-nodejs-mongo  # Inicializa el proyecto
azd up                  # Despliega en Azure
azd show                # Muestra la URL de la aplicación en ejecución
# La aplicación se abre en el navegador y funciona
azd down --force --purge  # Limpia los recursos
```

**📊 Tiempo Requerido:** 30-45 minutos  
**📈 Nivel de Habilidad Después:** Puede desplegar aplicaciones básicas de manera independiente

**✅ Validación de Éxito:**
```bash
# Después de completar el Capítulo 1, deberías poder:
azd version              # Muestra la versión instalada
azd init --template todo-nodejs-mongo  # Inicializa el proyecto
azd up                  # Despliega en Azure
azd show                # Muestra la URL de la aplicación en ejecución
# La aplicación se abre en el navegador y funciona
azd down --force --purge  # Limpia los recursos
```

**📊 Tiempo Requerido:** 30-45 minutos  
**📈 Nivel de Habilidad Después:** Puede desplegar aplicaciones básicas de manera independiente

---

### 🤖 Capítulo 2: Desarrollo AI-First (Recomendado para Desarrolladores de IA)
**Requisitos**: Capítulo 1 completado  
**Duración**: 1-2 horas  
**Complejidad**: ⭐⭐

#### Qué Aprenderás
- Integración de Microsoft Foundry con AZD
- Despliegue de aplicaciones impulsadas por IA
- Comprender configuraciones de servicios de IA

#### Recursos de Aprendizaje
- **🎯 Comienza Aquí**: [Integración Microsoft Foundry](docs/microsoft-foundry/microsoft-foundry-integration.md)
- **📖 Patrones**: [Despliegue de Modelos de IA](docs/microsoft-foundry/ai-model-deployment.md) - Despliega y gestiona modelos de IA
- **🛠️ Taller**: [Laboratorio de IA](docs/microsoft-foundry/ai-workshop-lab.md) - Prepara tus soluciones IA para AZD
- **🎥 Guía Interactiva**: [Materiales del Taller](workshop/README.md) - Aprendizaje en navegador con MkDocs * Entorno DevContainer
- **📋 Plantillas**: [Plantillas Microsoft Foundry](../..)
- **📝 Ejemplos**: [Ejemplos de Despliegue AZD](examples/README.md)

#### Ejercicios Prácticos
```bash
# Despliega tu primera aplicación de IA
azd init --template azure-search-openai-demo
azd up

# Prueba plantillas adicionales de IA
azd init --template openai-chat-app-quickstart
azd init --template agent-openai-python-prompty
```

**💡 Resultado del Capítulo**: Desplegar y configurar una aplicación de chat potenciada por IA con capacidades RAG

**✅ Validación de Éxito:**
```bash
# Después del Capítulo 2, deberías poder:
azd init --template azure-search-openai-demo
azd up
# Probar la interfaz de chat de IA
# Hacer preguntas y obtener respuestas con IA con fuentes
# Verificar que la integración de búsqueda funcione
azd monitor  # Comprobar que Application Insights muestra telemetría
azd down --force --purge
```

**📊 Tiempo Requerido:** 1-2 horas  
**📈 Nivel de Habilidad Después:** Puede desplegar y configurar aplicaciones IA listas para producción  
**💰 Conciencia de Costos:** Entiende costos de desarrollo $80-150/mes, costos producción $300-3500/mes

#### 💰 Consideraciones de Costos para Despliegues de IA

**Entorno de Desarrollo (Estimado $80-150/mes):**
- Azure OpenAI (Pago por uso): $0-50/mes (según uso de tokens)
- AI Search (nivel básico): $75/mes
- Container Apps (Consumo): $0-20/mes
- Almacenamiento (Estándar): $1-5/mes

**Entorno de Producción (Estimado $300-3,500+/mes):**
- Azure OpenAI (PTU para rendimiento constante): $3,000+/mes O pago por uso con alto volumen
- AI Search (nivel estándar): $250/mes
- Container Apps (Dedicado): $50-100/mes
- Application Insights: $5-50/mes
- Almacenamiento (Premium): $10-50/mes

**💡 Consejos para Optimizar Costos:**
- Usa **Nivel Gratis** de Azure OpenAI para aprendizaje (50,000 tokens/mes incluidos)
- Ejecuta `azd down` para desalocar recursos cuando no desarrolles activamente
- Comienza con facturación por consumo, actualiza a PTU solo para producción
- Usa `azd provision --preview` para estimar costos antes del despliegue
- Activa autoescalado: paga solo por uso real

**Monitoreo de Costos:**
```bash
# Verificar costos mensuales estimados
azd provision --preview

# Monitorear costos reales en el Portal de Azure
az consumption budget list --resource-group <your-rg>
```

---

### ⚙️ Capítulo 3: Configuración y Autenticación
**Requisitos**: Capítulo 1 completado  
**Duración**: 45-60 minutos  
**Complejidad**: ⭐⭐

#### Qué Aprenderás
- Configuración y gestión de entornos
- Prácticas recomendadas de autenticación y seguridad
- Nomenclatura y organización de recursos

#### Recursos de Aprendizaje
- **📖 Configuración**: [Guía de Configuración](docs/getting-started/configuration.md) - Configuración del entorno
- **🔐 Seguridad**: [Patrones de autenticación e identidad administrada](docs/getting-started/authsecurity.md) - Patrones de autenticación
- **📝 Ejemplos**: [Ejemplo de Aplicación de Base de Datos](examples/database-app/README.md) - Ejemplos AZD Base de Datos

#### Ejercicios Prácticos
- Configurar múltiples entornos (dev, staging, prod)
- Configurar autenticación con identidad administrada
- Implementar configuraciones específicas por entorno

**💡 Resultado del Capítulo**: Gestionar múltiples entornos con autenticación y seguridad adecuadas

---

### 🏗️ Capítulo 4: Infraestructura como Código y Despliegue
**Requisitos**: Capítulos 1-3 completados  
**Duración**: 1-1.5 horas  
**Complejidad**: ⭐⭐⭐

#### Qué Aprenderás
- Patrones avanzados de despliegue
- Infraestructura como Código con Bicep
- Estrategias para aprovisionamiento de recursos

#### Recursos de Aprendizaje
- **📖 Despliegue**: [Guía de Despliegue](docs/deployment/deployment-guide.md) - Flujos de trabajo completos
- **🏗️ Aprovisionamiento**: [Aprovisionamiento de Recursos](docs/deployment/provisioning.md) - Gestión de recursos Azure
- **📝 Ejemplos**: [Ejemplo de Container App](../../examples/container-app) - Despliegues containerizados

#### Ejercicios Prácticos
- Crear plantillas Bicep personalizadas
- Desplegar aplicaciones multi-servicio
- Implementar estrategias de despliegue blue-green

**💡 Resultado del Capítulo**: Desplegar aplicaciones multi-servicio complejas usando plantillas de infraestructura personalizadas

---
### 🎯 Capítulo 5: Soluciones de IA Multi-Agente (Avanzado)
**Prerrequisitos**: Capítulos 1-2 completados  
**Duración**: 2-3 horas  
**Complejidad**: ⭐⭐⭐⭐

#### Lo que aprenderás
- Patrones de arquitectura multi-agente
- Orquestación y coordinación de agentes
- Despliegues de IA listos para producción

#### Recursos de aprendizaje
- **🤖 Proyecto destacado**: [Solución Multi-Agente para Retail](examples/retail-scenario.md) - Implementación completa
- **🛠️ Plantillas ARM**: [Paquete de Plantillas ARM](../../examples/retail-multiagent-arm-template) - Despliegue con un clic
- **📖 Arquitectura**: [Patrones de coordinación multi-agente](/docs/pre-deployment/coordination-patterns.md) - Patrones

#### Ejercicios prácticos
```bash
# Desplegar la solución completa de agentes múltiples para retail
cd examples/retail-multiagent-arm-template
./deploy.sh

# Explorar configuraciones de agentes
az deployment group show --resource-group <rg-name> --name <deployment-name>
```

**💡 Resultado del capítulo**: Desplegar y gestionar una solución de IA multi-agente lista para producción con agentes de Cliente e Inventario

---

### 🔍 Capítulo 6: Validación y Planificación Pre-Despliegue
**Prerrequisitos**: Capítulo 4 completado  
**Duración**: 1 hora  
**Complejidad**: ⭐⭐

#### Lo que aprenderás
- Planificación de capacidad y validación de recursos
- Estrategias para selección de SKU
- Revisiones previas y automatización

#### Recursos de aprendizaje
- **📊 Planificación**: [Planificación de Capacidad](docs/pre-deployment/capacity-planning.md) - Validación de recursos
- **💰 Selección**: [Selección de SKU](docs/pre-deployment/sku-selection.md) - Opciones rentables
- **✅ Validación**: [Revisiones previas](docs/pre-deployment/preflight-checks.md) - Scripts automatizados

#### Ejercicios prácticos
- Ejecutar scripts de validación de capacidad
- Optimizar la selección de SKU para costos
- Implementar revisiones automatizadas pre-despliegue

**💡 Resultado del capítulo**: Validar y optimizar despliegues antes de la ejecución

---

### 🚨 Capítulo 7: Solución de Problemas y Depuración
**Prerrequisitos**: Cualquier capítulo de despliegue completado  
**Duración**: 1-1.5 horas  
**Complejidad**: ⭐⭐

#### Lo que aprenderás
- Enfoques sistemáticos para depuración
- Problemas comunes y sus soluciones
- Solución de problemas específica para IA

#### Recursos de aprendizaje
- **🔧 Problemas Comunes**: [Problemas comunes](docs/troubleshooting/common-issues.md) - Preguntas frecuentes y soluciones
- **🕵️ Depuración**: [Guía de depuración](docs/troubleshooting/debugging.md) - Estrategias paso a paso
- **🤖 Problemas de IA**: [Solución de problemas específica para IA](docs/troubleshooting/ai-troubleshooting.md) - Problemas con servicios de IA

#### Ejercicios prácticos
- Diagnosticar fallas de despliegue
- Resolver problemas de autenticación
- Depurar conectividad con servicios de IA

**💡 Resultado del capítulo**: Diagnosticar y resolver problemas comunes de despliegue de forma independiente

---

### 🏢 Capítulo 8: Patrones para Producción y Empresas
**Prerrequisitos**: Capítulos 1-4 completados  
**Duración**: 2-3 horas  
**Complejidad**: ⭐⭐⭐⭐

#### Lo que aprenderás
- Estrategias de despliegue en producción
- Patrones de seguridad empresarial
- Monitoreo y optimización de costos

#### Recursos de aprendizaje
- **🏭 Producción**: [Buenas prácticas de IA en producción](docs/microsoft-foundry/production-ai-practices.md) - Patrones empresariales
- **📝 Ejemplos**: [Ejemplo de microservicios](../../examples/microservices) - Arquitecturas complejas
- **📊 Monitoreo**: [Integración con Application Insights](docs/pre-deployment/application-insights.md) - Monitoreo

#### Ejercicios prácticos
- Implementar patrones de seguridad empresarial
- Configurar monitoreo completo
- Desplegar a producción con gobernanza adecuada

**💡 Resultado del capítulo**: Desplegar aplicaciones listas para empresa con capacidad completa de producción

---

## 🎓 Resumen del Taller: Experiencia de Aprendizaje Práctico

> **⚠️ ESTADO DEL TALLER: Desarrollo Activo**  
> Los materiales del taller están en proceso de desarrollo y refinamiento. Los módulos principales funcionan, pero algunas secciones avanzadas están incompletas. Estamos trabajando activamente para completar todo el contenido. [Seguir progreso →](workshop/README.md)

### Materiales Interactivos del Taller
**Aprendizaje práctico completo con herramientas basadas en navegador y ejercicios guiados**

Nuestros materiales del taller proporcionan una experiencia de aprendizaje estructurada e interactiva que complementa el currículo basado en capítulos anterior. El taller está diseñado para aprendizaje autodidacta y sesiones con instructor.

#### 🛠️ Características del Taller
- **Interfaz basada en navegador**: Taller completo con MkDocs, con búsqueda, copia y temas
- **Integración con GitHub Codespaces**: Configuración de entorno de desarrollo con un clic
- **Ruta de aprendizaje estructurada**: 7 ejercicios guiados (3.5 horas en total)
- **Descubrimiento → Despliegue → Personalización**: Metodología progresiva
- **Entorno DevContainer interactivo**: Herramientas y dependencias preconfiguradas

#### 📚 Estructura del Taller
El taller sigue una metodología de **Descubrimiento → Despliegue → Personalización**:

1. **Fase de Descubrimiento** (45 minutos)
   - Explorar plantillas y servicios de Microsoft Foundry
   - Entender patrones de arquitectura multi-agente
   - Revisar requisitos y prerrequisitos de despliegue

2. **Fase de Despliegue** (2 horas)
   - Despliegue práctico de aplicaciones IA con AZD
   - Configurar servicios y endpoints de Azure IA
   - Implementar patrones de seguridad y autenticación

3. **Fase de Personalización** (45 minutos)
   - Modificar aplicaciones para casos de uso específicos
   - Optimizar para despliegue en producción
   - Implementar monitoreo y gestión de costos

#### 🚀 Cómo comenzar con el Taller
```bash
# Opción 1: GitHub Codespaces (Recomendado)
# Haga clic en "Code" → "Create codespace on main" en el repositorio

# Opción 2: Desarrollo local
git clone https://github.com/microsoft/azd-for-beginners.git
cd azd-for-beginners/workshop
# Siga las instrucciones de configuración en workshop/README.md
```

#### 🎯 Resultados de aprendizaje del Taller
Al completar el taller, los participantes podrán:
- **Desplegar aplicaciones de IA en producción**: Usar AZD con servicios Microsoft Foundry
- **Dominar arquitecturas multi-agente**: Implementar soluciones coordinadas de agentes IA
- **Implementar mejores prácticas de seguridad**: Configurar autenticación y control de accesos
- **Optimizar para escala**: Diseñar despliegues rentables y de alto rendimiento
- **Solucionar problemas de despliegue**: Resolver problemas comunes de forma independiente

#### 📖 Recursos del Taller
- **🎥 Guía interactiva**: [Materiales del taller](workshop/README.md) - Ambiente de aprendizaje basado en navegador
- **📋 Instrucciones paso a paso**: [Ejercicios guiados](../../workshop/docs/instructions) - Guías detalladas
- **🛠️ Laboratorio de IA del taller**: [Laboratorio IA](docs/microsoft-foundry/ai-workshop-lab.md) - Ejercicios enfocados en IA
- **💡 Inicio Rápido**: [Guía de configuración del taller](workshop/README.md#quick-start) - Configuración del entorno

**Ideal para**: Formación corporativa, cursos universitarios, aprendizaje autodidacta y bootcamps para desarrolladores.

---

## 📖 ¿Qué es Azure Developer CLI?

Azure Developer CLI (azd) es una interfaz de línea de comandos centrada en el desarrollador que acelera el proceso de creación y despliegue de aplicaciones en Azure. Proporciona:

- **Despliegues basados en plantillas** - Usa plantillas preconstruidas para patrones comunes de aplicaciones
- **Infraestructura como Código** - Gestiona recursos Azure con Bicep o Terraform  
- **Flujos de trabajo integrados** - Provisión, despliegue y monitoreo de aplicaciones sin problemas
- **Amigable para desarrolladores** - Optimizado para productividad y experiencia del desarrollador

### **AZD + Microsoft Foundry: Perfecto para despliegues de IA**

**¿Por qué AZD para soluciones IA?** AZD aborda los principales desafíos que enfrentan los desarrolladores de IA:

- **Plantillas preparadas para IA** - Plantillas preconfiguradas para Azure OpenAI, Cognitive Services y cargas ML
- **Despliegues seguros de IA** - Patrones de seguridad integrados para servicios IA, claves API y endpoints de modelos  
- **Patrones de IA para producción** - Mejores prácticas para despliegues de aplicaciones IA escalables y rentables
- **Flujos de trabajo de IA de extremo a extremo** - Desde el desarrollo de modelos hasta el despliegue en producción con monitoreo adecuado
- **Optimización de costos** - Estrategias inteligentes para asignación y escalado de recursos IA
- **Integración con Microsoft Foundry** - Conexión fluida con catálogo y endpoints de modelos Microsoft Foundry

---

## 🎯 Biblioteca de Plantillas y Ejemplos

### Destacado: Plantillas Microsoft Foundry
**¡Comienza aquí si despliegas aplicaciones IA!**

> **Nota:** Estas plantillas muestran varios patrones IA. Algunas son muestras externas de Azure, otras implementaciones locales.

| Plantilla | Capítulo | Complejidad | Servicios | Tipo |
|----------|---------|------------|----------|------|
| [**Comienza con chat IA**](https://github.com/Azure-Samples/get-started-with-ai-chat) | Capítulo 2 | ⭐⭐ | AzureOpenAI + Azure AI Model Inference API + Azure AI Search + Azure Container Apps + Application Insights | Externo |
| [**Comienza con agentes IA**](https://github.com/Azure-Samples/get-started-with-ai-agents) | Capítulo 2 | ⭐⭐ | Azure AI Agent Service + AzureOpenAI + Azure AI Search + Azure Container Apps + Application Insights| Externo |
| [**Demo Azure Search + OpenAI**](https://github.com/Azure-Samples/azure-search-openai-demo) | Capítulo 2 | ⭐⭐ | AzureOpenAI + Azure AI Search + App Service + Storage | Externo |
| [**Inicio rápido OpenAI Chat App**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | Capítulo 2 | ⭐ | AzureOpenAI + Container Apps + Application Insights | Externo |
| [**Agent OpenAI Python Prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | Capítulo 5 | ⭐⭐⭐ | AzureOpenAI + Azure Functions + Prompty | Externo |
| [**Contoso Chat RAG**](https://github.com/Azure-Samples/contoso-chat) | Capítulo 8 | ⭐⭐⭐⭐ | AzureOpenAI + AI Search + Cosmos DB + Container Apps | Externo |
| [**Solución Multi-Agente Retail**](examples/retail-scenario.md) | Capítulo 5 | ⭐⭐⭐⭐ | AzureOpenAI + AI Search + Storage + Container Apps + Cosmos DB | **Local** |

### Destacado: Escenarios de aprendizaje completos
**Plantillas de aplicaciones listas para producción mapeadas a capítulos de aprendizaje**

| Plantilla | Capítulo de aprendizaje | Complejidad | Aprendizaje clave |
|----------|------------------|------------|--------------|
| [**openai-chat-app-quickstart**](https://github.com/Azure-Samples/openai-chat-app-quickstart) | Capítulo 2 | ⭐ | Patrones básicos de despliegue IA |
| [**azure-search-openai-demo**](https://github.com/Azure-Samples/azure-search-openai-demo) | Capítulo 2 | ⭐⭐ | Implementación RAG con Azure AI Search |
| [**ai-document-processing**](https://github.com/Azure-Samples/ai-document-processing) | Capítulo 4 | ⭐⭐ | Integración Document Intelligence |
| [**agent-openai-python-prompty**](https://github.com/Azure-Samples/agent-openai-python-prompty) | Capítulo 5 | ⭐⭐⭐ | Framework de agente y llamadas a funciones |
| [**contoso-chat**](https://github.com/Azure-Samples/contoso-chat) | Capítulo 8 | ⭐⭐⭐ | Orquestación de IA empresarial |
| [**retail-multi-agent-solution**](examples/retail-scenario.md) | Capítulo 5 | ⭐⭐⭐⭐ | Arquitectura multi-agente con agentes Cliente e Inventario |

### Aprendizaje por tipo de ejemplo

> **📌 Ejemplos Locales vs Externos:**  
> **Ejemplos Locales** (en este repositorio) = Listos para usar inmediatamente  
> **Ejemplos Externos** (Azure Samples) = Clonar desde repositorios enlazados

#### Ejemplos Locales (Listos para usar)
- [**Solución Multi-Agente Retail**](examples/retail-scenario.md) - Implementación completa lista para producción con plantillas ARM
  - Arquitectura multi-agente (agentes Cliente + Inventario)
  - Monitoreo y evaluación completos
  - Despliegue con un clic vía plantilla ARM

#### Ejemplos Locales - Aplicaciones en Contenedores (Capítulos 2-5)
**Ejemplos completos de despliegue de contenedores en este repositorio:**
- [**Ejemplos Container App**](examples/container-app/README.md) - Guía completa para despliegues contenerizados
  - [API Flask Simple](../../examples/container-app/simple-flask-api) - API REST básica con escala a cero
  - [Arquitectura Microservicios](../../examples/container-app/microservices) - Despliegue multi-servicio listo para producción
  - Patrones rápidos, producción y avanzados
  - Guía de monitoreo, seguridad y optimización de costos

#### Ejemplos Externos - Aplicaciones simples (Capítulos 1-2)
**Clonar estos repositorios Azure Samples para iniciar:**
- [App Web Simple - Node.js + MongoDB](https://github.com/Azure-Samples/todo-nodejs-mongo) - Patrones básicos de despliegue
- [Sitio Estático - React SPA](https://github.com/Azure-Samples/todo-csharp-sql-swa-func) - Despliegue de contenido estático
- [Container App - Python Flask](https://github.com/Azure-Samples/container-apps-store-api-microservice) - Despliegue API REST

#### Ejemplos Externos - Integración con Bases de Datos (Capítulos 3-4)  
- [App Base de Datos - C# + SQL](https://github.com/Azure-Samples/todo-csharp-sql) - Patrones de conectividad base de datos
- [Funciones + Cosmos DB](https://github.com/Azure-Samples/todo-python-mongo-swa-func) - Flujo de datos serverless

#### Ejemplos Externos - Patrones avanzados (Capítulos 4-8)
- [Microservicios Java](https://github.com/Azure-Samples/java-microservices-aca-lab) - Arquitecturas multi-servicio
- [Container Apps Jobs](https://github.com/Azure-Samples/container-apps-jobs) - Procesamiento en segundo plano  
- [Pipeline ML Empresarial](https://github.com/Azure-Samples/mlops-v2) - Patrones ML listos para producción

### Colecciones de Plantillas Externas
- [**Galería Oficial de Plantillas AZD**](https://azure.github.io/awesome-azd/) - Colección seleccionada de plantillas oficiales y de la comunidad
- [**Plantillas de Azure Developer CLI**](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/azd-templates) - Documentación de plantillas en Microsoft Learn
- [**Directorio de Ejemplos**](examples/README.md) - Ejemplos locales de aprendizaje con explicaciones detalladas

---

## 📚 Recursos y Referencias de Aprendizaje

### Referencias Rápidas
- [**Hoja de Trucos de Comandos**](resources/cheat-sheet.md) - Comandos esenciales de azd organizados por capítulo
- [**Glosario**](resources/glossary.md) - Terminología de Azure y azd  
- [**Preguntas Frecuentes (FAQ)**](resources/faq.md) - Preguntas comunes organizadas por capítulo de aprendizaje
- [**Guía de Estudio**](resources/study-guide.md) - Ejercicios prácticos completos

### Talleres Prácticos
- [**Laboratorio de Taller de IA**](docs/microsoft-foundry/ai-workshop-lab.md) - Hacer que tus soluciones de IA sean desplegables con AZD (2-3 horas)
- [**Guía Interactiva del Taller**](workshop/README.md) - Taller basado en navegador con MkDocs y entorno DevContainer
- [**Ruta de Aprendizaje Estructurada**](../../workshop/docs/instructions) - Ejercicios guiados de 7 pasos (Descubrimiento → Despliegue → Personalización)
- [**Taller AZD para Principiantes**](workshop/README.md) - Material completo para taller práctico con integración de GitHub Codespaces

### Recursos Externos de Aprendizaje
- Documentación de Azure Developer CLI (https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)
- Centro de Arquitectura de Azure (https://learn.microsoft.com/en-us/azure/architecture/)
- Calculadora de Precios de Azure (https://azure.microsoft.com/pricing/calculator/)
- Estado de Azure (https://status.azure.com/)

---

## 🔧 Guía Rápida de Solución de Problemas

**Problemas comunes que enfrentan los principiantes y soluciones inmediatas:**

### ❌ "azd: comando no encontrado"

```bash
# Instalar AZD primero
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
curl -fsSL https://aka.ms/install-azd.sh | bash

# Verificar la instalación
azd version
```

### ❌ "No se encontró suscripción" o "Suscripción no configurada"

```bash
# Listar suscripciones disponibles
az account list --output table

# Establecer suscripción predeterminada
az account set --subscription "<subscription-id-or-name>"

# Establecer para el entorno AZD
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# Verificar
az account show
```

### ❌ "Cuota insuficiente" o "Cuota excedida"

```bash
# Prueba diferentes regiones de Azure
azd env set AZURE_LOCATION "westus2"
azd up

# O usa SKUs más pequeños en desarrollo
# Edita infra/main.parameters.json:
{
  "sku": "B1"  // Instead of "P1V2"
}
```

### ❌ Fallo a la mitad de "azd up"

```bash
# Opción 1: Limpiar y reintentar
azd down --force --purge
azd up

# Opción 2: Solo arreglar la infraestructura
azd provision

# Opción 3: Revisar registros detallados
azd show
azd logs
```

### ❌ "Autenticación fallida" o "Token expirado"

```bash
# Reautenticar
az logout
az login

azd auth logout
azd auth login

# Verificar la autenticación
az account show
```

### ❌ "El recurso ya existe" o conflictos de nombres

```bash
# AZD genera nombres únicos, pero si hay conflicto:
azd down --force --purge

# Entonces reintenta con un entorno nuevo
azd env new dev-v2
azd up
```

### ❌ La implementación de la plantilla tarda demasiado

**Tiempos normales de espera:**
- Aplicación web sencilla: 5-10 minutos
- Aplicación con base de datos: 10-15 minutos
- Aplicaciones de IA: 15-25 minutos (La provisión de OpenAI es lenta)

```bash
# Verificar progreso
azd show

# Si está atascado >30 minutos, revise el Portal de Azure:
azd monitor
# Buscar implementaciones fallidas
```

### ❌ "Permiso denegado" o "Prohibido"

```bash
# Verifica tu rol de Azure
az role assignment list --assignee $(az account show --query user.name -o tsv)

# Necesitas al menos el rol de "Colaborador"
# Pide a tu administrador de Azure que otorgue:
# - Colaborador (para recursos)
# - Administrador de acceso de usuario (para asignaciones de roles)
```

### ❌ No se puede encontrar la URL de la aplicación desplegada

```bash
# Mostrar todos los puntos finales del servicio
azd show

# O abrir el portal de Azure
azd monitor

# Verificar servicio específico
azd env get-values
# Buscar variables *_URL
```

### 📚 Recursos completos para solución de problemas

- **Guía de Problemas Comunes:** [Soluciones detalladas](docs/troubleshooting/common-issues.md)
- **Problemas específicos de IA:** [Solución de problemas de IA](docs/troubleshooting/ai-troubleshooting.md)
- **Guía de depuración:** [Depuración paso a paso](docs/troubleshooting/debugging.md)
- **Obtén ayuda:** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🔧 Guía Rápida de Solución de Problemas

**Problemas comunes que enfrentan los principiantes y soluciones inmediatas:**

<details>
<summary><strong>❌ "azd: comando no encontrado"</strong></summary>

```bash
# Instale AZD primero
# Windows (PowerShell):
winget install microsoft.azd

# macOS:
brew tap azure/azd && brew install azd

# Linux:
curl -fsSL https://aka.ms/install-azd.sh | bash

# Verificar instalación
azd version
```
</details>

<details>
<summary><strong>❌ "No se encontró suscripción" o "Suscripción no configurada"</strong></summary>

```bash
# Listar suscripciones disponibles
az account list --output table

# Establecer suscripción predeterminada
az account set --subscription "<subscription-id-or-name>"

# Configurar para entorno AZD
azd env set AZURE_SUBSCRIPTION_ID "<subscription-id>"

# Verificar
az account show
```
</details>

<details>
<summary><strong>❌ "Cuota insuficiente" o "Cuota excedida"</strong></summary>

```bash
# Prueba con una región diferente de Azure
azd env set AZURE_LOCATION "westus2"
azd up

# O usa SKUs más pequeños en desarrollo
# Edita infra/main.parameters.json:
{
  "sku": "B1"  // Instead of "P1V2"
}
```
</details>

<details>
<summary><strong>❌ Fallo a la mitad de "azd up"</strong></summary>

```bash
# Opción 1: Limpiar y reintentar
azd down --force --purge
azd up

# Opción 2: Solo arreglar la infraestructura
azd provision

# Opción 3: Revisar registros detallados
azd show
azd logs
```
</details>

<details>
<summary><strong>❌ "Autenticación fallida" o "Token expirado"</strong></summary>

```bash
# Reautenticar
az logout
az login

azd auth logout
azd auth login

# Verificar autenticación
az account show
```
</details>

<details>
<summary><strong>❌ "El recurso ya existe" o conflictos de nombres</strong></summary>

```bash
# AZD genera nombres únicos, pero si hay conflicto:
azd down --force --purge

# Entonces reintentar con un entorno nuevo
azd env new dev-v2
azd up
```
</details>

<details>
<summary><strong>❌ La implementación de la plantilla tarda demasiado</strong></summary>

**Tiempos normales de espera:**
- Aplicación web sencilla: 5-10 minutos
- Aplicación con base de datos: 10-15 minutos
- Aplicaciones de IA: 15-25 minutos (La provisión de OpenAI es lenta)

```bash
# Comprobar el progreso
azd show

# Si está atascado >30 minutos, revisar el Portal de Azure:
azd monitor
# Buscar implementaciones fallidas
```
</details>

<details>
<summary><strong>❌ "Permiso denegado" o "Prohibido"</strong></summary>

```bash
# Verifica tu rol de Azure
az role assignment list --assignee $(az account show --query user.name -o tsv)

# Necesitas al menos el rol de "Colaborador"
# Pide a tu administrador de Azure que otorgue:
# - Colaborador (para recursos)
# - Administrador de acceso de usuario (para asignaciones de roles)
```
</details>

<details>
<summary><strong>❌ No se puede encontrar la URL de la aplicación desplegada</strong></summary>

```bash
# Mostrar todos los puntos finales del servicio
azd show

# O abrir el portal de Azure
azd monitor

# Verificar servicio específico
azd env get-values
# Buscar variables *_URL
```
</details>

### 📚 Recursos completos para solución de problemas

- **Guía de Problemas Comunes:** [Soluciones detalladas](docs/troubleshooting/common-issues.md)
- **Problemas específicos de IA:** [Solución de problemas de IA](docs/troubleshooting/ai-troubleshooting.md)
- **Guía de depuración:** [Depuración paso a paso](docs/troubleshooting/debugging.md)
- **Obtén ayuda:** [Azure Discord](https://discord.gg/microsoft-azure) #azure-developer-cli

---

## 🎓 Finalización del Curso y Certificación

### Seguimiento del Progreso
Realiza un seguimiento de tu avance en cada capítulo:

- [ ] **Capítulo 1**: Fundamentos e Inicio Rápido ✅
- [ ] **Capítulo 2**: Desarrollo enfocado en IA ✅  
- [ ] **Capítulo 3**: Configuración y Autenticación ✅
- [ ] **Capítulo 4**: Infraestructura como Código y Despliegue ✅
- [ ] **Capítulo 5**: Soluciones de IA Multi-Agente ✅
- [ ] **Capítulo 6**: Validación y Planificación Previa al Despliegue ✅
- [ ] **Capítulo 7**: Solución de Problemas y Depuración ✅
- [ ] **Capítulo 8**: Patrones para Producción y Empresa ✅

### Verificación del Aprendizaje
Después de completar cada capítulo, verifica tus conocimientos mediante:
1. **Ejercicio Práctico**: Completa el despliegue práctico del capítulo
2. **Revisión de Conocimientos**: Consulta la sección FAQ para tu capítulo
3. **Discusión Comunitaria**: Comparte tu experiencia en Azure Discord
4. **Próximo Capítulo**: Avanza al siguiente nivel de complejidad

### Beneficios al Completar el Curso
Al finalizar todos los capítulos, habrás conseguido:
- **Experiencia en Producción**: Despliegue de aplicaciones reales de IA en Azure
- **Habilidades Profesionales**: Capacidades para despliegues listos para la empresa  
- **Reconocimiento Comunitario**: Miembro activo de la comunidad de desarrolladores de Azure
- **Avance Profesional**: Experiencia demandada en despliegue AZD e IA

---

## 🤝 Comunidad y Soporte

### Obtén Ayuda y Soporte
- **Problemas Técnicos**: [Reporta errores y solicita funcionalidades](https://github.com/microsoft/azd-for-beginners/issues)
- **Preguntas sobre el Aprendizaje**: [Comunidad Microsoft Azure Discord](https://discord.gg/microsoft-azure) y [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)
- **Ayuda Específica de IA**: Únete al [![Microsoft Foundry Discord](https://dcbadge.limes.pink/api/server/nTYy5BXMWG)](https://discord.gg/nTYy5BXMWG)
- **Documentación**: [Documentación oficial de Azure Developer CLI](https://learn.microsoft.com/en-us/azure/developer/azure-developer-cli/)

### Perspectivas Comunitarias del Discord de Microsoft Foundry

**Resultados recientes de la encuesta en el canal #Azure:**
- **45%** de los desarrolladores quieren usar AZD para cargas de trabajo de IA
- **Principales desafíos**: Despliegues multi-servicio, gestión de credenciales, preparación para producción  
- **Más solicitados**: Plantillas específicas para IA, guías de solución de problemas, mejores prácticas

**Únete a nuestra comunidad para:**
- Compartir tus experiencias con AZD + IA y recibir ayuda
- Acceder a versiones preliminares de nuevas plantillas de IA
- Contribuir a las mejores prácticas de despliegue de IA
- Influir en el desarrollo futuro de funciones de IA + AZD

### Contribuir al Curso
¡Aceptamos contribuciones! Por favor lee nuestra [Guía de Contribución](CONTRIBUTING.md) para detalles sobre:
- **Mejoras de Contenido**: Mejorar capítulos y ejemplos existentes
- **Nuevos Ejemplos**: Añadir escenarios y plantillas del mundo real  
- **Traducción**: Ayudar a mantener soporte multilingüe
- **Reportes de Errores**: Mejorar exactitud y claridad
- **Normas Comunitarias**: Seguir nuestras pautas inclusivas de comunidad

---

## 📄 Información del Curso

### Licencia
Este proyecto está licenciado bajo la Licencia MIT - vea el archivo [LICENSE](../../LICENSE) para más detalles.

### Recursos Relacionados de Microsoft Learning

Nuestro equipo produce otros cursos completos de aprendizaje:

<!-- CO-OP TRANSLATOR OTHER COURSES START -->
### LangChain
[![LangChain4j para Principiantes](https://img.shields.io/badge/LangChain4j%20for%20Beginners-22C55E?style=for-the-badge&&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchain4j-for-beginners)
[![LangChain.js para Principiantes](https://img.shields.io/badge/LangChain.js%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=0553D6)](https://aka.ms/langchainjs-for-beginners?WT.mc_id=m365-94501-dwahlin)

---

### Azure / Edge / MCP / Agentes
[![AZD para Principiantes](https://img.shields.io/badge/AZD%20for%20Beginners-0078D4?style=for-the-badge&labelColor=E5E7EB&color=0078D4)](https://github.com/microsoft/AZD-for-beginners?WT.mc_id=academic-105485-koreyst)
[![Edge AI para Principiantes](https://img.shields.io/badge/Edge%20AI%20for%20Beginners-00B8E4?style=for-the-badge&labelColor=E5E7EB&color=00B8E4)](https://github.com/microsoft/edgeai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![MCP para Principiantes](https://img.shields.io/badge/MCP%20for%20Beginners-009688?style=for-the-badge&labelColor=E5E7EB&color=009688)](https://github.com/microsoft/mcp-for-beginners?WT.mc_id=academic-105485-koreyst)
[![Agentes de IA para Principiantes](https://img.shields.io/badge/AI%20Agents%20for%20Beginners-00C49A?style=for-the-badge&labelColor=E5E7EB&color=00C49A)](https://github.com/microsoft/ai-agents-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### Serie de IA Generativa
[![IA Generativa para Principiantes](https://img.shields.io/badge/Generative%20AI%20for%20Beginners-8B5CF6?style=for-the-badge&labelColor=E5E7EB&color=8B5CF6)](https://github.com/microsoft/generative-ai-for-beginners?WT.mc_id=academic-105485-koreyst)
[![IA Generativa (.NET)](https://img.shields.io/badge/Generative%20AI%20(.NET)-9333EA?style=for-the-badge&labelColor=E5E7EB&color=9333EA)](https://github.com/microsoft/Generative-AI-for-beginners-dotnet?WT.mc_id=academic-105485-koreyst)
[![IA Generativa (Java)](https://img.shields.io/badge/Generative%20AI%20(Java)-C084FC?style=for-the-badge&labelColor=E5E7EB&color=C084FC)](https://github.com/microsoft/generative-ai-for-beginners-java?WT.mc_id=academic-105485-koreyst)
[![IA Generativa (JavaScript)](https://img.shields.io/badge/Generative%20AI%20(JavaScript)-E879F9?style=for-the-badge&labelColor=E5E7EB&color=E879F9)](https://github.com/microsoft/generative-ai-with-javascript?WT.mc_id=academic-105485-koreyst)

---
 
### Aprendizaje Básico
[![ML para Principiantes](https://img.shields.io/badge/ML%20for%20Beginners-22C55E?style=for-the-badge&labelColor=E5E7EB&color=22C55E)](https://aka.ms/ml-beginners?WT.mc_id=academic-105485-koreyst)
[![Data Science para Principiantes](https://img.shields.io/badge/Data%20Science%20for%20Beginners-84CC16?style=for-the-badge&labelColor=E5E7EB&color=84CC16)](https://aka.ms/datascience-beginners?WT.mc_id=academic-105485-koreyst)
[![IA para Principiantes](https://img.shields.io/badge/AI%20for%20Beginners-A3E635?style=for-the-badge&labelColor=E5E7EB&color=A3E635)](https://aka.ms/ai-beginners?WT.mc_id=academic-105485-koreyst)
[![Ciberseguridad para Principiantes](https://img.shields.io/badge/Cybersecurity%20for%20Beginners-F97316?style=for-the-badge&labelColor=E5E7EB&color=F97316)](https://github.com/microsoft/Security-101?WT.mc_id=academic-96948-sayoung)
[![Desarrollo Web para Principiantes](https://img.shields.io/badge/Web%20Dev%20for%20Beginners-EC4899?style=for-the-badge&labelColor=E5E7EB&color=EC4899)](https://aka.ms/webdev-beginners?WT.mc_id=academic-105485-koreyst)
[![IoT para Principiantes](https://img.shields.io/badge/IoT%20for%20Beginners-14B8A6?style=for-the-badge&labelColor=E5E7EB&color=14B8A6)](https://aka.ms/iot-beginners?WT.mc_id=academic-105485-koreyst)
[![Desarrollo XR para Principiantes](https://img.shields.io/badge/XR%20Development%20for%20Beginners-38BDF8?style=for-the-badge&labelColor=E5E7EB&color=38BDF8)](https://github.com/microsoft/xr-development-for-beginners?WT.mc_id=academic-105485-koreyst)

---
 
### Serie Copilot
[![Copilot para Programación Asistida por IA](https://img.shields.io/badge/Copilot%20for%20AI%20Paired%20Programming-FACC15?style=for-the-badge&labelColor=E5E7EB&color=FACC15)](https://aka.ms/GitHubCopilotAI?WT.mc_id=academic-105485-koreyst)
[![Copilot para C#/.NET](https://img.shields.io/badge/Copilot%20for%20C%23/.NET-FBBF24?style=for-the-badge&labelColor=E5E7EB&color=FBBF24)](https://github.com/microsoft/mastering-github-copilot-for-dotnet-csharp-developers?WT.mc_id=academic-105485-koreyst)
[![Aventura Copilot](https://img.shields.io/badge/Copilot%20Adventure-FDE68A?style=for-the-badge&labelColor=E5E7EB&color=FDE68A)](https://github.com/microsoft/CopilotAdventures?WT.mc_id=academic-105485-koreyst)
<!-- CO-OP TRANSLATOR OTHER COURSES END -->

---

## 🗺️ Navegación del Curso

**🚀 ¿Listo para comenzar a aprender?**

**Principiantes**: Comienza con [Capítulo 1: Fundamentos y Inicio Rápido](../..)  
**Desarrolladores de IA**: Salta a [Capítulo 2: Desarrollo con IA como Prioridad](../..)  
**Desarrolladores Experimentados**: Empieza con [Capítulo 3: Configuración y Autenticación](../..)

**Próximos Pasos**: [Comenzar Capítulo 1 - Conceptos Básicos de AZD](docs/getting-started/azd-basics.md) →

---

<!-- CO-OP TRANSLATOR DISCLAIMER START -->
**Aviso legal**:
Este documento ha sido traducido utilizando el servicio de traducción automática [Co-op Translator](https://github.com/Azure/co-op-translator). Aunque nos esforzamos por la precisión, tenga en cuenta que las traducciones automáticas pueden contener errores o inexactitudes. El documento original en su idioma nativo debe considerarse la fuente autorizada. Para información crítica, se recomienda una traducción profesional realizada por un humano. No somos responsables por malentendidos o interpretaciones erróneas derivadas del uso de esta traducción.
<!-- CO-OP TRANSLATOR DISCLAIMER END -->