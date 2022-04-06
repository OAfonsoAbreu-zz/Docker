# Docker
Projeto para reunir conhecimento e testes do Docker


## Comandos

#### docker container run  "imagem"  "comando" : Baixa imagem, Cria container, executa container, executa o comando e finaliza container.
  
#### docker container run -it "imagem" "comando": Baixa imagem, Cria container, executa container, executa o comando e mantém container ativo e permitindo interação via terminal.
  
#### docker container start "containerID": Inicia container já criado.
  
#### docker container exec "containerID" "comando": Executa comando em container em execução.
  
#### docker container stop "containerID": Para um container em execução.

#### docker container run --name "nome" "imagem": Cria um container com um nome especifico.
  
#### docker container rm "containerID": Remove um container criado.

#### docker container run --name "nome" -p 8080:80 -d "imagem": Cria um container com um nome especifico e uma porta externa (8080) para acessar uma porta interna (80) e executar em segundo plano (-d)

#### docker container run --name "nome" -p 8080:80 -v "mapeamento_local":"mapeamento_interno" -d "imagem": Cria um container com um nome especifico e uma porta externa (8080) para acessar uma porta interna (80), mapear o diretório do host para ser interpretado quando o container tentar acessar o correspondente interno e executar em segundo plano (-d)

#### docker container inspect "containerID": Listar todas especificações do container (incluindo seus mapeamentos de rede, diretórios e etc)

#### docker container prune: Remover todos container parados.

#### docker container start -ia "containerID": Iniciar o projeto com terminal interativo (-ia).

#### docker iamge rm "containerID": Remove uma imagem.

#### docker image prune: Remover todas imagens sem uso.
  
****:
