<p align="center">
 <img src="https://user-images.githubusercontent.com/22691244/85969179-4b25e480-b99d-11ea-90cf-bf50b805a626.jpg"  width="150"/>
</p>
<h1 align="center">:brazil: +500 Comandos Linux :brazil:</h1>
<p align="center">
 <a href="https://github.com/carloskotacho/comandos-linux/blob/master/LICENSE">
  <img src="https://img.shields.io/github/license/carloskotacho/comandos-linux?color=%23fedb3d&label=licen%C3%A7a&style=flat-square" alt="Github License">
 </a>
 <a href="https://github.com/carloskotacho/comandos-linux/graphs/contributors">
  <img src="https://img.shields.io/github/contributors/carloskotacho/comandos-linux?color=%23fedb3d&label=colaboradores&style=flat-square" alt="Github Contributors">
 </a>
 <a href="https://github.com/carloskotacho/comandos-linux/stargazers">
  <img src="https://img.shields.io/github/stars/carloskotacho/comandos-linux?color=%23fedb3d&style=flat-square" alt="Github Stars">
 </a>
</p>

## ➤ Tabelas de comandos

<details>
<summary>📖 Comandos</summary>
<br />

| Comando | Descrição |
|---------|--------|
|`[qualquer_comando] -help` | *descrição do comando* |
| `man [qualquer_comando]` | *manual do comando* |
| `ls` | *listar arquivos / diretórios* |
| `ls -la` | *listar arquivos / diretórios incluindo ocultos* |
| `cd [diretorio]` | *mudar para o diretório especificado* |
| `cd` | *mudar para o diretório **/home*** |
| `pwd` | *exibe o diretório atual* |
| `mkdir [nome_diretorio]` | *criar um diretório* |
| `rm [nome_arquivo]` | *remover um arquivo* |
| `rm -r [nome_diretorio]` | *remover um diretório* |
| `rm -f [nome_arquivo]` | *forçar remoção de um arquivo* |
| `rm -rf [nome_diretorio]` | *forçar remoção de um diretório* |
| `cp -r [nome_arquivo_1] [nome_arquivo_2]` | *copiar o **arquivo 1** para o **arquivo 2*** |
| `cp -r [nome_diretorio_1] [nome_diretorio_2]` | *copiar o **diretório 1** para o **diretório 2**; cria o **diretório 2** caso não exista.* |
| `mv [nome_arquivo_1] [nome_arquivo_2]` | *renomear / mover **arquivo 1** para o **arquivo 2*** |
| `ln -s [nome_arquivo] [nome_link]` | *criar um link(atalho) simbólico para o arquivo* |
| `touch [nome_arquivo]` | *criar / atualizar o arquivo* |
| `cat > [nome_arquivo]` | *direcionar a entrada padrão para um arquivo* |
| `more [nome_arquivo]` | *exibir o conteúdo de um arquivo* |
| `head [nome_arquivo]` | *exibir as **primeiras** 10 linhas de um arquivo* |
| `tail [nome_arquivo]` | *exibir as **últimas** 10 linhas de um arquivo* |
| `tail -f [nome_arquivo]` | *exibir o conteúdo de um arquivo enquanto ele é atualizado, iniciando com as últimas 10 linhas* |
| `ps` | *exibir processos dos usuários ativos* |
| `top` | *exibir todos os processos* |
| `kill [pid]` | *matar um processo específico pelo ID* |
| `killall [nome_processo]` | *matar todos os processos com o nome especificado* |
| `bg` | *listar trabalhos parados / segundo plano* |
| `fg` | *traz o trabalho mais recente para o primeiro plano* |
| `fg [nome_processo]` | *traz o trabalho para o primeiro plano* |
| `chmod [valores_octal] [nome_arquivo]` | *mudar as permissões de um arquivo [➤ sistema octal](#-exemplos-do-modo-octal)* |
| `ssh [nome_usuário]@host` | *conectar ao host como usuário* |
| `ssh -p [numero_porta] [nome_usuario]@host` | *conectar ao host na porta especificada* |
| `ssh-copy-id [nome_usuario@host]` | *adicionar a sua chave para o host e usuário daquele host; serve para ativar logins sem senha com uso de chaves* |
| `grep [sequencia_arquivos]` | *pesquisar pela sequência nos arquivos* |
| `grep -r [sequencia_diretorios]` | *pesquisar recursivamente pela sequência no diretório* |
| `[nome_comando] | grep [sequencia]` | *pesquisar pela sequência na saída do comando* |
| `locate [nome_arquivo]` | *encontrar instâncias de um arquivo* |
| `date` | *exibir hora / data atual* |
| `cal` | *exibir calendario do mês atual* |
| `uptime` | *exibir tempo de atividade do sistema* |
| `w` | *exibir quem está online* |
| `whoami` | *exibir como quem você está logado* |
| `finger` | *exibir informações do usuário* |
| `uname -a` | *exibir informações do kernel* |
| `cat /porc/cpuinfo` | *exibir informações CPU* |
| `cat /proc/meminfo` | *exibir informações da memória* |
| `df` | *exibir uso de disco* |
| `du` | *exibir uso do espaço em um diretório* |
| `free` | *exibir uso da memória e swap* |
| `whereis [nome_programa]` | *exibir localização do aplicativo* |
| `which [nome_programa]` | *exibe que a aplicação irá rodar por omissão* |
| `tar cf [nome_pacote.tar] [nome_arquivos]` | *criar pacote TAR com os arquivos especificados* |
| `tar xf [nome_pacote.tar]` | *extrair arquivos do pacote* |
| `tar czf [nome_pacote.tar.gz] [nome_arquivos]` | *criar um pacote TAR com compressão GZip* |
| `tar xzf [nome_pacote.tar.gz]` | *extrair um pacote TAR com compressão GZip* |
| `tar cjf [nome_pacote.tar.bz2]` | *criar um pacote TAR com compressão BZip2* |
| `tar xjf [nome_pacote.tar.bz2]` | *extrair um pacote TAR com compressão BZip2* |
| `gzip [nome_arquivo]` | *compactar um arquivo e o renomeia para nome_arquivo.gz* |
| `gzip -d [nome_arquivo.gz]` | *descompactar nome_arquivo.gz para um arquivo* |
| `ping [site_ou_numip]` | *envia um pacote ICMP para o host e exibe o resultado* |
| `whois [site_ou_numip]` | *retornar informações sobre o domínio* |
| `dig [site_ou_numip]` | *retornar informações de DNS para o domínio* |
| `ListAllCommands | grep searchstr` | *instalação a partir do código fonte* |
| `dig -x [site_ou_ip]` | *exibir retorno reverso para um host* |
| `wget [endereço_arquivo]` | *faz download do arquivo espicíficado* |
| `wget -c [endereco_arquivo]` | *continuar download interrompido* |
| `./configure	` | *comando de instaladores* |
| `make` | *comando de instaladores* |
| `make install` | *comando de instaladores* |
| `dpkg -i [nome_pacote].deb` | *instalar pacotes DEB* |
| `rpm -Uvh [nome_pacote].rpm` | *instalar um pacote RPM* |

</details>

<details>
<summary>📖 Mais comandos - Avançados</summary>
<br />

| Comando | Descrição |
|---------|--------|
| `arc` | *exibe a arquitetura da máquina* |
| `uname -m` | *exibe a arquitetura da máquina* |
| `uname -r` | *versão do kernel* |
| `dmidecode -q` | *exibir componentes do hardware* |
| `hdparm -i /dev/hda` | *exibir as carecterísticas de um disco rígido* |
| `hdparm -tT /dev/das` | *executar testes de leitura em um disco rígido* |
| `cat /proc/cpuinfo` | *informações CPU* |
| `cat /proc/interrupts` | *exibir interrupçes* |
| `cat /proc/meminfo` | *verificar a utilização de memória* |
| `cat /proc/swaps:df -h` | *exibir tamanho de arquivos / diretórios ordenados por tamanho* |
| `du -sh [nome_diretorio]` | *exibe tamanho dos arquivos / diretórios ordenados por tamanho* |
| `cat /proc/version` | *versão do kernel* |
| `cat /proc/net/dev` | *exibir estatísticas e adaptadores de rede* |
| `cat /proc/mounts` | *exibir o sistema de arquivos montados* |
| `lspci -tv` | *exibir dispositivos PCI* |
| `lsusb -tv` | *exibir dispositivos USB* |
| `cal [ano]` | *exibir o calendario do ano específicado* |
| `cal [mes] [ano]` | *exibir o calendario do mês e ano específicado* |
| `date 041217002016.00` | *coloca (estado, ajustar) data e hora* |
| `clock -w` | *salvar alterações para a data na BIOS* |
| `ls -lSr \| more` | *estima o espaço usado pelo diretório 'dir1'* |
| `du -sk * \| sort -rn` | *exibir espaço usado por pacotes RPM instalados e organizados pelo tamanho (Fedora, Red Hat, etc)* |
| `rpm -q -a –qf ‘%10{SIZE}t%{NAME}n’ \| sort -k1,1n` | *exibe o espaço usado por pacotes instalados, organizado pelo tamanho (Debian, Ubuntu, etc)* |
| `dpkg-query -W -f=’${Installed-Size;10}t${Package}n’ \| sort -k1,1n` | *exibe arquivos de swap* |

</details>

<details>
<summary>📖 Mais comandos - Reinicialização do sistema ou logout</summary>
<br />

| Comando | Descrição |
|---------|--------|
| `shutdown -h now` | *desligar o sistema* |
| `shutdown -h [minutos]` | *desligar o sistema de acordo com minutos definido* |
| `init 0` | *desligar o sistema* |
| `telinit 0` | *desligar o sistema* |
| `halt` | *desligar o sistema* |
| `shutdown -r [mensagem]` | *desligar o sistema e enviar uma mensagem* |
| `shutdown -c` | *cancelar desligamento do sistema planejado* |
| `shutdown -r now` | *reiniciar o sistema* |
| `reboot` | *reiniciar o sistema* |
| `logout` | *fechar sessão* |

</details>

<details>
<summary>📖 Mais comandos - Arquivos e diretórios</summary>
<br />

| Comando | Descrição |
|---------|--------|
| `cd /home` | *vá para home* |
| `cd ..` | *voltar 1 nível* |
| `cd ../..` | *voltar 2 níveis* |
| `cd` | *vá para diretório raiz* |
| `cd ~[nome_usuário]` | *vá para diretório do usuário especificado* |
| `cd -` | *voltar para o diretório anterior* |
| `pwd` | *exibir o diretório corrente* |
| `ls` | *consultar arquivos em um diretório* |
| `ls -F` | *consultar arquivos em um diretório* |
| `ls -l` | *exibir detalhes de arquivos/pastas em um diretório* |
| `ls -a` | *exibir arquivos ocultos* |
| `ls *[0-9]*` | *exibir arquivos/pastas que contêm números* |
| `tree` | *exibir arquivos/pastas em uma árvore a partir da raíz (1)* |
| `lstree` | *exibir arquivos/pastas em uma árvore a partir da raiz (2)* |
| `mkdir [nome_diretorio]` | *criar uma pasta/diretório com o nome específicado* |
| `mkdir [nome_diretorio1] [nome_diretorio2]` | *criar duas pastas/diretórios simultaneamente* |
| `mkdir -p /tmp/dir1/dir2` | *criar uma árvore de diretórios* |
| `rm -f [nome_arquivo]` | *excluir o arquivo específicado* |
| `rmdir [nome_pasta]` | *excluir a pasta específicada* |
| `rm -rf [nome_diretorio]` | *excluir a pasta específicada e seu conteúdo forçadamente* |
| `rm -rf [nome_diretorio1] [nome_diretorio2]` | *exluir duas pastas/diretórios com o seu conteúdo forçadamente* |
| `mv [nome_diretorio1] [nome_novo_diretorio]` | *renomeiar/mover um arquivo/pasta* |
| `cp [nome_arquivo]` | *copiar um arquivo* |
| `cp [nome_arquivo1] [nome_arquivo2]` | *copiar os dois arquivos ao mesmo tempo* |
| `cp dir /*.` | *copiar todos os arquivos de um diretório dentro do diretório de trabalho atual* |
| `cp -a /tmp/dir1` | *copiar um diretório dentro do diretório de trabalho atual* |
| `cp -a [nome_diretorio]` | *copiar um diretório* |
| `cp -a [nome_diretorio1] [nome_diretorio2]` | *copiar diretório1 para diretório2* |
| `ln -s [nome_arquivo1] [nome_link]` | *criar um link simbólico para o arquivo/diretório* |
| `ln [nome_arquivo1] [nome_link]` | *criar um vínculo físico para o arquivo/diretório* |
| `touch -t 0712250000 [nome_arquivo]` | *modificar o tempo real (tempo de criação) de um arquivo ou diretório.* |
| `file [nome_arquivo]` | *saída do tipo mime de um arquivo de texto* |
| `iconv -l` | *lista de cifras conhecidas* |
| `iconv -f fromEncoding -t toEncoding inputFile > outputFile` | *criar uma nova forma de arquivo de entrada assumindo que está codificado em fromEncoding e converte para ToEncoding.* |
| `find . -maxdepth 1 -name *.jpg -print -exec convert ”{}” -resize 80×60 “thumbs/{}” \;` | *agrupar arquivos dimensionados no diretório atual e os envia aos diretórios de visualização em miniaturas (requer o conversor do ImagemagicK).* |

</details>


<details>
<summary>📖 Mais comandos - Encontrar arquivos</summary>
<br />

| Comando | Descrição |
|---------|--------|
|`find / -name [nome_arquivo]` | *buscar arquivos/diretórios da raiz do sistema* |
|`find / -user [nome_usuario]` | *encontrar arquivos/diretórios pertencentes ao usuário específicado* |
|`find /home/user1 -name \*.bin` | *procurar arquivos com extensão **.bin** no diretório específicado* |
|`find /usr/bin -type f -atime +100` | *pesquisar arquivos binários não utilizados nos **últimos 100 dias*** |
|`find /usr/bin -type f -mtime -10` | *pesquisar arquivos criados/alterados nos **últimos 10 dias*** |
|`find / -name \*.rpm -exec chmod 755 ‘{}’ \;` | *procurar arquivos com extensão **.rpm** e modificar permissões* |
|`find / -xdev -name \*.rpm` | *procurar arquivos com extensão **.rpm** ignorando a mídia removível (pen-drive, cd-rom, etc)* |
|`locate \*.ps` | *encontrar arquivos com a extensão **.ps** primeiramente executado com o comando **updatedb*** |
|`whereis halt` | *exibir localização de um arquivo binário* |
|`which halt` | *exibir caminho completo para um binário/executável* |

</details>

<details>
<summary>📖 Mais comandos - Sistema de arquivos</summary>
<br />
	
| Comando | Descrição |
|---------|--------|
|`mount /dev/hda2 /mnt/hda2` | *monta um disco chamado hda2. Se não possuir o diretório **/ mnt/hda2**, crie-o!* |
|`umount /dev/hda2` | *remove um disco chamado hda2. Em primeiro lugar, do ponto de ‘ / mnt/hda2* |
|`fuser -km /mnt/hda2` | *força a remoção quando o dispositivo está ocupado* |
|`umount -n /mnt/hda2` | *executa a remoção sem ler o arquivo/etc/MTAB* |
|`mount /dev/fd0 /mnt/floppy` | *monta um disco flexível (disquete)* |
|`mount /dev/cdrom /mnt/cdrom` | *monta um cdrom/dvdrom* |
|`mount /dev/hdc /mnt/cdrecorder` | *monta um cd gravável/dvdrom* |
|`mount /dev/hdb /mnt/cdrecorder` | *monta um cd gravável/dvdrom (um dvd)* |
|`mount -o loop file.iso /mnt/cdrom` | *monta um arquivo/imagem iso* |
|`mount -t vfat /dev/hda5 /mnt/hda5` | *monta um sistema de comandos em arquivos FAT32* |
|`mount /dev/sda1 /mnt/usbdisk` | *monta uma memória/pen-drive USB (sem especificar o tipo de sistema de arquivos)* |

</details>

<details>
<summary>📖 Mais comandos - Espaço em disco</summary>
<br />

| Comando | Descrição |
|---------|--------|
|`df -h` | *tamanho dos arquivos/diretórios ordenados por tamanho* |
|`ls -lSr \|more` | *estima o espaço usado pelo diretório **dir1*** |
|`du -sh dir1` | *tamanho dos arquivos/diretórios ordenados por tamanho* |
|`du -sk * \| sort -rn` | *exibe o espaço usado por pacotes **.rpm** instalados, organizados pelo tamanho (Fedora, Red Hat e outros)* |
|`rpm -q -a –qf ‘%10{SIZE}t%{NAME}n’ \| sort -k1,1n` | *exibe o espaço usado por pacotes instalados e organizados pelo tamanho (Debian, Ubuntu e outros)* |
|`dpkg-query -W -f=’${Installed-Size;10}t${Package}n’ \| sort -k1,1n > g` | *exibe (no Debian ou derivados) uma lista com 25 pacotes instalados que consomem mais espaço (em ordem decrescente)* |

</details>

<details>
<summary>📖 Mais comandos - Usuários e grupos</summary>
<br />
	
| Comando | Descrição |
|---------|--------|
|`groupadd nome_grupo` | *criar um grupo* |
|`groupdel nome_grupo` | *excluir um grupo* |
|`groupmod -n novo_nome_grupo viejo_nome_novo_grupo` | *renomear um grupo* |
|`useradd -c “Name Surname ” -g admin -d /home/user1 -s /bin/bash user1` | *criar um novo usuário “admin” do grupo* |
|`useradd user1` | *criar um novo usuário* |
|`userdel -r user1` | *excluir um usuário ('-r' elimina o diretório Home)* |
|`usermod -c “User FTP” -g system -d /ftp/user1 -s /bin/nologin user1` | *alterar os atributos do usuário* |
|`passwd` | *alterar a senha* |
|`passwd user1` | *alterar a senha do usuário (apenas pelo root)* |
|`chage -E 2020-12-22 user1` | *definir um limite de tempo para a senha do usuário (a chave expira a 22 de dezembro de 2020).* |
|`pwck` | *verificar a sintaxe correta ‘/ etc/passwd’ arquivo formato e a existência de usuários* |
|`grpck` | *verificar a sintaxe correta e formato do arquivo ‘/ etc/grupo’ e a existência de grupos* |
|`newgrp group_name` | *registrar um novo grupo para alterar o grupo padrão dos arquivos recém-criados* |

</details>

<details>
<summary>📖 Mais comandos - Permissões de arquivos</summary>
<br />
	
- [Workview](https://github.com/carloskotacho/comandos-linux/projects/1)

</details>

<details>
<summary>📖 Mais comandos - Atributos especiais de arquivo: (+ = Adiciona e - = Remove permissões)</summary>
<br />
	
- [Workview](https://github.com/carloskotacho/comandos-linux/projects/1)

</details>

<details>
<summary>📖 Mais comandos - Arquivos e arquivos compactados</summary>
<br />
	
- [Workview](https://github.com/carloskotacho/comandos-linux/projects/1)

</details>

<details>
<summary>📖 Mais comandos - Pacotes RPM (Red Hat, Fedora e derivados)</summary>
<br />
	
- [Workview](https://github.com/carloskotacho/comandos-linux/projects/1)
	
</details>

<details>
<summary>📖 Mais comandos - Pacotes YUM Updater (Red Hat, Fedora e derivados)</summary>
<br />
	
- [Workview](https://github.com/carloskotacho/comandos-linux/projects/1)

</details>

<details>
<summary>📖 Mais comandos - Pacotes DEB (Debian, Ubuntu e derivados)</summary>
<br />
	
- [Workview](https://github.com/carloskotacho/comandos-linux/projects/1)

</details>


<details>
<summary>📖 Mais comandos - Atualizador de pacotes APT (Debian, Ubuntu e derivados)</summary>
<br />
	
- [Workview](https://github.com/carloskotacho/comandos-linux/projects/1)

</details>

<details>
<summary>📖 Mais comandos - Exibir o conteúdo de um arquivo</summary>
<br />
	
- [Workview](https://github.com/carloskotacho/comandos-linux/projects/1)

</details>

<details>
<summary>📖 Mais comandos - Manipulação de texto</summary>
<br />
	
- [Workview](https://github.com/carloskotacho/comandos-linux/projects/1)

</details>

<details>
<summary>📖 Mais comandos - Estabelecer o formato de conversão de arquivos</summary>
<br />
	
- [Workview](https://github.com/carloskotacho/comandos-linux/projects/1)

</details>

<details>
<summary>📖 Mais comandos - Análise de sistemas de arquivos</summary>
<br />
	
- [Workview](https://github.com/carloskotacho/comandos-linux/projects/1)

</details>

<details>
<summary>📖 Mais comandos - Formatar sistemas de arquivos</summary>
<br />
	
- [Workview](https://github.com/carloskotacho/comandos-linux/projects/1)

</details>

<details>
<summary>📖 Mais comandos - Backups</summary>
<br />
	
- [Workview](https://github.com/carloskotacho/comandos-linux/projects/1)

</details>


<details>
<summary>📖 Mais comandos - CD-ROM</summary>
<br />
	
- [Workview](https://github.com/carloskotacho/comandos-linux/projects/1)

</details>

<details>
<summary>📖 Mais comandos - Redes (LAN e Wi-Fi)</summary>
<br />
	
- [Workview](https://github.com/carloskotacho/comandos-linux/projects/1)

</details>

<details>
<summary>📖 Mais comandos - Redes Microsoft Windows (SAMBA)</summary>
<br />
	
- [Workview](https://github.com/carloskotacho/comandos-linux/projects/1)

</details>

<details>
<summary>📖 Mais comandos - Firewall (iptables)</summary>
<br />
	
- [Workview](https://github.com/carloskotacho/comandos-linux/projects/1)

</details>

<details>
<summary>📖 Mais comandos - Monitoramento e depuração</summary>
<br />
	
- [Workview](https://github.com/carloskotacho/comandos-linux/projects/1)

</details>

<details>
<summary>📖 Mais comandos - Dicas e comandos úteis</summary>
<br />
	
- [Workview](https://github.com/carloskotacho/comandos-linux/projects/1)

</details>

## ➤ Exemplos do modo octal

| Valor Octal | Valor Binário rwx | Caracteres | Significado |
|---------|--------|--------|--------|
| 0 | 000 | --- | *nenhuma permissão de acesso* |
| 1 | 001 | --x | *permissão de execução* |
| 2 | 010 | -w- | *permissão de gravação* |
| 3 | 011 | -wx | *permissão de gravação e execução* |
| 4 | 100 | r-- | *permissão de leitura* |
| 5 | 101 | r-x | *permissão de leitura e execução* |
| 6 | 110 | rw- | *permissão de leitura e gravação* |
| 7 | 111 | rwx | *permissão de leitura, gravação e execução* |

## ➤ Referências

- [chmod | Guia Linux](https://guialinux.uniriotec.br/chmod/)
- [Guia comandos do Linux](https://www.linuxpro.com.br/dl/guia_500_comandos_Linux.pdf)
- [Explain shell](https://explainshell.com/explain?cmd=cp+-r+%2Fdir1+%2Fdir2#)

## ➤ License
	
Licença [MIT](https://github.com/carloskotacho/comandos-linux/blob/master/LICENSE).
