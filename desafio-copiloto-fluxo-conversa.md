# Criando um Copiloto com Fluxo de Conversa Personalizado no Microsoft Copilot Studio

## 1. Acessar o Microsoft Copilot Studio
- Entre no portal do [Microsoft Copilot Studio](https://www.microsoft.com/pt-br/microsoft-copilot/microsoft-copilot-studio).
- Faça login com sua conta Microsoft 365.

## 2. Criar um Novo Projeto
- Clique em "Criar Novo Copiloto".
- Escolha a opção "Novo Agente" para criar um copiloto em branco, sem modelos predefinidos.

## 3. Configurar o Modelo
- Escolha um nome e um ícone que representem claramente a funcionalidade principal do copiloto, facilitando sua identificação.
- Defina manualmente as funcionalidades e os fluxos de trabalho do copiloto, detalhando as ações que ele deve realizar e os resultados esperados.
- Inicialmente, não adicione fontes de dados ou APIs. Concentre-se em estruturar o copiloto e definir suas funcionalidades básicas antes de integrar a base de conhecimento.
- Configure os parâmetros de interação, como:
  - Idioma principal para comunicação.
  - Tom de comunicação (formal, informal, técnico, etc.).
  - Formato das respostas (texto curto, detalhado, com links, etc.).
- Acesse "Configurações Avançadas" para personalizar ainda mais o comportamento do copiloto e, se necessário, selecione uma solução previamente criada para reutilizar configurações existentes.

## 4. Customizar um tópico
- Acesse a aba "Tópicos" no menu de navegação do projeto.
- Clique em "Adicionar Tópico" para criar um novo fluxo de conversa.
- Defina o nome do tópico e adicione uma descrição para facilitar a identificação.
- Configure frases de gatilho para ativar o tópico com base nas entradas do usuário.
- Adicione respostas generativas no fluxo, utilizando "Activity.Text" como entrada. Caso necessário, inclua a base de conhecimento do Microsoft Learn.
- Configure uma mensagem de encerramento para indicar o término do tópico.
- Teste o fluxo de conversa para garantir que o comportamento esteja alinhado com os objetivos definidos.

## 5. Personalizar uma mensagem de erro de tópico
- No editor de tópicos, localize a seção "Conversational boosting".
- Clique em "Editar Fontes de Dados" e desabilite o uso de bases de dados gerais para respostas.
- Personalize o texto da mensagem de erro para torná-la mais clara e útil ao usuário.
- Inclua sugestões ou links que ajudem o usuário a resolver o problema.
- Salve as alterações e teste o fluxo para verificar se a mensagem de erro aparece corretamente em cenários de falha.

## 6. Aumentar e diminuir a qualidade da resposta com GenAI
- Acesse as configurações de "Fontes de Dados" dentro de "Conversational boosting".
- Adicione bases de dados relevantes para enriquecer as respostas.
- Habilite ou desabilite o uso de conhecimento geral do GPT, conforme necessário.
- Ajuste parâmetros como criatividade, nível de detalhe e tom de voz para personalizar as respostas.
- Utilize exemplos de entrada e saída para treinar o modelo e refinar a qualidade das respostas.
- Acesse a seção "IA Generativa" nas configurações do copiloto.
- Escolha o modo de interação do agente com o usuário, ajustando o estilo de comunicação.
- Salve as alterações e valide o comportamento do copiloto em cenários reais para garantir a eficácia das configurações.
