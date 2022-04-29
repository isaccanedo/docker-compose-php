# docker-compose-php
:star2: Instalando o Docker Compose no Ubuntu 20.04 e executando uma aplicação de teste em PHP

# Como instalar e utilizar o Docker Compose no Ubuntu 20.04

O Docker simplifica o fluxo de gerenciamento de processos de aplicações em contêineres. Embora os contêineres sejam semelhantes às máquinas virtuais em certos aspectos, eles são mais leves e fáceis de usar. Isso permite que os desenvolvedores dividam um ambiente de aplicação em vários serviços isolados.

Para aplicações que dependem de vários serviços, orquestrar todos os contêineres para iniciar, comunicar e fechar juntos pode tornar-se algo rapidamente incontrolável. O Docker Compose é uma ferramenta que lhe permite executar ambientes de aplicações com vários contêineres com base nas definições contidas em um arquivo YAML. Ele usa as definições de serviço para compilar ambientes totalmente personalizados com contêineres múltiplos que podem compartilhar redes e volumes de dados.

Neste guia, vamos demonstrar como instalar o Docker Compose em um servidor Ubuntu 20.04 e como começar a usar esta ferramenta.
```
Pré-requisitos
Para seguir este artigo, você irá precisar do seguinte:
```

Acesso a uma máquina local com Ubuntu 20.04, ou um servidor de desenvolvimento como um usuário não-root com privilégios sudo. Se estiver usando um servidor remoto, é recomendável ter um firewall ativo instalado. Para configurar tudo isso, consulte nosso tutorial Initial Server Setup Guide for Ubuntu 20.04.
O Docker instalado em seu servidor ou máquina local, seguindo os Passos 1 e 2 de How To Install and Use Docker on Ubuntu 20.04.
