
# Sikuar on Starknet

> A privacy-first, zero-knowledge-native data infrastructure for trust, dignity, and decentralized ESG—now a full SaaS platform.

---

## 📖 Table of Contents

1. [Problem](#problem)  
2. [Solution – Sikuar](#solution--sikuar)  
3. [Why Starknet?](#why-starknet)  
4. [Use Cases](#use-cases)  
5. [What We’re Building Next](#what-we’re-building-next)  
6. [Ask](#ask)  
7. [Sikuar SaaS Platform](#sikuar-saas-platform)  
8. [README Técnico de SIKUAR](#readme-técnico-de-sikuar)  
   - [🚀 Inicialización del Proyecto](#🚀-inicialización-del-proyecto)  
   - [🏃‍♂️ Ejecución del Proyecto](#🏃‍♂️-ejecución-del-proyecto)  
   - [📁 Estructura del Proyecto](#📁-estructura-del-proyecto)  
   - [🔧 Componentes Principales](#🔧-componentes-principales)  
   - [⚙️ Configuración Técnica](#⚙️-configuración-técnica)  
   - [🔐 Variables de Entorno Requeridas](#🔐-variables-de-entorno-requeridas)  
   - [📚 Flujo de Trabajo](#📚-flujo-de-trabajo)  
   - [🧪 Tecnologías Utilizadas](#🧪-tecnologías-utilizadas)  
   - [📋 Consideraciones Adicionales](#📋-consideraciones-adicionales)  

---

## Problem

In communities and institutions across Latin America (and globally), people often need to report abuse, participate in sensitive surveys, or provide feedback — but they’re forced to choose between anonymity and legitimacy. This creates data black holes in HR systems, public services, and AI pipelines. The result:

- ❌ No trust in reporting channels  
- ❌ Biased ESG reports  
- ❌ Unusable or unethical datasets for AI  

---

## Solution – Sikuar

We’re building a ZK-native data collection layer on Starknet that allows people to:

- ✅ Submit sensitive information (e.g. violence reports, climate surveys) anonymously but verifiably  
- ✅ Receive non-transferable NFTs (soulbound tokens) as proof of participation  
- ✅ Maintain data sovereignty, traceability and auditability — without surveillance  

> **Status:** Front-end and dashboard components are live.  
> Next up: full ZK identity verification and on-chain tokenization of participation.

---

## Why Starknet?

- **ZK-native execution** — perfect fit for privacy, proofs of participation, and data authenticity  
- **Cairo** — enables scalable, verifiable computation for sensitive environments  
- **Community** — Starknet supports public goods, infrastructure, and real-world impact  

---

## Use Cases

- **ESG SaaS for corporations** (HR, compliance, climate & ethics reporting)  
- **Safe anonymous reporting** in vulnerable territories (e.g. Amazon, mining zones)  
- **Integrity verification** for decentralized AI data pipelines  

---

## What We’re Building Next

- Integrating identity proofing (via SDKs like Chipi) + optional DID systems  
- Starknet NFT minting for verified, anonymous participation  
- Modular ZK form engine for governments, NGOs, and enterprise ESG systems  

---

## Ask

We’re looking for:

- 🎁 **Grants** — Starknet grants for ZK form modules & Cairo dev support  
- 🤝 **Collaborators** — integrations (ZK KYC, AI governance, compliance tooling)  
- 🧠 **Mentors & Researchers** — co-builders who care about privacy, impact, and trustless evidence  

> **Sikuar is how we protect the truth — without exposing the vulnerable.**  
> Let’s make dignity programmable. 🛡️🧬  

---

## Sikuar SaaS Platform

Sikuar is a SaaS platform that empowers companies to prevent workplace risks, foster a positive organizational culture, and achieve ESG compliance through anonymous reporting technology and ethical participation traceability. It leverages Zero-Knowledge Proofs (ZKPs) and non-transferable NFTs (soulbound tokens) to ensure privacy and verifiable compliance.

### 🛑 The Problem Sikuar Solves

- **Silence and fear in the workplace:** Employees hesitate to report harassment, discrimination, or misconduct due to fear of retaliation, job loss, or lack of trust in internal channels.  
- **False signals in workplace climate reports:** Internal surveys often yield biased or overly positive data, leading to misleading insights and poor strategic decisions.  
- **Reputational and compliance risk:** Without secure, ethical reporting systems, companies face legal claims, loss of talent, diminished workplace trust, and poor ESG or audit scores.  
- **No ethical traceability of participation:** Current systems can't prove ethical workforce engagement without compromising privacy.

### 🛠️ How Sikuar Solves It

- Secure, anonymous reporting and survey platform using **Zero-Knowledge Proofs (ZKPs)** to validate participation without revealing identity.  
- Issues **non-transferable NFTs (soulbound tokens)** to confirm survey completion or protocol compliance—without collecting personal data.  
- Real-time dashboard for HR and ESG teams with aggregated reports and red flag alerts.  
- Ethical traceability and measurable compliance aligned with ESG frameworks and privacy standards.

> **Sikuar offers companies a modular, secure infrastructure to improve ESG compliance, prevent workplace risks, and foster a culture of equality through technological tools for anonymous reporting, participation traceability, and privacy-guaranteed sensitive data management.**

### 🧩 What Do We Offer?

1. **Usage license (SaaS)**  
   - Anonymous or verifiable whistleblowing channel  
   - Secure workplace climate surveys (identity validated via ZKP)  
   - ESG analytics dashboard and key indicators  
   - Downloadable reports for audits and certifications  

2. **On-chain verification and identity services**  
   - Private participation validation via Chipi SDK  
   - Issuance of participation NFTs (climate surveys, training, compliance)  
   - Integration with official or institutional digital identity  

3. **Consultancy & custom setup**  
   - Adapting forms and protocols  
   - Training for HR and ethics teams  
   - Integration with internal systems (intranet, apps, corporate email)  

### 🎯 Who Is It For?

- Medium and large companies in hospitality, tourism, healthcare, manufacturing, agroindustry  
- Multinationals with ESG requirements  
- Companies with high turnover or reputational risk  
- Organizations aiming to improve workplace climate or achieve certifications (EcoVadis, B Corp, ESG ratings)  

### 📈 Business Model

| Revenue Source           | Model                   | Notes                                             |
|--------------------------|-------------------------|---------------------------------------------------|
| SaaS Licenses            | Annual subscription     | Scaled by company size (number of employees)      |
| Verification services    | Pay-per-use / API       | Per validated survey or issued NFT                |
| Integration consultancy  | One-time or monthly fee | Includes technical setup and ESG alignment        |

### 🎖️ What Makes Us Unique?

- Use of **ZK Proofs** for anonymous yet legitimate participation  
- **Ethical data tokenization** (compliance without surveillance)  
- Native alignment with **ESG certifications** and external audits  

---

# README Técnico de SIKUAR

## 🚀 Inicialización del Proyecto

### Requisitos Previos

- Node.js (v18 o superior)  
- PNPM (gestor de paquetes)  
- Una cuenta en [Clerk](https://clerk.com/) para la autenticación  
- Una cuenta en [Chipi](https://www.chipi.dev/) para interactuar con contratos Starknet  

### Instalación

1. Clona el repositorio y accede al directorio:
   ```bash
   git clone https://github.com/tu-usuario/sikuar-nft.git
   cd sikuar-nft
````

2. Instala las dependencias:

   ```bash
   pnpm install
   ```
3. Copia el fichero de ejemplo de variables de entorno:

   ```bash
   cp example.env .env.local
   ```
4. Edita `.env.local` y añade tus claves API:

   ```env
   # Clerk
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=tu_clave_publica_de_clerk
   CLERK_SECRET_KEY=tu_clave_secreta_de_clerk

   # Chipi & Starknet
   NEXT_PUBLIC_CHIPI_PUBLIC_KEY=tu_clave_publica_de_chipi
   NEXT_PUBLIC_STARKNET_RPC_URL=https://starknet.rpc.endpoint
   CONTRACT_ADDRESS=0xTuDireccionDeContrato
   ```

---

## 🏃‍♂️ Ejecución del Proyecto

### Desarrollo Local

```bash
pnpm dev
```

Accede a `http://localhost:3000`.

### Compilar para Producción

```bash
pnpm build
```

### Iniciar en Modo Producción

```bash
pnpm start
```

---

## 📁 Estructura del Proyecto

```
sikuar-nft/
├── .next/                       # Archivos generados por Next.js
├── app/                         # Directorio principal de la aplicación Next.js
│   ├── contracts/              # Contratos inteligentes en Cairo
│   ├── form/                   # Página del formulario de denuncias
│   ├── login/                  # Página de login y onboarding
│   ├── globals.css             # Estilos globales CSS
│   ├── layout.tsx              # Layout principal de la aplicación
│   ├── page.tsx                # Página principal
│   ├── provider.tsx            # Proveedores de contexto
│   └── StarknetProviderWrapper.tsx # Wrapper para el proveedor de Starknet
├── components/                 # Componentes reutilizables
│   └── ui/                     # Componentes de interfaz (shadcn/ui)
├── hooks/                      # Custom hooks
├── lib/                        # Utilidades y funciones auxiliares
├── public/                     # Archivos estáticos
├── styles/                     # Estilos adicionales
└── types/                      # Definiciones de tipos TypeScript
```

---

## 🔧 Componentes Principales

### Autenticación y Wallet

* El sistema utiliza Clerk para la autenticación de usuarios
* En la página de onboarding (`app/login/page.tsx`), se crea un wallet Starknet para el usuario
* El PIN del usuario se utiliza para encriptar la clave privada del wallet

### Formulario de Denuncias

* La página principal del formulario está en `app/form/page.tsx`
* Permite a los usuarios enviar denuncias que se registran en la blockchain Starknet
* Las denuncias se convierten en NFTs no transferibles (soulbound tokens)

### Contrato Inteligente

* El contrato principal está en `app/contracts/SikuarNft.cairo`
* Implementa un NFT no transferible usando el estándar ERC-721
* Cada denuncia se registra como un hash en la blockchain

---

## ⚙️ Configuración Técnica

### Middleware

El archivo `middleware.ts` controla:

* Redirecciones para usuarios no autenticados
* Redirecciones para usuarios sin wallet a la página de onboarding

### Integración con Starknet

* La aplicación utiliza Chipi SDK para interactuar con contratos en Starknet
* El archivo `StarknetProviderWrapper.tsx` proporciona el contexto de Starknet

---

## 🔐 Variables de Entorno Requeridas

```env
# Clerk Authentication
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

# Chipi SDK
NEXT_PUBLIC_CHIPI_PUBLIC_KEY=

# Starknet
NEXT_PUBLIC_STARKNET_RPC_URL=
CONTRACT_ADDRESS=
```

---

## 📚 Flujo de Trabajo

1. Los usuarios se registran con Clerk
2. Crean un wallet Starknet protegido con PIN durante el onboarding
3. Pueden enviar denuncias a través del formulario
4. Las denuncias se convierten en hashes y se almacenan en la blockchain
5. Se emite un NFT como comprobante de la denuncia

---

## 🧪 Tecnologías Utilizadas

* **Frontend**: Next.js, React, Tailwind CSS, shadcn/ui
* **Autenticación**: Clerk
* **Blockchain**: Starknet, Chipi SDK
* **Smart Contracts**: Cairo
* **Estilado**: Tailwind CSS, CSS Modules

---

## 📋 Consideraciones Adicionales

* Este proyecto utiliza el middleware de Clerk para proteger rutas
* Los contratos deben ser desplegados previamente en la red de Starknet
* La dirección del contrato desplegado debe configurarse en `CONTRACT_ADDRESS` en `.env.local`


