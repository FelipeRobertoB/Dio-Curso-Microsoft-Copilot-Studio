
# Guia para Criar um Copilot no Copilot Studio

## 1. Conectar ao Copilot Studio
- **Passo 1:** Utilize um **e-mail corporativo ou de estudante**.
- **Passo 2:** Acesse o site [Copilot Studio](https://copilotstudio.microsoft.com/).

## 2. Criar um Copilot Baseado em Modelo
- **Passo 1:** Escolha o **modelo de agente** que deseja utilizar. Exemplo: **Safe Travels**.
- **Passo 2:** Defina o **nome** do agente, por exemplo, "Dio Viagens Agente".
- **Passo 3:** Escreva uma **descrição** sobre o que o agente faz.
- **Passo 4:** Forneça as **instruções do agente**, incluindo o **prompt** e as **regras** que o agente deve seguir. (Funciona melhor se escrito em inglês).
- **Passo 5:** Adicione a **Knowledge** (base de conhecimento), como sites, banco de dados e tabelas.
- **Passo 6:** Configure o **idioma** que o agente irá utilizar. Lembre-se de que o agente pode ter apenas um idioma principal e outros secundários. Não é possível alterar o idioma principal após a criação.

## 3. Criar um Copilot Baseado em Descrição com IA
- **Passo 1:** Na aba inicial do site, localize o chatbox com a opção "Descreva seu agente para criá-lo".
- **Passo 2:** Descreva as especificações do agente que deseja criar. (Funciona melhor se escrito em inglês).
- **Passo 3:** Utilize os **modelos de prompts** disponíveis para facilitar a criação (conteúdo disponível em inglês).
- **Passo 4:** Após enviar a especificação, a IA será usada para configurar o agente automaticamente.

## 4. Criar um Copilot em Branco
- **Passo 1:** Na lateral esquerda do site, clique em **Criar**, depois selecione a opção **Novo Agente** (geralmente a primeira opção que aparece).
- **Passo 2:** Crie um **nome** para o agente.
- **Passo 3:** Altere a **logo** do agente (opcional).
- **Passo 4:** Escreva a **descrição** do agente.
- **Passo 5:** Escreva as **instruções do agente** (Prompt).
- **Passo 6:** Adicione a **Knowledge**. É recomendado não adicionar nesta etapa, pois há poucas opções de conexão nesse momento. Após a criação, mais opções de conexão serão liberadas.
- **Passo 7:** Clicando no ícone de **...** e indo em **Configurações Avançadas**, é possível conectar a outra solução já criada.

## 5. Customizar um Tópico
- **Passo 1:** Selecione o **Agente** ao qual deseja adicionar o tópico.
- **Passo 2:** Vá até a opção **Tópicos (Topics)**.
- **Passo 3:** Clique em **Adicionar um Tópico** e selecione a opção **"A partir de um documento em branco"** (também é possível criar usando uma descrição com o Copilot).
- **Passo 4:** Adicione as **frases de gatilho** para o tópico (recomendado adicionar mais de uma frase semelhante).
- **Passo 5:** Clique em **Adicionar um novo nó** (ação, representado por um sinal de **+**), vá para a opção **Avançado** e selecione **"Respostas Generativas"**.
- **Passo 6:** Selecione a **entrada (input)** e a **fonte de dados** que será usada para essa resposta.
- **Passo 7:** É possível **customizar o prompt de respostas** do tópico para que fique diferente do prompt do agente.

## 6. Personalizar uma Mensagem de Erro de Tópico
- **Passo 1:** Para exibir uma mensagem de erro, existem duas opções de configuração de tópico: **Conversational Boosting** e **Fallback**.
- **Passo 2:** Na configuração dos tópicos, adicione uma mensagem após a condição **"Todas as outras condições"**. Essa mensagem ou ação será ativada em caso de falha.

## 7. Aumentar e Diminuir a Qualidade da Resposta com GenAI
- **Passo 1:** Selecione a ação que contenha uma **resposta generativa** e clique em **Editar Fonte de Dados**.
- **Passo 2:** Dentro desta configuração, é possível:
  - Permitir que a **IA use seus próprios conhecimentos gerais** (atualmente utilizando **GPT-4.0**).
  - Adicionar um **Prompt personalizado** para a ação.
  - Configurar o **nível de moderação de conteúdo**.
- **Passo 3:** Sobre o **nível de moderação de conteúdo**:
  - Níveis **mais baixos** significam que o agente irá gerar mais respostas, mas estas podem não ser tão relevantes.
  - Níveis **mais altos** favorecem a **relevância** em detrimento do número de respostas.
- **Passo 4:** É possível configurar, a nível de agente, a **qualidade das respostas generativas**, clicando na parte superior do site na opção **Configuração**, depois em **IA Generativa**.
