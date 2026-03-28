# Assistente de Parametrização
Ferramenta web interna de consulta rápida de regras por empresa e tipo de documento, voltada para equipes que analisam documentos de colaboradores — como atestados médicos, cartões de vacina e declarações.

Contexto
Equipes de análise documental precisam aplicar regras diferentes dependendo da empresa cliente e do tipo de documento recebido. Esse conhecimento costuma ficar disperso em e-mails, planilhas e anotações internas.
O Assistente de Parametrização centraliza essas regras em uma interface de consulta rápida, permitindo que o analista visualize em segundos o que pode ser aceito, o que deve ser recusado e como tratar cada situação.

Funcionalidades

Busca por empresa com autocomplete em tempo real
Seleção de tipo de documento
Exibição de regras categorizadas em cards visuais
Cópia do resultado em texto estruturado
Regras globais separadas das regras por empresa
Interface responsiva para uso em desktop


Categorias de parametrização
CategoriaDescrição✅ PodeO que é aceito sem ressalvas❌ Não podeO que deve ser recusado⚠️ AtençãoPontos que exigem cuidado na análise🔍 Depende de análiseSituações que exigem julgamento do analista↗ EncaminhamentoPara onde o caso deve ser direcionado📋 ObservaçõesNotas e informações adicionais da empresa

Empresas configuradas

FGH
IMIP
SOLL
Austa
Supermercados Pernambucano
Unimed
Santa Casa


Tipos de documento suportados

Atestado médico
Cartão de vacina
Cartão de vacina da Covid
Declaração de comparecimento
Receituário médico
Afastamento INSS


Regras globais
Alguns tipos de documento seguem parametrização única, independente da empresa selecionada:

Cartão de vacina — regras gerais de validação documental
Cartão de vacina da Covid — mesmas regras do cartão de vacina, com adição da política de recusa mediante termo de responsabilidade assinado e justificativa obrigatória


Stack

HTML5
CSS3
JavaScript (vanilla)
Sem framework, sem dependência externa, sem backend

Toda a parametrização é mantida diretamente no arquivo, em objetos JavaScript estruturados.

Como usar

Abrir o arquivo assistente_parametrizacao.html no navegador
Buscar ou selecionar a empresa
Selecionar o tipo de documento
Clicar em Consultar
Visualizar os cards com as regras categorizadas
Usar o botão Copiar resultado para exportar em texto, se necessário


Observação
Esta ferramenta é um apoio à análise documental. Ela organiza e exibe as regras de parametrização, mas não substitui o julgamento humano. A decisão final é sempre responsabilidade do analista.

Expansão
Para adicionar uma nova empresa ou tipo de documento, basta incluir a entrada correspondente
