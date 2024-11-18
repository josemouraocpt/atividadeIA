# Trabalho Prático Final de Inteligência Artificial: Resolvendo um Problema Real com IA
O objetivo do modelo criado é a classificação de imagens utilizando inteligência artificial, 
ou seja , a capacidade do computador em identificar padrões em uma imagem e conseguir categorizar o que a imagem representa.

O dataset utilizado foi o [CIFAR10](https://www.cs.toronto.edu/~kriz/cifar.html)

##  Método utilizado
Para a criação do modelo optamos por utilizar uma Rede Neural Convolucional, onde cada camada convolucional da rede é responsável por identificar pequenos padrões, 
uma camada de filtro responsável por transcrever os padrões encontrados em uma nova imagem e três camadas totalmente conectadas responsável por agrupar os padrões encontrados 
nas camadas anteriores e analisar a imagem do filtro para produzir uma saída, sendo zero ou u

## Resultados
As imagens do dataset foram divididas em 10 classes: ['plane', 'car', 'bird', 'cat', 'deer', 'dog', 'frog', 'horse', 'ship', 'truck'].
Após o treinamento e avaliação do modelo conseguimos uma acurácia de 65.13%.

Já com o modelo treinado fizemos um teste com 100 imagens sendo 10 de cada classe e foi possível verificar que o modelo ainda comete alguns erros durante a classificação de imagens, 
principalmente com ângulos não convencionais dos objetos fotografados.

## Aplicação no mundo real
Como se trata de um modelo de classificação de imagem a sua aplicação é muito diversa e pode ser implementada em diversas áreas do conhecimento, podemos generalizar o modelo em troca de acurácia ou diminuir as classes em troca de melhores resultados, criando assim um específico para certas tarefas.

### Autores:
* José Mourão - RA: 121116938
* Gabriel Gontijo - RA: 121118394