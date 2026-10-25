# Desafio-DIO-Medusa
Praticando o que aprendi no bootcamp da DIO com o santander de cyberseguranca.
irei fazer esse desafio usando o linux Ubuntu(SO da minha maquina pessoal) para realizar esse desafio invadindo um local controlado usando VM da Oracle, para a maquina vitima estarei usando o metasplaitable.
Foi criado um wordlist onde contem os possiveis usuarios e senhas, separei em dois arquivos para facilitar o meu aprendizado.
Efetuei a invasao por brute force com sucesso.
passo a passo:
Primeiro eu fiz uma varredura de rede utilizando a ferramenta nmap usando o comando : nmap -v [ip da minha rede]
em seguida localizei o host que seria a minha vitima nessa simulacao
usei o comando especifico para o ip da vitima utilizando  a ferramenta nmap com o comando : nmap -A [IP do pc da vitima]
Com esse comando eu consegui ver a vulnerabilidade no SSH e em outros servicos, mas foquei no ssh ja que tenho mais familiaridade
usei a medusa para fazer o brute force
tive sucesso na medusa mas o ssh do pc da vitima era legado e eu tive que usar um comando para que minha maquina rodasse o acesso com essa incompatibilidade de versao do ssh
efetoei login com sucesso na maquina da vitima.
