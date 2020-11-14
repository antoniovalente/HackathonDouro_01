<style TYPE="text/css">
code.has-jax {font: inherit; font-size: 100%; background: inherit; border: inherit;}
</style>
<script type="text/x-mathjax-config">
MathJax.Hub.Config({
    tex2jax: {
        inlineMath: [['$','$'], ['\\(','\\)']],
        skipTags: ['script', 'noscript', 'style', 'textarea', 'pre'] // removed 'code' entry
    }
});
MathJax.Hub.Queue(function() {
    var all = MathJax.Hub.getAllJax(), i;
    for(i = 0; i < all.length; i += 1) {
        all[i].SourceElement().parentNode.className += ' has-jax';
    }
});
</script>
<script type="text/javascript" src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.4/MathJax.js?config=TeX-AMS_HTML-full"></script>


# Conclusões 

* Todos os sensores colocados nas quatro Quintas do Douro comunicaram os seus dados,
apesar de uma gateway (Quinta do Crasto) não ter estado operacional

* Um sensor na Quinta do Seixo comunicou os seus dados através da gateway da Galafura ($9,8\,\mathrm{km}$) o que dá uma área de cobertura de aproximadamente $300\, \mathrm{km}^2$.

* A rede de comunicações baseada em LoRaWAN mostra-se, assim, uma possível mais-valia para a 
implementação de IoT na Região Demarcada do Douro

* Este projeto piloto demonstrou que se poderá implementar uma rede de comunicação de dados 
democratizadora, colaborativa e inclusiva, com uma grande capacidade de estímulo a inovação  

* Toda a documentação estará disponível em https://github.com/antoniovalente/HackathonDouro_01
e em https://hackathon-douro-porto-desafio-1.readthedocs.io/

# Trabalho Futuro

O trabalho futuro passa por arranjar um financiamneto, através de um projeto nacional ou europeu, para implementar a rede de comunicações LoRaWAN em toda a Região Demarcada do Douro.

Atendendo a que a área total da RDD é de $250000\,\mathrm{ha}=2500\,\mathrm{km}^2$ (fonte [IVDP](http://www.ivdp.pt/consumidor/regiao-limite-da-regiao-demarcada-do-douro)) e que a área com vinha na RDD é de $45613\,\mathrm{ha}=456,13\,\mathrm{km}^2$, poderse-á ter uma excelente cobertura de toda a RDD com cerca de dez gateways.

O valor de cada gateway com torre, apoio de energia solar e bateria é de aproximadamente $2000\,€$. Considerando um valor de $5000\,€$ para deslocações e outros gastos na montagem das gateways, o preço estimado para a cobertura da RDD será de aproximandamente $25000\,€$.

No entanto, o número total de gateways necessárias carece de um estudo sobre os locais onde colocar as mesmas. Também será elaborado um melhor estudo da cobertura das atuais gateways para comparar os dados da simulação com os dados desse estudo. Com os dados obtidos pelos sensores pode-se afirmar que, com somente duas gateways, conseguiu-se total cobertura nos locais onde estes foram colocados. Com o próximo estudo, onde um sensor com GPS irá percorrer as estradas cobertas, na simulação, pelas duas gateways (Galafura e Quinta do Seixo), poderemos ter uma melhor comparação entre os dados da simulação e os dados reais. 


[![CC BY 4.0](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)
