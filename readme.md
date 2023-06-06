### **Contexto**
As comunidades empresariais nos Estados Unidos enfrentam uma alta demanda por recursos humanos, mas um dos desafios constantes é identificar e atrair o talento certo, que é talvez o elemento mais importante para se manter competitivo. Empresas nos Estados Unidos procuram indivíduos trabalhadores, talentosos e qualificados tanto localmente quanto no exterior.

A Lei de Imigração e Nacionalidade (INA) dos EUA permite que trabalhadores estrangeiros venham trabalhar nos Estados Unidos temporária ou permanentemente. A lei também protege os trabalhadores americanos contra impactos adversos em seus salários ou condições de trabalho, garantindo que os empregadores americanos cumpram os requisitos legais ao contratar trabalhadores estrangeiros para suprir a escassez de mão de obra. Os programas de imigração são administrados pelo Escritório de Certificação de Trabalho Estrangeiro (OFLC).

O OFLC processa pedidos de certificação de emprego para empregadores que buscam trazer trabalhadores estrangeiros para os Estados Unidos e concede certificações nos casos em que os empregadores podem demonstrar que não há trabalhadores americanos suficientes disponíveis para realizar o trabalho com salários que atendam ou excedam o salário pago para a ocupação na área de emprego pretendida.

### **Objetivo**
No ano fiscal de 2016, o OFLC processou 775.979 pedidos de empregadores para 1.699.957 posições de certificações de trabalho temporárias e permanentes. Isso representou um aumento de nove por cento no número total de pedidos processados em relação ao ano anterior. O processo de revisar cada caso está se tornando uma tarefa tediosa à medida que o número de candidatos aumenta a cada ano.

O aumento do número de candidatos a cada ano demanda uma solução baseada em Aprendizado de Máquina que possa ajudar na pré-seleção dos candidatos com maiores chances de aprovação de VISTO. O OFLC contratou sua empresa, TopVistos, para soluções baseadas em dados. Como Cientista de Dados, você deve analisar os dados fornecidos e, com a ajuda de um modelo de classificação:

Facilitar o processo de aprovação de vistos.

Recomendar um perfil adequado para os candidatos para os quais o visto deve ser certificado ou negado, com base nos fatores que influenciam significativamente o status do caso.

### **Descrição dos Dados**

Os dados contêm diferentes atributos do empregado e do empregador. O dicionário de dados detalhado é fornecido abaixo.

#### Arquivos
- **train.csv** - dataset de treino
- **test.csv** - dataset de testes

#### Dicionário dos Dados

- **id_do_caso:** ID de cada solicitação de visto
- **continente:** Informação do continente do empregado
- **educação_do_empregado:** Informação sobre a educação do empregado
- **tem_experiência_de_trabalho:** O empregado possui alguma experiência de trabalho? S = Sim; N = Não
- **requer_treinamento_de_trabalho:** O empregado requer algum treinamento de trabalho? S = Sim; N = Não
- **num_de_empregados:** Número de funcionários na empresa do empregador
- **ano_de_estabelecimento:** Ano em que a empresa do empregador foi estabelecida
- **região_de_emprego:** Informação da região de emprego pretendida pelo trabalhador estrangeiro nos EUA.
- **salário_prevalecente:** Salário médio pago a trabalhadores em ocupações semelhantes na área de emprego pretendida. O objetivo do salário prevalecente é garantir que o trabalhador estrangeiro não seja subremunerado em comparação com outros trabalhadores que oferecem o mesmo serviço ou serviço similar na mesma área de emprego.
- **unidade_de_salário:** Unidade do salário prevalecente. Os valores incluem Por Hora, Por Semana, Por Mês e Por Ano.
- **posição_em_tempo_integral:** A posição de trabalho é em tempo integral? S = Posição em Tempo Integral; N = Posição em Meio Período
- **status_do_caso:** Indicador se o visto foi certificado ou negado