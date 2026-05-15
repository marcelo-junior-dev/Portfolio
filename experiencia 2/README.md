# 💧 Sistema de Irrigação Automatizado
# 📝 Descrição do Projeto
Este projeto apresenta o desenvolvimento de um sistema inteligente para controle de irrigação de solo, focado na eficiência hídrica e segurança operacional. O sistema monitora as condições ambientais em tempo real para decidir a necessidade de rega, além de possuir mecanismos de detecção de falhas. 

Desenvolvido para a disciplina de Programação de Computadores (26/03/2026), o trabalho utiliza representações visuais (fluxogramas) e lógicas (pseudocódigo) para estruturar a tomada de decisão algorítmica. 

# 🚀 Tecnologias e Lógica Aplicada
•	Monitoramento de Sensores: Leitura constante da umidade do solo e do fluxo de água. 

•	Variáveis de Controle: Definição de parâmetros críticos como Umidade_Ideal e Limite_Fluxo. 

•	Gestão de Recursos: O sistema calcula a quantidade exata de água necessária antes de ativar a irrigação. 
•	Segurança e Manutenção:
o	Detecção de Vazamento: Se o fluxo de água exceder o limite estipulado, o sistema emite um alerta de "Possível desperdício ou vazamento" e encerra a operação imediatamente. 
o	Loop de Monitoramento: Enquanto a irrigação está ativa, o algoritmo continua verificando os sensores para garantir que o desligamento ocorra assim que a umidade ideal for atingida. 
# 📊 Resultados e Aprendizados
O projeto foca na transformação de dados complexos em decisões binárias e na robustez do software contra falhas externas.
•	Abstração do Mundo Real: Aprendizado sobre como transformar variáveis físicas (umidade, tempo, fluxo) em decisões lógicas de "Sim" ou "Não". 
•	Prevenção de Erros: A inclusão de verificações de fluxo visa mitigar possíveis problemas causados por falhas humanas ou defeitos nos sensores. 
•	Estrutura de Controle: Uso de estruturas Enquanto (loops) e Se...Então (condicionais) para manter o sistema em funcionamento contínuo e seguro. 
# 🔧 Estrutura do Algoritmo
1.	Início: Inicialização das variáveis de umidade e limite de fluxo. 
2.	Verificação: Leitura da umidade atual; se o solo já estiver úmido, o sistema permanece desligado. 
3.	Ação: Cálculo do volume de água e ativação da bomba de irrigação. 
4.	Auditoria: Monitoramento constante do fluxo para interromper a operação em caso de anomalia grave. 
________________________________________
Atividade acadêmica realizada em 26/03/2026 como parte do estudo de lógica de programação.

