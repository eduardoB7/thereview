# Casos de uso completos

### 1. **Realizar Cadastro na Plataforma**

- **Pré-Requisito:** O usuário deve acessar a página inicial da plataforma "thereview."
- **Ator Principal:** Novo usuário interessado em usar "thereview."
- **Interessados:**
  - Usuário em busca de informações sobre produtos tecnológicos.
  - Administradores da plataforma.
- **Garantia de Sucesso:**
  - O usuário conclui com êxito o processo de cadastro.
  - O endereço de e-mail do usuário é verificado e a conta é ativada.
- **Fluxo Principal:**
  - O usuário acessa a página inicial da plataforma "thereview."
  - Ele encontra a opção de "Cadastro" e inicia o processo.
  - O usuário preenche as informações solicitadas, incluindo nome, endereço de e-mail e senha.
  - Após preencher os dados, ele confirma o cadastro.
  - O sistema envia um e-mail de confirmação para verificar o endereço de e-mail do usuário.
  - O usuário verifica seu e-mail, clica no link de confirmação e ativa sua conta na plataforma.
- **Fluxo Alternativo:**
  - Se o usuário inserir informações incorretas ou um endereço de e-mail inválido, o sistema exibirá uma mensagem de erro e solicitará que ele corrija os campos relevantes antes de prosseguir.

### 2. **Editar Perfil:**

- **Pré-Requisito:**
  - O usuário deve estar registrado e logado na plataforma "thereview."
- **Ator Principal:**
  - Usuário registrado que deseja atualizar suas informações pessoais.
- **Interessados:**
  - Usuário em busca de informações sobre produtos tecnológicos.
  - Administradores da plataforma.
- **Garantia de Sucesso:**
  - O usuário conclui com êxito a edição de seu perfil.
- **Fluxo Principal:**
  - O usuário faz login na plataforma "thereview" com suas credenciais.
  - Ele navega até a seção de "Perfil" em sua conta.
  - O usuário seleciona a opção de "Editar Perfil."
  - Ele pode atualizar informações pessoais, como nome, foto de perfil, endereço de entrega ou preferências de notificação.
  - Após fazer as alterações desejadas, o usuário confirma as atualizações.
- **Fluxo Alternativo:**
  - Se o usuário tentar fazer alterações que não são permitidas (por exemplo, tentar alterar um endereço de e-mail já existente), o sistema exibirá uma mensagem de erro e instruirá o usuário a fazer as correções necessárias.

### 3. **Publicar um Review:**

- **Pré-Requisitos:**
  - O usuário deve estar registrado e logado na plataforma "thereview".
- **Ator Principal:**
  - Usuário registrado que deseja publicar um review em sua conta.
- **Interessados:**
  - Usuário em busca de compartilhar informações sobre produtos tecnológicos.
  - Administradores da plataforma.
- **Garantia de Sucesso:**
  - O usuário conclui com êxito a publicação de um review em seu perfil.
- **Fluxo Principal:**
  - O usuário realiza login na plataforma "thereview" com suas credenciais.
  - Na página inicial o usuário tem de localizar o botão que se destina a criar uma nova publicação.
  - Após selecionar o botão, o usuário será direcionado para uma aba onde ele deve preencher as informações e arquivos necessários para realizar a publicação.
  - Após o devido preenchimento dos campos, o usuário deve confirmar a ação fazendo com que o review seja publicado.
- **Fluxo Alternativo:**
  - O usuário pode inserir dados que não são aceitos pelo sistema. Como por exemplo palavras de baixo calão, termos ofensivos, arquivos que contenham conteúdo explicito ou algo relacionado a tais casos. O sistema irá exibir uma mensagem de erro indicando o(os) campo(os )que o usuário precisa alterar para que a publicação possa ser processada.

### 4. **Excluir Perfil:**

- **Pré-Requisitos:**
  - O usuário deve estar registrado e logado na plataforma "thereview".
- **Ator Principal:**
  - Usuário que deseja realizar a exclusão de seu perfil da plataforma "thereview".
- **Interessados:**
  - Usuário que, por algum motivo, opta por remover seu perfil da plataforma apagando toda e qualquer informação relacionada ao mesmo.
  - Administradores da plataforma que buscam entender o motivo de tal evasão.
- **Garantia de Sucesso:**
  - O usuário deve concordar que todas as informações relacionadas a sua conta serão removidas permanentemente da plataforma, fazendo assim com que logre êxito ao excluir seu perfil.
- **Fluxo Principal:**
  - O usuário faz login na plataforma "thereview" com suas credenciais.
  - Ele navega até a seção de "Perfil" em sua conta.
  - Ele localiza a opção de excluir perfil e seleciona a mesma.
  - Ao selecionar a opção de excluir perfil, o usuário ira ver uma tela com as condições para excluir o perfil. Tendo como condição principal estar ciente de que seus dados serão excluídos permanentemente.
  - Ao afirmar que esta ciente de tal condição a solicitação de exclusão poderá ser processada pelo sistema.
- **Fluxo Alternativo:**
  - O usuário pode desistir de tal solicitação ainda na aba para finalizar a exclusão. Neste caso haverá a opção de cancelar exclusão que o direcionará para a aba perfil.

# Casos de uso resumidos

### 1. **Cadastro na Plataforma:**

- **Descrição:** Novos usuários podem se cadastrar na plataforma "thereview" para acessar análises de produtos tecnológicos.
- **Garantia de Sucesso:**
  O usuário conclui o processo de cadastro e ativa sua conta por meio de um e-mail de confirmação.

### 2. **Editar Perfil:**

- **Descrição:** Usuários cadastrados podem atualizar suas informações pessoais em seus perfis.
- **Garantia de Sucesso:** O usuário conclui com sucesso a edição de seu perfil, fazendo alterações como nome, foto de perfil e opções de notificação.

### 3. **Publicar uma revisão:**

- **Descrição:** Usuários registrados podem compartilhar análises de produtos tecnológicos na plataforma.
- **Garantia de Sucesso:** O usuário publica uma avaliação bem-sucedida, fornece informações e arquivos relevantes.

### 4. **Excluir perfil:**

- **Descrição:** Os usuários podem optar por excluir permanentemente seus perfis na plataforma.
- **Garantia de Sucesso:** O usuário confirma a exclusão de seu perfil, ciente de que todas as informações associadas a sua conta serão removidas permanentemente.

# Casos de uso informais

### 1. **Recuperação de Senha Esquecida:**

- **Descrição:**: Os usuários podem esquecer suas senhas e precisam de um processo de recuperação. Isso não é coberto nos casos de uso principais.
- **Fluxo:**
  O usuário clica na opção "Esqueci minha senha" na tela de login.
  O sistema solicita que o usuário insira seu endereço de e-mail.
  Um e-mail de recuperação de senha é enviado para o endereço fornecido.
  O usuário segue o link no e-mail, define uma nova senha e pode fazer login com a nova senha.
