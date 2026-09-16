# 06 — Exchange Online

## Implantação

O Exchange Online foi implantado como serviço de e-mail corporativo. Foram provisionadas caixas de usuário e o domínio personalizado foi associado à operação de e-mail da empresa.

## Objetos configurados

- Caixas do tipo usuário.
- Endereços alternativos associados a caixas existentes.
- Lista de distribuição para comunicação funcional.

O inventário de aliases, suas caixas correspondentes e os membros da lista permanecem fora do repositório porque não são necessários para demonstrar a atividade técnica.

## Domínio e roteamento

O domínio corporativo foi validado no Microsoft 365 e os registros necessários ao funcionamento do Exchange Online foram configurados e verificados.

![Validação dos registros associados ao Exchange Online](../assets/evidence/dns-exchange-anonimizado.jpg)

A captura preserva os tipos de configuração e os indicadores administrativos, enquanto domínio, destinos, valores e demais parâmetros operacionais permanecem censurados.

A autenticação do domínio é detalhada em [08 — Segurança de e-mail](08-seguranca-de-email.md).

## Histórico de mensagens

O histórico mantido no provedor anterior não foi migrado. A entrega corresponde à implantação e transição do serviço, e não a uma migração de conteúdo IMAP ou PST.

## Validação

O estado das caixas e objetos foi verificado administrativamente. Não foram acessadas caixas de colaboradores para produzir testes ou capturas de conteúdo.

A configuração individual do Outlook desktop e de dispositivos móveis não integrou o escopo documentado.

## Resultado

O Exchange Online passou a operar como plataforma corporativa de e-mail, integrado ao domínio e às identidades provisionadas no Microsoft 365.
