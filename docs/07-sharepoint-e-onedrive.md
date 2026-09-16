# 07 — SharePoint Online e OneDrive

## SharePoint Online

Foi implantado um site de equipe privado para centralizar a colaboração documental da empresa.

![Site de equipe no SharePoint Online](../assets/evidence/sharepoint-site-equipe-anonimizado.jpg)

A captura demonstra o ambiente implantado sem expor URL, armazenamento, conta administrativa ou demais identificadores operacionais.

## Organização documental

O conteúdo foi estruturado em bibliotecas funcionais e o acesso foi associado a grupos baseados nas funções de trabalho.

```mermaid
flowchart TB
    SITE["Site Corporativo Privado"] --> A["Biblioteca Funcional A"]
    SITE --> B["Biblioteca Funcional B"]
    SITE --> C["Biblioteca Funcional C"]
    GA["Grupo de Segurança A"] --> A
    GB["Grupo de Segurança B"] --> B
    GC["Grupo de Segurança C"] --> C
```

O diagrama representa o modelo adotado sem reproduzir nomes ou relações internas do ambiente.

## Permissões por grupos

O modelo principal de acesso foi baseado em grupos, facilitando a administração e evitando concessões individuais como padrão.

![Administração por grupos](../assets/evidence/grupos-seguranca-anonimizado.jpg)

Permissões exclusivas ou exceções específicas permanecem fora do portfólio.

## Versionamento

As bibliotecas foram configuradas com versionamento de documentos. Uma biblioteca foi utilizada como evidência visual da configuração padronizada aplicada ao ambiente.

![Versionamento no SharePoint Online](../assets/evidence/sharepoint-versionamento-anonimizado.jpg)

Parâmetros numéricos detalhados foram omitidos por não serem necessários para demonstrar a implantação.

## Compartilhamento

O site permaneceu privado. A capacidade de colaboração externa foi analisada administrativamente, mas não havia convidados no estado observado durante a documentação do projeto.

## OneDrive

O OneDrive esteve presente nas configurações organizacionais do Microsoft 365, porém não houve uma implantação individual ou frente específica de OneDrive neste projeto. Por isso, ele não é apresentado como entrega independente.
