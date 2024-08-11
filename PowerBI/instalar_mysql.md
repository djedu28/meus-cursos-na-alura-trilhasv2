# instalar a máquina o MySQL

O MySQL Workbench é uma ferramenta de administração e modelagem de bancos de dados MySQL que possui uma interface gráfica amigável. É amplamente utilizado por profissionais que trabalham com banco de dados para **projetar, desenvolver e administrar bancos de dados relacionais**. Com o MySQL Workbench, é possível criar, modificar e excluir tabelas, definir relacionamentos entre elas, executar consultas SQL, importar e exportar dados, entre outras funcionalidades. Ele oferece uma visão geral do esquema do banco de dados, permitindo que as pessoas usuárias visualizem e modifiquem sua estrutura de forma intuitiva.

Para instalar o MySQL Workbench, vamos seguir as seguintes etapas:

**Passo 1**: Acesse o site oficial do MySQL para baixar o instalador do MySQL. **Recomendamos baixar a versão 8.0.33**. Você pode encontrar o site pesquisando "MySQL Installer download" em um mecanismo de busca, ou clicando no link abaixo que já está direcionado para as outras versões:

[Download MySQL Installer](https://downloads.mysql.com/archives/installer/)

**Passo 2**: Na página de downloads do MySQL Installer, você encontrará diferentes versões disponíveis para diferentes sistemas operacionais. Selecione a **versão 8.0.33** e faça o download recomendado.

![alt text: Captura de tela da janela de download do MySQL Installer. Na imagem, uma seção principal com o nome MySQL Installer 8.0.33, e, abaixo, uma primeira opção de seleção do sistema operacional, destacado com um retângulo e uma seta vermelhos. Abaixo, temos as opções de download do MySQL Installer, com botão de “Download” da segunda opção destacado com um retângulo e uma seta vermelhos.](https://cdn3.gnarususercontent.com.br/2956-power-bi-desktop/Images/aula1-img74.png)

**Passo 3**: Após escolher o local de download do arquivo e finalizá-lo, localize o arquivo de instalação no seu computador e execute-o. Você pode ser solicitado a confirmar se deseja permitir que o programa faça alterações no seu dispositivo - nesse caso, clique em "Sim" ou "Permitir".

**Passo 4**: Na primeira tela, selecionamos a opção “Developer Default” e selecionamos o botão “Next >”.

> **Observação:** Caso a opção "Developer Default" não apareça para você, basta marcar a opção **Full** e seguir os próximos passos.

![alt text: Captura de tela do instalador do MySQL, com fundo branco. Na esquerda, temos o menu lateral das etapas a serem realizadas, com fundo azul; a etapa atual é a de “Choosing a setup type”. Na direita, temos as opções a serem selecionadas para a configuração do setup; no topo, temos o título da etapa, e, abaixo, temos as opções disponíveis, com a opção no topo “Developer Default” escolhida. Na direita dessas opções, temos uma descrição da opção escolhida. No canto inferior direito, temos os botões de Next e Cancel.](https://cdn3.gnarususercontent.com.br/2956-power-bi-desktop/Images/aula1-img8.png)

**Passo 5**: Na próxima tela, de Download, e durante a instalação, você será solicitado a selecionar os componentes que deseja instalar. Certifique-se de que a opção "MySQL Workbench" está na lista para que seja baixado no seu sistema. Após isso, selecione a opção “Execute”.

![alt text: Captura de tela do instalador do MySQL, com fundo branco. Na esquerda, temos o menu lateral das etapas a serem realizadas, com fundo azul; a etapa atual é a de “Download”. Na direita, temos os produtos que estão sendo baixados e o estado atual de download, com destaque para o MySQL Workbench com uma seta vermelha. No canto inferior direito, temos o botão Back, o botão Execute, destacado com um retângulo vermelho e uma seta vermelha, e o botão Cancel.](https://cdn3.gnarususercontent.com.br/2956-power-bi-desktop/Images/aula1-img9.png)

**Passo 6**: Devemos aguardar até que o processo de download esteja concluído. Uma vez concluído, aperte o botão “Next >” e prossiga para o processo de instalação. Na tela de instalação, vamos selecionar a opção “Execute”.

![alt text: Captura de tela do instalador do MySQL, com fundo branco. Na esquerda, temos o menu lateral das etapas a serem realizadas, com fundo azul; a etapa atual é a de “Installation”. Essa etapa está destacada por uma seta vermelha. Na direita, temos os produtos que estão sendo baixados e o estado atual de download. No canto inferior direito, temos o botão Back, o botão Execute, destacado com um retângulo vermelho, e o botão Cancel.](https://cdn3.gnarususercontent.com.br/2956-power-bi-desktop/Images/aula1-img10.png)

**Passo 7**: Devemos aguardar até que o processo de instalação esteja concluído. Uma vez concluído, aperte o botão “Next >” e prossiga até o final do assistente de instalação.

> Nas próximas telas, irão aparecer configurações relativas a configuração do servidor do MySQL Server. Apenas trabalhe sobre os campos que considerar achar necessário. Para esse cursos, não iremos nos aprofundar nessas opções, apenas na criação da conta de administrador necessária (Root account), localizada na tela de “Account and Roles”.

**Passo 8**: Na janela “Account and Roles”, precisamos criar uma senha para o administrador do MySQL. Digite a senha desejada e a salve um local de fácil acesso. Caso esse banco venha a ser utilizado em outros projetos, lembre-se de construir uma senha forte. Após digitar a senha, prossiga selecionando “Next >” para prosseguir até chegar na tela “Connect to Server”.

![alt text: Captura de tela do instalador do MySQL, com fundo branco. Na esquerda, temos o menu lateral das etapas a serem realizadas, com fundo azul; a etapa atual é a de “Accounts and Roles”. Na direita, temos os campos de configuração de conta, com os campos de senha e repetir senha; mais abaixo, temos uma tabela com as pessoas usuárias já criados. No canto inferior direito, temos os botões de Back, Next e Cancel.](https://cdn3.gnarususercontent.com.br/2956-power-bi-desktop/Images/aula1-img11.png)

**Passo 9**: Agora, precisamos digitar a senha que foi criada para o usuário `root` no passo anterior. Após isso, clique no botão “Check” e siga prosseguindo para as próximas telas.

![alt text: Captura de tela do instalador do MySQL, com fundo branco. Na esquerda, temos o menu lateral das etapas a serem realizadas, com fundo azul; a etapa atual é a de “Connect To Server”. Na direita, temos uma tabela com o MySQL Server, mostrando seu status; mais abaixo, temos o campo User name e o campo Password, destacado por um círculo em vermelho com o número 1, em branco. Na sequência, temos o botão Check, também destacado por um círclo em vermelho mas com o número 2 em branco. No canto inferior direito, temos os botões de Next e Cancel.](https://cdn3.gnarususercontent.com.br/2956-power-bi-desktop/Images/aula1-img12.png)

**Passo 10**: Quando a instalação estiver completa, você irá para a página de título “Installation Complete”. Para finalizar a instalação, clique em “Finish”.

![alt text: Captura de tela do instalador do MySQL, com fundo branco. Na esquerda, temos o menu lateral das etapas a serem realizadas, com fundo azul; a etapa atual é a de “Installation complete”. Na direita, a informação de que a instalação foi completada, com as caixas de seleção para começar o MySQL Workbench e o MySQL Shell após finalizar . No canto inferior direito, temos o botão de Finish, destacado com uma seta e um retângulo vermelho.](https://cdn3.gnarususercontent.com.br/2956-power-bi-desktop/Images/aula1-img13.png)

**Passo 11**: Após finalizar a instalação desses componentes, precisamos adicionar mais um componente: o Connector. Esse componente é necessário para que o Power BI identifique o MySQL. Para isso, pesquise pelo MySQL Installer no seu computador e o inicie:

![Captura de tela da pesquisa do MySQL Instalar no Windows, com fundo preto. O  ícone da ferramenta está destacado com um retângulo vermelho.](https://cdn3.gnarususercontent.com.br/2956-power-bi-desktop/Images/aula1-img75.png)

**Passo 12**: Na tela inicial do MySQL Installer, você irá encontrar os componentes do MySQL que estão instalados. Para adicionar o componente do Connector, clique no botão “Add” na direita:

![Captura de tela da tela inicial do MySQL Installer, com os componentes instalados e com o botão de adicionar um novo componente destacado com um retângulo vermelho, localizado no canto superior direito.](https://cdn3.gnarususercontent.com.br/2956-power-bi-desktop/Images/aula1-img76.png)

**Passo 13**: Na tela de Seleção de Produtos, expanda o campo “MySQL Connection”, depois o campo “Connector/NET” e, por fim, o campo “Connector/NET 8.0”.

![Captura de tela da janela de Seleção de Produtos do MySQL Installer, contendo a listagem dos produtos, com destaque para o MySQL Connectors, mais especificamente o Connector/NET 8.0.](https://cdn3.gnarususercontent.com.br/2956-power-bi-desktop/Images/aula1-img77.png)

**Passo 14**: Ao expandir o campo “Connector/NET 8.0”, várias versões do Connector serão listadas. Para que o MySQL seja reconhecido pelo Power BI, as versões `8.0.29` em diante não funcionam. Nesse caso, vamos **utilizar a versão `8.0.28`**. Para isso, clique no campo dessa versão e depois na seta verde ao meio, para que ela seja selecionada:

![Captura de tela da janela de Seleção de Produtos do MySQL Installer, contendo a listagem dos MySQL Connectors, mais especificamente o Connector/NET 8.0.28. No meio temos um botão em forma de seta que seleciona o produto destacado em vermelho.](https://cdn3.gnarususercontent.com.br/2956-power-bi-desktop/Images/aula1-img78.png)

**Passo 15**: Após selecionar a versão adequada do conector, clique em Next:

![Captura de tela da janela de Seleção de Produtos do MySQL Installer, contendo a listagem dos MySQL Connectors, mais especificamente o Connector/NET 8.0.28 selecionado. No canto inferior direito temos o botão Next em destaque.](https://cdn3.gnarususercontent.com.br/2956-power-bi-desktop/Images/aula1-img79.png)

**Passo 16**: Na janela de Instalação, clique em Execute:

![Captura de tela da janela de Instalação, com o Connector/NET 8.0.28 pronto para instalação. No canto inferior direito temos o botão Execute em destaque.](https://cdn3.gnarususercontent.com.br/2956-power-bi-desktop/Images/aula1-img80.png)

**Passo 17**: Assim que a execução finalizar, clique em Next:

![Captura de tela da janela de Instalação, com o Connector/NET 8.0.28 instalado. No canto inferior direito temos o botão Next em destaque.](https://cdn3.gnarususercontent.com.br/2956-power-bi-desktop/Images/aula1-img81.png)

**Passo 18**: Para completar o processo, clique em Finish. Com isso, finalizamos a instalação do conector do MySQL:

![Captura de tela da janela de Instalação Completa. No canto inferior direito temos o botão Finish em destaque.](https://cdn3.gnarususercontent.com.br/2956-power-bi-desktop/Images/aula1-img82.png)
