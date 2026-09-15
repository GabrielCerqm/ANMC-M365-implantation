# 14 — Evidências públicas

## Estratégia adotada

O repositório combina documentação textual, diagramas conceituais e uma seleção de capturas tratadas do projeto executado para a **Matheus Cavalcanti Advocacia e Negócios (ANMC)**.

A empresa autorizou a divulgação do projeto, incluindo identificação institucional e uso da marca, para fins de portfólio profissional. Ainda assim, as imagens publicadas continuam protegendo dados pessoais, credenciais, identificadores técnicos sensíveis, URLs administrativas, valores DNS e demais informações operacionais que não sejam necessárias para demonstrar o trabalho realizado.

## Evidências analisadas

Foram utilizadas como base de documentação e validação:

- telas de domínio e integridade DNS;
- inventário de licenças e caixas;
- configuração de lista de distribuição;
- lista de grupos de segurança;
- sites e bibliotecas do SharePoint;
- páginas de permissões;
- configuração de versionamento;
- configuração de compartilhamento;
- habilitação dos Padrões de Segurança;
- fluxo de MFA administrativo;
- estado de DKIM;
- resolução de DMARC;
- avaliação de postura;
- painel do provedor DNS.

Os arquivos brutos não integram o portfólio quando apresentam dados pessoais, conteúdo corporativo, credenciais, IDs, URLs administrativas ou outros elementos operacionais sensíveis.

## Galeria tratada

### Licenciamento do serviço

![Licenciamento](../assets/evidence/licenciamento-business-basic-anonimizado.jpg)

Demonstra a administração do licenciamento Microsoft 365. Quantidades, usuários, endereços e dados desnecessários à apresentação permanecem omitidos.

### Site de equipe

![Site de equipe](../assets/evidence/sharepoint-site-equipe-anonimizado.jpg)

Demonstra a implantação do site de equipe no SharePoint Online. Informações administrativas sensíveis continuam protegidas.

### Administração por grupos

![Grupos de segurança](../assets/evidence/grupos-seguranca-anonimizado.jpg)

Demonstra o uso de grupos de segurança para administração de acesso. Relações detalhadas de usuários e permissões não são publicadas.

### Versionamento documental

![Versionamento](../assets/evidence/sharepoint-versionamento-anonimizado.jpg)

Demonstra a configuração de versionamento aplicada às bibliotecas documentais.

### Padrões de Segurança

![Padrões de Segurança](../assets/evidence/entra-padroes-seguranca-anonimizado.jpg)

Demonstra o controle de segurança habilitado durante o projeto. Informações da conta autenticada e identificadores administrativos permanecem protegidos.

### Fluxo de MFA

![MFA](../assets/evidence/mfa-authenticator-anonimizado.jpg)

Demonstra a validação de autenticação multifator com Microsoft Authenticator realizada em contexto administrativo autorizado.

### Validação de registros DNS

![DNS](../assets/evidence/dns-exchange-anonimizado.jpg)

Demonstra as verificações relacionadas ao domínio e ao Exchange Online. Valores técnicos que possam ser reutilizados indevidamente não são expostos sem necessidade.

### DKIM

![DKIM](../assets/evidence/dkim-anonimizado.jpg)

Demonstra a habilitação e validação do DKIM para o domínio corporativo.

### Consulta DMARC

![Consulta DMARC](../assets/evidence/dmarc-consulta-anonimizado.jpg)

Demonstra o uso de consulta DNS para validar a existência e resposta do registro DMARC.

## Representações públicas complementares

| Evidência técnica | Representação no portfólio |
|---|---|
| Arquitetura do ambiente | Diagrama Mermaid conceitual |
| Organização documental | Diagrama e descrição funcional |
| Fluxo de e-mail | Diagrama conceitual |
| Segurança de identidade | Capturas tratadas e descrição dos controles confirmados |
| DNS | Capturas tratadas e descrição dos mecanismos implantados |
| Testes | Matriz de validação com limitações |
| Permissões | Explicação de administração por grupos |

## Informações deliberadamente excluídas

Mesmo com autorização de divulgação, permanecem fora das evidências públicas:

- credenciais, códigos de autenticação, tokens ou segredos;
- conteúdo de caixas postais;
- documentos, arquivos e conteúdo jurídico corporativo;
- dados pessoais de colaboradores ou terceiros;
- inventários completos de aliases, caixas e usuários;
- IDs de tenant, objetos ou aplicações quando desnecessários;
- URLs administrativas sensíveis;
- matriz detalhada de membros e permissões;
- informações de segurança cuja exposição possa ampliar risco operacional.

## Regra para novas imagens

Novas evidências podem preservar o nome e a identidade visual da ANMC dentro do escopo autorizado. Antes da inclusão, cada imagem deve ser revisada para garantir que a identificação institucional autorizada não venha acompanhada de informações pessoais, credenciais ou parâmetros operacionais sensíveis.
