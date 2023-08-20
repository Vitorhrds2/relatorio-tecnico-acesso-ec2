# Relatório Técnico: Criação de Instância EC2 na AWS e Acesso SSH

## Introdução

Este relatório documenta o processo de criação de uma instância EC2 na AWS e o subsequente acesso a essa instância por meio de SSH. O objetivo era configurar uma máquina virtual na nuvem e demonstrar a habilidade de acesso remoto.

## Objetivo

O objetivo deste relatório é fornecer uma visão geral passo a passo da criação de uma instância EC2 e do acesso via SSH. Além disso, detalhei a criação de um repositório no GitHub para documentar o processo.

## Materiais

- Conta na AWS com permissões para criar instâncias EC2.
- Chave privada (.ppk) para autenticação SSH.
- Conta no GitHub para criar um repositório e armazenar o relatório.

## Método

### Criação da Instância EC2 na AWS

1. Acessei o Console de Gerenciamento da AWS.
2. Naveguei até o serviço EC2.
3. Inicio o assistente de criação de instâncias.
4. Escolhi uma AMI, tipo de instância, configurações e armazenamento.
5. Configurei o grupo de segurança para permitir tráfego SSH (porta 22).