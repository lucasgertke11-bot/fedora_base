# fedora_base

Arquivos base do sistema Fedora para criar uma distribuição personalizada.

## O que é isto?

Este repositório contém a **estrutura básica de diretórios** do Fedora Linux, similar ao que outras distribuições (como Arch Linux) usam como base.

## Para que serve?

Este repositório deve ser usado em conjunto com o **[fedora-livecd](https://github.com/lucasgertke11-bot/fedora-livecd)** (Lorax) para:

1. Criar uma ISO Live CD do Fedora
2. Personalizar o sistema base
3. Adicionar o Calamares como instalador
4. Compilar sua própria distribuição baseada em Fedora

## Estrutura

```
fedora_base/
├── bin/      # Comandos essenciais
├── etc/      # Arquivos de configuração
├── home/     # Diretório dos usuários
├── lib/      # Bibliotecas essenciais
├── root/     # Diretório do root
├── usr/      # Programas e bibliotecas
├── var/      # Dados variáveis
└── ...
```

## Como usar

O lorax (do repo fedora-livecd) vai usar esses arquivos base como molde para gerar o sistema durante a criação da ISO.

Consulte o repositório **[fedora-livecd](https://github.com/lucasgertke11-bot/fedora-livecd)** para ver como criar a ISO.

## Licença

GPL-3.0
