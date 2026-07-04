📊 Controle de Pagamento de RPA (Recibo de Pagamento a Autônomo)

Planilha Excel para automatizar o controle mensal e anual de pagamentos a
prestadores de serviço autônomos, com cálculo automático de INSS (retido do
autônomo e cota patronal) e um dashboard consolidado.

✨ Funcionalidades


Dashboard anual automático — consolida os 12 meses do ano em uma única
visão, com total de serviços, INSS, valor líquido pago, número de
prestadores e gráfico de evolução mensal.
Parâmetros centralizados — alíquotas de INSS e dados da empresa ficam
em uma única aba (Parâmetros), usados por meio de named ranges
(ALIQ_AUTONOMO, ALIQ_EMPRESA). Alterar a alíquota em um único lugar
atualiza todos os cálculos automaticamente.
12 abas mensais (RPA-Jan2026 a RPA-Dez2026), cada uma com:

Cadastro de prestadores (data, nome, CPF, valor do serviço)
Cálculo automático de INSS descontado, INSS da empresa e valor líquido
Totalizador do período



Formatação profissional: cores padronizadas, cabeçalhos destacados,
moeda em R$, linhas zebradas e formatação condicional destacando meses
acima da média.
Zero fórmulas quebradas — modelo validado sem erros (#REF!,
#DIV/0!, #VALUE!, etc).


🗂 Estrutura do arquivo

AbaDescriçãoDashboardResumo anual + gráficoParâmetrosAlíquotas de INSS e dados da empresa (únicas células editáveis)RPA-Jan2026 ... RPA-Dez2026Lançamentos e cálculo mês a mês

🧮 Lógica de cálculo

INSS Descontado do Autônomo = Valor do Serviço × Alíquota Autônomo (11%)
INSS da Empresa              = Valor do Serviço × Alíquota Empresa (20%)
Valor Líquido a Pagar        = Valor do Serviço − INSS Descontado

As alíquotas seguem o percentual padrão de contribuição previdenciária de
autônomos (Lei 8.212/91) e podem ser ajustadas na aba Parâmetros conforme
legislação vigente.

🚀 Como usar


Baixe o arquivo Controle-RPA-Autonomos.xlsx.
Ajuste, se necessário, as alíquotas e os dados da empresa na aba
Parâmetros.
Preencha os lançamentos de cada mês na respectiva aba RPA-MêsAno.
O Dashboard atualiza automaticamente com o consolidado do ano.


🛠 Tecnologias / conceitos aplicados


Microsoft Excel (fórmulas, named ranges, formatação condicional,
gráficos dinâmicos)
Boas práticas de modelagem: separação entre dados de entrada (azul) e
fórmulas (preto), parâmetros centralizados, layout replicável mês a mês
Cálculo de encargos trabalhistas/previdenciários (INSS sobre RPA)


📌 Contexto

Projeto desenvolvido como estudo/portfólio para demonstrar organização de
planilhas de controle financeiro e folha de pagamento de autônomos,
aplicável a rotinas de Departamento Pessoal, Contabilidade e Financeiro.
