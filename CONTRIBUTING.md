# Contribuir al Proyecto

¡Gracias por tu interés en contribuir a la documentación de Brutus.finance!

## Guía Rápida

### Requisitos
- Node.js (v14+)
- HonKit CLI: `npm install -g honkit`

### Estructura del Proyecto
```
brutus-finance-docs/
├── README.md           # Página principal
├── SUMMARY.md          # Índice / Tabla de contenidos
├── GLOSSARY.md         # Glosario de términos
├── gitbook.json        # Configuración del libro
├── styles/
│   └── website.styl    # Estilos personalizados
├── pages/              # Contenido por sección
│   ├── about-us.md
│   ├── products.md
│   ├── brut.md
│   ├── brst.md
│   ├── brgy.md
│   ├── resource-rental.md
│   ├── lottery.md
│   ├── cirotrx.md
│   ├── technology.md
│   ├── tron-blockchain.md
│   ├── tron-energy.md
│   ├── smart-contracts.md
│   ├── energy-cards.md
│   ├── metrics.md
│   ├── governance.md
│   ├── organization.md
│   ├── legal-framework.md
│   ├── value-distribution.md
│   ├── security.md
│   ├── getting-started.md
│   ├── first-steps.md
│   ├── connect-wallet.md
│   ├── provider-guide.md
│   ├── blog.md
│   └── blog/
│       ├── cirotrx.md
│       ├── brst-1-69.md
│       ├── energy-bot-updates.md
│       ├── brst-1-5.md
│       ├── locking-updates.md
│       └── become-provider.md
│       └── faq.md
│       └── community.md
└── _book/              # (Generado) Archivos HTML compilados
```

## Cómo Editar

### 1. Editar un archivo Markdown
- Abre cualquier archivo `.md` en la carpeta `pages/`
- Usa la sintaxis **Markdown estándar**
- Guarda los cambios

### 2. Vista previa local
```bash
honkit serve
```
Esto abrirá una vista previa en `http://localhost:4000` con recarga automática.

### 3. Construir el sitio
```bash
honkit build
```
Los archivos HTML generados se encuentran en la carpeta `_book/`.

## Reglas de Estilo

- Usar **Markdown estándar** para todo el contenido
- Los encabezados principales (`#`) deben coincidir con los títulos en `SUMMARY.md`
- Agregar `> ⚠️` para advertencias y avisos legales
- Usar tablas para datos comparativos
- Mantener el tono informativo y educativo
- Agregar disclaimers financieros donde sea relevante

## Cómo Agregar una Nueva Página

1. Crea un nuevo archivo `.md` en `pages/` o `pages/blog/`
2. Agrega la entrada correspondiente en `SUMMARY.md`
3. Rebuild: `honkit build`

## Cómo Agregar/Actualizar Imágenes

1. Sube la imagen a la carpeta `images/`
2. Referencia en Markdown: `![descripción](images/nombre.png)`
3. Alternativamente, usa URLs externas

## Instalar HonKit (si no lo tienes)
```bash
npm install -g honkit
```

## Aviso
Todas las contribuciones están sujetas a revisión. El contenido debe ser factual, respetuoso y relevante para el ecosistema Brutus.finance.