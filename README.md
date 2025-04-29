# VirtualMachineAzureDIO
Documentação de criação de uma máquina virtual no Microsoft Azure para desafio DIO.

# Projeto de Criação de Máquina Virtual no Azure

## Introdução
Este projeto documenta o processo de criação de uma máquina virtual na plataforma Microsoft Azure como parte do desafio do bootcamp XP DIO.

## Objetivo
Aplicar os conhecimentos adquiridos no curso, praticando a criação e configuração de uma VM, além de documentar toda a experiência.

## Passo a Passo
- Criação da conta Azure
- Acesso ao Portal Azure
- Criação da Máquina Virtual
  - Sistema Operacional: Windows (Windows Server 2022 Datacenter Azure Edition)
  - Tamanho: Standard B1s (1 vcpu, 1 GiB de memória)
  - Localização: West US
  - Endereço IP público: 52.234.126.31
  - Rede virtual/sub-rede: RedeTeste/default
  - Nome DNS: Não configurado

## Dicas
- Use instâncias gratuitas para evitar custos
- Configure regras de firewall corretamente
- Faça snapshots regulares para backup

## Problemas e Soluções
- Problema: Porta SSH bloqueada.
- Solução: Configurar NSG (Network Security Group) para liberar porta 22.

## Conclusão
Experiência enriquecedora, consolidando o aprendizado sobre infraestrutura em nuvem.

