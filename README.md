# Projeto Potencializa

## 📖 Descrição da solução

**Professores** enfrentam diariamente o desafio de realizar diversas tarefas administrativas, como adaptar avaliações, preencher relatórios e organizar planos de aula. Essas atividades consomem tempo e energia que poderiam ser dedicados ao ensino.
O **Projeto Potencializa** surge para apoiar docentes na redução desse esforço, começando pela **adaptação de avaliações para alunos com diferentes necessidades**.
A solução utiliza **Inteligência Artificial generativa** para automatizar essas tarefas, gerando versões adaptadas de provas acompanhadas de justificativas pedagógicas. Assim, promove inclusão e eficiência sem substituir a prática docente, mas sim fortalecendo-a.

--- 

## 🛠️ Tecnologias, linguagens e frameworks utilizados

O protótipo foi desenvolvido utilizando a plataforma **Lovable**, que permite criar aplicações de forma rápida e acessível, sem necessidade de programação tradicional. 
Além disso, foram aplicados recursos de **Inteligência Artificial generativa** para gerar múltiplas versões de provas, cada uma acompanhada de uma justificativa pedagógica clara, oferecendo suporte direto ao professor sem substituir sua prática docente. Com isso, o Potencializa promove inclusão, eficiência e personalização, devolvendo tempo ao professor para o que realmente importa: ensinar e potencializar o aprendizado dos alunos. 

--- 

## 🏗️ Arquitetura geral do sistema

- 👩‍🏫 User[Professor] --> Lovable[💻 Interface Lovable]: responsável pela interação com o usuário, oferecendo uma navegação acessível e intuitiva.
- 💻 Lovable --> IA[🤖 Módulo de IA]
- 🤖 IA --> Output[📄 Avaliações adaptadas + justificativas]: gera versões adaptadas das avaliações e fornece justificativas pedagógicas, 
    apoiando o professor sem substituir sua prática.
- 👩‍🏫 User --> Validation[📊 Formulário de validação]
- 📊 Validation --> Feedback[🔄 Aprendizados e melhorias]: coleta feedback dos professores por meio de formulários, permitindo ajustes 
    contínuos e evolução da solução.


--- 

## 🤖 APIs, modelos de IA e bases de dados utilizadas

O protótipo utiliza **modelos de linguagem generativa** para apoiar professores em tarefas administrativas, com foco inicial na adaptação de avaliações.  

Principais funcionalidades:  
- **Produção de versões diferenciadas de provas** → garantindo adequação às necessidades de cada aluno.  
- **Geração de justificativas pedagógicas** → alinhadas às adaptações realizadas, fortalecendo a prática docente.  

Esses recursos de IA foram integrados à interface para oferecer suporte prático e inclusivo, sem substituir o papel do professor.


--- 

## ⚙️ Instruções de instalação e execução

O protótipo pode ser acessado diretamente pelo navegador, sem necessidade de instalação.  

Principais características:  
- **🌐 Acesso via navegador** → não requer instalação local.  
- **🖱️ Protótipo navegável** → permite clicar nas opções disponíveis.  
- **📸 Interações simuladas** → fluxo semelhante ao que o professor realizaria na prática (ex.: tirar foto da prova ou selecionar adaptações).  
- **🚫 Limitações técnicas** → não há integração com câmera ou upload de arquivos nesta versão; o sistema apenas demonstra o comportamento esperado.  
- **📄 Geração de versões** → cada execução produz até três versões diferentes, acompanhadas de justificativas pedagógicas.  
- **⚡ Dados em tempo real** → não há persistência de dados; os resultados são gerados dinamicamente e não ficam armazenados.  
- **✅ Funcionalidades disponíveis** → adaptação de avaliações e geração de justificativas.  
- **🚧 Limitações atuais** → não há integração com banco de dados ou sistemas escolares nesta versão.

--- 

## 👥 Equipe e contribuições

* **Francine Souza Milke:** Desenvolveu o protótipo navegável, estruturando o fluxo principal da solução.
* **Gustavo de Souza Marques:** Contribuiu com a ideia inicial e direcionamento da proposta.
* **Yara Maria Santos Morais:** Realizou a validação com usuários, organizou a documentação e consolidou os aprendizados.

--- 

## 🚧 Limitações conhecidas e próximos passos

### Limitações atuais
- ❌ Não há integração com banco de dados ou sistemas escolares.  
- ❌ Não há persistência de dados: os resultados são gerados em tempo real e não ficam armazenados.  
- ❌ Não há integração com câmera ou upload de arquivos nesta versão.  
- ❌ Interface ainda em versão inicial, com funcionalidades restritas à adaptação de avaliações e geração de justificativas.  

### Próximos passos
- 📊 Implementar relatórios individuais para acompanhamento do desempenho dos alunos.  
- 📚 Alinhar planos de aula e adaptações à **BNCC** (Base Nacional Comum Curricular).  
- 🖥️ Criar painel da coordenação para gestão centralizada das adaptações.  
- 🔄 Evoluir para integração completa com sistemas escolares e bancos de dados.  
- 🧪 Ampliar testes com professores para validar novas funcionalidades e ajustar a experiência de uso.


--- 


