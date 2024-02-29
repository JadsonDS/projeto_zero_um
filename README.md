![image](https://github.com/JadsonDS/projeto_zero_um/blob/main/logo.png)

# Airline Loyalty Campaign Program Impact on Flights
  A companhia aérea implementou uma campanha promocional, com o objetivo de potenciar a adesão ao programa. 

#  1. Problema de negócio
  O objetivo principal e traçar perfis individuais para cada clientes com base em seus programas de fidelidade de voos: Star, Nova e Aurora.
  
  A partir desses perfis, foi desenvolvido um modelo capaz de recomendar o programa de fidelidade mais adequado para novos clientes, estimando suas probabilidades de adesão a cada opção.

# 2. Premissas assumidas para a análise
  Os dados utilizados no estudo e construção deste dashboard foram disponibilizados na plataforma Kaggle, sendo assim, os dados ficaram públicos para utilizá-los em suas análises. O link é: [https://www.kaggle.com/datasets/akashram/zomato-restaurants-autoupdated-dataset?resource=download&select=zomato.csv ](https://www.kaggle.com/datasets/agungpambudi/airline-loyalty-campaign-program-impact-on-flights).

# 3. Estratégia da solução
  O painel estratégico foi desenvolvido utilizando as métricas que refletem as visões do modelo de negócio da empresa, seus programas de fidelidade de voos.
  
  Para o desenvolvimento e manipulamos do banco de dados foi utilizado SQL e Python, a Biblioteca Pandas para limpar e preparar os dados, preparando-os para a construção do modelo de classificação. Optando pela árvore de decisão, disponível na biblioteca sklearn.
  Foi implementamos um painel interativo permitindo que o time de vendas insira os dados do cliente e receba instantaneamente a recomendação ideal.
  
 ![image](https://github.com/JadsonDS/projeto_zero_um/assets/125108476/cc731af6-34c5-459c-a186-f685b168182f)

# 4. Principais insights
  - O Rendimento Anual e o Valor Total para Todos os Voos, tem uma influência significativa nas probalididades de Adesão ao Programa de Fidelidade;
  - Todos os outros Atributos tem pouca influência na escolha de recomendação;
  - Ter o Perfil  desenvolvido pelo programa voltado para cada cliente tem uma probabilidade de adeção maior ao Program de Fidelidade.

# 5 O produto final do projeto:
  Um dashboard iterativo hospedado em cloud que está disponível para acesso de qualquer dispositivo com conexão à internet. Para acessá-los basta clicar no link a seguir: https://projetozeroum.streamlit.app/

# 6 Conclusão
  Projetos como este são fundamentais para empresas que buscam otimizar suas estratégias de vendas e marketing, oferecendo aos clientes uma experiência personalizada, aumentando as chances de sua adesão e, consequentemente, melhorando a fidelidade do cliente e os resultados da empresa.
