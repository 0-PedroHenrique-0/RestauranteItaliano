# 🍝 Restaurante Italiano

> Projeto acadêmico de análise de requisitos para um sistema de restaurante italiano.

## 📌 Sobre o projeto

O **Restaurante Italiano** tem como objetivo apoiar o atendimento e a experiência dos clientes de um restaurante especializado em culinária italiana.

Nesta etapa foram definidas **6 personas**, representando diferentes perfis de usuários e suas necessidades. Para cada persona foram levantados **5 requisitos funcionais (RF)** e **5 requisitos não funcionais (RNF)**, totalizando **60 requisitos**.

Os requisitos servirão como base para as próximas etapas de análise, prototipação, modelagem e desenvolvimento do sistema.

## 🎯 Objetivos

- Identificar as necessidades dos diferentes perfis de usuários.
- Transformar necessidades em requisitos claros, objetivos e verificáveis.
- Melhorar a experiência de pedido, atendimento e acompanhamento.
- Criar uma base organizada para futuras telas, banco de dados e APIs.
- Facilitar a evolução do sistema durante o desenvolvimento.

# 👥 Personas

## 👤 Persona 01 — Lucas Almeida

**Idade:** 22 anos  
**Profissão:** Estudante universitário  
**Perfil:** Jovem que costuma pedir comida pelo celular e valoriza rapidez, praticidade e facilidade de uso.

**Objetivos:** Fazer pedidos rapidamente, visualizar o cardápio e acompanhar a entrega.  
**Dores:** Processos demorados, excesso de etapas, informações incompletas e falta de previsão do pedido.

### ⚙️ Requisitos Funcionais

- **RF-P01-01:** O sistema deve permitir consultar o cardápio com nome, descrição, preço, categoria e imagem dos pratos.
- **RF-P01-02:** O sistema deve permitir adicionar, remover e alterar a quantidade de itens no carrinho antes da confirmação do pedido.
- **RF-P01-03:** O sistema deve permitir realizar pedidos informando endereço de entrega ou opção de retirada no restaurante.
- **RF-P01-04:** O sistema deve permitir acompanhar o status do pedido desde a confirmação até a entrega ou retirada.
- **RF-P01-05:** O sistema deve permitir visualizar uma estimativa de tempo para preparação e entrega do pedido.

### 🛡️ Requisitos Não Funcionais

- **RNF-P01-01:** As principais telas de navegação e pedido devem apresentar tempo de resposta adequado para uso em dispositivos móveis.
- **RNF-P01-02:** A interface deve ser responsiva e adaptada a smartphones e tablets.
- **RNF-P01-03:** O fluxo de realização do pedido deve possuir navegação simples e intuitiva.
- **RNF-P01-04:** O sistema deve apresentar mensagens claras de confirmação, alerta e erro ao usuário.
- **RNF-P01-05:** O sistema deve manter os dados do pedido consistentes durante todo o processo de compra.

---

## 👩 Persona 02 — Mariana Souza

**Idade:** 34 anos  
**Profissão:** Gerente de projetos  
**Perfil:** Profissional com pouco tempo disponível que costuma pedir almoço durante o expediente.

**Objetivos:** Pedir sem perder tempo, repetir pedidos, pagar com segurança e acompanhar o pedido durante o trabalho.  
**Dores:** Fluxos longos, repetição de informações, demora no checkout e insegurança no pagamento online.

### ⚙️ Requisitos Funcionais

- **RF-P02-01:** O sistema deve permitir realizar novamente um pedido a partir do histórico de pedidos anteriores.
- **RF-P02-02:** O sistema deve permitir cadastrar, editar, selecionar e excluir endereços de entrega.
- **RF-P02-03:** O sistema deve permitir selecionar uma das formas de pagamento disponíveis no momento da finalização.
- **RF-P02-04:** O sistema deve permitir aplicar cupons ou benefícios válidos ao pedido.
- **RF-P02-05:** O sistema deve enviar uma confirmação após a conclusão do pedido e disponibilizar seu status para acompanhamento.

