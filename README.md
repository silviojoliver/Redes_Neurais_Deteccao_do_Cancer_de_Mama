# Redes_Neurais_Deteccao_do_Cancer_de_Mama

A utilização de Machine Learning para a detecção do câncer de mama vem crescendo cada vez mais e contribuindo para diagnósticos mais rápidos e precisos.

De acordo com a Sociedade Brasileira de Mastologia, uma em cada 12 mulheres terá um tumor nas mamas até os 90 anos. Infelizmente, o câncer de mama é a principal causa de morte entre as mulheres, de todos os diferentes tipos de câncer.

Machine Learning Python Câncer de Mama
Uma das principais características do câncer de mama é que quanto mais precoce for o seu diagnóstico, maiores são as chances de tratamento. Entretanto, uma pesquisa realizada revelou que mais de 3,8 milhões de mulheres na faixa de 50 a 69 anos nunca haviam feito autoexame ou mamografia.

A fim de aumentar a conscientização a respeito da prevenção e diagnóstico precoce, há, todo ano, a campanha Outubro Rosa, que visa alertar principalmente as mulheres sobre esta causa.


#Explicação dos atributos


-Os atributos são divididos em três grupos: Mean, SE e Worst.

Mean: média de todas as células;

SE: Standard Error (erro padrão de todas as células);

Worst: média dos três piores valores medidos das células. Na verdade, é considerado "pior" porque são medidas indicativas de células não saudáveis; na realidade o "pior" significa os maiores valores medidos para raio, perímetro, textura etc.

Cada grupo tem 10 atributos:

radius (raio da célula) texture (textura da célula - medida pelo desvio padrão de escalas de cinza, que ajudam a indicar se a célula é saudável ou não) perimeter (perímetro) area (área) smoothness (variação local em comprimentos de raio) compactness (campactude = perimetro²/area - 1) concavity (gravidade das porções côncavas das células) concave points (número de porções côncavas no contorno da célula), symmetry (simetria) fractal_dimension (dimensão fractal)
