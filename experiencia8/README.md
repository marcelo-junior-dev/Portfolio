# 🔍 Sistema de Auditoria Financeira Recursiva
# 📝 Descrição do Projeto
Este projeto apresenta um sistema avançado de auditoria financeira capaz de navegar por estruturas corporativas complexas. O sistema utiliza técnicas de recursividade para consolidar orçamentos de diferentes filiais e departamentos, permitindo a exclusão seletiva de setores e a conversão monetária automática. 
Desenvolvido para a disciplina de Programação de Computadores (2026), o código destaca-se pelo uso de decoradores (decorators) para automatizar o rastro de auditoria, registrando o tempo de execução e os parâmetros utilizados em cada cálculo. 
# 🚀 Tecnologias e Lógica Avançada
•	Linguagem: Python 3.10 utilizando functools.wraps para preservação de metadados de funções. 

•	Padrão Decorator: Implementação da função @auditor que envolve a lógica principal para gerar relatórios de início e fim de cálculo automaticamente. 
•	Recursividade: Função interna _somar que percorre dicionários aninhados (árvores de decisão) para somar valores de infraestrutura, RH e operações. 
•	Flexibilidade de Parâmetros:
o	*args: Permite ignorar departamentos específicos e todos os seus subdepartamentos durante a soma. 
o	kwargs: Suporta configurações dinâmicas como taxa_cambio e moeda_destino. 
# 📊 Resultados e Aprendizados
A aplicação deste sistema em cenários corporativos reais revelou a eficiência do processamento modular:
•	Alta Performance: O sistema realiza cálculos complexos em milissegundos, conforme registado pelo time.perf_counter(). 
•	Gestão de Cenários: Capacidade de gerar "Resumos Executivos" comparando orçamentos totais vs. orçamentos filtrados em diferentes moedas (USD, EUR, BRL). 
•	Transparência: O rastro de auditoria garante que qualquer exclusão de departamento (ex: "Jurídico" ou "Marketing") seja devidamente documentada no log de saída. 

# 🔧 Estrutura do Processamento
1.	Monitorização: O decorador regista o timestamp e os departamentos que serão ignorados. 
2.	Navegação: O algoritmo identifica se um nó é um dict (continua a navegar) ou um valor numérico (acumula no total). 
3.	Conversão: Aplica-se o fator de câmbio sobre o total_base consolidado. 
4.	Finalização: Exibe o total convertido e o tempo exato gasto na operação. 
________________________________________
Relatório técnico de auditoria e lógica recursiva finalizado em maio de 2026