### 🛡️ Requisitos Não Funcionais

- **RNF-P02-01:** O processo de checkout deve ser objetivo, com o menor número possível de etapas sem comprometer a segurança.
- **RNF-P02-02:** As informações sensíveis relacionadas ao pagamento devem ser protegidas contra acesso não autorizado.
- **RNF-P02-03:** O sistema deve possuir disponibilidade adequada durante horários de maior movimento.
- **RNF-P02-04:** O sistema deve manter o carrinho e os dados do pedido sem perda indevida durante a navegação.
- **RNF-P02-05:** As mensagens e rótulos do checkout devem utilizar linguagem clara e de fácil compreensão.

---

## 👨‍👩‍👧 Persona 03 — Família Oliveira

**Idade:** 41 anos  
**Profissão:** Empresário  
**Perfil:** Cliente que costuma realizar pedidos grandes para a família, principalmente aos finais de semana.

**Objetivos:** Montar pedidos variados, personalizar pratos e visualizar o valor total antes da confirmação.  
**Dores:** Dificuldade com pedidos grandes, erros de quantidade, pouca personalização e confusão no valor final.

### ⚙️ Requisitos Funcionais

- **RF-P03-01:** O sistema deve permitir alterar individualmente a quantidade de cada item presente no carrinho.
- **RF-P03-02:** O sistema deve permitir adicionar observações e selecionar complementos ou opções de personalização disponíveis para cada prato.
- **RF-P03-03:** O sistema deve calcular e exibir o subtotal dos itens, taxas aplicáveis, descontos e valor total do pedido.
- **RF-P03-04:** O sistema deve permitir revisar todos os itens e respectivas quantidades antes da confirmação do pedido.
- **RF-P03-05:** O sistema deve permitir adicionar diferentes pratos e categorias no mesmo pedido.

### 🛡️ Requisitos Não Funcionais

- **RNF-P03-01:** Os valores apresentados no carrinho devem permanecer consistentes com o valor calculado na finalização do pedido.
- **RNF-P03-02:** A interface deve apresentar de forma destacada os itens, quantidades, adicionais e valores individuais.
- **RNF-P03-03:** O sistema deve suportar pedidos com grande quantidade de itens sem degradação significativa de desempenho.
- **RNF-P03-04:** Alterações de quantidade e personalização devem atualizar os valores do pedido de forma rápida e confiável.
- **RNF-P03-05:** O sistema deve reduzir a possibilidade de erros de entrada por meio de controles adequados de quantidade e confirmação.

---

## 🌎 Persona 04 — Gabriel Rossi

**Idade:** 29 anos  
**Profissão:** Designer freelancer / Turista  
**Perfil:** Visitante que procura uma experiência gastronômica italiana e precisa de informações claras antes de escolher o restaurante e os pratos.

**Objetivos:** Conhecer os pratos, ingredientes, localização, horários e possibilidades de reserva.  
**Dores:** Informações incompletas, dificuldade para encontrar o restaurante e falta de dados sobre restrições alimentares.

### ⚙️ Requisitos Funcionais

- **RF-P04-01:** O sistema deve apresentar descrição, ingredientes principais e informações relevantes dos pratos disponíveis.
- **RF-P04-02:** O sistema deve disponibilizar endereço, horário de funcionamento, telefone e demais canais oficiais de contato.
- **RF-P04-03:** O sistema deve informar alergênicos e restrições alimentares cadastradas para os pratos.
- **RF-P04-04:** O sistema deve permitir consultar o cardápio por categorias, como entradas, massas, pizzas, sobremesas e bebidas.
- **RF-P04-05:** O sistema deve permitir solicitar ou realizar uma reserva de mesa, quando esse serviço estiver disponível.

### 🛡️ Requisitos Não Funcionais

