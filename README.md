# Funcionalidades da Automação em Selenium para PowerBI

Este repositório contém uma automação em Selenium para simplificar duas tarefas comuns relacionadas ao Microsoft PowerBI:

## Atualização de Indicadores

A funcionalidade de atualização de indicadores permite automatizar o processo de atualização dos indicadores em um workspace do Microsoft PowerBI. Isso é útil para manter as informações sempre atualizadas com o mínimo esforço manual.

## Download de Relatórios

A funcionalidade de download de relatórios permite automatizar o processo de baixar relatórios gerados no Microsoft PowerBI. Isso pode economizar tempo e garantir que os relatórios sejam arquivados de forma organizada.

## Pré-requisitos

Para utilizar estas funcionalidades, você precisa ter o seguinte configurado em seu ambiente:

- Python instalado em seu sistema.
- Biblioteca Selenium instalada.
- Chrome WebDriver instalado (ou outro WebDriver compatível com seu navegador).
- Contas válidas para login no Microsoft PowerBI.

Lembre-se de personalizar as configurações, como URLs e credenciais, de acordo com suas necessidades específicas.

## Notas

- Esta automação é fornecida como um exemplo e pode ser personalizada para atender a requisitos específicos.
- Esteja ciente das políticas de uso dos serviços que você está automatizando e garanta que as informações confidenciais sejam tratadas com segurança.

Se você encontrar problemas ou tiver sugestões de melhorias, sinta-se à vontade para abrir problemas ou solicitações de pull. Essas funcionalidades foram criadas para simplificar as tarefas relacionadas ao PowerBI e economizar tempo.
## Funções

Este repositório oferece duas funções principais:

1. `Atualizarindicador(login, senha, workspace)`: Esta função é responsável pela atualização de indicadores no Microsoft PowerBI. Para utilizá-la, você precisa fornecer suas credenciais de login e o link do workspace a ser atualizado.

2. `BaixarPowerBi(login, senha, links)`: Esta função automatiza o processo de download de relatórios do PowerBI. Para utilizá-la, você deve fornecer suas credenciais de login no Microsoft PowerBI e uma lista de URLs que apontam para os relatórios específicos que você deseja baixar.

Certifique-se de configurar corretamente as credenciais e links relevantes de acordo com a tarefa desejada antes de executar as funções. Essas funções foram desenvolvidas para simplificar as tarefas de atualização de indicadores e download de relatórios no PowerBI.
