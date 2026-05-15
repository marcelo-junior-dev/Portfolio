# 💸 Sistema de Processamento de Pagamento e Troco
# 📝 Descrição do Projeto
Este projeto consiste num sistema automatizado para gerir transações financeiras num ponto de venda. O objetivo principal é validar pagamentos e decompor o valor do troco na menor quantidade possível de notas e moedas, garantindo precisão e eficiência no fecho da compra.
Desenvolvido para a disciplina de Programação de Computadores (2026), o sistema utiliza funções modulares para separar a lógica de validação da lógica de cálculo matemático, transformando um processo manual numa operação digital estruturada. 
# 🚀 Tecnologias e Lógica Aplicada
•	Validação de Transações: Implementação de uma função validar-pagamento que verifica se o valor entregue é suficiente para cobrir o total da compra. 
•	Cálculo de Diferencial: Uma função dedicada para subtrair o total do valor pago e retornar o montante exato do troco. 
•	Decomposição de Notas:
o	Iteração sobre Vetores: O sistema utiliza um vetor pré-definido com os valores das notas (100, 50, 20, 10, 5, 1). 
o	Divisão Inteira e Resto: Através de operadores como MOD, o algoritmo calcula a quantidade necessária de cada nota e atualiza o saldo restante para a próxima iteração. 
•	Tipagem de Dados: Uso de tipos REAL para valores monetários e INTEIRO para contagem de unidades de notas e itens da compra. 
# 📊 Resultados e Aprendizados
O desenvolvimento deste sistema permitiu o domínio de técnicas essenciais de algoritmos bancários:
•	Segurança na Validação: Aprendizado sobre a importância de retornos booleanos (VERDADEIRO/FALSO) para impedir que o sistema prossiga com pagamentos inválidos. 
•	Otimização de Recursos: A lógica de "decompor notas" ensina como reduzir o volume físico de dinheiro em circulação, entregando sempre as maiores denominações primeiro. 
•	Modularização: A separação entre o "Início" do programa e as funções específicas facilita a manutenção e a identificação de erros em fluxos complexos. 
# 🔧 Estrutura do Algoritmo
1.	Entrada: Coleta do valor total da compra e do valor entregue pelo cliente. 
2.	Validação: Se o pagamento for menor que o total, o sistema exibe "Pagamento Inválido" e encerra; caso contrário, prossegue para o cálculo. 
3.	Processamento de Troco: O valor excedente é passado para a função de decomposição. 
4.	Saída: Exibição detalhada da quantidade de cada nota a ser entregue (Ex: "2 x R$ 50").

