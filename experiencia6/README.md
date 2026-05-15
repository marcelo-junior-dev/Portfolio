# 🎨 Processamento de Matrizes e Manipulação de Pixels
# 📝 Descrição do Projeto
Este projeto explora o uso de estruturas de dados complexas e aninhadas para manipulação de mídias digitais (imagens e áudio). O foco está no uso de loops de múltiplos níveis para navegar por dicionários, listas e tuplas, aplicando transformações matemáticas diretamente nos dados.
Desenvolvido para a disciplina de Programação de Computadores (2026), os desafios envolvem desde a criação de filtros de brilho em emojis baseados em cores RGB até a transposição de matrizes musicais para alteração de melodias.
# 🚀 Desafios e Tecnologias
•	Linguagem: Python 3.10.
•	Manipulação de Imagem (Pixels): * Criação de um emoji 5x5 onde cada "pixel" é uma tupla (R, G, B).
o	Aplicação de um filtro de sombra: redução de 50% nos valores de pixels amarelos para criar profundidade visual.
•	Matrizes Musicais: * Transposição de matrizes 2x2 representando frequências sonoras (inversão de linhas por colunas).
o	Uso do método .update() para atualizar a biblioteca musical com as novas melodias transpostas.
•	Integração de Dados: * Desenvolvimento de uma "Playlist de Imagens" integrando múltiplos tipos de dados.
o	Uso obrigatório de métodos como .pop(), .keys() e .insert() para gerenciamento dinâmico da estrutura.
# 📊 Resultados e Aprendizados
O projeto consolidou a habilidade de lidar com estruturas imutáveis e loops profundos:
•	Imutabilidade das Tuplas: Reforço do conceito de que pixels (tuplas) não podem ser alterados diretamente; é necessário gerar uma nova tupla com os valores processados.
•	Navegação em 3 Níveis: Domínio da técnica de loops triplos (Lote -> Linha -> Pixel/Nota) para processar grandes volumes de dados aninhados.
•	Lógica de Cores: Compreensão de como a manipulação matemática dos canais RGB (Red, Green, Blue) altera a percepção visual da imagem (brilho e sombra).
•	Transposição Matemática: Aplicação prática de álgebra linear para inverter a estrutura de dados de uma melodia digital.
# 🔧 Estrutura Lógica
1.	Dicionário: Atua como o contêiner principal (ex: emoji_data ou biblioteca_musical).
2.	Lista de Listas: Forma a grade bidimensional (matriz) de pixels ou notas.
3.	Tupla: Armazena os valores fixos de cada elemento (canais de cor ou frequências).
4.	Processamento: Uso de loops for com enumerate() ou .items() para garantir que o índice correto seja atualizado durante a transformação.
