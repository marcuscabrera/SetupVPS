# SetupVPS - Auto-Instalador Orion Design

Bem-vindo ao repositório oficial do **SetupVPS** (Self-Hosted AI). Este projeto oferece um instalador automatizado robusto para implantar rapidamente um ecossistema completo de aplicações de Inteligência Artificial, Automação, CRM e Banco de Dados em seu próprio servidor VPS.

Desenvolvido para facilitar a vida de desenvolvedores e empreendedores, o script automatiza a configuração do ambiente (Docker, Traefik) e a instalação de ferramentas populares como n8n, Typebot, Chatwoot e Evolution API com apenas alguns cliques.

## 🚀 Funcionalidades Principais

* **Instalação Automatizada:** Esqueça configurações manuais complexas.
* **Menu Interativo:** Interface via terminal amigável para selecionar o que instalar.
* **Gestão Centralizada:** Inclui Portainer para gerenciamento visual dos containers.
* **Segurança:** Configuração básica de firewall e proxy reverso.
* **Stack Moderna:** Baseado em Docker e Docker Compose.

## 📦 Aplicações Suportadas

O instalador permite implantar diversas ferramentas, organizadas por categorias:

### 🤖 Automação & IA

* **n8n:** Automação de fluxo de trabalho.
* **Typebot:** Construtor de chatbots visual.
* **Flowise:** Orquestração de LLMs (LangChain UI).
* **Botpress:** Criação de chatbots conversacionais.
* **Langfuse:** Observabilidade e análise para LLMs.
* **Evolution API:** API para WhatsApp.

### 💬 CRM & Atendimento

* **Chatwoot:** Plataforma de suporte ao cliente omnicanal.
* **WoofedCRM:** CRM integrado.
* **Mautic:** Automação de marketing open-source.

### 💾 Banco de Dados & Backend

* **Supabase:** Alternativa open-source ao Firebase.
* **PostgreSQL (PgAdmin):** Gestão de banco de dados.
* **MongoDB:** Banco de dados NoSQL.
* **Qdrant:** Banco de dados vetorial para IA.
* **Baserow:** Banco de dados no-code (alternativa ao Airtable).
* **NocoDB:** Transforma bancos de dados em planilhas inteligentes.

### 🛠️ Utilitários & Infraestrutura

* **Portainer:** Gerenciamento de Docker.
* **Uptime Kuma:** Monitoramento de uptime.
* **Traefik:** Proxy reverso.

## 📋 Pré-requisitos

Para garantir o funcionamento correto, recomenda-se:

* **Sistema Operacional:** Debian 11 (Bullseye) Recomendado / Ubuntu 20.04+.
* **Usuário:** Acesso **Root**.
* **Hardware:** Mínimo de 2GB RAM (4GB+ recomendado para rodar múltiplas apps de IA).
* **Portas:** 80 e 443 livres.

## 🛠️ Como Usar

1. Acesse seu servidor via SSH.
2. Clone este repositório ou baixe o script de setup:

```bash
git clone https://github.com/marcuscabrera/SetupVPS.git
cd SetupVPS
chmod +x Setup
./Setup
```

1. O script irá verificar e instalar as dependências necessárias (Docker, jq, dialog, etc.) e em seguida abrirá o menu interativo do **Setup VPS**.
2. Siga as instruções na tela para selecionar e configurar as aplicações desejadas.

## 📄 Licença

Este projeto é distribuído sob a licença **MIT**.
Consulte o arquivo [LICENSE](LICENSE.txt) para mais detalhes.
