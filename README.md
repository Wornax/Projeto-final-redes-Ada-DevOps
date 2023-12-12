# Projeto de Comunicação entre Redes

## Descrição

Este projeto tem como objetivo demonstrar a configuração e comunicação entre duas redes distintas, A e B, utilizando equipamentos de rede e estabelecendo a comunicação entre elas por meio do protocolo ICMP.

## Configuração das Redes

### Rede A (Alunos)

- **CIDR:** 192.168.0.0/24
- **Gateway:** 192.168.0.254
- **DHCP e DNS:** 192.168.0.253
- **Máquinas na Rede A:**
    - 4 desktops utilizando DHCP
    - 2 servidores com IPs fixos

### Rede B (Alunos)

- **CIDR:** 172.15.0.0/24
- **Gateway:** 172.15.0.254
- **DHCP e DNS:** 172.15.0.253
- **Servidor Web:** 172.15.0.252
- **Máquinas na Rede B:**
    - 5 desktops utilizando DHCP
    - 1 servidor web com IP fixo

## Equipamentos Utilizados

- 1 Router Cisco 1841
- 3 Switches Cisco 2960 24TT

## Objetivo

O objetivo final deste projeto é permitir que um dos desktops na Rede A possa acessar e carregar a página do servidor web localizado na Rede B através de um navegador, validando assim o correto funcionamento do roteamento entre as redes, configurações de DNS e a camada de aplicação.

## Configurações e Execução

1. **Configuração dos Equipamentos:** 
   - Configurar o Router 1841 para roteamento entre as redes A e B.
   - Configurar os Switches 2960 para permitir a comunicação entre os dispositivos.

2. **Configuração das Redes:**
   - Atribuir corretamente os endereços IP, gateways, DHCP e DNS conforme especificado para cada rede.

3. **Validação da Comunicação:**
   - Testar a conectividade entre os desktops e servidores dentro da mesma rede.
   - Garantir que um desktop da Rede A seja capaz de acessar o servidor web da Rede B por meio do navegador.

## Observações

Certifique-se de ajustar as configurações de acordo com a infraestrutura e requisitos específicos do ambiente antes de executar o projeto.

Para informações mais detalhadas sobre configurações específicas, consulte a documentação dos equipamentos Cisco e as configurações de rede sugeridas para a realização deste projeto.
