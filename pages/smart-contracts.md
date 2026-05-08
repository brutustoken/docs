# Smart Contracts de Brutus.finance

## Contratos Inteligentes en la Blockchain de Tron

Los **contratos inteligentes** son la base tecnológica fundamental de todos los productos de Brutus.finance. Estos programas se ejecutan de manera autónoma y transparente en la blockchain de Tron.

---

## ¿Qué es un Smart Contract?

Un **contrato inteligente** es un programa informático que se ejecuta automáticamente en la blockchain cuando se cumplen condiciones predefinidas. En el caso de Brutus.finance, estos contratos gestionan:

- La emisión y gestión de tokens
- El staking y distribución de rendimientos
- El alquiler de recursos de red
- La lotería y selección de ganadores
- La gobernanza del protocolo

---

## Estándares Utilizados

### TRC-20 (Tokens Fungibles)
Utilizado para los tokens **BRUT** y **BRST**. Define funciones estándar como:
- `transfer(address _to, uint256 _value)`
- `balanceOf(address _owner)`
- `approve(address _spender, uint256 _value)`

### TRC-721 (Tokens No Fungibles)
Utilizado para los NFTs de **Brutus Gallery (BRGY)**. Define funciones como:
- `mint(address _to, uint256 _tokenId)`
- `ownerOf(uint256 _tokenId)`
- `safeTransferFrom(address _from, address _to, uint256 _tokenId)`

---

## Contratos Principales

### 1. BRUT Token Contract
- **Estándar:** TRC-20
- **Función:** Emisión y gestión del token BRUT
- **Característica:** Respaldo automatizado en USDT
- **Verificación:** Pública en Tronscan

### 2. BRST Staking Contract
- **Estándar:** TRC-20
- **Función:** Gestión del staking automatizado
- **Características:**
  - Acumulación automática de rendimientos
  - Interés compuesto
  - Delegación de recursos

### 3. BRLT Lottery Contract
- **Estándar:** NFT
- **Función:** Gestión de la lotería descentralizada
- **Características:**
  - Sorteos automáticos y verificables
  - Distribución de premios del pool
  - Registro permanente de participantes

### 4. Resource Pool Contract
- **Función:** Gestión del pool de alquiler de recursos
- **Características:**
  - Delegación automática de energía y ancho de banda
  - Distribución de rendimientos a proveedores
  - Gestión dinámica del pool

---

## Seguridad de los Contratos

### Prácticas de Seguridad
- ✅ **Auditorías internas** — Revisión continua del código
- ✅ **Revisión cruzada** — Mínimo 2 revisores por cambio de código
- ✅ **Bug Bounty** — Programa permanente de recompensas por hallazgo de vulnerabilidades
- ✅ **Testing automatizado** — Cobertura superior al 90%
- ✅ **Auditorías externas** — Antes de cada lanzamiento mayor
- ✅ **Simulacros de incidentes** — Pruebas periódicas de respuesta

### Vulnerabilidades Comunes Mitigadas
- Reentrancia — Protección con modificadores y patrones de verificación
- Desbordamiento de enteros — Uso de librerías de SafeMath
- Control de acceso — Roles y permisos estrictos
- Manipulación de oráculos — Fuentes de datos verificadas

---

## Verificación en Blockchain

Todos los contratos inteligentes de Brutus.finance pueden ser **verificados públicamente**:

1. Accede a **[Tronscan](https://tronscan.io)**
2. Busca la dirección del contrato correspondiente
3. Verifica el código fuente y las interacciones

---

## Principios de Diseño

| Principio | Descripción |
|-----------|-------------|
| **Open Source** | Todo el código es público y verificable |
| **Immutabilidad** | Los contratos una vez desplegados no se alteran arbitrariamente |
| **Transparencia** | Todas las operaciones son visibles en cadena |
| **Eficiencia** | Optimización del consumo de energía y gas |
| **Modularidad** | Diseño que permite extensión sin afectar componentes existentes |

---

## Información Técnica

- **Lenguaje:** Solidity
- **Blockchain:** Tron (TVM compatible con EVM)
- **Repositorio:** [github.com/brutustoken/smart-contracts](https://github.com/brutustoken/smart-contracts)
- **Herramientas de desarrollo:** Remix, TronBox, Hardhat

## Aviso

> ⚠️ Esta información es con fines educativos e informativos. No constituye asesoramiento financiero. Investiga y evalúa los riesgos antes de invertir.