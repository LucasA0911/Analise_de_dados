# Modulo 1
## Conhecendo os dados.

Um dado é uma unidade bruta dentro da informação. Ou seja ele é uma parte da informação.
Os dados vem de qualquer tipo de interação que fazemos em redes sociais e na internet, geram dados, seja ele por um PC ou por um dispositivo IoT.
Os dados são a base da informação. Ele sozinho não me dá nenhuma informação, um nome em uma tabela de clientes, é só um nome entre milhares. Porém quando esse nome vem acompanhado de uma data de nascimento por exemplo após o processamento dos dados consigo ter alguns insights como por exemplo, possiveis gostos, se já concluiu o ensino médio ou não, consigo colocar este cliente em uma categoria de clientes separados por idade, etc...
O objetivo da analise de dados é que os dados brutos se transforme em informação.

## DIKW
- Dados, Informação, Conhecimento, Sabedoria.
### DIKW nas carreiras.
- O **engenheiro de dados** prepara e entrega os dados
- O **analista de dados** transforma os dados em informação
- O **cientista de dados** busca modelos e insights

### Cenário 1
#### Transito em uma avenida central
1. O engenheiro de dados
   - Pergunta: De quais dados você precisa para entender o problema do transito na avenida central?
   - Resposta: Dados brutos como:
       - Contagem de veículos
       - Dados de GPS dos carros
       - Horários
       - Dados dos semáforos
       - ...
2. O Analista de dados
   - Pergunta: Quais características posso retirar desses dados coletados?
   - Resposta:
     - Faria a comparação com dias anteriores para mostrar se houve ou não um aumento no fluxo de veículos.
     - Identificaria cruzamentos com lentidão
     - Horários que acontecem a lentidão
     - Dias onde o fluxo de veículos é maior
     - ...
3. O cientista de dados
   - Realiza perguntas que possam transformar a informação gerada pelo analista de dados em conhecimento.
   - Ex:
     - Quais eventos ocorrem para que o fluxo de veículos aumentem em dias específicos?
     - Tem obras no local?
     - Houve fechamentos de vias nos arredores?
     - Houve algum acidente?
     - É periódico ou foi uma exceção?
     - ...
4. O stakeholder (Líder da equipe de mobilidade)
   - Com o conhecimento que foi gerado, cria estratégias para que o problema seja resolvido.
   - Ex:
     - Ajuste de semáforos
     - Criação de rotas alternativas
     - Alertas para os motoristas evitarem o local
     - Ajuste da via (Retirar uma faixa de um sentido que está menos movimentado, etc...)
    
## Tipos de dados
### Estruturados
São dados que estão em uma estrutura de organização rígida, em um molde pré-definido. Ex:
- Planilha
- Bancos de dados relacionais (CSV, CLSX)
São ideais para analise de dados pois nos permite fazer cálculos, comparações etc...
### Semi-estruturados
São informações que estão dentro de uma estrutura de organização menos rígida que geralmente utilizam marcadores como tags ou chaves para identificar e para definir os elementos e a hierarquia dos dados. Ex:
- JSON
- XML
- E-mails
- Logs de sistemas
- Dados de sistemas IoT
- Posts em redes sociais
São muito importantes porque muitas informações que vem da internet vem nesse formato, como APIs, logs, dados de redes sociais etc...
O pandas consegue transformar dados semi-estruturados em dados estruturados.
### Não-estruturados
São informações que não tem nenhum tipo de estrutura de organização, e nenhum tipo de molde pré-definido. Ex:
- Vídeos
- Áudios
- Fotos
Para analisar os dados não estruturados geralmente são utilizadas técnicas como:
  - PLN
    - Para entender textos e sentimentos
  - Reconhecimento de imagem e vídeo
    - Para identificar padrões visuais
  - Analise de áudio
    - Para transcrever e interpretar falas
  - ML e IA
    - Para extrair padrões e prever comportamentos
Os maiores desafios em analisar dados não estruturados envolvem custos, sejam computacionais ou financieiros. Dificuldade de padronização porque cada dado requer uma abordagem especifica para aquele dado. E a segurança, cada região tem sua propria lei de proteção de dados, que geralmente tornam essas analises mais complexas.
