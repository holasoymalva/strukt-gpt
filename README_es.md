# 🏗️ Strukt GPT 🦙

> *"Infrastructure as simple as ordering tacos."*

![Strukt Banner](https://placehold.co/1200x300/5046e4/ffffff?text=Strukt+GPT:+Infrastructure+por+conversación&font=montserrat)

[![Versión](https://img.shields.io/badge/version-0.1.0-brightgreen)](https://github.com/holasoymalva/strukt-gpt)
[![Estado](https://img.shields.io/badge/estado-MVP-orange)](https://github.com/holasoymalva/strukt-gpt)
[![Hecho con 💜 en LATAM](https://img.shields.io/badge/hecho%20con%20%F0%9F%92%9C-en%20LATAM-blueviolet)](https://github.com/holasoymalva)

## 🪄 ¿Qué es Strukt?

Strukt es como ese amigo ingeniero que siempre te resuelve todo - pero para tu infraestructura en la nube. Es una aplicación de IA que convierte tus descripciones en español cotidiano en código Terraform profesional, sin tener que aprender HCL o recordar la sintaxis de AWS.

**Ejemplo:**
> "Necesito una Lambda que se active cuando suben archivos a S3 y guarde datos en DynamoDB"

Y ¡BAM! 💥 Tienes código Terraform listo para implementar. Así de simple.

## 🚀 Características

- 🗣️ **Infraestructura por conversación**: Descríbela como le explicarías a tu abuela
- 🧠 **Potenciado por Claude**: La IA que realmente entiende lo que necesitas
- ☁️ **Enfocado en AWS**: Por ahora solo AWS, pero pronto GCP y Azure (¡paciencia, che!)
- 📋 **Código listo para producción**: No más copiar y pegar de StackOverflow
- 🔄 **Conversación continua**: Refina tu infraestructura con preguntas de seguimiento

## 🖥️ Demo

![Strukt Demo](https://placehold.co/800x450/48507c/ffffff?text=Demo+de+Strukt+GPT&font=montserrat)

## 🛠️ Instalación

¿Ansioso por probarlo? Aquí tienes todo lo que necesitas:

### Prerrequisitos
- Node.js (v16+)
- NPM o Yarn
- Una clave API de Anthropic (para Claude)
- Mate y alfajores para la sesión de código (opcional pero recomendado)

### Instalación Local

```bash
# Clona el repo, ¡pero con ganas!
git clone https://github.com/holasoymalva/strukt-gpt.git

# Entra al directorio como Pedro por su casa
cd strukt-gpt

# Instala dependencias (tómate un mate mientras esperas)
npm install
# o si eres team Yarn
yarn install

# Crea un archivo .env.local y agrega tu API key
echo "ANTHROPIC_API_KEY=tu_clave_secreta_aquí" > .env.local

# ¡A darle átomos!
npm run dev
# o con Yarn
yarn dev
```

Ahora abre tu navegador en `http://localhost:3000` y ¡listo! A generar infraestructura como si fuera una pachanga.

## 🌎 Despliegue en Vercel

¿Quieres presumir con tus amigos? ¡Despliégalo en Vercel!

1. Haz fork de este repo (o clónalo a tu cuenta)
2. Conéctalo en [Vercel](https://vercel.com)
3. Configura tu variable de entorno `ANTHROPIC_API_KEY`
4. Dale a "Deploy" y ¡BAM! 💥 Tu app en producción

## 👨‍💻 Uso

### 1. Describe tu infraestructura

```
Quiero un clúster de Kubernetes con autoescalado y monitoreo para nuestra aplicación de delivery de empanadas
```

### 2. Obtén código Terraform mágicamente

```hcl
# Provider configuration
provider "aws" {
  region = var.region
}

# Variables
variable "region" {
  description = "AWS region"
  default     = "us-east-1"
}

variable "cluster_name" {
  description = "Name of the EKS cluster"
  default     = "empanadas-delivery-cluster"
}

# ... más código Terraform magnífico ...
```

### 3. ¡Implementa y disfruta!

## 🤝 Contribuciones

¡Queremos tu ayuda para hacer de Strukt algo grandioso!

1. Haz fork del repo (dale sin miedo)
2. Crea tu rama de feature (`git checkout -b feature/empanadas-support`)
3. Commitea tus cambios (`git commit -m 'Agregado soporte para infraestructura de empanadas'`)
4. Haz push a tu rama (`git push origin feature/empanadas-support`)
5. Abre un Pull Request y ¡listo!

## 🗺️ Roadmap

- [ ] Soporte para GCP (¡próximamente!)
- [ ] Soporte para Azure (también próximamente, pero un poco después)
- [ ] Autenticación de usuarios (para guardar tus infras favoritas)
- [ ] Integración con Terraform Cloud
- [ ] Aplicación móvil (para infraestructura sobre la marcha)
- [ ] Modo "Asado" - optimización de infraestructura para el fin de semana

## 🧠 El Equipo Detrás de Strukt

Somos un equipo de ingenieros LATAM obsesionados con hacer que la infraestructura sea tan fácil como pedir un delivery.

## 🔐 Seguridad

No almacenamos tu código. Lo que pasa en Strukt, se queda en Strukt (a menos que tú lo guardes).

## 📜 Licencia

Este proyecto está licenciado bajo la Licencia MIT - mira el archivo [LICENSE](LICENSE) para más detalles.

## 🙏 Agradecimientos

- A todas las abuelas que inspiraron este proyecto con sus preguntas como "¿Qué es eso de la nube, mijito?"
- A los proveedores de café que mantuvieron a nuestro equipo funcionando
- A todos los ingenieros de infraestructura que han sufrido escribiendo Terraform a mano

---

<p align="center">
  <img src="https://placehold.co/150x150/5046e4/ffffff?text=Strukt&font=montserrat" alt="Strukt Logo">
</p>

<p align="center">
  Hecho con 💜 desde LATAM para el mundo
</p>

<p align="center">
  <a href="https://twitter.com/holasoymalva">Twitter</a> •
  <a href="https://github.com/holasoymalva">GitHub</a> •
  <a href="https://www.linkedin.com/in/malvabombom/">LinkedIn</a>
</p>
