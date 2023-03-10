OBJETIVO: A partir da base de dados "in-vehicle coupon recommendation Data", implementaremos os seguintes métodos de aprendizado de máquina:
* Random Forest 
* KNN
* Árvore de Decisão
* SVM

Com o intuito de classificar um conjunto de teste (de forma supervisionada) que analisa qual, dos 5 tipos de cupom (**Bar, Restaurante Apenas p/ Retirada, Cafeteria, Restaurante Barato, Restaurante Caro)**, foi oferecido a ela durante o trânsito, baseado em condições como:

* **Aceitação: Cupom Aceito, Cupom não aceito**

* **destino: Local Não Urgente, Casa, Trabalho**

* **Passageiro: Sozinho, Amigo(s), Filho(s), Parceiro (que são os passageiros do carro)**

* **Clima: Ensolarado, Chuvoso, Nevado**

* **Temperatura: 55, 80, 30**

* **hora: 14h , 10h, 18h, 7h, 22h**

---------------------------------------------------------

Para isso, utilizaremos:
* Uma técnica de validação cruzada (Stratified KFold);
* Otimização dos parâmetros do algoritmo de aprendizagem de máquina;
* Métodos de Avaliação dos resultados.

-----------------------------------------------------------------
Referências:

* http://archive.ics.uci.edu/ml/datasets/in-vehicle+coupon+recommendation

* Wang, Tong, Cynthia Rudin, Finale Doshi-Velez, Yimin Liu, Erica Klampfl, and Perry MacNeille. 'A bayesian framework for learning rule sets for interpretable classification.' The Journal of Machine Learning Research 18, no. 1 (2017): 2357-2393.
