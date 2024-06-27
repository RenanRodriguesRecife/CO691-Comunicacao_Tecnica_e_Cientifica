# Experimentação
## Planejando e projetando seu experimento


# Experimentos são úteis para:

- Confirmar as teorias conhecidas
- Confirmar (ou às vezes refutar) um conhecimento comum
- Explore as relações existentes entre as variáveis
- Muitas vezes você acredita que algo é verdade
  - ... mas então você poderá descobrir muitas surpresas

# In vitro ou in vivo

- In vitro:
  - Realizado em laboratório
  - Condições controladas
  - Custos razoáveis, baixo risco
    - Experimentos realizados com alunos para avaliar a eficácia de uma técnica de teste
  - A realidade poderia ser diferente
- Usar o experimento para preparar estudos adicionais num contexto mais realista

- In vivo:
  - Projetos reais
  - Não é possível controlar as condições experimentais
  - Configurações e tópicos mais realistas
  - Os resultados podem ser diferentes
  - Custos mais elevados
  - Riscos possivelmente inaceitáveis
- Podemos fazer isso quando tivermos certeza de que o estudo está maduro
  - Experimentos in vitro fornecem resultados encorajadores

# O processo experimental

## Por onde começamos?

  - Temos uma ideia/conjectura sobre uma relação de causa e efeito
  - Temos uma teoria
  - Assim podemos formular uma hipótese
  - E para testar... fazemos um experimento!

## Princípios experimentais

<img src=".assets/41.jpg">

# Terminologia - I

<img src=".assets/42.jpg">

- **Variáveis depéndentes:** variáveis que estamos interessados em estudar
- **Variáveis independentes:** variáveis que controlamos
Exemplo: avaliar a produtividade (**variável dependente**) com base no método de desenvolvimento, habilidades, ferramentas (**variáveis independentes**)

# Terminology - II

- O experimento estuda como as mudanças que ocorrem na **variáveis independentes** (**fatores**) influenciam uma **variável dependente**

# Terminology - III

- Um tratamento é aplicado a uma combinação de **sujeitos** e **objetos**
- Um experimento é um conjunto de **teste** (ou **ensaios**) definidos como combinação de tratamentos, sujeitos e objetos.
  - Joe (**sujeito**) usa o novo método de desenvolvimento (**tratamento**) para desenvolver o programa A (**objeto**)
  - O número de teste influencia a capacidade de tirar conclusões estatisticamente significativas

# Controlando as variáveis

<img src=".assets/42.jpg">

# Etapas de um processo experimental

<img src=".assets/43.jpg">

# Definições do experimento

# Fase de Definição

- Baseado em Métricas de Metal e Questões

- Apresenta a base para a experimentação

- Definição errada -> resultados inúteis

# Modelo de definição de meta

Analisar ->Objeto(s) de estudo<-

para o propósito de ->Propósito<-

com relação ao seu ->Foco na qualidade<-

do ponto de vista da ->Perspectiva<-

no contexto de ->Contexto<-

# Modelo de definição de meta - II

- **Objeto de estudo: Entidade a estudar
  - Produtos, processos, teorias, ferramentas
 
- **Objetivo: intenção do experimento**
  - Compare duas técnicas, caracterize um processo de aprendizagem
 
- **Foco na qualidade: Efeito no estudo**
  - Eficácia, custo, eficiência, precisão...
 
- **Perspectiva:** de que ponto de vista deve interpretar os resultados?
  - Pesquisador, gerente de projetos, desenvolvedor...
 
- Modelo de definição de meta - III
- **Contexto:** ambiente onde o estudo é realizado
  - **Sujeitos:** experiência, habilidades, específicas, etc.
  - **Objetos:** complexidade, domínio de aplicação, etc.
 
# Exemplo
- **Objetivo:** Analizar o uso de diagrama UML estereotipados com o **objetivo** de avaliar sua utilizade na **compreensão** de aplicações Web **para diferentes categorias de usuários**
    - **Foco na qualidade:** alto entendimento e facilidade de manutenção
    - **Perspectiva:** perquisador, gerentes de projetos
    - **Contexto:**
      - Duas aplicações Web
      - Aluno de graduação e pós-graduação, pesquisadores.
     
# Planejamento de Experimentos

# Planejamento

- A **defeinição** descreve **por que** realizamos um experimento
- O **planejamento** determina **como** o experimento será executado
- Indispensável para qualquer tarefa de engenharia.

# Seleção de Contexto

- Conjunto de **objetos** e **sujeitos** envolvidos no experimento
- 4 dimensões
  - Off-line vs on-line
  - Problemas didáticos vs Problemas reais
  - Específico vs geral

# Seleção de Objetos

