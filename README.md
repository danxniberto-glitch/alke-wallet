Alke Wallet - Trabajo Práctico M2 Frontend


Billetera digital simulada desarrollada para el Módulo 2 - Fundamentos del Desarrollo Frontend.
Implementa todas las funcionalidades requeridas: login seguro, gestión de saldo, transferencias con contactos y historial sincronizado.

🚀 Demo Rápido
Abrir index.html en cualquier navegador

Credenciales Demo:

text
Usuario: admin
Contraseña: 1234

📱 Pantallas del Sistema
text
index.html     → Landing / Bienvenida
login.html     → Autenticación segura
menu.html      → Dashboard principal
deposit.html   → Depósitos con validación
sendmoney.html → Transferencias + contactos
transactions.html → Historial completo

🛠️ Tecnologías Stack
xml
├── HTML5 (Semántica)
├── CSS3 (Variables + Gradientes)
├── Bootstrap 5.3.3 (Responsive)
├── JavaScript Vanilla (localStorage)
├── Google Fonts (Roboto)
└── Git + GitHub (Feature Branch Workflow)

Paleta Colores Fintech:

Primary: #1e3a8a    Accent: #3b82f6
Success: #10b981    Danger: #ef4444
Background: #f8fafc


📂 Estructura del Proyecto
text
alke-wallet/
├── index.html          # Landing
├── login.html          # Autenticación
├── menu.html           # Dashboard
├── deposit.html        # Depósitos
├── sendmoney.html      # Transferencias
├── transactions.html   # Historial
├── styles.css          # Estilos globales
├── README.md           # 📄 Este archivo
└── .gitignore          # Limpieza repo

🔄 Flujo GitHub Implementado
text
main                 → Código estable
├── feature/login    → [MERGED] Validación
├── feature/transacciones → [MERGED] Transferencias
└── feature/depositos → [MERGED] Depósitos

Commits Conventional:
feat(login): validación credenciales
feat(transacciones): autocompletar contactos
feat(depositos): gestión saldo persistente

📊 Características Técnicas
javascript
// Persistencia localStorage
localStorage: ['saldo', 'contactos', 'historialMovimientos']

🙌 Contribuidores

👤 Desarrollador Frontend Daniel Morales
💻 Trabajo Práctico M2 - Fundamentos Frontend
📅 Enero 2026
📄 Licencia: Proyecto educativo - Trabajo Práctico Módulo 2. Uso libre para portafolio.
