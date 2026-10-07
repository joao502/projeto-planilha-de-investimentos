Quanto uma pessoa deve investir por mês
→ Localizado na tabela Configurações → Sugestão de investimento (30%)

Quanto a pessoa terá investido após determinado número de anos
→ Localizado na tabela Investimento Mensal → Por quantos anos?

Quanto de patrimônio acumulado a pessoa terá no final do período selecionado
→ Localizado na tabela Investimento Mensal → Patrimônio acumulado

Quanto de dividendos a pessoa receberá por mês
→ Localizado na tabela Investimento Mensal → Dividendos Mensais

Projeção de quanto a pessoa terá com 2, 5, 10, 20 e 30 anos investidos
→ Localizado na tabela Cenários

Percentual de investimento sugerido para cada tipo de FII, de acordo com o perfil de investidor
→ Localizado na tabela Perfil

A fórmula =VF entra no cálculo do patrimônio acumulado, calculando o valor final que o investidor terá no período selecionado anteriormente.

O PROCV foi usado para que, quando o investidor selecionar seu perfil, a função cruze os dados e retorne o percentual sugerido de investimento de acordo com esse perfil.
Ela vai até a tabela de apoio e faz o cruzamento. Por exemplo, se o perfil do investidor for conservador, a função procura a coluna que mostra a porcentagem sugerida 
para o perfil conservador e retorna esse valor na planilha principal.


Foram criados os intervalos nomeados a seguir:

aporte                     |      TIPOS DE FIIs
patrimonio                 |     
PERFIL                     |     Tipo1 -> PAPEL
qtd_anos                   |     Tipo2 -> TIJOLO  
rendimento_carteira        |     Tipo3 -> HIBRIDOS
salario                    |     Tipo4 -> FOFs
suestao_investimento       |     Tipo5 -> DESENVOLVIMENTO
taxa_mensal                |     Tipo6 -> HOTELARIAS

Os percentuais usados para cada perfil foram:
-----------------------------------
Conservador |	PAPEL	30%
Conservador	| TIJOLO	50%
Conservador	| HIBRIDOS	10%
Conservador	| FOFs	10%
Conservador	| DESENVOLVIMENTO	0%
Conservador	| HOTELARIAS	0%
------------------------------------
Moderado	  | PAPEL	32%
Moderado	  | TIJOLO	35%
Moderado	  | HIBRIDOS	8%
Moderado	  | FOFs	5%
Moderado	  | DESENVOLVIMENTO	10%
Moderado	  | HOTELARIAS	10%
-------------------------------------
Agressivo	  | PAPEL	50%
Agressivo	  | TIJOLO	10%
Agressivo	  | HIBRIDOS	5%
Agressivo	  | FOFs	5%
Agressivo	  | DESENVOLVIMENTO	20%
Agressivo	  | HOTELARIAS	10%
-------------------------------------
Os percentuais vieram da aula com o experd.

Com relação da ferramenta do experd eu bloqueia a planilha para que só possa ser mexidos nas células que eu autorizei
Coloquei uma validação de dados, para aonde for colocar numero não seja preenchido texto e nem valor negativo, 
apresentando uma mensagem de erro e informando o que deve ser preenchido
Bloqueei e Ocultei a tabela de apoio para que não seja alterado nada nela

<img width="581" height="583" alt="image" src="https://github.com/user-attachments/assets/3261a35a-7853-4c25-b822-fc6acc58001e" />
<img width="567" height="530" alt="image" src="https://github.com/user-attachments/assets/3ce609b8-98e1-42d9-8389-0e91af249176" />
<img width="586" height="553" alt="image" src="https://github.com/user-attachments/assets/997ca8ec-3b93-401f-ad42-f953d03a0f3c" />







