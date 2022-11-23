# Internet protocol - IP

### Representação numérica criada por identificar uma interface específica em uma rede

###### (Estudar protocolos TCP, UDP e IP)

<br/>

### RFC 791 - 1981 - ipv4
#### Ipv4 é composto por números decimais de 32 bits
##### o número de 32 bits suporta até 2^32 possibilidades, e por isso foi criada uma nova versão uma vez que o número de dispositivos pode ultrapassar essa quantidade. (Pouco mais de 4bi)

### IPv6 
#### Possui 128 bits hexadecimais ou seja 2^128 Muito mais que os antigos 32 bits
##### Tem uma lenta adoção, vide site do goole que acompanha isso:
[site do google que acompanha isso](https://www.google.com/intl/pt-BR/ipv6/statistics.html)

### IP não é a única tecnologia de protocolo que compõe a internet.

#### No protocolo TCP/IP existem 5 camadas principais:
## Aplicação
- telnet
- FTP
- DHCP
- TFTP
- HTTP
- SMTP
- DNS
- SNMP

## Trasnsporte
- TCP
- UDP

## Internet 
- ICPM
- ARP
- RARP
- IP

## Interface


# Máscara de subrede - Subnet Mask

### É um número binário que é usado para identificar a rede e o host de um endereço IP
### O número de bits 1 na máscara de subrede representa o número de bits na rede e o número de bits 0 representa o número de bits no host.



### Exemplo:

| Endereço IP | Máscara de subrede | Rede | Host |
| ----------- | ------------------ | ---- | ---- |
|
| 10101010.11111111.00000000.00001111 | 11111111.11111111.11111111.00000000 | 10101010.11111111.00000000.00000000 | 00000000.00000000.00000000.00001111 |
| 10101010.11111111.00000000.00001111 | 11111111.11111111.00000000.00000000 | 10101010.11111111.00000000.00000000 | 00000000.00000000.00001111.00000000 |
| 10101010.11111111.00000000.00001111 | 11111111.11111111.11111111.11111111 | 10101010.11111111.00000000.00000000 | 00000000.00000000.00000000.00000000 |
| 10101010.11111111.00000000.00001111 | 11111111.11111111.11111111.11110000 | 10101010.11111111.00000000.00000000 | 00000000.00000000.00000000.00001111 |
| 10101010.11111111.00000000.00001111 | 11111111.11111111.11111111.11111100 | 10101010.11111111.00000000.00000000 | 00000000.00000000.00000000.00001100 |
| 10101010.11111111.00000000.00001111 | 11111111.11111111.11111111.11111110 | 10101010.11111111.00000000.00000000 | 00000000.00000000.00000000.00001110 |
| 10101010.11111111.00000000.00001111 | 11111111.11111111.11111111.11111111 | 10101010.11111111.00000000.00000000 | 00000000.00000000.00000000.00001111 |

<iframe width="560" height="315" src="https://www.youtube.com/embed/O8DmpmBMUSw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>














