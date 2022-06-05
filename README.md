# Studying: Transfer Learning


![image](https://user-images.githubusercontent.com/69597971/171987271-09960699-5b4f-4b2e-93c2-07c7385e26ff.png)


Os modelos tradicionais de aprendizado de máquina causam muita dor quando não temos dados rotulados suficientes para a tarefa ou domínio específico com o qual nos preocupamos para treinar um modelo confiável.

Por exemplo: preciso treinar o reconhecimento de texto manuscrito usando algum modelo treinado no conjunto de dados do [IAM Handwriting Database](https://fki.tic.heia-fr.ch/databases/iam-handwriting-database). 


Então, o aprendizado de transferência nos permite lidar com esses cenários, aproveitando os dados rotulados já existentes de alguma tarefa ou domínio relacionado. Tentamos armazenar esse conhecimento adquirido na resolução da tarefa de origem no domínio de origem e aplicá-lo ao nosso problema de interesse.

Em suma, Transfer Learning é a reutilização de um modelo pré-treinado em um novo problema. Isto é, vou usar uma rede neural treinada em outro outro conjunto de dados, geralmente maior, para resolver um novo problema.

## Por que usar o Transfer Learning?

Lembrando que está técnica é usada em Visão computacional, Speech Processing, etc. Então, usamos Transfer Learning:

* já que é difícil obter um conjunto de dados grande o suficiente, raramente ``CNNs`` (por exemplo) são treinadados do zero

* CNN muito profundas são muito caras para serem treinadas. Os modelos mais complexos podem demorar uma semana utilizando centenas de GPUs muito caras (Tesla V100 e cia)


A maioria dos problemas envolvendo ``visão computacional`` usam conjuntos de dados aparentemente grandes (4000 - 20000 imagens), mas que ainda não são grandes o suficiente para se treinar adequadamente uma ``CNN``. Assim, treinar estas redes com centenas de milhões de parametros quase sempre criam o problema do ``overfitting``. Então, usamos o ``Transfer Learning`` para nos ajudar.



Links de estudo:

* [Tutorial: Transfer Learning aplicado no reconhecimento de flores](https://medium.com/ensina-ai/tutorial-transfer-learning-3972cac5e9b5)

* [Improve your model accuracy by Transfer Learning](https://medium.com/data-science-101/transfer-learning-57ce3b98650)







Thanks God!
