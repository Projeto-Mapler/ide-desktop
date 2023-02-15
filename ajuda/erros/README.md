# Ajuda em geral sobre o Mapler.

# Acesso rápido
> # Soluções para alguns problemas
> [![java](https://img.shields.io/badge/Java%20-%23323330.svg?&style=for-the-badge&logo=perfil&logoColor=black&color=f2274c)](https://github.com/Projeto-Mapler/ide-desktop/tree/main/ajuda/erros#java)
> [![javahome](https://img.shields.io/badge/Java_HOME%20-%23323330.svg?&style=for-the-badge&logo=perfil&logoColor=black&color=f2274c)](https://github.com/Projeto-Mapler/ide-desktop/tree/main/ajuda/erros#java)
> [![javafx](https://img.shields.io/badge/JavaFx%20-%23323330.svg?&style=for-the-badge&logo=perfil&logoColor=black&color=f2274c)](https://github.com/Projeto-Mapler/ide-desktop/tree/main/ajuda/erros#javafx)
>
> # Ajudas com o uso da IDE
> [![manuais](https://img.shields.io/badge/manuais%20-%23323330.svg?&style=for-the-badge&logo=perfil&logoColor=black&color=c5f745)](https://portugol.sourceforge.io/manuais.html#VisaoGeral)
> [![portugol](https://img.shields.io/badge/sintaxe_portugol%20-%23323330.svg?&style=for-the-badge&logo=perfil&logoColor=black&color=4287f5)](https://github.com/Projeto-Mapler/portugol)
> [![fluxograma](https://img.shields.io/badge/fluxogramas%20-%23323330.svg?&style=for-the-badge&logo=perfil&logoColor=black&color=4287f5)](https://github.com/Projeto-Mapler/fluxograma)
# Dificuldades na instalação

> # Java
> > O projeto da IDE Mapler foi feito em Java e por isso o mesmo se faz necessário para a execução da IDE. Caso o projeto esteja apresentando erros e você suspeite que seja o Java tente esse tutorial:
> > 
> > Windows
> > - Abra o prompt de comando e digite `java -version`, é esperado que a versão instalada do Java seja 11 ou superior. Caso não reconheça o comando ou a versão esteja incorreta: [java](https://www.oracle.com/java/technologies/downloads/). 
> > - Verifique as variaveis de ambiente, se faz necessário que JAVA_HOME esteja com o valor correto. Para fazer isso procure a interface "Propriedades do Sistema" e busque a opção "Variaveis de Ambiente". Na janela de variaveis de ambiente, procure em variáveis do sistema a variavel com nome "JAVA_HOME" e verifique se a mesma tem como valor o caminho correto para a pasta onde o Java foi instalado. Caso não encontre a mesma clique em novo e adicione esta variavel e em seu valor coloque o caminho para a pasta do Java: normalmente o caminho é `C:\Program Files\Java\{aqui vem a versao do java}`
> >
> > Linux
> > - Abra o terminal e digite `java -version`, é esperado que a versão instalada do Java seja 11 ou superior. Caso não reconheça o comando ou a versão esteja incorreta: [java](https://www.oracle.com/java/technologies/downloads/).
> > - Verifique as variaveis de ambiente, no terminal digite `echo $JAVA_HOME` e é esperado como resultado o caminho para a parta onde o java foi instalado. Caso o valor não seja apresentado corretamente ou não reconheça a variavel basta usar o comando `export JAVA_HOME=` e depois do `=` digite o caminho para o diretorio onde o java foi instalado.  Por exemplo: `export JAVA_HOME=/usr/lib/jvm/java-11-oracle`
> # JavaFx:
> > O JavaFx é a tecnologia usada pela interface desktop e durante a instalação da aplicação já encontramos algumas dificuldades quanto a essa biblioteca. Caso aconteça um erro e você veja "JavaFx" em algum trecho deste erro, este tutorial pode lhe ajudar:
> > - Baixe a SDK do JavaFx (também recomendamos atualizar caso já tenha uma versão instalada), para download siga esse [link](https://wiki.openjdk.org/display/OpenJFX/Main) e procure pelo download OpenJfx da Oracle.
> > 
> > Para instalar a JDK do JavaFx se faz necessários diferente passos de acordo com o seu sistema operacional. 
> > - Certifique-se de que a versão baixada da SDK do JavaFx está correta.
> > - Identifique a pasta bin do Java de seu sistema, este passo foi descrito na parte de [ajuda com java]().
> > 
> > MAC
> > > No zip do SDK do JavaFx, procure a pasta bin e em seguinda pegue todos os arquivos com a extensão .dylib e faça a extração colocando estes arquivos na pasta bin do Java instalado.
> > 
> > Windows
> > > No zip do SDK do JavaFx, procure a pasta bin e em seguinda pegue todos os arquivos com a extensão .dll e faça a extração colocando estes arquivos na pasta bin do Java instalado.
> > 
> > Linux
> > > No zip do SDK do JavaFx, procure a pasta bin e em seguinda pegue todos os arquivos com a extensão .so e faça a extração colocando estes arquivos na pasta bin do Java instalado.
> >
> > Depois de colocar os arquivos da JDK do JavaFx no Java, reinicie o computador e tempo executar novamente o Mapler.