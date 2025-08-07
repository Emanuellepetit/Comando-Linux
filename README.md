# COMANDOS PARA SER REALIZADOS NO TERMINAL DO LINUX<Br> 🍓

> [!TIP]
> **CRTL + ALT + T - atalho para abrir o terminal<Br>**

**Comando sudo**- concede privilégio de administrador<Br>
**Comando apt** - gerenciador de pacotes<Br>

- sudo apt update - baixa pacotes + recentes<Br>
- sudo apt upgrade - executar<Br>
- sudo reboot - reiniciar<Br>
- sudo  ./VBowLinuxAdditions.run - executa a aplicação disponível no diretório que acessou e instala os recursos<Br>

- linux - headers - $(uname  -r) - arquivos nesseários para compilar módulos compativeis com kernel atual<Br>
- install build - essential dkms linux - headers - $(aname  -r)<Br>
- Instala: build-essential: ferramenta para compilar código-fonte<Br>
- dkms - recompilador de aplicações para compalibilidade com kernel do convidado (guest)<Br>

# cd /media/$USER/VBox_GAs_7.0.6
- cd - caminha até o diretório onde está o aplicativo para instalar recursos adicionais de convidado<Br>
- $USER - é uma variável de ambiente que referencia o valor do usuário que está logado (nome de usuário)<Br>

# lsmod | grep vbox
- lsmod - listar módulos carregados no kernel<Br>
- grep - funciona como um filtro para pesquisar apenas linha que contenham o texto que deseja pesquisa (nesse caso, vbox)<Br>
- vbox - prefixo que inicia normalmente os nomes dos módulos do virtualbox<Br>