- **RNF-P04-01:** As informações do restaurante e do cardápio devem ser apresentadas de forma clara, organizada e facilmente escaneável.
- **RNF-P04-02:** O sistema deve funcionar corretamente em diferentes tamanhos de tela e dispositivos.
- **RNF-P04-03:** O conteúdo principal deve possuir boa legibilidade, contraste adequado e hierarquia visual consistente.
- **RNF-P04-04:** As informações de endereço e horário devem ser atualizadas de forma consistente quando alteradas pelo estabelecimento.
- **RNF-P04-05:** As páginas públicas do restaurante devem ter carregamento eficiente, inclusive em conexões móveis mais lentas.

---

## ⭐ Persona 05 — Camila Ferreira

**Idade:** 38 anos  
**Profissão:** Médica  
**Perfil:** Cliente recorrente que valoriza qualidade, personalização, praticidade e benefícios para clientes frequentes.

**Objetivos:** Receber um atendimento personalizado, encontrar seus pratos preferidos, aproveitar benefícios e avaliar a experiência.  
**Dores:** Dificuldade para repetir pedidos, falta de benefícios de fidelidade e ausência de um canal simples para feedback.

### ⚙️ Requisitos Funcionais

- **RF-P05-01:** O sistema deve permitir cadastrar e identificar clientes recorrentes por meio de uma conta de usuário.
- **RF-P05-02:** O sistema deve permitir marcar e remover pratos da lista de favoritos.
- **RF-P05-03:** O sistema deve permitir visualizar o histórico de pedidos realizados pelo cliente.
- **RF-P05-04:** O sistema deve permitir avaliar um pedido concluído, atribuindo uma nota e, quando desejado, um comentário.
- **RF-P05-05:** O sistema deve permitir consultar benefícios, pontos ou vantagens disponíveis no programa de fidelidade, quando existente.

### 🛡️ Requisitos Não Funcionais

- **RNF-P05-01:** As avaliações devem ser registradas de forma segura e vinculadas corretamente ao pedido correspondente.
- **RNF-P05-02:** O histórico de pedidos deve permanecer organizado, íntegro e disponível para consulta do cliente autenticado.
- **RNF-P05-03:** O acesso a favoritos, histórico e benefícios deve exigir poucos passos de navegação.
- **RNF-P05-04:** Os dados pessoais do cliente devem ser armazenados e transmitidos com mecanismos adequados de proteção.
- **RNF-P05-05:** O sistema deve manter consistência nos pontos ou benefícios apresentados ao cliente, evitando divergências de saldo.

---

## 👨‍💼 Persona 06 — Roberto Martins

**Idade:** 46 anos  
**Profissão:** Proprietário do restaurante  
**Perfil:** Responsável pela operação, gerenciamento do cardápio, acompanhamento dos pedidos e visão geral do negócio.

**Objetivos:** Controlar pedidos, atualizar o cardápio, acompanhar vendas e ter uma visão centralizada da operação.  
**Dores:** Informações descentralizadas, dificuldade para atualizar pratos, atraso na atualização dos pedidos e pouca visão do desempenho.

### ⚙️ Requisitos Funcionais

- **RF-P06-01:** O sistema deve permitir cadastrar, editar, ativar, desativar e excluir pratos do cardápio conforme as permissões do administrador.
- **RF-P06-02:** O sistema deve permitir visualizar os pedidos recebidos e atualizar seus respectivos status.
- **RF-P06-03:** O sistema deve permitir controlar a disponibilidade dos pratos para impedir pedidos de itens indisponíveis.
- **RF-P06-04:** O sistema deve disponibilizar uma área administrativa com informações de pedidos, faturamento e quantidade de vendas.
- **RF-P06-05:** O sistema deve permitir consultar informações básicas dos clientes e seus pedidos para apoiar o atendimento.

### 🛡️ Requisitos Não Funcionais

