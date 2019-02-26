# Como executar o notebook através do binder

Esta é a opção mais simples, que não exige instalação de programas adicionais.

Clique na *badge* abaixo e ele irá te levar a uma outra página web, onde você encontrará os arquivos para executar o notebook.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/leobezerra/pensamento-computacional/master)

Aguarde um pouco a página terminar de carregar e você verá uma página semelhante a página abaixo:

![img-binder-1](images/img-binder-1.png)

Quando a página estiver completamente carregada, clique no nome do notebook que deseja abrir.

> Notebooks são arquivos especiais cuja extensão é `ipynb`. Neste caso, o notebook que você deve abrir é o `blockly.ipynb`.

O notebook é aberto em uma nova aba, em uma página parecida com a imagem abaixo:

![img-binder-2](images/img-binder-2.png)

Esta é a interface do *Jupyter notebook*. 

Antes de começar a usar, você precisa instalar a biblioteca que dá acesso ao Blockly.

> Tudo será instalado no ambiente virtual que você está utilizando, nada rodará localmente no seu computador 😉

Para isso você deve selecionar a primeira célula (que começa com `!git clone ...`) e executá-la. 

Você pode fazer isso apertando `Alt + Enter` ou clicando na aba `Cell` e em seguida em `Run Cells`.

> Quando a execução de uma célula é concluída, aparece um número entre colchetes do lado dela 👍🏻

Uma vez instalado o Blockly, você precisa recarregar a página (aperte `F5` no seu teclado).

> Se o navegador pedir confirmação de que você deseja deixar a página, pode confirmar 👍🏻

Se a instalação tiver funcionado, a barra de menu do Jupyter deverá ter agora uma opção "Blockly language". 

Por padrão, o Blockly vêm em inglês, mas você pode escolher a que preferir (incluindo Português brasileiro).

Agora que tudo está instalado, você só precisa executar a próxima célula do notebook e seu ambiente de aprendizado com o blockly estará pronto!

![img-binder-3](images/img-binder-3.png)
