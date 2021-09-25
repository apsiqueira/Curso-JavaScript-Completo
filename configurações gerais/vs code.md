<ol>

<li>instalar plugin code runner 
<ol>
Acesse: "File" > "Preferences" > "Settings" e pesquise por "Code-Runner: Save File Before Run". Marque a caixa referente a esta opção.
</ol>
</li>
<li>instalar plugin prettier
<ol>
definir o arquivo setings.json > inserir >
<code>
{
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  }
}
</code>

</ol>

<ol>
Editor:tab Size =2
</ol>
Editor:Detect identation: disable
<ol>
Editor:Render Whitespace :all
</ol>

<ol>
Editor:Render Whitespace :all
</ol>

<ol>

workbentch >editor: Enable Preview: disable

</ol>
<ol>
Editor:Format on Save > enable
</ol>

</li>
<ol>
<li>Git token
<ol>
A partir de 13 de agosto de 2021, o GitHub não aceita mais senhas de conta ao autenticar as operações do Git. Em vez disso, você precisa adicionar um PAT (Personal Access Token) e você pode seguir o método abaixo para adicionar um PAT em seu sistema.

Criar token de acesso pessoal no GitHub
Da sua conta do GitHub, vá para Configurações => Configurações do Desenvolvedor => Token de Acesso Pessoal => Gerar Novo Token (Dê sua senha) => Fillup o formulário => clique Em Gerar token => Copiar o Token gerado, será algo como ghp_sFhFsSHhTzMDreGRLjmks4Tzuzgthdvfsrta

Agora siga abaixo o método com base em sua máquina:

Para o ⤴ do Sistema Operacional Windows
Vá para o Gerenciador de Credenciais do Painel de Controle => Credenciais do Windows => encontrar => Edit => Em Senha substituir com o seu Token de Acesso Pessoal gitHub => você está feitogit:https://github.com

Se você não encontrar => Clique em Adicionar uma credencial genérica => endereço da Internet será e você precisa digitar seu nome de usuário e senha será o seu Token de Acesso Pessoal gitHub => Clique Ok e você está feitogit:https://github.comgit:https://github.com

Para ⤴ macOS
Clique no ícone Spotlight (lupa) no lado direito da barra de menu. Digite o acesso ao Chaveiro e pressione a tecla Enter para iniciar o aplicativo => Em acesso à chaveiro, procure => Encontre a entrada de senha da internet para => Editar ou excluir a entrada de acordo => Você está feitogithub.comgithub.com

Para um ⤴ operacional baseado em Linux
Para Linux, você precisa configurar o cliente GIT local com um nome de usuário e endereço de e-mail,

$ git config --global user.name "your_github_username"
$ git config --global user.email "your_github_email"
$ git config -l
Uma vez que o GIT esteja configurado, podemos começar a usá-lo para acessar o GitHub. Exemplo:

$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY

> Cloning into `Spoon-Knife`...
> $ Username for 'https://github.com' : username
> $ Password for 'https://github.com' : give your personal access token here
> Agora cache o registro dado em seu computador para lembrar o token:

$ git config --global credential.helper cache
Se necessário, sempre que você pode excluir o registro de cache por:

$ git config --global --unset credential.helper
$ git config --system --unset credential.helper
Agora tente puxar com para verificar-v

$ git pull -v

</ol>

</li>

</ol>

</ol>