- Em muitos projetos experimentais você pode precisar de mais de um objeto
- É bom variar entre domínios
- Mas a sua complexidade não deve ser muito diferente
- Os objetos devem ser simples o suficientes para permitir a execução da tarefa em um período de tempo limitado
  - Mas se possível evite exemplos fictícios
- Às vezes você tem que prepará-los
  - E.g injetando falhas etc.
  - **Tenha cuidado para evitar distorcer o experimento**
  - **Verifique se há erros nos objetos, uma das principais causas de falhas em experimentos!**
 
# Seleção de Sujeitos

- Influencia a possibilidade de generalizar nossos resultados
- Precisa representar a população
- **Amostragem probabilística**
  - Amostragem aleatória simples, amostragem sistemática, amostragem aleatória estratificada
- **Amostragem por conveniência**
  - Basta selecionar os sujeitos disponíveis
  - ..ou aqueles mais apropriados
- **Muitas vezes a amostragem por conveniência é a única maneira de proceder**

# IMPORTANTE!

- **Um experiemento não prova nenhuma teoria**

- A lógica da descoberta científica
  - Qualquer afirmação feita num campo científico é verdadeira até que alguém possa contradizê-la
 
# Projeto de experimento

- É o conjunto de teste de tratamento
  - Combinações de tratamentos, sujeitos e objetos.
- Define como os testes são organizados e executados
- Influencia as análises estatísticas que podem fazer
- Com base nas hipóteses formuladas
- Influencia a capacidade de realizar replicações
  - E combinar resultados
 
# Princípios básicos - I

- O design experimental é baseado em três princípios
  1. Randomização
  2. Bloqueio
  3. Balanceamento
 
- Randomização: a observação deve ser feita sobre variáveis aleatórias
  - Influencia a alocação de objetos, assuntos e a ordem em que os teste são realizados
  - Útil para mitigar o efeito de confusão
    - E.g influência de objetos, efeitos de aprendizagem

# Princípios básicos - II

- **Bloqueio:** às vezes alguns fatores influenciam os nossos resultados, mas que querem mitigar o seus efeitos
  - Podemos dividir uma população em blocos com o mesmo nível de fator
  - e.g. experiência dos sujeitos
 
- **Equilíbrio:** devo tentar ter o mesmo (ou semelhante) número de sujeitos para cada tratamento
  - Simplifica a análise estatística
  - Não é estritamente necessário e às vezes não conseguimos alcençar um equilíbrio perfeito
 
# Projeto de experimento conclusões

- Escolha essencial ao fazer um experimento
- As conclusões que podemos tirar dependem do tipo de design que escolhemos
- Restrições em métodos estatísticos
- Se possível, use um design simples
- Maximize o uso dos sujeitos disponíveis
  - **Muitas vezes não há muitos sujeitos disponíveis**
 
# Avaliação e Validação

# Avaliação e Validação

- Questões cruciais na análise dos resultados do experimento
  - Até que ponto nossos resultados são válidos?
  - Eles devem ser pelo menos válidos para a população de interesse
  - Então, se pudéssemos generalizar...
 
- Riscos à validade
  1. Validade da coclusão (C)
  2. Validade interna (I)
  3. Validade de construção (S)
  4. Validade externa (E)
 
# Riscos à validação

- **Validação de conclusão (C):** diz respeito à relação entre tratmento e resultado
    - Deve haver uma relação estatisticamente significativa

- **Validação interna (I):** diz respeito a fatores que podem afetar nossos resultados
   - Não controlamos nem medimos
  
- **Validação de construção (S):** relação entre teoria e observação
    - O tratamento deve refletir a construção da causa
    - O resultado reflete a construção do efeito
 
- **Validação externa (E):** dis respeito à generalização dos resultados
    - Se existe uma relação causal entre construção e efeito, essa relação poderia ser generalizada?

# Priorize risco à validação

- Muitos riscos são conflitantes
  - Quanto reduzo um risco, a outra pode aumentar
  - Um grande problema de otimização
- Experimentos com alunos
  - Amostras maiores, maior homogeneidade
    -> boa validação da conclusão
  - Baixa validação externa
- Uso de diferentes medidas para garantir que o tratamento e o resultado representem bem a construção
  - Boa validação de construção
  - Problemas na validação da conclusão
    -> erros devido a multiplas medidas

# Execução

# Execução

- Depois de projetar um experimento, precisamos executá-lo
- Estamos em contato com os sujeitos pela primeira vez

- **Embora o design e o plano sejam perfeitos, tudo depende da operação**
  - **Se algo der errado em algumas horas, podemos perder meses de trabalho...**
 
# Preparação

- **Obtenha consentimento:**
  - Os participantes concordam com os objetivos da pesquisa
    - 
