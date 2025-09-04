## Distribuições de Probabilidade 

     Conforme o tamanho da amostra cresce, a distribuição de frequência tende a se aproximar da distribuição de probabilidade teórica (Lei dos Grandes Números).  


- Distribuição de frequência → mostra como os dados observados se comportaram.
- Distribuição de probabilidade → mostra como os dados deveriam se comportar, segundo um modelo probabilístico

### Distribuição binomial  

> __Problema__: Concurso com 10 questões múltipla escolha com 3 alternativas cada. __Cada questão tem o mesmo valor__. Um candidato chuta todas as questões. Assumindo que a prova vale 10 pontos e que a nota de corte seja 5, obtenha a probabilidade de o candidato acertar 5 questões e também a probabilidade deste candidato __passar para a próxima etapa do processo seletivo__  

Um _evento binomial_ é caracterizado pela ocorrência de apenas duas categorias. Estas categorias somadas representam todo o espaço amostral, sendo também mutuamente excludentes, ou seja, a ocorrência de uma implica na não ocorrência da outra.  

Em análises estatísticas o uso mais comum da distribuição binomial é na solução de problemas que envolvem situações de __sucesso__ e __fracasso__.


> $$
> P(k) = \binom{n}{k}p^k q^{n-k} 
> $$
> $p$ : probabilidade de sucesso  
> $q = 1 - p$ : probabilidade de fracasso  
> $n$ : número de eventos estudados  
> $k$ : número de eventos desejados que tenham sucesso  

As probabilidades $p$ e $q$ não se modificam de um ensaio para outro.

--- 

### Distribuição de Poisson  

Descreve a probabilidade de ocorrência de um número específico de eventos dentro de um intervalo fixo de tempo ou espaço, sob certas condições:  

     Eventos devem ser independentes entre si, ocorrer de forma aleatória e com uma taxa média conhecida μ. 

 $$ 
 P(X=k) = \frac{e^{-\mu}\mu^k}{k!}
 $$    

 --- 

 ### Distribuição normal  

 __Problema__: Altura de pessoas que segue aproximadamente uma distribuição normal com média de 1,70 e desvio padrão de 0,1. Com estas informações obter as probabilidades de:

 __A.__ Altura $\le$ 1.80m  
 __B.__ Altura 1.60m $\le$ h $\le$ 1.80m  
 __C.__ Altura $>$ 1.80m  


$$
f(x) = \frac{1}{\sqrt{2\pi\sigma}} \exp \left\{-\frac{1}{2}\left(\frac{x - \mu}{\sigma}\right)^2\right\}
$$


#### Tabelas padronizadas   

Obter probabilidade sem calcular integral:

$$
Z = \frac{x -\mu}{\sigma}
$$

     Z representa o afastamento em desvios padrões da variável original em relação a média.
 