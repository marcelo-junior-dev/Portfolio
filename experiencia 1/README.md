# 🛡️ Algoritmo de Auditoria de Dados

# 📝 Descrição do Projeto
Este projeto consiste em um sistema de auditoria financeira desenvolvido para identificar anomalias, fraudes ou erros em lançamentos de vendas. O objetivo principal é garantir a integridade dos dados financeiros, utilizando uma margem de tolerância e limites de segurança para sinalizar transações que fogem do padrão esperado.
Desenvolvido para a disciplina de Programação de Computadores (2026), o sistema processa entradas de vendas diárias, calcula médias e aplica gatilhos lógicos de investigação para colocar o sistema em "quarentena" ou sugerir revisões manuais quando valores discrepantes são detectados.

# 🚀 Tecnologias e Conceitos Utilizados
Linguagem: Python   
Tipagem de Dados: Tratamento rigoroso de float para precisão financeira e conversão de strings (substituição de vírgulas por pontos).  
Lógica de Auditoria:Média Aritmética: Utilizada para estabelecer a base de comparação das vendas.  
Limites de Segurança: Definição de variáveis globais para controle de teto transacional.  
Detecção de Anomalias: Gatilhos automáticos para vendas que superam em 5x a média calculada.  

# 📊 Resultados e Aprendizados
O projeto demonstrou a importância da normalização de dados para obter resultados realistas.
Sensibilidade do Sistema: Identificou-se que um multiplicador de 5x pode ser muito alto para certas brechas de negócio, sugerindo-se o ajuste para 2.5x para capturar anomalias mais sutis.  
Segurança de Software: O uso de global LIMITE_SEGURANCA foi identificado como uma vulnerabilidade em sistemas bancários reais, reforçando a necessidade de encapsulamento em classes privadas para evitar scripts maliciosos.  
Tratamento de Erros: Aprendizado prático sobre exceções comuns, como ValueError na entrada de dados e UnboundLocalError ao tentar manipular variáveis globais sem a declaração correta.  
