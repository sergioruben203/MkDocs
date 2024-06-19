A seguir, um guia detalhado para a instalação do GLPI, para a instalação desse webservice em uma máquina com o sistema operacional Windows 10 será necessário instalar e utilizar o XAMPP.

-1. Instalação do XAMPP
*Baixar o XAMPP através do link: https://www.apachefriends.org/pt_br/download.html

*Baixe a versão mais recente adequada para Windows.

*Aguarde a instalação o XAMPP:

*Execute o instalador do XAMPP.

*Siga as instruções na tela para completar a instalação. Durante a instalação, selecione os componentes Apache, MySQL e PHP.

Iniciar o XAMPP:

*Abra o painel de controle do XAMPP.

*Inicie os módulos Apache e MySQL clicando nos botões "Start".

-2. Preparação do Banco de Dados
Acessar o phpMyAdmin:

*No painel de controle do XAMPP, clique em "Admin" ao lado de MySQL para abrir o phpMyAdmin no navegador.

Criar um Banco de Dados:

*No phpMyAdmin, clique em "Databases".

*Insira um nome para o novo banco de dados (por exemplo, glpi) e clique em "Create".

-3. Download e Extração do GLPI
Baixar o GLPI:

*Acesse o site oficial do GLPI: glpi-project.org.

*Baixe a versão mais recente do GLPI.

Extrair o GLPI:

*Extraia o arquivo baixado para a pasta htdocs do XAMPP. O caminho padrão é C:\xampp\htdocs.

*Renomeie a pasta extraída para glpi (o nome da pasta será usado no navegador para acessar o GLPI).

-4. Configuração do GLPI
Acessar o GLPI no Navegador:

*Abra o navegador e digite http://localhost/glpi na barra de endereços.

Instalação do GLPI:

*Siga as instruções na tela para iniciar a instalação do GLPI.

*Escolha o idioma desejado e clique em "OK".

Verificar Requisitos:

*O instalador verificará os requisitos do sistema. Certifique-se de que todas as verificações estejam marcadas como "OK". Corrija quaisquer problemas, se necessário, antes de prosseguir.

Configurar o Banco de Dados:

*Insira os detalhes do banco de dados criado anteriormente:

 - Servidor: localhost

 - Nome do banco de dados: glpi

 - Nome de usuário: root (ou outro usuário configurado no MySQL)

 - Senha: (deixe em branco se estiver usando o usuário root padrão do XAMPP)

Finalizar a Instalação:

*Siga as instruções restantes para completar a instalação.

*Após a conclusão, anote as credenciais de login geradas pelo instalador (usuário e senha do administrador).
-5. Acesso e Configuração Inicial
*Login no GLPI:

 - Acesse http://localhost/glpi no navegador.

 - Faça login com as credenciais de administrador fornecidas durante a instalação.

*Configuração Inicial:

 - Configure os parâmetros iniciais do GLPI, como preferências de idioma, fuso horário e outras opções relevantes.

Com esses passos, você terá o GLPI instalado e funcionando em sua máquina com Windows 10 usando o XAMPP. Agora, você pode começar a explorar as funcionalidades e personalizar o sistema de acordo com as necessidades da sua organização.