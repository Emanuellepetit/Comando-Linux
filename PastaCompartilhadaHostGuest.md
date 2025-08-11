# Pasta Compartilhada no Linux<Br> 

- Vai no VirtualBox -> configurações -> pastas compartilhadas -> + -> C:\virtualBox-PastaCompartilhada -> coloca um nome na pasta -> dar check em montar automaticamente e tornar permanentemente (desmarca apenas leitura) -> ok -> reinicializar o linux <Br>
- Agora vai na unidade C: do Windows -> criar pasta -> criar um arquivo dentro da pasta -> arquivo_text_host -> colocar alguma coisa e salvar<Br>

## Via Terminal Linux

- comando ls serve para listar<Br>
- ls\media<Br>
- cd é comando dentro da pasta<Br>
- cd/media<Br>
- cd sf_virtualbox-PastaCompartilhada //se usar esse comando sem adicionar o usuário vai dar permisão negada<Br>
- sudo adduser$USER vboxsf -> adiciona um novo usuário ao grupo<Br>
- sudo reboot<Br>

- Após reinicializar você executa os comandos<Br>
- cd/media<Br>
- C:\virtualBox-PastaCompartilhada<Br>
- ls -> lista o que tem dentro do arquivo<Br>

- comando clear -> serve para limpar o terminal<Br>

### Comando cat - serve para ler e exibir o que foi colocado<Br>

- cat arquivo_test_host.txt -> esse é o nome do arquivo que coloquei dentro da pasta compartilhada<Br>

### Comando echo - serve para gravar<Br>

- acho "este é um teste para verificar se funciona"> arquivo_teste_guest.txt ----- faz gravação em uma nova pasta<Br>

### Editor: VIN e Nano<Br>

- nano arquivo_teste_guest ---- dentro do arquivo para editar<Br>

### Instalar o Vin<Br>

- sudo get install vin -> sim
- reboot<Br>
- vin nome_arquivo<Br>
- : set number -> colocar linhas<Br>
- :wq -> grave e saia<Br>
- q! -> sair sem salvar<Br>
- tecla insert -> insere valores<Br>

- comando cd home - home do usuário<Br>
- cd linux (nome usuário)<Br>
- C: DO Windows é o $ do Linux (Raiz)<Br>
- vin ~/.vimrc -> enter
