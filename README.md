# 📦 Sistema de Gestão de Estoque com Integração a ERPs

Sistema completo para controle de estoque, integração com ERPs e separação de pedidos via celular ou coletor, com foco em operações logísticas e fulfillment.

---

## ✅ MVP - Etapas de Desenvolvimento

### 🧱 ETAPA 1: Estrutura Base do Sistema
- [ ] Cadastro de empresas (multi CNPJ)
- [ ] Cadastro de usuários
- [ ] Autenticação com permissões (admin, operador)
- [ ] Dashboard inicial por usuário

### 📦 ETAPA 2: Cadastro de Produtos e Estoque
- [ ] Cadastro de produtos (SKU, EAN, descrição)
- [ ] Cadastro de posições de estoque (endereçamento)
- [ ] Entrada e saída de estoque manual
- [ ] Histórico de movimentações

### 🔄 ETAPA 3: Integração com ERPs/Plataformas
- [ ] Cadastro de credenciais do ERP
- [ ] Integração com Bling (exemplo inicial)
- [ ] Importação de produtos e pedidos
- [ ] Atualização automática de status

### 🚚 ETAPA 4: Gestão de Pedidos e Separação
- [ ] Listagem de pedidos recebidos
- [ ] Prioridade na separação
- [ ] Controle de status (novo, separando, finalizado)
- [ ] Geração de listas de separação

### 📲 ETAPA 5: Aplicação Mobile / Coletor
- [ ] Aplicativo Android para separação
- [ ] Leitura de código de barras (câmera ou scanner)
- [ ] Validação de itens via bipagem
- [ ] Confirmação de coleta em tempo real

### 📊 ETAPA 6: Dashboard e Financeiro
- [ ] Indicadores de performance (SLA, pedidos, estoque)
- [ ] Cadastro de custos operacionais
- [ ] Cálculo automático de manuseio por cliente
- [ ] Relatórios mensais exportáveis

---

## 🔧 Tecnologias utilizadas

| Componente | Stack |
|------------|-------|
| Backend | Node.js + Express ou Django REST |
| Frontend | React.js + Tailwind CSS |
| Mobile | Kotlin ou Flutter |
| Banco de Dados | PostgreSQL |
| Integração com ERP | API REST (ex: Bling, Tiny, etc) |
| Deploy | Docker + Render/Railway/Vercel |

---

## 🗂️ Organização por Módulos

- `auth/` - Autenticação e permissões
- `products/` - Cadastro e estoque de produtos
- `orders/` - Controle de pedidos e separação
- `integrations/` - Comunicação com ERPs
- `mobile/` - Aplicação de separação
- `finance/` - Fechamento financeiro
- `dashboard/` - Indicadores e visualizações

---

## 📌 Objetivos Principais

- Centralizar o controle de estoque de múltiplas empresas
- Automatizar a integração com ERPs/plataformas
- Eliminar impressão de pedidos usando separação via coletor
- Reduzir erros com validação por código de barras
- Gerar dados de performance e relatórios de cobrança

---

## 🚀 Autor

**Denis Elias Cugler**  
Back-end Developer  
📧 deniscugler@gmail.com  
📍 Curitiba - PR

---

