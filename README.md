# 🍝 Restaurante Italiano

> Projeto acadêmico de análise de requisitos para um sistema de restaurante italiano.

## 📌 Sobre o projeto

O **Restaurante Italiano** tem como objetivo apoiar o atendimento e a experiência dos clientes de um restaurante especializado em culinária italiana.

Nesta primeira etapa, foram definidas **6 personas** para representar diferentes perfis de usuários e suas necessidades. A partir delas, foram levantados **requisitos funcionais (RF)** e **requisitos não funcionais (RNF)** que servirão como base para as próximas etapas de análise, prototipação e desenvolvimento.

## 🎯 Objetivos

- Entender as necessidades dos diferentes perfis de usuários.
- Transformar necessidades em requisitos claros e verificáveis.
- Melhorar a experiência de pedido, atendimento e acompanhamento.
- Criar uma base organizada para futuras telas, banco de dados e APIs.
- Facilitar a evolução do sistema durante o desenvolvimento.

# 👥 Personas

## 👤 Persona 01 — Lucas Almeida

**Idade:** 22 anos  
**Profissão:** Estudante universitário  
**Perfil:** Jovem que costuma pedir comida pelo celular e valoriza rapidez e praticidade.

**Objetivos:** Fazer pedidos rapidamente, visualizar o cardápio e acompanhar o pedido.  
**Dores:** Processos demorados, informações incompletas e falta de previsão do pedido.

### Requisitos

**Requisitos Funcionais**
- **RF-P01-01:** O sistema deve permitir consultar o cardápio com pratos, descrições, preços e imagens.
- **RF-P01-02:** O sistema deve permitir adicionar, remover e alterar itens no carrinho antes da confirmação.
- **RF-P01-03:** O sistema deve permitir acompanhar o status do pedido por etapas definidas pelo restaurante.

**Requisitos Não Funcionais**
- **RNF-P01-01:** As principais telas do pedido devem carregar rapidamente em dispositivos móveis.
- **RNF-P01-02:** A interface deve ser responsiva e adequada para smartphones.
- **RNF-P01-03:** O sistema deve apresentar mensagens claras para confirmar ações e informar erros.

---

## 👩 Persona 02 — Mariana Souza

**Idade:** 34 anos  
**Profissão:** Gerente de projetos  
**Perfil:** Profissional com pouco tempo disponível que costuma pedir almoço durante o expediente.

**Objetivos:** Pedir sem perder tempo, repetir pedidos e utilizar pagamento seguro.  
**Dores:** Fluxos longos, repetição de dados e insegurança no pagamento online.

### Requisitos

**Requisitos Funcionais**
- **RF-P02-01:** O sistema deve permitir realizar um novo pedido a partir do histórico de pedidos.
- **RF-P02-02:** O sistema deve permitir selecionar as formas de pagamento disponíveis.
- **RF-P02-03:** O sistema deve armazenar os endereços cadastrados para facilitar pedidos futuros.

**Requisitos Não Funcionais**
- **RNF-P02-01:** O fluxo de checkout deve possuir poucos passos e linguagem simples.
- **RNF-P02-02:** Os dados sensíveis de pagamento não devem ser armazenados de forma insegura.
- **RNF-P02-03:** O sistema deve manter disponibilidade adequada durante horários de maior movimento.

---

## 👨‍👩‍👧 Persona 03 — Família Oliveira

**Idade:** 41 anos  
**Profissão:** Empresário  
**Perfil:** Cliente que costuma realizar pedidos grandes para a família, principalmente aos finais de semana.

**Objetivos:** Montar pedidos variados, personalizar itens e visualizar o valor total.  
**Dores:** Dificuldade com pedidos grandes, poucas opções de personalização e erros de quantidade.

### Requisitos

**Requisitos Funcionais**
- **RF-P03-01:** O sistema deve permitir alterar a quantidade de cada item do carrinho.
- **RF-P03-02:** O sistema deve permitir selecionar complementos, observações ou opções de personalização disponíveis.
- **RF-P03-03:** O sistema deve calcular e exibir subtotal, taxas e valor total do pedido.

**Requisitos Não Funcionais**
- **RNF-P03-01:** O cálculo do pedido deve evitar divergências entre o carrinho e o valor final.
- **RNF-P03-02:** A interface deve permitir visualizar claramente os itens e suas quantidades.
- **RNF-P03-03:** O sistema deve suportar pedidos com grande quantidade de itens sem perda significativa de desempenho.

---

## 🌎 Persona 04 — Gabriel Rossi

**Idade:** 29 anos  
**Profissão:** Designer freelancer / Turista  
**Perfil:** Visitante que procura uma experiência gastronômica italiana e precisa de informações claras.

**Objetivos:** Conhecer pratos, ingredientes, localização e horários.  
**Dores:** Informações incompletas, dificuldade para encontrar o restaurante e falta de dados sobre restrições alimentares.

### Requisitos

**Requisitos Funcionais**
- **RF-P04-01:** O sistema deve apresentar descrição dos pratos e seus principais ingredientes.
- **RF-P04-02:** O sistema deve disponibilizar endereço, horário de funcionamento e canais de contato.
- **RF-P04-03:** O sistema deve permitir consultar informações sobre alergênicos ou restrições alimentares quando cadastradas.

