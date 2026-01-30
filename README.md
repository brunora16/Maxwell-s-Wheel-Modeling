# Maxwell-s-Wheel-Modeling
Projeto final da disciplina Modelagem Matemática e Computacional.

# 🎡 Simulação da Roda de Maxwell

Este projeto consiste em uma ferramenta de simulação física e análise computacional do movimento da Roda de Maxwell. 
O programa utiliza abordagens simbólicas, analíticas e numéricas para descrever a dinâmica de descida e subida da roda, validando o modelo através da conservação de energia.

# 📋 Visão Geral

O código foi desenvolvido em Python e está estruturado para: Derivar a aceleração do sistema via Mecânica Lagrangiana (SymPy).
Calcular a solução analítica (exata) das equações de movimento.
Simular numericamente o sistema via método de Euler-Cromer.
Comparar os resultados com dados experimentais fornecidos no arquivo científico baseado.
Analisar a conservação de energia (Cinética de Translação, Rotação e Potencial).

# 🛠️ Tecnologias Utilizadas

SymPy: Manipulação algébrica simbólica para as equações de Euler-Lagrange.

NumPy: Processamento numérico e manipulação de arrays de dados.

Matplotlib: Geração de gráficos de alta qualidade para análise de trajetória e espaço de fase.

Pandas: Estruturação de tabelas de dados para comparação e exportação.

# 🔬 O Modelo Físico

A aceleração efetiva é obtida considerando que a energia potencial gravitacional é convertida em energia cinética de translação e rotação.

A fórmula derivada pelo programa é: a = -g / (1 + (R**2 / (2 * r**2))) Onde: 

g: Aceleração da gravidade. 

R: Raio do disco da roda. 

r: Raio do eixo (onde o fio é enrolado).

# 🚀 Funcionalidades


## 1. Soluções de Movimento

Analítica: Utiliza as integrais diretas da aceleração para obter h(t) e v(t).

Numérica (Euler-Cromer): Integra a aceleração passo a passo, permitindo observar comportamentos de discretização temporal (dt).

## 2. Visualizações Gráficas

Posição vs. Tempo: Mostra o comportamento parabólico de descida e subida.

Espaço de Fase (Velocidade vs. Posição): Demonstra o ciclo fechado da oscilação.

Análise de Energia: Gráfico comparativo entre energia cinética (translação + rotação) e potencial, evidenciando a conservação da energia mecânica total.


## 3. Geração de Tabelas

Geração automática de tabelas de dados em função da distância percorrida ou do tempo, facilitando a comparação com experimentos de laboratório.

# 📈 Como Executar

Defina as constantes iniciais no topo do código:m_val (massa), R_val (raio do disco), r_val (raio do eixo).H0_val (altura inicial) e dt (passo de tempo).
Execute as células em ordem para processar desde a simbologia até os gráficos finais.
