# Terminal Pro Suite 🚀

Advanced Terminal application s integrací **Framer**, **Figma**, **Canva Pro** a **Claude Code**.

## ✨ Funkčnosti

### 🎨 Design Integration
- **Figma** - Import designů a automatická konverze
- **Canva Pro** - Tvorba grafiky a assets
- **Framer** - Interaktivní komponenty a animace
- **Figma Aura** - AI-powered design asistence

### 💻 Terminal Features
- Pokročilý CLI s full funkcionalitou
- Interaktivní příkazy a menu
- Real-time logging a monitoring
- Error handling a recovery
- Custom theme podpora

### 🤖 Claude Code Integration
- AI-powered kód generování
- Automatické code completion
- Smart refactoring asistence
- Code review a optimization

### 📊 Workflow Management
- Project management CLI
- Task automation
- Asset synchronizace
- Version control integrovaný

## 🛠️ Instalace

```bash
git clone https://github.com/jakub1duch-a11y/terminal-pro-suite.git
cd terminal-pro-suite
npm install
npm run setup
```

## ⚙️ Konfigurace

1. Zkopíruj `.env.example` na `.env`:
```bash
cp .env.example .env
```

2. Vyplň API klíče:
   - **Figma**: https://www.figma.com/developers/api
   - **Canva**: https://www.canva.com/developers
   - **Claude**: https://console.anthropic.com
   - **Framer**: https://www.framer.com/developers

## 🚀 Spuštění

```bash
# Development
npm run dev

# Production
npm run build
npm start
```

## 📋 Hlavní Příkazy

```bash
# Terminal help
terminal-pro --help

# Design synchronizace
terminal-pro design:sync

# Figma import
terminal-pro figma:import --file-id <ID>

# Canva asset management
terminal-pro canva:assets

# Claude code generation
terminal-pro claude:generate --prompt "your prompt"

# Framer components
terminal-pro framer:list

# Project management
terminal-pro project:init
terminal-pro task:add <task>
terminal-pro task:list
```

## 📁 Struktura Projektu

```
terminal-pro-suite/
├── src/
│   ├── cli.ts                 # Main CLI entry point
│   ├── commands/              # CLI команды
│   │   ├── design.ts         # Design commands
│   │   ├── figma.ts          # Figma integration
│   │   ├── canva.ts          # Canva integration
│   │   ├── claude.ts         # Claude Code commands
│   │   ├── framer.ts         # Framer integration
│   │   └── project.ts        # Project management
│   ├── services/              # Business logic
│   │   ├── figma-service.ts
│   │   ├── canva-service.ts
│   │   ├── claude-service.ts
│   │   ├── framer-service.ts
│   │   └── project-service.ts
│   ├── utils/
│   │   ├── logger.ts         # Logging utility
│   │   ├── config.ts         # Configuration loader
│   │   ├── api-client.ts     # HTTP client
│   │   └── formatters.ts     # Output formatting
│   └── types/
│       └── index.ts          # TypeScript types
├── scripts/
│   ├── setup.js              # Initial setup
│   └── design-sync.js        # Design sync script
├── tests/                     # Jest tests
├── .env.example               # Environment template
├── package.json
├── tsconfig.json
└── README.md
```

## 🔗 API Integrations

### Figma
- Automatický import designů
- Component extraction
- Variant management
- Export na více formátů

### Canva Pro
- Asset library management
- Template creation
- Batch export
- Version history

### Claude Code
- Code generation z popisu
- Smart refactoring
- Type checking
- Documentation generation

### Framer
- Component library management
- Interactive previews
- Prototype export
- Design-to-code

## 📝 Licença

MIT License - viz LICENSE soubor

## 👨‍💻 Autor

**jakub1duch-a11y** - [GitHub](https://github.com/jakub1duch-a11y)

## 🤝 Přispívání

Přispívání jsou vítána! Prosím, vytvoř pull request nebo otevři issue.

## 📞 Kontakt

Máš dotazy nebo nápady? Otevři [GitHub Discussion](https://github.com/jakub1duch-a11y/terminal-pro-suite/discussions)
