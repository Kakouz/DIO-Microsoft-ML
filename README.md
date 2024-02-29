# DIO-Microsoft-ML
Repositório para o desafio de machine learning da DIO

## Passo a Passo!

- Primeiro precisei acessar o portal da Azure, criei uma conta com créditos gratuitos por 30 dias usando o free-trial disponibilizado para novas pessoas na plataforma.
- Após todas as configurações iniciais seguindo o passo a passo do vídeo, acessei o Machine Learn Studio, para criar o meu trabalho de aprendizado de máquina automatizado.
- A documentação oficial, passa para nós um problema referente ao aluguel de bicicletas.
- Após configurar o ambiente, definimos a tarefa como regressão e os dados advindo de uma fonte [WEB](https://aka.ms/bike-rentals)
- Continuei realizando algumas configurações conforme a documentação para realizar a tarefa de maneira eficaz e satisfatória.
- Após finalizar o envio do trabalho, ele vai passar pelo proxesso de configuração das execuções e após 15 minutos (aproximadamente), estará concluído.


## Sobre o modelo!
- Na página do modelo, ao acessar a aba "Pontos de extremidade". Acessei o ponto correspondente ao modelo gerado.
- Em seguida, acessei a aba "Testar".

Para o teste, segue o json abaixo:
```json
{
  "input_data": {
    "data": [
       {
         "day": 1,
         "mnth": 1,   
         "year": 2022,
         "season": 2,
         "holiday": 0,
         "weekday": 1,
         "workingday": 1,
         "weathersit": 2, 
         "temp": 0.3, 
         "atemp": 0.3,
         "hum": 0.3,
         "windspeed": 0.3 
       }
     ]
  }
}
```

O resultado devolvido pelo modelo foi o seguinte:
```json
[
  361.95238671338427
]
```
