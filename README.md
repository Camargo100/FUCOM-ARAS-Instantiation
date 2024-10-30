Arquivo "Toy Example FUCOM-ARAS":
Demonstração da implementação do método FUCOM-ARAS: verificação de funcionalidade
- Não há julgamento de decisores/analistas/especialistas. As comparações de prioridade entre os critérios são realizadas aleatoriamente pelo programa

Arquivo "FUCOM-ARAS":
Avaliação do artefato (DSR): validação de desempenho
- Avaliação Experimental: simulação em ambiente controlado empregando dados reais;
- Avaliação Analítica: exame de robustez e estabilidade do comportamento da instanciação do método FUCOM-ARAS, por meio de análise de sensibilidade
  Opções dadas pelo programa:
  1) variação dos pesos dos critérios:
     a) técnica de Simulação de Monte Carlo: trata o peso do critério como uma distribuição de probabilidade (distribuição normal);
     b) técnica de redução sucessiva de pesos em um intervalo 15-90%
  2) eliminação da pior alternativa
Dados de entrada a partir de planilhas .xlsx: o código foi implementado para atender à instanciação do método FUCOM-ARAS. Para usar o método em outros contextos, é necessário adaptar o código, caso mudem as planilhas, ou suas abas, ou o número de analistas/especialistas.
- Para o FUCOM: dados de entrada nas planilhas em arquivos .xlsx com nome iniciado por "input";
- Para o ARAS: dados de entrada no arquivo "Alt_ARAS_v2.xlsx"