**Requisitos Não Funcionais**
- **RNF-P04-01:** As informações do restaurante devem ser apresentadas de forma clara e organizada.
- **RNF-P04-02:** O sistema deve funcionar corretamente em diferentes tamanhos de tela.
- **RNF-P04-03:** O conteúdo principal deve possuir boa legibilidade e contraste visual.

---

## ⭐ Persona 05 — Camila Ferreira

**Idade:** 38 anos  
**Profissão:** Médica  
**Perfil:** Cliente recorrente que valoriza qualidade, personalização e benefícios.

**Objetivos:** Receber atendimento personalizado, aproveitar benefícios e avaliar os pratos.  
**Dores:** Não receber benefícios pela fidelidade, dificuldade para encontrar favoritos e falta de canal simples para feedback.

### Requisitos

**Requisitos Funcionais**
- **RF-P05-01:** O sistema deve permitir cadastrar e identificar clientes recorrentes.
- **RF-P05-02:** O sistema deve permitir marcar pratos como favoritos para facilitar novos pedidos.
- **RF-P05-03:** O sistema deve permitir avaliar pedidos realizados após a conclusão do atendimento.

**Requisitos Não Funcionais**
- **RNF-P05-01:** As avaliações devem ser registradas com segurança e vinculadas ao pedido correto.
- **RNF-P05-02:** O sistema deve manter o histórico de pedidos organizado e consistente.
- **RNF-P05-03:** A navegação deve permitir acessar favoritos e histórico em poucos passos.

---

## 👨‍💼 Persona 06 — Roberto Martins

**Idade:** 46 anos  
**Profissão:** Proprietário do restaurante  
**Perfil:** Responsável pela operação, cardápio e acompanhamento dos pedidos e resultados.

**Objetivos:** Controlar pedidos, atualizar o cardápio e acompanhar a operação.  
**Dores:** Informações descentralizadas, dificuldade para atualizar o cardápio e pouca visão do desempenho.

### Requisitos

**Requisitos Funcionais**
- **RF-P06-01:** O sistema deve permitir cadastrar, editar, ativar e desativar pratos do cardápio.
- **RF-P06-02:** O sistema deve permitir visualizar e atualizar o status dos pedidos recebidos.
- **RF-P06-03:** O sistema deve disponibilizar uma área administrativa com informações básicas de pedidos e vendas.

**Requisitos Não Funcionais**
- **RNF-P06-01:** O acesso à área administrativa deve exigir autenticação.
- **RNF-P06-02:** Alterações críticas do cardápio e dos pedidos devem ser registradas de forma consistente.
- **RNF-P06-03:** A área administrativa deve possuir controle de acesso contra usuários não autorizados.

---

# 📋 Resumo dos requisitos

| Persona | Funcionais | Não funcionais |
|---|---:|---:|
| Lucas Almeida | 3 | 3 |
| Mariana Souza | 3 | 3 |
| Família Oliveira | 3 | 3 |
| Gabriel Rossi | 3 | 3 |
| Camila Ferreira | 3 | 3 |
| Roberto Martins | 3 | 3 |
| **Total** | **18** | **18** |

# 🧩 Visão geral do sistema

```text
Restaurante Italiano
│
├── 👤 Cliente
│   ├── Cadastro / Login
│   ├── Cardápio
│   ├── Carrinho
│   ├── Checkout
│   ├── Pagamentos
│   ├── Histórico de pedidos
│   ├── Favoritos
│   └── Avaliações
│
├── 🍝 Cardápio
│   ├── Pratos
│   ├── Categorias
│   ├── Preços
│   ├── Ingredientes
│   └── Disponibilidade
│
└── ⚙️ Administração
    ├── Gestão de pratos
    ├── Gestão de pedidos
    ├── Gestão de clientes
    └── Indicadores
```

# ✅ Critérios utilizados

1. **Clareza:** cada requisito descreve uma necessidade de forma objetiva.
2. **Verificabilidade:** deve ser possível testar se o requisito foi atendido.
3. **Rastreabilidade:** os requisitos possuem identificadores próprios.
4. **Foco no usuário:** cada requisito foi relacionado a uma persona e às suas necessidades.

# 🚀 Próximas etapas

- [ ] Criar casos de uso.
- [ ] Criar histórias de usuário.
- [ ] Criar diagrama de casos de uso.
- [ ] Modelar banco de dados.
- [ ] Definir arquitetura da aplicação.
- [ ] Criar protótipos das telas.
- [ ] Implementar API e regras de negócio.
- [ ] Implementar interface do cliente e área administrativa.
- [ ] Criar testes.

## 📚 Tecnologias previstas

> As tecnologias podem ser ajustadas durante a implementação.

- **Frontend:** React Native / React
- **Backend:** Node.js / Java / Kotlin
- **API:** REST
- **Banco de dados:** PostgreSQL ou MySQL
- **Versionamento:** Git + GitHub

## 👨‍💻 Projeto

**Nome:** Restaurante Italiano  
**Tipo:** Projeto acadêmico  
**Status:** Em desenvolvimento — levantamento de requisitos

## 📄 Licença

Este projeto possui finalidade acadêmica e pode ser utilizado para estudos e evolução do trabalho.
