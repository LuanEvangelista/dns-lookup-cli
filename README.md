# DNS Lookup CLI

Uma ferramenta de linha de comando escrita em Go para realizar consultas DNS e obter informações sobre servidores e IPs.

## Descrição

O DNS Lookup CLI é uma aplicação simples que permite:
- Buscar IPs associados a um domínio
- Buscar servidores de nomes (NS) de um domínio

## Instalação

### Pré-requisitos
- Go 1.16 ou superior

### Compilação
```bash
git clone https://github.com/LuanEvangelista/dns-lookup-cli.git
cd dns-lookup-cli
go build -o dns-lookup
```

## Uso

### Buscar IPs de um domínio
```bash
./dns-lookup ip --host google.com
```

### Buscar servidores de nomes de um domínio
```bash
./dns-lookup servidor --host google.com
```

### Opções
- `--host`: Especifica o domínio a ser consultado (padrão: google.com)

## Exemplos

```bash
# Buscar IPs do Google
./dns-lookup ip --host google.com

# Buscar servidores de nomes do GitHub
./dns-lookup servidor --host github.com
```

## Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

## Licença
Este projeto está licenciado sob a licença MIT - veja o arquivo LICENSE para detalhes. 