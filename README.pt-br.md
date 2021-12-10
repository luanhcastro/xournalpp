# Xournal++

[![Build Status](https://dev.azure.com/xournalpp/xournalpp/_apis/build/status/CI?branchName=master)](https://dev.azure.com/xournalpp/xournalpp/_build/latest?definitionId=1&branchName=master)
[![Join the chat at https://gitter.im/xournalpp/xournalpp](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/xournalpp/xournalpp?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

<table border="0px" ><tr><td width = 600px>

<img src="readme/main.png" width=550px% title="Xournal++ Screenshot on Linux"/>

</td><td>

## Alerta! - Precisamos de tradutores!

Recentemente, revisitamos a caixa de diálogo de configurações para melhorar a sensação e a usabilidade.
Ao fazer isso, também adicionamos descrições melhores, para as quais exigimos
novas traduções.

Traduções parciais, que precisam ser atualizadas:

- Tcheca
- Polonês
- Chinês

Traduções completas para todos os idiomas não mencionados anteriormente **exceto**:

- Inglês
- Alemâo
- Italiano

Se você quiser nos ajudar a melhorar a localização do Xournal ++, dê uma olhada em [nosso projeto Crowdin](https://crowdin.com/project/xournalpp). Se você estiver interessado em traduzir um novo idioma, entre em contato conosco no [Gitter](https://gitter.im/xournalpp/xournalpp) ou crie um novo fascículo e nós desbloquearemos o idioma no Crowdin.

**Obrigado desde já!**

</td></tr></table>

## Recursos

Xournal++ (/ˌzɚnl̟ˌplʌsˈplʌs/) é um software para tomar notas escrito em C ++ com o objetivo de flexibilidade, funcionalidade e velocidade.
O reconhecedor de traços e outras partes são baseados no código Xournal, que você pode encontrar em [sourceforge](http://sourceforge.net/projects/xournal/)

Recursos do Xournal++:

- Suporta estiletes sensíveis à pressão e mesas de caneta digital (por exemplo, tablets Wacom, Huion, XP Pen, etc.)
- Planos de fundo de papel para anotações, rascunho ou quadro branco
- Faça anotações sobre PDFs
- Exporte para uma variedade de formatos, incluindo SVG, PNG e PDF, tanto da GUI quanto da linha de comando
- Diferentes ferramentas de desenho (por exemplo, caneta, marca-texto) e estilos de traçado (por exemplo, sólido, pontilhado)
- Desenho de forma (linha, seta, círculo, retângulo, spline)
- Funcionalidade de forma de preenchimento
- redimensionamento e rotação da forma
- Rotação e ajuste de grade para alinhamento preciso de objetos
- Estabilização de entrada para escrita / desenho mais suave
- Ferramenta de texto para adicionar texto em diferentes fontes, cores e tamanhos
- Suporte aprimorado para inserção de imagem
- Borracha com múltiplas configurações
- Suporte a LaTeX (requer uma instalação LaTeX funcional) com modelo personalizável
- Barra lateral com visualizações de página com classificação de página avançada, marcadores e camadas de PDF (podem ser ocultados / editados individualmente)
- Permite mapear diferentes ferramentas / cores, etc. para botões da caneta / mouse
- Barra de ferramentas personalizável com várias configurações, por exemplo para otimizar a barra de ferramentas para retrato / paisagem
- Definições de modelo de página
- Relatórios de bugs, salvamento automático e ferramentas de backup automático
- Gravação e reprodução de áudio junto com notas manuscritas
- Suporte multilíngue (mais de 20 idiomas suportados)
- Plugins usando script Lua

## Aplicativo mobile & web

Desde meados de 2020, existe um aplicativo móvel escrito pelo Flutter para ** Android **, ** Chrome OS ** e ** iOS ** (em breve), bem como um ** aplicativo web ** disponível. Mesmo que não seja perfeitamente estável e nem todos os recursos do Xournal ++ sejam totalmente suportados, você pode verificar e abrir seus notebooks Xournal ++ em seus dispositivos móveis. Você pode entrar em contato em seu [repositório separado no GitLab](https://gitlab.com/TheOneWithTheBraid/xournalpp_mobile).

[Obtenha no Google Play](https://play.google.com/store/apps/details?id=online.xournal.mobile)

A versão web é disponibilizada em [xournal.online](https://xournal.online).

_Por que o aplicativo iOS ainda não foi publicado?_

De acordo com as diretrizes da Apple App Store, é proibido publicar aplicativos instáveis ou beta. Portanto, esperamos até que o Xournal ++ Mobile funcione de maneira mais estável e ofereça compatibilidade de recursos mais completa com o Xournal ++.

<table>
<tr>
<td>

## Linux

<img src="readme/main.png" width=100% title="Xournal++ Screenshot on Linux"/>

</td><td>

## Windows 10

<img src="readme/main-win.png" width=100% title="Xournal++ Screenshot on Win10"/>

</td></tr><tr><td>

## macOS Catalina

<img src="readme/main-mac.png" width=100% title="Xournal++ Screenshot on macOS"/>

</td><td>

## Xournal++ Mobile

<img src="https://gitlab.com/TheOneWithTheBraid/xournalpp_mobile/-/raw/master/fastlane/metadata/android/en_US/images/tenInchScreenshots/03.png" width=100% title="Xournal++ Mobile Screenshot on Chromium OS"/>

</td></tr><tr><td>

## Barra de Ferramentas / Fundo da Página / Camada

Plano de fundo de várias páginas, facilmente selecionável na barra de ferramentas
<img src="readme/background.png" width=100% title="Xournal++ Screenshot"/>

</td><td>

## Barra lateral da camada e seleção de camada avançada.

<img src="readme/layer.png" width=100% title="Xournal++ Screenshot"/>

</td></tr><tr><td>

## Barra de ferramentas predefinida e totalmente personalizável.

<img src="readme/toolbar.png" width=100% title="Xournal++ Screenshot"/>

</td></tr></table>

## Manual do usuário e FAQ

Para uso geral, consulte o [Manual de Usuário](https://github.com/xournalpp/xournalpp/wiki/User-Manual). Respostas para
algumas perguntas comuns podem ser encontradas no
[FAQ](https://github.com/xournalpp/xournalpp/wiki/Frequently-Asked-Questions-&-Problem-Solving).

## Recursos experimentais:

Às vezes, é adicionado um recurso que pode não ser sólido como uma rocha ou os desenvolvedores não têm certeza se é útil.
Experimente e dê-nos algum feedback.

Aqui estão alguns em desenvolvimento com os quais você pode jogar agora.

- <img src="readme/floatingtoolboxmbmenu.png"  title="Xournal++ Screenshot"/> Atribua um botão do mouse ou botão da caneta para abrir uma caixa de ferramentas de barras de ferramentas logo abaixo do cursor. Você também pode modificar o que está na caixa de ferramentas através do usual Exibir-> Barras de Ferramentas-> Personalizar, embora **não apareça a menos que você tenha atribuído um botão nas preferências: mouse ou caneta** (ou selecionado uma configuração de barra de ferramentas que usa isto).

 - Este é um recurso experimental porque nem tudo que você pode colocar na caixa de ferramentas se comporta. Portanto, esteja atento.

    <img src="readme/floatingtoolbox.png" width=25% />

* Fique atento a outros recursos experimentais nas preferências, conforme visto aqui:

   DrawingTools: Ao desenhar uma caixa, círculo, etc., simula os modificadores ctrl ou shift pela direção inicial em que você move o mouse.

   Ação no toque da ferramenta: Permitir um breve toque na tela para abrir a caixa de ferramentas flutuante e / ou selecionar um objeto. Pode funcionar apenas com caneta e marcador.

   <img src="readme/moreexperimentals.png" width=50% />

## Instalação

Os lançamentos oficiais do Xournal ++ podem ser encontrados na
[Releases](https://github.com/xournalpp/xournalpp/releases) página. Nós provemos
binários para Debian (Buster), Ubuntu (16.04), MacOS (10.15 e mais recente) e
Janelas. Para outras distribuições Linux (ou mais antigas / mais recentes), também fornecemos um
AppImage que é binário compatível com qualquer distribuição lançada em torno de ou
após o Ubuntu 16.04. Para instalar o Xournal ++ Mobile em dispositivos portáteis, veja [Xournal++ Mobile's instructions](https://gitlab.com/TheOneWithTheBraid/xournalpp_mobile#try-it-out)

**Uma observação para usuários do Ubuntu / Debian**: os binários oficiais que fornecemos são
compatível apenas com a _versão específica do Debian ou Ubuntu_ indicada pelo
nome do arquivo. Por exemplo, se você estiver no Ubuntu 20.04, o binário cujo nome
contém `Ubuntu-bionic` é _somente_ compatível com Ubuntu 18.04. Se o seu sistema
não é uma das versões específicas do Debian ou Ubuntu que são suportadas pelo
binários oficiais, recomendamos que você use o PPA (somente Ubuntu), o Flatpak ou o
AppImage.

Também existe uma _unstable_, [automated nightly
release](https://github.com/xournalpp/xournalpp/releases/tag/nightly) onde
inclui os recursos e correções de bugs mais recentes.

Com a ajuda da comunidade, o Xournal ++ também está disponível nos repositórios oficiais
de algumas distribuições e plataformas Linux populares.

### Debian

Aqui estão [Stable releases](https://github.com/xournalpp/xournalpp/releases) e
_unstable_ [automated nightly releases](https://github.com/xournalpp/xournalpp/releases/tag/nightly)
para Debian.

### Ubuntu e derivados

#### Stable PPA
A última versão estável está disponível através do seguinte [_unofficial_ PPA](https://github.com/xournalpp/xournalpp/issues/1013#issuecomment-692656810):

```bash
sudo add-apt-repository ppa:apandada1/xournalpp-stable
sudo apt update
sudo apt install xournalpp
```

#### Unstable PPA
Um lançamento noturno _unstable_ está disponível para distribuições baseadas no Ubuntu por meio do seguinte PPA:

```bash
sudo add-apt-repository ppa:andreasbutti/xournalpp-master
sudo apt update
sudo apt install xournalpp
```

Este PPA é fornecido pela equipe do Xournal ++. Embora tenha os recursos mais recentes e
correções de bugs, ele também não foi testado completamente e pode falhar periodicamente (nós
tente o nosso melhor para não quebrar as coisas).

### Fedora

A [released version of
xournalpp](https://src.fedoraproject.org/rpms/xournalpp) está disponível em
[main repository](https://bodhi.fedoraproject.org/updates/?packages=xournalpp)
via aplicação de software do seguinte comando:

```bash
sudo dnf install xournalpp
```

or

```bash
pkcon install xournalpp
```

Os pacotes de última geração sincronizados com xournalpp git master diariamente estão disponíveis em [COPR luya/xournalpp](https://copr.fedorainfracloud.org/coprs/luya/xournalpp/).
[![Copr build status](https://copr.fedorainfracloud.org/coprs/luya/xournalpp/package/xournalpp/status_image/last_build.png)](https://copr.fedorainfracloud.org/coprs/luya/xournalpp/package/xournalpp/)

### openSUSE

No openSUSE Tumbleweed, a versão lançada do Xournal ++ está disponível no
repositório principal:

```bash
sudo zypper in xournalpp
```

Para o openSUSE Leap 15.0 e anterior, use o link de instalação de
[X11:Utilities](https://software.opensuse.org//download.html?project=X11%3AUtilities&package=xournalpp).

Para todas as versões do openSUSE, pacotes de última geração sincronizados com xournalpp git
master em uma base semanal estão disponíveis em
[home:badshah400:Staging](https://software.opensuse.org//download.html?project=home%3Abadshah400%3AStaging&package=xournalpp).

### Arch Linux

A última versão estável está disponível [in the [community]
repository](https://www.archlinux.org/packages/community/x86_64/xournalpp/).

Para construir você mesmo o estado mais recente do branch master, use [this AUR
package](https://aur.archlinux.org/packages/xournalpp-git/).

### Solus

A última versão estável está disponível no repositório principal:

```bash
sudo eopkg it xournalpp
```

### Flatpak

A equipe do Xournal ++ suporta oficialmente um [FlatHub
release](https://flathub.org/apps/details/com.github.xournalpp.xournalpp), que
pode ser instalado com

```bash
flatpak install flathub com.github.xournalpp.xournalpp
```

Observe que para o Xournal ++ funcionar corretamente, você deve ter pelo menos um tema GTK
e um tema de ícone instalado no Flatpak. Para habilitar o suporte a LaTeX, você também
precisa instalar a extensão TeX Live:

```bash
flatpak install flathub org.freedesktop.Sdk.Extension.texlive
```

O manifesto Flatpak pode ser encontrado no pacote [Xournal ++ Flatpak
repositório] (https://github.com/flathub/com.github.xournalpp.xournalpp), e todos
Problemas de empacotamento relacionados ao Flatpak devem ser relatados lá.

### Android and Chrome OS

O Android é compatível com o Xournal ++ Mobile. Ele pode ser baixado em [Tags page](https://gitlab.com/TheOneWithTheBraid/xournalpp_mobile/-/tags) ou [from Google Play](https://play.google.com/store/apps/details?id=online.xournal.mobile).

### iOS

Infelizmente, o aplicativo iOS ainda não foi publicado na Apple App Store. Veja [here](#mobile--web-app) para saber por quê. De qualquer forma, em [Building section](#building) você pode aprender como construir uma prévia.

### Windows

Os lançamentos oficiais do Windows são fornecidos em [Releases
page](https://github.com/xournalpp/xournalpp/releases).

**Notas:**

- Atualmente, apenas drivers WinTab são suportados. Isso é devido a uma limitação com
  a biblioteca subjacente que usamos, GTK.
- Existe um bug GTK que impede que a entrada da caneta funcione corretamente. Por favor comece
  Xournal ++, toque com a caneta, saia do Xournal ++ e comece novamente. Então caneta
  entrada estará funcionando, até que você reinicie o Windows. Ver
   [#659](https://github.com/xournalpp/xournalpp/issues/659).

### Mac OS X

As versões do Mac OS X são fornecidas em [Releases
page](https://github.com/xournalpp/xournalpp/releases).

**Notas:**

- Houve problemas de compatibilidade com o Mac OS X Catalina em relação a ambos
  permissões de arquivo e suporte para stylus
  ([#1772](https://github.com/xournalpp/xournalpp/issues/1772) e
  [#1757](https://github.com/xournalpp/xournalpp/issues/1757)). Infelizmente,
  não temos recursos para apoiar adequadamente Catalina neste momento. Ajuda
  seria apreciado!
- Xournal ++ será entregue com um GTK corrigido. Caso contrário, a sensibilidade à pressão não funcionará no Mac
  [#569](https://github.com/xournalpp/xournalpp/issues/569).

# Construindo

## Linux

### Instalando as dependências

Xournal++ é programado com c++17 e precisa de cabeçalho e de uma biblioteca de sistema de arquivos, seja STL ou o boost implementation. Portanto, é necessário instalar um compilador para implementar esses recursos. Recomenda-se g++-8 ou clang-9 ou versões mais recentes.

Se você souber de depedências melhores e mais precisas, por favor, crie um pull request (ou uma issue).

Lua precisa de plugins, caso esses plugins não sejam encontrados, eles serão desabilitados.

#### Gerador CMake

As instruções de instalação não se referem a nenhuma ferramenta geradora específica (a não ser o CMake), porém eles requerem make, ninja ou qualquer outro gerador CMake. É necessário ter instalado tal ferramenta para dar continuidade na instalação do xournalapp.

A versão mínima do CMake necessária é a versão 3.10, mas é mais recomendado utilizar da versão 3.15 para cima.

#### Comandos específicos para cada distribuição

**Arch:**
```bash
sudo pacman -S cmake gtk3 base-devel libxml2 cppunit portaudio libsndfile \
poppler-glib texlive-bin texlive-pictures gettext libzip lua53 lua53-lgi
```

**Fedora/ CentOS/ RHEL:**
```bash
sudo dnf install gcc-c++ cmake gtk3-devel libxml2-devel cppunit-devel portaudio-devel libsndfile-devel \
poppler-glib-devel texlive-scheme-basic texlive-dvipng 'tex(standalone.cls)' gettext libzip-devel \
librsvg2-devel lua-devel lua-lgi
```

**Ubuntu/ Debian e Raspberry Pi OS:**
```bash
sudo apt-get install cmake libgtk-3-dev libpoppler-glib-dev portaudio19-dev libsndfile-dev \
libcppunit-dev dvipng texlive libxml2-dev liblua5.3-dev libzip-dev librsvg2-dev gettext lua-lgi
```

**openSUSE:**
```bash
sudo zypper install cmake gtk3-devel cppunit-devel portaudio-devel libsndfile-devel \
texlive-dvipng texlive libxml2-devel libpoppler-glib-devel libzip-devel librsvg-devel lua-lgi
```

**Solus:**
```bash
sudo eopkg it -c system.devel

sudo eopkg it cmake libgtk-3-devel libxml2-devel poppler-devel libzip-devel \
portaudio-devel libsndfile-devel alsa-lib-devel cppunit-devel lua-devel \
librsvg-devel gettext
```

### Compilando

Os passos para compilar Xournal++ são bem simples:

```bash
git clone http://github.com/xournalpp/xournalpp.git
cd xournalpp
mkdir build
cd build
cmake ..
cmake --build .
# For a faster build, set the flag -DCMAKE_BUILD_TYPE=RelWithDebInfo
```
Para configurar a compilação graficamente, use ```cmake-gui ..```

Com Cairo 1.16 PDF, é possível fazer anotações (bookmarks), mas esta versão não está sempre disponível, portanto ao exportar um arquivo como PDF pelo Cairo, ele é exportado sem as anotações realizadas.

O executável binário estará no subdiretório ```build/src/```.

### Packaging e instalação

#### Criando pacotes para os gestores de pacotes 

Primeiramente, certifique-se de que o destino das traduções tenha sido construído antes de tentar gerar qualquer outro pacote.
```bash
cmake --build . --target translations
```

Após a compilação, selecione quais pacotes você deseja gerar (veja as seções mais relevantes abaixo) e então execute o comando para gerar o pacote. Os pacotes gerados estarão localizados em ```build/packages```. Exemplo dos comandos:
```bash
cmake .. -DCPACK_GENERATOR="TGZ;DEB"  # Generate .tar.gz and .deb packages
cmake --build . --target package
```

Por padrão, o pacote ```.tar.gz``` será gerado. Para outros distritos, como AppImages e Flatpaks, veja a seção abaixo.

**Pacotes .deb**
```bash
cmake .. -DCPACK_GENERATOR="DEB" ..
cmake --build . --target package
```

**Pacotes .rpm**
TODO

**AppImage**

A forma mais rápida para gerar o AppImage, é primeiro gerar o pacote ```.tar.gz``` e depois usá-lo com o script ```azure-pipelines/util/build_appimage.sh```.

```bash
cmake .. -DCPACK_GENERATOR="TGZ"
cmake --build . --target package
../azure-pipelines/util/build_appimage.sh
```

O script ```build_appimage.sh``` fará o download, automaticamente, de LinuxDeploy. Basta copiar os arquivos ```.tar.gz``` e as bibliotecas e recursos necessários para o diretório ```appimage_staging``` e executar LinuxDeploy no diretório preparado.

Automaticamente, o ```build_appimage.sh``` fará uma cópia do tema Adwaita GTK e o do ícone Adwaita de AppImage.

**Flatpak**

A patente de Xournal++ está localizado em [https://github.com/flathub/com.github.xournalpp.xournalpp], e deve ser clonado em um diretório separado antes das contruções.
```bash
git clone https://github.com/flathub/com.github.xournalpp.xournalpp xournalpp-flatpak
```

Por padrão, a patente do Flatpak fará o download da versão atual mais estável do Xournal++. Você poderá mudar a versão para a versão desejada editando o *commit* da patente. Também é interessante especificar a *tag*, se você estiver fazendo a alteração para uma versão estável.
```bash
 - name: xournalpp
     buildsystem: cmake-ninja
     sources:
       - type: git
         url: https://github.com/xournalpp/xournalpp
-        commit: 14e9012b94e005112387dbb7d2ed59274d542885
-        tag: 1.0.10
+        commit: a911a3911df7c588c23997a29ad6a2e8d48b4aea
+        tag: 1.0.15
```

Também é possível construir o clone do Xournal++ alterando o tipo para ```dir``` e especificando o caminho para o clone.

#### Instação a partir da origem

**Nós, fortemente, NÃO recomendamos fazer a instação a partir da origem**, pois pode levar a problemas quando for necessária atualizações para novas versões. Ao invés disso, pense em criar um pacote nativo, como AppImage ou Fratpak. As instruções estão a cima.

Caso você realmente não queira criar um pacote, é possível instalar o Xournal++ na sua pasta de usuário apenas especificando ```CMAKE_INSTALL_PREFIX```:

```bash
cmake .. -DCMAKE_INSTALL_PREFIX=$HOME/.local
cmake --build . --target install
./cmake/postinst configure
```

Se você desejar fazer o download do Xournal++ pelo âmbito do sistema diretamente pela contrução de diretório, utilize o seguinte comando:
```bash
cmake .. -DCMAKE_INSTALL_PREFIX=/usr
sudo cmake --build . --target install
./cmake/postinst configure
```


## MacOS .app

Não instale macports ou homebrew. Caso você já tenha instalado, será necessário criar outro user e usá-lo para esse processo. jhbuild também não funcionará.

Uma possível forma de utilizar o jhbuild juntamente com o brew é se você desatar todos os módulos do brew antes de executar o jhbuild. Depois de finalizado a construção, eles podem ser atados novamente. Mas esse método não foi testado, então existe a possibilidade de não dar certo.

### Certifique-se de que o ambiente de desenvolvimento foi instalado

Abra o terminal e digite ```git```, confirme o pop-up da AppleStore clicando em 'Instalar', nas ferramentas de desenvolvimento.

### Construa as bibliotecas (só é necessário realizar uma única vez)

Antes de seguir os próximos passos, resolva todos os problemas pendentes com a atual versão do seu SO. Os erros irão variar de acordo com a versão das bibliotecas. Se você se deparar com um erro desconhecido, sinta-se a vontade em adicioná-lo nesta seção de instruções.

#### 1. Contruindo GTK

```bash
./build-gtk3.sh
```

**Erros mais comuns**

*itstool (version 2.0.6 on macOS High Sierra 10.13)*

itstool pode falhar ao tentar realizar a configuração procurando por uma ligação com libxml2 python.
Siga os passos abaixo para resolver o problema:
    1. Abra o shell com a opção 4
    2. Altere a versão do Python para a versão 2.7, usando: ```export PYTHON=/usr/bin/python2.7```
    3. Execute a etapa de configuração manualmente, usando: ```./configure --prefix $HOME/gtk/inst``
    4. Saia do shell com ```exit```
    5. Continue a construção com a opção 2

*expat (macOS Mojave 10.14)*

O construtor pode se deparar com o seguinte erro:
```bash
configure: error: C compiler cannot create executables
```

Siga os passos abaixo para resolver o problema:
    1. Abra o shell com a opção 4
    2. Execute a etapa de configuração manualmente, usando: ```./configure --prefix $HOME/gtk/inst```
    3. Saia do shell com ```exit```
    4. Continue a construção com a opção 2

#### 2. Inicie o jhbuild shell

```bash
$HOME/.new_local/bin/jhbuild shell
```

#### 3. Construa o Poppler

Execute o seguinte comando no diretório:

```bash
./build-poppler.sh
```

#### 4. Construa PortAudio

```bash
./build-portaudio.sh
```

#### 5. Construa LibZip

```bash
./build-libzip.sh
```

**Erros comuns**

*Unknown module (macOS Mojave 10.14)*

Caso houver um erro como o a seguir:

```bash
xcode-select: error: tool 'xcodebuild' requires Xcode, but active developer directory '/Library/Developer/CommandLineTools' is a command line tools instance
```

Siga os passos abaixo para resolver o problema:
    1. Instale Xcode () se você ainda não o possuir
    2. Aceite os termos e condições
    3. Certifique-se de  que o aplicativo Xcode está em /Application e **não** em /Users/{user}/Applications
    4. Direcione o xcode-select para o diretório de desenvolvimento do aplicativo Xcode, usando o seguinte comando:
      4.1 ```sudo xcode-select -s /Applications/Xcode.app/Contents/Developer```
    5. Certifique-se de qe o caminho do Xcode está correto:
      i) Xcode: */Applications/Xcode.app/Contents/Developer*
      ii) Xcode-beta: */Applications/Xcode-beta.app/Contents/Developer*

#### 6. Construa sndfile

**Gravar e escutar áudios ainda não são é suportado pelo MacOS.**
```bash
./build-sndfile.sh
```

#### 7. Construa ícone adwaita 

```bash
jhbuild build adwaita-icon-theme
```

### Construa o Xournal++ e pacotes como .app

**Passo automatizado**

```bash
./complete-build.sh $HOME/gtk
```

**Passos manuais**

Construa Xournal++

```bash
export PATH="$HOME/.local/bin:$HOME/gtk/inst/bin:$PATH"

cmake -DCMAKE_INSTALL_PREFIX:PATH=$HOME/gtk/inst ..
make -j 4
make install
```

Construa App

```bash
./build-app.sh $HOME/gtk
```

## Construindo Xournal++ para Mac Homebrew

**Nós, oficialmente, não damos suporte às construçĩes com Homebrew. Eles existem por completa conveniência.**

É fortemente recomendado que se use ou o lançamento oficial ou o noturno. 

### Instalando Homebrew

[https://brew.sh/]

```bash
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

### Instalando as dependências

```bash
brew install cmake pkg-config gtk+3 poppler librsvg adwaita-icon-theme libzip portaudio libsndfile
```

### Construindo Xournal++

```bash
git clone http://github.com/xournalpp/xournalpp.git
cd xournalpp
mkdir build
cd build
cmake ..
make
```


## Windows

### Preparação

  1. Instale [MSYS2] em um caminho curto e sem espaços
  2. Instale [NSIS] no diretório padrão
  3. Inicie Mingw-w64 64bit. (Esteja sempre atento se está **MINGW64** e não 32bit e/ou MSYS2)

Isso abrirá um console. Todos os próximos passos serão descritos abaixo.

### Faça Update de MSYS2

Realize esta etapa múltiplas vezes. A cada vez que realizá-la, feche o terminal e abra-o novamente.
```bash
pacman -Syuu
```

### Instale GIT

```bash
pacman -S git
```

### Instale as ferramentas de construção

```bash
pacman -S mingw-w64-x86_64-toolchain \
          mingw-w64-x86_64-cmake \
          mingw-w64-x86_64-ninja \
          patch \
          mingw-w64-x86_64-cppunit \
          make \
          mingw-w64-x86_64-imagemagick
```

->Pressione enter multiplas vezes e confirme todos os valores padrões.

### Instale as dependências

```bash
pacman -S mingw-w64-x86_64-poppler \
          mingw-w64-x86_64-gtk3 \
          mingw-w64-x86_64-libsndfile \
          mingw-w64-x86_64-libzip \
          mingw-w64-x86_64-lua
```

->Pressione enter multiplas vezes e confirme todos os valores padrões.

### Tenha acesso às fontes

```bash
git clone https://github.com/xournalpp/xournalpp.git
cd xournalpp/
```

### Instale sndfile / PortAudio

```bash
windows-setup/build-portaudio.sh
```

### Construa o Xournal++

```bash
mkdir build
cd build/
cmake ..
cmake --build .
```

### Modifique a variável de ambiente do caminho (path)

Adicione ```C:\msys64\mingw64\bin``` e ```C:\msys64\usr\bin``` para o topo da sua variável de ambiente de caminho nas configurações avançadas do sistema Windows (assume-se que o diretório padrão da instação seja MSYS2).

Agora você pode executar/rodar o Xournal++ com o seguinte comando:

```bash
./src/xournalpp.exe
```

### Packaging e Setup

Criei um instalador com o seguinte comando:

```bash
windows-setup/package.sh
```

O instalador estará localizado em ```windows-setup/xournalpp-setup.exe```. Esse comando também irá criar uma versão portátil do Xournal++, localizado em ```windows-setup/dist```.


## Formato de arquivo

O formato de arquivo _.xopp é um XML compactado em .gz. Os PDFs não são incorporados ao arquivo, portanto, se o PDF for excluído, o fundo será perdido. _.xopp é basicamente o mesmo formato de arquivo que _.xoj, que é usado pelo Xournal. Portanto, o Xournal ++ é capaz de ler arquivos _.xoj e também exportar para _.xoj. Assim que as notas são exportadas para um arquivo _.xoj, todas as extensões específicas do Xournal ++, como tipos de fundo adicionais, são perdidas.

\*. xopp pode, teoricamente, ser lido pelo Xournal, desde que você não use nenhum recurso novo. O Xournal não abre arquivos que contêm novos atributos ou valores desconhecidos, então o Xournal ++ adicionará a extensão .xopp a todos os arquivos salvos para indicar a presença potencial de recursos exclusivos do Xournal ++.

Todos os novos arquivos serão salvos como _.xopp. Se um arquivo _.xoj criado pelo Xournal for aberto, a caixa de diálogo Salvar como será exibida ao salvar. Se o arquivo \ *. Xoj foi criado pelo Xournal ++, o arquivo será sobrescrito ao salvar e a extensão do arquivo não será alterada.

**No momento, estamos introduzindo um novo formato de arquivo que pode armazenar com eficiência arquivos PDF anexados e outros anexos internamente. Ainda permitiremos anexos vinculados a arquivos externos. Consulte [#937](https://github.com/xournalpp/xournalpp/issues/937) para mais detalhes.**

## Desenvolvimento

Para desenvolver novos recursos, crie um problema ou comente sobre um problema existente para que outras pessoas saibam o que você está fazendo.
Para o desenvolvimento, crie um fork e use o master como base. Crie uma solicitação Pull para cada correção.
Não crie grandes solicitações de pull, contanto que você não quebre nada, os recursos também podem ser
fundidos, mesmo que não estejam 100% concluídos.

Veja [GitHub:xournalpp](http://github.com/xournalpp/xournalpp) para o desenvolvimento atual. Você também pode entrar
nosso canal Gitter através do crachá na parte superior.

Também dê uma olhada em [Coding Conventions](https://github.com/xournalpp/xournalpp/wiki/Coding-conventions)

## Documentação

A documentação do código é gerada usando Doxygen.

Para gerar a documentação por conta própria, primeiro instale o Doxygen e o graphviz, ou seja,

```bash
sudo apt install doxygen
sudo apt install graphviz
```

no Debian ou Ubuntu. Finalmente, digite `doxygen` no diretório raiz do repositório.
A documentação pode ser encontrada em `doc / html` e` doc / latex`. Convenientemente exiba o
documentação com `python3 -m http.server 8000` e visite o URL mostrado para ver o
documentação.
