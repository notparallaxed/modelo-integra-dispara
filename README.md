# Modelos Integra-e-Dispara

![grafico exemplo da dinamica do modelo](/exemplo-dinamica-modelo.jpg)

Os modelos integra e dispara correspondem a um conjunto de modelos que buscam representar o comportamento elétrico neuronal:

- As propriedades integrativas da membrana a estímulos excitatórios e inibitórios.
- A dinâmica de equilibrio estacionário do potencial de repouso. 
- O indicativo de um disparo de potencial de ação.

## Limitações
O modelo implementado neste projeto corresponde ao de dinâmica simples unidimensional, portanto não é capaz de representar a dinâmica do potencial de ação tal como ocorre quando o potencial de membrana atinge certo limiar. Para suprir essa lacuna, o modelo prevê o "reset" do sistema ao ponto de hiperpolarização de membrana, abaixo do potencial de repouso, registrando a parte um indicativo de disparo de potencial de ação. 

## Ferramentas utilizadas

- Python 3.9.6
- Jupyter Notebook
