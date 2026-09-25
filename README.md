# IA_Excel
Curso de IA com Excel
README — Organizador de Declaração de Imposto de Renda

1. Objetivo da planilha

Esta planilha foi criada para organizar as principais informações e documentos utilizados na preparação da Declaração de Imposto de Renda da Pessoa Física.

O arquivo funciona como uma base de apoio para centralizar:

dados cadastrais do titular;

informações bancárias e respectivos informes de rendimentos;

valores de receitas recebidas ao longo do período;

referência aos documentos que deverão ser utilizados na declaração.

Importante: a planilha é um organizador de informações. Ela não substitui o programa oficial da declaração, não calcula o imposto devido e não realiza a transmissão da declaração.

2. Estrutura do arquivo

A planilha possui três abas principais:

Aba

Finalidade

TITULAR

Cadastro das informações pessoais do contribuinte.

INFORMES

Registro dos bancos, valores informados e arquivos de comprovantes.

NOTAS

Registro das receitas e entradas financeiras ao longo do período.

3. Aba “TITULAR”

Esta aba concentra os dados cadastrais da pessoa física que serão utilizados como referência na preparação da declaração.

Informações cadastradas

Campo

Finalidade

Nome

Identificação do titular da declaração.

CPF

Cadastro de Pessoa Física do titular.

Nascimento

Data de nascimento.

Título de eleitor

Número do título de eleitor.

Cônjuge

Nome do cônjuge, quando aplicável.

Rua

Endereço completo.

Rua abreviada

Versão abreviada do endereço, quando necessária.

CEP

Código de Endereçamento Postal.

Telefone

Telefone de contato.

Celular

Número de celular.

E-mail

E-mail de contato.

Houve alterações da entrega anterior

Indica se houve mudança cadastral em relação à declaração anterior.

Dependente cônjuge

Indica se o cônjuge será informado como dependente.

Residente do exterior

Indica a condição de residência fiscal informada no cadastro.

Como utilizar

Substitua os dados de exemplo pelas informações corretas do titular.

Revise especialmente CPF, data de nascimento, endereço e informações de contato.

Nos campos de decisão, mantenha um padrão de preenchimento, preferencialmente SIM ou NÃO.

Antes de utilizar os dados na declaração, confira se houve alguma alteração em relação ao exercício anterior.

4. Aba “INFORMES”

Esta aba organiza os informes de rendimentos bancários e os valores associados a cada instituição financeira.

A estrutura atual possui espaço para três bancos.

Informações registradas para cada banco

Campo

Finalidade

Banco

Nome e/ou código da instituição financeira.

Valor atual

Valor informado para aquela instituição.

Anexo

Nome do arquivo do informe ou comprovante correspondente.

Total dos valores

O total apresentado na planilha é calculado automaticamente pela fórmula existente na célula C6:

=SUM(D10,D15,D20)

Ou seja, o total considera os valores cadastrados para:

1º banco — D10;

2º banco — D15;

3º banco — D20.

Atenção ao adicionar novos bancos

A fórmula atual foi construída especificamente para os três blocos existentes. Portanto, se um quarto banco ou outros bancos forem adicionados, eles não serão incluídos automaticamente no total.

Nesse caso, a fórmula deverá ser atualizada para considerar também as novas células de valor.

Organização dos anexos

O campo ANEXO deve ser utilizado como referência para identificar rapidamente o informe correspondente.

Recomenda-se manter os documentos em uma pasta organizada junto ao projeto, utilizando nomes padronizados, por exemplo:

Informe - Nome do Banco - Ano.pdf

Isso facilita a conferência entre a planilha e os documentos utilizados na declaração.

5. Aba “NOTAS”

Esta aba é destinada ao registro das entradas financeiras e receitas recebidas ao longo do período.

A estrutura utiliza três colunas principais:

Coluna

Conteúdo

DATA

Data de recebimento da receita.

CATEGORIA

Tipo da entrada financeira.

VALOR

Valor recebido.

Exemplos de categorias

Dependendo da finalidade do controle, podem ser utilizadas categorias como:

HOLERITE;

PRÓ-LABORE;

ALUGUEL;

SERVIÇO;

RENDIMENTO;

OUTROS.

O ideal é manter os nomes das categorias padronizados ao longo do arquivo para facilitar consultas e conferências posteriores.

Forma recomendada de preenchimento

Registre cada entrada em uma linha separada:

DATA

CATEGORIA

VALOR

05/01/AAAA

HOLERITE

R$ 0,00

05/02/AAAA

HOLERITE

R$ 0,00

15/02/AAAA

OUTROS

R$ 0,00

A aba atualmente funciona como um registro de entradas e não possui um totalizador automático das receitas.

6. Fluxo recomendado de utilização

Para utilizar a planilha de forma organizada:

Atualize os dados do titular na aba TITULAR.

Reúna os informes bancários recebidos das instituições financeiras.

Preencha cada banco na aba INFORMES e registre o nome do respectivo arquivo.

Confira se o valor total apresentado contempla todas as instituições utilizadas.

Registre na aba NOTAS as receitas e demais entradas financeiras relevantes.

Compare os registros da planilha com os documentos originais antes de utilizar as informações na declaração.

Mantenha todos os comprovantes e informes arquivados junto ao material da declaração daquele exercício.

7. Pontos de atenção

Dados pessoais

A planilha contém informações pessoais e financeiras. Portanto:

evite compartilhar o arquivo sem necessidade;

armazene-o em local seguro;

não publique versões preenchidas em locais públicos;

antes de utilizar a planilha como modelo para outra pessoa, remova todos os dados pessoais existentes.

Fórmulas

A única fórmula de consolidação identificada na estrutura atual está na aba INFORMES e soma os três bancos cadastrados.

Evite sobrescrever essa célula acidentalmente.

Novas instituições financeiras

Caso novos bancos sejam adicionados, será necessário:

criar um novo bloco para a instituição;

informar banco, valor e anexo;

atualizar a fórmula do total para incluir o novo valor.

Novas receitas

A aba NOTAS pode ser ampliada com novas linhas conforme necessário. Ao fazer isso, mantenha:

datas no mesmo formato;

categorias padronizadas;

valores em formato monetário.

8. Sugestão de organização dos documentos

Uma estrutura simples de pastas pode facilitar bastante a utilização da planilha:

Imposto de Renda - Ano
│
├── Planilha de Controle
│
├── Informes Bancários
│   ├── Banco 01
│   ├── Banco 02
│   └── Banco 03
│
├── Holerites
│
├── Comprovantes
│
└── Declaração Entregue

Essa organização ajuda a manter rastreabilidade entre os registros da planilha e os documentos utilizados na declaração.

9. Resumo rápido

Preencher

dados pessoais do titular;

informações dos bancos;

valores dos informes;

nome dos documentos anexos;

receitas recebidas ao longo do período.

Conferir

dados cadastrais;

total dos bancos;

existência dos comprovantes;

receitas registradas;

inclusão de todas as instituições financeiras utilizadas.

Não esquecer

O arquivo é uma ferramenta de organização e conferência. Os valores finais devem sempre ser confrontados com os informes e documentos oficiais antes do preenchimento da Declaração de Imposto de Renda.

README elaborado com base na estrutura atual do arquivo “Criando Um Organizador de Declaração de Imposto de Renda.xlsx”.
