# RecToken - Tokenização de Recebíveis

![RecToken Logo](https://img.shields.io/badge/RecToken-Blockchain-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow?style=for-the-badge)
![License](https://img.shields.io/badge/License-Proprietary-red?style=for-the-badge)

## 🚀 Sobre o Projeto

RecToken é uma plataforma revolucionária que transforma recebíveis de PMEs em tokens digitais, democratizando o acesso ao capital e criando uma nova classe de investimentos através da tecnologia blockchain.

### 🎯 Missão
Democratizar o acesso ao capital de giro para pequenas e médias empresas brasileiras através da tokenização de recebíveis, oferecendo uma alternativa mais eficiente, transparente e acessível ao factoring tradicional.

### 🌟 Principais Características

- **Tokenização de Recebíveis**: Conversão de títulos de crédito em tokens digitais
- **Acesso Rápido ao Capital**: Liquidação em até 24 horas
- **Taxas Competitivas**: 50-70% mais baixas que o factoring tradicional
- **Compliance Regulatório**: Totalmente aderente às normas da CVM
- **Transparência Blockchain**: Rastreabilidade completa das operações
- **Marketplace Digital**: Conectando PMEs e investidores

## 📊 Mercado e Oportunidade

### Cenário Atual
- **R$ 600 bilhões**: Demanda não atendida por crédito para PMEs
- **20.3 milhões**: PMEs no Brasil
- **R$ 2.5 trilhões**: Volume anual de recebíveis gerados
- **25%**: Taxa de crescimento anual do mercado de factoring

### Nossa Proposta de Valor

#### Para PMEs:
- ⚡ **Velocidade**: Capital em 24h vs 15 dias do factoring tradicional
- 💰 **Custo**: Taxas 2-3% vs 5-8% do factoring tradicional
- 📱 **Simplicidade**: Processo 100% digital
- 🔍 **Transparência**: Acompanhamento em tempo real

#### Para Investidores:
- 📈 **Rentabilidade**: 15-25% a.a. com baixo risco
- 🛡️ **Segurança**: Garantia pelos recebíveis tokenizados
- 🎯 **Diversificação**: Acesso a nova classe de ativos
- 💎 **Liquidez**: Tokens negociáveis no marketplace

## 🏗️ Arquitetura Tecnológica

### Stack Principal
- **Blockchain**: Polygon (Layer 2 Ethereum)
- **Smart Contracts**: Solidity
- **Backend**: Node.js + TypeScript
- **Frontend**: React + Next.js + Tailwind CSS
- **Database**: PostgreSQL + Redis
- **APIs**: REST + GraphQL

### Componentes do Sistema

```
┌─────────────────┐    ┌─────────────────┐    ┌─────────────────┐
│   Frontend Web  │    │   Mobile App    │    │  Admin Panel    │
└─────────┬───────┘    └─────────┬───────┘    └─────────┬───────┘
          │                      │                      │
          └──────────────────────┼──────────────────────┘
                                 │
                    ┌─────────────┴─────────────┐
                    │     API Gateway           │
                    └─────────────┬─────────────┘
                                 │
          ┌──────────────────────┼──────────────────────┐
          │                      │                      │
┌─────────┴───────┐    ┌─────────┴───────┐    ┌─────────┴───────┐
│ Tokenization    │    │   Marketplace   │    │   Compliance    │
│ Service         │    │   Service       │    │   Service       │
└─────────┬───────┘    └─────────┬───────┘    └─────────┬───────┘
          │                      │                      │
          └──────────────────────┼──────────────────────┘
                                 │
                    ┌─────────────┴─────────────┐
                    │   Blockchain Layer        │
                    │   (Smart Contracts)       │
                    └───────────────────────────┘
```

### Smart Contracts
- **RecToken.sol**: Token principal (ERC-20)
- **Marketplace.sol**: Trading e liquidez
- **Escrow.sol**: Custódia dos ativos
- **Compliance.sol**: Validações regulatórias

## 📁 Estrutura do Projeto

```
rectoken/
├── README.md
├── index.html              # Página principal
├── pme.html               # Página para PMEs
├── investidores.html      # Página para investidores
├── whitepaper.html        # Whitepaper técnico
├── src/
│   ├── components/        # Componentes React
│   ├── contracts/         # Smart Contracts
│   ├── services/          # Serviços backend
│   ├── utils/            # Utilitários
│   └── types/            # Definições TypeScript
├── docs/                 # Documentação
├── tests/               # Testes automatizados
└── deploy/              # Scripts de deploy
```

## 🎯 Roadmap de Implementação

### Fase 1: MVP (Q2 2025) ✅
- [x] Landing pages
- [x] Whitepaper técnico
- [x] Prototipação da interface
- [x] Arquitetura dos smart contracts
- [x] Validação regulatória inicial

### Fase 2: Desenvolvimento (Q3-Q4 2025)
- [ ] Desenvolvimento dos smart contracts
- [ ] API backend completa
- [ ] Interface web funcional
- [ ] Integração com sistemas financeiros
- [ ] Testes de segurança

### Fase 3: Lançamento (Q1 2026)
- [ ] Deploy em mainnet
- [ ] Programa piloto com PMEs selecionadas
- [ ] Onboarding de investidores qualificados
- [ ] Marketplace operacional

### Fase 4: Expansão (Q2+ 2026)
- [ ] Escala nacional
- [ ] Novos produtos financeiros
- [ ] Parcerias estratégicas
- [ ] Expansão internacional

## 🔧 Como Executar Localmente

### Pré-requisitos
- Node.js 18+
- Git
- Navegador moderno

### Instalação

```bash
# Clone o repositório
git clone https://github.com/rectoken/rectoken.git

# Entre no diretório
cd rectoken

# Instale as dependências (se houver package.json no futuro)
npm install

# Execute o servidor local
npx http-server . -p 3000

# Ou use Live Server se estiver no VS Code
# Clique com botão direito em index.html > "Open with Live Server"
```

### Acesso
- **Página Principal**: http://localhost:3000
- **Para PMEs**: http://localhost:3000/pme
- **Para Investidores**: http://localhost:3000/investidores
- **Whitepaper**: http://localhost:3000/whitepaper

## 📊 Projeções Financeiras

| Métrica | Ano 1 | Ano 2 | Ano 3 |
|---------|-------|-------|-------|
| Volume Tokenizado | R$ 50M | R$ 300M | R$ 1B |
| Receita | R$ 1.25M | R$ 7.5M | R$ 25M |
| PMEs Atendidas | 500 | 3.000 | 10.000 |
| Investidores | 1.000 | 5.000 | 15.000 |
| Margem Líquida | -20% | 15% | 68% |

## 🛡️ Segurança e Compliance

### Aspectos Regulatórios
- **CVM**: Instrução 588/2017 (Crowdfunding)
- **BACEN**: Resolução 4.656/2018 (Arranjos de Pagamento)
- **LGPD**: Lei Geral de Proteção de Dados
- **Sandbox Regulatório**: Participação no programa CVM

### Medidas de Segurança
- Smart contracts auditados
- Testes de penetração regulares
- Criptografia end-to-end
- Multi-signature para operações críticas
- Segregação de ativos

## 👥 Equipe

- **CEO**: Estratégia e visão do negócio
- **CTO**: Arquitetura técnica e blockchain
- **CPO**: Experiência do usuário e produto
- **CFO**: Finanças e compliance regulatório
- **Head of Legal**: Aspectos jurídicos e regulamentares

## 📞 Contato

- **Website**: [rectoken.com](https://rectoken.com)
- **Email**: contato@rectoken.com
- **LinkedIn**: [@rectoken](https://linkedin.com/company/rectoken)
- **Telegram**: [@rectoken_oficial](https://t.me/rectoken_oficial)

## 📄 Documentação

- [Whitepaper Técnico](./whitepaper.html)
- [Documentação da API](./docs/api.md)
- [Guia de Integração](./docs/integration.md)
- [Roadmap Detalhado](./docs/roadmap.md)

## ⚖️ Licença

Este projeto é proprietário e confidencial. Todos os direitos reservados à RecToken Ltda.

## 🚨 Avisos Importantes

> ⚠️ **Investimento de Risco**: Investimentos em tokens envolvem riscos. Consulte sempre um consultor financeiro.

> 📋 **Compliance**: Este projeto está sujeito a aprovações regulatórias. As informações podem mudar.

> 🔐 **Segurança**: Nunca compartilhe suas chaves privadas. Sempre use carteiras seguras.

---

**RecToken** - *Transformando o futuro do factoring no Brasil* 🇧🇷
