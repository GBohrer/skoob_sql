# skoob_sql
Projeto sobre Fundamentos de Banco de Dados

Finalizado em Março de 2023, este projeto consiste em 2 etapas do desenvolvimento: Modelagem de um Universo de Discurso (UdD) em um esquema Entidade-Relacionamento (ER) e seu mapeamento para o modelo lógico, e a implementação, em SQL, de instâncias e consultas baseadas no "suposto" banco de dados do UdD.

Os arquivos .pdf explicam com clareza e detalhamento o UdD, que é uma rede social brasileiro para leitores chamada Skoob, o dicionário de dados e o mapeamento.
O programa "BRmodelo" foi utilizado para compor todo o esquema ER do banco de dados. O arquivo do esquema feito está incluso, e o programa pode ser utilizado via web ou instalado na máquina. O arquivo em .png é um export do esquema final feito.
E os arquivos em SQL compõem os códigos desenvolvidos no SGBD Oracle Cloud Infrastructure.

Observações ->  Algumas tabelas não foram utilizadas em consultas (exemplo: ETAGS e RECADOS); 
		            Alguns dados inseridos são meramente ilustrarivos;
		            Alguns dados não foram utilizados em consultas (exemplo: NOTAS ou LIVRO.TIPO/LIVRO.MODELO)
		            pois necessitariam de procedimentos e gatilhos não formulados para apresentarem resultados
		            corretos e interessantes. As Notas de um determinado Livro, por exemplo, deveriam ser a
		            média de todas as Notas dadas em Estantes que referenciam o Livro.
		            Sem este controle, as consultas sobre as informações inseridas estariam erradas.
