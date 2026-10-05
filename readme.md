# Exercícios e Configurações — Cisco Packet Tracer 🚀

Repositório com exercícios práticos, topologias e configurações desenvolvidos no **Cisco Packet Tracer**, organizados para facilitar o estudo de redes de computadores.

## Conteúdo

- Fundamentos de redes
- Endereçamento IPv4 e IPv6
- Sub-redes e VLSM
- Configuração de switches e roteadores
- VLANs e trunking
- Roteamento estático e dinâmico
- DHCP, DNS e NAT
- ACLs e segurança básica
- Testes de conectividade e diagnóstico

## Estrutura do repositório

```text
.
├── README.md
├── exercicios/
│   ├── 01-fundamentos/
│   ├── 02-enderecamento-ip/
│   ├── 03-vlans/
│   └── 04-roteamento/
├── configuracoes/
│   ├── roteadores/
│   └── switches/
└── imagens/


-------------------------------------------------
*Cada exercício pode incluir:*

- Arquivo .pkt da topologia
- Enunciado e objetivos
- Configurações dos dispositivos
- Capturas de tela ou diagramas
- Testes realizados e resultados esperados

_______________________________________________

Como usar

Instale o Cisco Packet Tracer.
Clone ou baixe este repositório.
Abra o arquivo .pkt do exercício desejado.
Consulte o enunciado e tente resolver a atividade.
Compare sua solução com os arquivos de configuração disponíveis.

Comandos úteis
Desativar a tentativa de resolução DNS quando um comando é digitado incorretamente:

```bash
Router> enable
Router# configure terminal
Router(config)# no ip domain-lookup
Router(config)# end
```

Salvar a configuração:

```bash
Router# copy running-config startup-config
```

Verificar interfaces e conectividade:

```bash
Router# show ip interface brief
Router# show running-config
Router# ping 192.168.1.1
```