- **RNF-P06-01:** O acesso à área administrativa deve exigir autenticação e autorização adequada.
- **RNF-P06-02:** Alterações críticas realizadas no cardápio, pedidos e configurações devem ser registradas de forma consistente.
- **RNF-P06-03:** A área administrativa deve possuir controle de acesso para impedir ações de usuários não autorizados.
- **RNF-P06-04:** As informações operacionais apresentadas no painel administrativo devem ser atualizadas de forma confiável.
- **RNF-P06-05:** O sistema deve manter os dados administrativos íntegros mesmo em situações de falha ou interrupção inesperada.

---

# 📋 Resumo dos requisitos

| Persona | Funcionais | Não funcionais | Total |
|---|---:|---:|---:|
| Lucas Almeida | 5 | 5 | 10 |
| Mariana Souza | 5 | 5 | 10 |
| Família Oliveira | 5 | 5 | 10 |
| Gabriel Rossi | 5 | 5 | 10 |
| Camila Ferreira | 5 | 5 | 10 |
| Roberto Martins | 5 | 5 | 10 |
| **Total** | **30** | **30** | **60** |

# 🏷️ Padrão de identificação

Os requisitos utilizam uma identificação padronizada para facilitar rastreabilidade e organização:

- **RF:** Requisito Funcional.
- **RNF:** Requisito Não Funcional.
- **P01 a P06:** Identificação da persona relacionada.
- **01 a 05:** Número sequencial do requisito daquela categoria.

**Exemplo:** `RF-P03-04` representa o quarto requisito funcional relacionado à Persona 03.

# 🧩 Visão geral do sistema

```text
Restaurante Italiano
│
├── 👤 Cliente
│   ├── Cadastro / Login
│   ├── Cardápio
│   ├── Busca e categorias
│   ├── Carrinho
│   ├── Checkout
│   ├── Pagamentos
│   ├── Histórico de pedidos
│   ├── Favoritos
│   ├── Fidelidade
│   └── Avaliações
│
├── 🍝 Restaurante
│   ├── Pratos
│   ├── Categorias
│   ├── Preços
│   ├── Ingredientes
│   ├── Alergênicos
│   ├── Disponibilidade
│   └── Reservas
│
└── ⚙️ Administração
    ├── Gestão de pratos
    ├── Gestão de pedidos
    ├── Gestão de clientes
    ├── Gestão de reservas
    └── Indicadores e vendas
```

# ✅ Critérios utilizados

1. **Clareza:** cada requisito descreve uma necessidade de forma objetiva.
2. **Verificabilidade:** deve ser possível testar se o requisito foi atendido.
3. **Rastreabilidade:** os requisitos possuem identificadores próprios.
4. **Consistência:** os requisitos devem evitar contradições e ambiguidades.
5. **Foco no usuário:** cada requisito foi relacionado às necessidades de uma persona específica.
6. **Escalabilidade:** os requisitos foram estruturados pensando em uma futura evolução do sistema.

# 🚀 Próximas etapas

- [ ] Criar casos de uso.
- [ ] Criar histórias de usuário.
- [ ] Criar diagrama de casos de uso.
- [ ] Modelar banco de dados.
- [ ] Definir arquitetura da aplicação.
- [ ] Criar protótipos das telas.
- [ ] Implementar API e regras de negócio.
- [ ] Implementar interface do cliente e área administrativa.
- [ ] Integrar pagamentos.
- [ ] Criar testes funcionais e não funcionais.
- [ ] Realizar validação dos requisitos com os usuários.

## 📚 Tecnologias previstas

> As tecnologias podem ser ajustadas durante a implementação.

- **Frontend:** React Native / React
- **Backend:** Node.js / Java / Kotlin
- **API:** REST
- **Banco de dados:** PostgreSQL ou MySQL
- **Versionamento:** Git + GitHub
- **Pagamentos:** integração com gateway de pagamento

## 👨‍💻 Projeto

**Nome:** Restaurante Italiano  
**Tipo:** Projeto acadêmico  
**Status:** Em desenvolvimento — levantamento e especificação de requisitos

## 📄 Licença

Este projeto possui finalidade acadêmica e pode ser utilizado para estudos e evolução do trabalho.
