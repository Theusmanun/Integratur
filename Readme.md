![Logo do Projeto](./assets/Logo.jpeg)

# 🏛️ IntegraTur: Solução para Gestão Integrada das Secretarias de Turismo e Cultura de Recife  

**Projeto desenvolvido para a Prefeitura do Recife, visando a integração entre as Secretarias de Turismo e Cultura.**  

---

## 👥 Equipe  
| Nome             | Funções | Hobby                                                                 | Contato |
|------------------|---------|-----------------------------------------------------------------------|---------|
| André Ferraz     | Scrum Master| Surfar, ir à academia, jogar basquete e acompanhar outros esportes.  |afg@cesar.school     |
| Luiz Felipe      |Project Owner| Jogar videogame, cozinhar e jogar vôlei.                             | lfmf@cesar.school      |
| Gustavo Rodrigues|Quality Assurance (QA)| Escutar música, ir à academia e andar de bicicleta.                  | grq@cesar.school     |
| Jorge Tadeu      |Desenvolverdor Front End| Ir à academia e jogar vôlei.                                         |jtgsf@cesar.school     |
| Maria Eduarda    |Desenvolverdor Front End| Escutar música, jogar videogame, pintar e desenhar.                  | merm@cesar.school    |
| Maria Julia      |Desenvolverdor Front End| Desenhar (papel e digital, ainda aprendendo), ler e assistir sitcom. | mjmr@cesar.school     |
| Mateus Jose      |Desenvolverdor Back End| Jogar videogame, praticar natação, correr e acompanhar esportes.     | mjgmg@cesar.school     |
| Matheus Melquiades |Desenvolverdor Front End| Jogar videogame, ler quadrinhos e ir ao cinema.                      | mmn3@cesar.school     |
  
---

## 📌 Contexto do Problema  
As secretarias municipais de **Turismo** e **Cultura** de Recife enfrentam desafios críticos devido à **falta de comunicação e integração**, resultando em:  
- **Ações desarticuladas** e perda de eficiência.  
- **Retrabalho** e custos desnecessários.  
- **Impacto negativo** na experiência do cidadão e turistas.  

A Prefeitura do Recife nos solicitou uma solução para **conectar essas áreas**, otimizando recursos e melhorando serviços públicos.  

---

## 🎯 Objetivo do Produto  
O **IntegraTur** é um sistema que:  
✔ **Centraliza informações** entre as secretarias.    
✔ **Reduz duplicidade** de esforços e custos operacionais.  
✔ **Melhora a experiência** do usuário

## 📋 Histórias de Usuário Implementadas

### 1. Etapa de chat de Secretarias  
**Descrição:**  
“Como Diretora de Comunicação da Prefeitura, quero me conectar com as Secretarias via chat, para resolver questões dos eventos.”  

**Critérios de aceitação (CDA):**  
- É necessário que a ferramenta tenha uma parte para conversas entre membros de ambas as secretarias.  
- A página de chat deve conter receber somente digitação, não possibilitando, inicialmente, o envio de áudio.  
- A aba deve ter uma restrição para palavras consideradas ofensivas.  

**Prioridade:** Média.  
**Estimativa de Esforço:** 5 horas.  

---

### 2. Cadastrar Evento  
**Descrição:**  
"Como gestor da Secretaria de Turismo, quero cadastrar eventos no calendário compartilhado para garantir que as atividades sejam planejadas sem conflitos e divulgadas adequadamente."  

**Critérios de Aceitação (CDA):**  
- Título do evento  
- Data  
- Atrações e orçamento  
- Programação  
- Local (com opção de selecionar endereços pré-cadastrados).  
- Exibir mensagem de sucesso: "Evento 'Carnaval 2025' cadastrado com sucesso!"  
- Atualizar o calendário em tempo real.  
- Recursos como fornecedores, patrocinadores e equipamentos  
- Requisitos como alvarás, licenças e autorizações  

**Prioridade:** Alta  
**Estimativa:** 5 horas  

---

### 3. Procurar Evento na Home  
**Descrição:**  
"Como funcionário da Secretaria de Turismo ou Cultura, quero buscar eventos por palavras-chave, datas ou locais no feed da home para encontrar rapidamente informações relevantes para meu planejamento."  

**Critérios de Aceitação (CDA):**  
- Barra de busca fixa no topo da home: "Buscar por nome, data ou local...".  
- Filtro por data  
- Filtro por secretaria (Turismo/Cultura)  
- Buscar por: Título do evento (ex.: Carnaval). Local (ex.: Praça Central).  
- Exibir mensagem "Nenhum evento encontrado" se a busca não retornou resultados.  
- Manter os filtros ativos (ex.: se "Turismo" estiver selecionado, a busca só considera eventos desta secretaria).  

**Prioridade:** Alta 
**Estimativa:** 4 horas  

---

### 4. Cadastro de Fornecedores  
**Descrição:**  
"Como Secretário de Cultura, quero cadastrar fornecedores para facilitar a organização e logística dos eventos."  

**Critérios de Aceitação:**  
- Deve haver um campo para inserir o nome do fornecedor.  
- Deve ser possível adicionar informações de contato e tipo de serviço prestado.  
- O sistema deve permitir cadastrar múltiplos fornecedores.  
- Os fornecedores cadastrados devem ficar disponíveis para seleção em eventos futuros.  

**Prioridade:** Média  
**Estimativa de esforço:** 4 horas  

---

### 5. Login Institucional  
**Descrição:**  
“Como funcionário da Secretaria de Turismo, quero fazer login no Integratur usando meu e-mail institucional para acessar ferramentas exclusivas de planejamento e evitar acesso não autorizado”.  

