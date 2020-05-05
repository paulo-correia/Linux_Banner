# Banner
Arte ASCII para o linux, normalmente usado para identificar o servidor no arquivo /etc/motd

## No Docker (Alpine Linux)
[Docker_Banner](https://github.com/paulo-correia/Docker_Banner)

Exemplo:

```
   #      #####    #####   ###  ###  
  # #    #     #  #     #   #    #   
 #   #   #        #         #    #   
#     #   #####   #         #    #   
#######        #  #         #    #   
#     #  #     #  #     #   #    #   
#     #   #####    #####   ###  ###   
```

## Instalação
Toda a instalação é feita como **root**

### Debian
#### Instalação por código fonte

Instale o pacote wget usando o comando:

`apt-get install wget`

Clone este repositório ou baixe o banner usando o comando (tudo numa só linha):

`wget http://pkgs.fedoraproject.org/repo/pkgs/banner/banner-1.3.4.tar.gz/cfd45b431a5356c086657365b23ab0c4/banner-1.3.4.tar.gz`

Instale o pacote gcc usando o comando:

`apt-get install gcc`

Instale o pacote make usando o comando:

`apt-get install make`

Extraia o conteúdo do arquivo banner-1.3.4.tar.gz usando o comando:

`tar -xvzf banner-1.3.4.tar.gz`

Entre na pasta banner-1.3.4 com o comando:

`cd banner-1.3.4`

Compile o fonte com o comando:

`./configure`

crie o executável com o comando:

`make`

Teste use o comando `./banner oi`

### CentOS
Instale o repositório EPEL com o comando:

` yum -y install epel-release`

Instale o banner com o comando:

` yum -y install banner`
 
Teste use o comando `./banner oi`
