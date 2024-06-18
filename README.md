# Sobre Docker

Docker é uma plataforma de código aberto projetada para simplificar o processo de criação, implantação e execução de aplicativos em contêineres. 
Os contêineres são unidades de software leves e portáteis que encapsulam todos os componentes necessários para que um aplicativo seja executado,
incluindo código, bibliotecas, dependências e configurações.

Algumas das principais características e benefícios do Docker incluem:

1. <b> Portabilidade:</b> Os contêineres Docker são independentes da plataforma e podem ser executados em qualquer ambiente que suporte o Docker, seja um ambiente
   de desenvolvimento, testes ou produção.

2. <b> Isolamento: </b> Os contêineres Docker fornecem isolamento completo dos recursos do sistema, o que significa que cada contêiner é executado em seu próprio
   ambiente isolado, separado dos outros contêineres e do sistema host.

3. <b> Eficiência: </b> Os contêineres Docker são extremamente leves e consomem poucos recursos do sistema, tornando-os ideais para implantações em escala e ambientes
   de nuvem.

4. <b> Rápida implantação:</b> Os contêiner Docker podem ser iniciados em questão de segundos, o que permite uma rápida implantação e escala de aplicativos.

5. <b> Gerenciamento simplificado: </b> O Docker fornece ferramentas poderosas para criar, implantar e gerenciar contêineres, incluindo o Docker Engine para execução
   de contêineres, incluindo o Docker Engine para execução de contêiners, o Docker Compose para definição e execução de aplicativos multiconteineres e o Docker Swarm para orquestração de conteiners em cluster.

6. <b> Padronização: </b> O Docker promove a padronização dos ambientes de desenvolvimento e produção, garantindo consistência e uniformidade em todo o ciclo de vida do aplicativo.

No Geral, o Docker revolucionou a forma como os aplicativos são desenvovidos, implantados e gerenciados, proporcionando maior agilidade, eficiência e escabilidade para
equipes de desenvolvimento e operações de TI.

# Um pouco sobre a história do Docker

A história do Docker remonta ao ano de 2013, quando Solomon Hykes, fundador da dotCloud, uma plataforma de hospedagem de aplicativos, criou uma ferramenta interna chamada "dotCloud Container Manager" para facilitar a implantação e gerenciamento de aplicativos em contêineres Linux.

# Download e Instalação do Docker no Windows

<img src="https://github.com/JosiTubaroski/Airflow_Preparar_Ambiente/blob/main/img/Docker_Windows.png">

<img src="https://github.com/JosiTubaroski/Airflow_Preparar_Ambiente/blob/main/img/Instalando_Docker.png">

Aguardar o termino da instalação

### Verificar a versão do docker instalado

1) Abra o prompt de comando. Você pode fazer isso pressionando as teclas "Windows + R" para abrir a caixa de diálogo "Executar", digitando "cmd" e pressionando Enter.

2) No prompt de comando, digite o seguinte comando <b>'docker --version'</b> e pressione Enter:

<img src="https://github.com/JosiTubaroski/Docker/blob/main/img/01_Verificar_VersaoDocker.png">

### Como funciona o Docker

1) <b>Imagens Docker:</b> Uma imagem Docker é um pacote de software que contém todo o código necessário para executar um aplicativo, juntamente com suas dependências. As imagens são usadas como base para criar contêineres em tempo de execução. Elas são criadas a partir de um arquivo de configuração chamado Dockerfile, que especifica como o ambiente do contêiner deve ser configurado.

2) <b>Contêineres:</b> O Docker usa contêineres para empacotar e isolar aplicativos juntamente com todas as suas dependências (bibliotecas, binários, arquivos de configuração, etc.) em um ambiente auto-suficiente. Os contêineres são executados no topo do sistema operacional host e compartilham os recursos do sistema operacional subjacente, tornando-os leves e eficientes.

- O Contêiner é tranferido entre maquinas, entre servidores, entre ambientes com a imagem lá dentro.

### O que é Docker Hub
   
<b>Docker Hub:</b> O Docker Hub é um serviço de registro de contêineres que permite armazenar, compartilhar e distribuir imagens Docker. Ele fornece acesso a uma grande variedade de imagens Docker pré-construídas, permitindo que os desenvolvedores economizem tempo e esforço na configuração de ambientes de desenvolvimento e implantação.

## Acessando o hub docker

https://hub.docker.com/

<b>Observação:</b> No meu caso utilizei o acesso do github para acessar o docker hub

<img src="https://github.com/JosiTubaroski/Docker/blob/main/img/04_Hub_Docker.png">

# O Docker

<div> 
<p><a href="https://github.com/JosiTubaroski/PrimeiraImagem/blob/main/README.md">01. O Docker</a></p>
</div> 

# Linux

<div> 
<p><a href="https://github.com/JosiTubaroski/Linux/blob/main/README.md">02. O basico de linux para gerenciamento e configuração de ambiente.</a></p>
</div> 

# Criando imagem Docker

<div> 
<p><a href="https://github.com/JosiTubaroski/Criando-Imagens-Docker/tree/main">03. Criando imagens docker.</a></p>
</div> 