**Critérios de aceitação:**  
- O sistema valida e-mails (institucionais) no formato @recife.pe.gov.br  
- Exibe mensagem de erro se e-mail/senha estiverem incorretos.  
- Redireciona para a página inicial após login válido.  

**Prioridade:** Alta  
**Estimativa de esforço:** 3 horas  

---

### 6. Calendário de Eventos  
**Descrição:**  
"Como usuário, eu quero visualizar um calendário de eventos para acompanhar a programação de eventos de forma organizada."  

**Critérios de Aceitação:**  
- O calendário deve exibir os dias do mês em um formato organizado.  
- Os eventos cadastrados devem aparecer nos dias correspondentes.  
- Deve ser possível navegar entre os meses para visualizar eventos passados e futuros.  
- Os eventos devem ser destacados com um nome e um ícone representativo.  

**Prioridade:** Alta  
**Estimativa de esforço:** 5 horas  

---

### 7. Gestão de Orçamento  
**Descrição:**  
"Como gestor da Secretaria de Turismo ou Cultura, quero cadastrar e monitorar o orçamento total do evento, para manter o controle financeiro."  

**Critérios de Aceitação (CDA):**  
- Campo para inserir valor total.  
- Exibir mensagem de confirmação: "Orçamento inicial salvo com sucesso!".  
- Descrição (ex.: "Aluguel de palco").  
- Botão "Adicionar Despesa" que atualiza o saldo em tempo real.  
- Barra de progresso ou gráfico mostrando: Verde: 0-80% do orçamento utilizado. Amarelo: 81-99% do orçamento. Vermelho: 100% ou mais (ex.: "Orçamento ultrapassado em R$ 1.200,00").  
- Permitir editar/excluir despesas mesmo após ultrapassar o orçamento.  
- Não bloquear o cadastro de novas despesas.  
- Botão "Exportar para PDF" com resumo: Total gasto por categoria.  

**Prioridade:** Alta  
**Estimativa:** 6 horas  

---

### 8. Filtro por Secretaria  
**Descrição:**  
“Como Secretário Geral de Cultura, quero filtrar os eventos realizados pela Secretaria de Cultura dentro da IntegraTur.”  

**Critérios de aceitação (CDA):**  
- A plataforma deve ter a opção “Secretaria de Cultura” como opção de filtro na página principal.  
- Ao clicar no filtro, devem aparecer as informações de todos os eventos que serão realizados pela Secretaria de Cultura.  
- A procura não pode ser trocada por outro filtro para que não ocorram conflitos.  

**Prioridade:** Média  
**Estimativa de Esforço:** 3 horas

---

### 9. Cadastro de Usuários  
**Descrição:**  
“Como Coordenador de Projetos da Secretaria de Turismo, quero fazer o cadastro na plataforma IntegraTur, para que consiga utilizar de suas ferramentas.”  

**Critérios de aceitação (CDA):**  
- A plataforma deve aceitar minhas informações pessoais como corretas.  
- Ao clicar no botão de cadastro, deve aparecer uma confirmação de que o usuário não é robô.  
- A plataforma deve permitir que somente usuários que trabalham em uma das Secretarias entrem.  
- A confirmação de cadastro deve ser acelerada, evitando travamentos e transtorno ao usuário.  

**Prioridade:** Alta  
**Estimativa de Esforço:** 5 horas  

---

### 10. Mapa de Eventos  
**Descrição:**  
"Como secretário de Turismo, eu quero visualizar os eventos no mapa para monitorar a distribuição geográfica e identificar oportunidades de promoção turística."  

**Critérios de Aceitação:**  
- O mapa deve carregar automaticamente ao acessar a página.  
- Os eventos devem ser exibidos como marcadores geolocalizados.  
- Ao clicar em um marcador, um card deve exibir detalhes como nome do evento, data, local e organizador.  
- Deve haver um campo de busca por cidade ou CEP para filtrar eventos por localização.  
- O sistema deve permitir a navegação entre diferentes regiões para uma visão mais ampla dos eventos.  

**Prioridade:** Alta  
**Estimativa de esforço:** 5 horas  

## 🎨 Storyboard - Cadastro de Evento

### **Tela 1: Formulário Base**
![Tela 1 - Estrutura Inicial](./assets/sb%20cadastrar%20novo%20evento/WhatsApp%20Image%202025-03-31%20at%2003.34.08.jpeg)  
**Fluxo:**  
1. Preenchimento das **Informações Básicas** (Título, Responsável, Local, Descrição).  
2. Seção de **Programação** com opção "+ Adicional Horário".  
3. **Recursos** e **Requisitos** com checkboxes para autorizações.  

---

### **Tela 2: Preenchimento Parcial**  
![Tela 2 - Dados Parciais](./assets/sb%20cadastrar%20novo%20evento/WhatsApp%20Image%202025-03-31%20at%2003.34.08%20(1).jpeg)  
**Destaques:**  
- Exemplo de evento: "Oficina do Bob" (data 23/03/2025).  
- Checkboxes para licenças (**Licença Biomédica**, **Autorização Sonora**).  
- Seção de **Marketing** e **Segurança** ainda não preenchidas.  

---

### **Tela 3: Confirmação**  
![Tela 3 - Evento Salvo](./assets/sb%20cadastrar%20novo%20evento/WhatsApp%20Image%202025-03-31%20at%2003.34.09.jpeg)  
**Feedback do Sistema:**  
- Mensagem de sucesso: *"Evento Salvo Com Sucesso!"*.  
- Dados persistidos: Título ("Oficina do Belo"), Data, Descrição.  
- **Checklists** visíveis para acompanhamento pós-cadastro.  
--- 