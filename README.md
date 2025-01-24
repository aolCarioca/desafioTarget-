# desafioTarget
fase de teste e conhecimentos técnicos

Como Funciona o Código:
Parse do XML: O código usa o módulo xml.etree.ElementTree para ler o conteúdo XML e navegar pelos elementos <row>.

Filtragem de Valores: Apenas valores maiores que 0 são adicionados à lista valores_validos.

Cálculo de Estatísticas:

Média (media_valores): Soma dos valores válidos dividida pelo número de elementos.
Maior e menor valor: Extraídos com as funções max e min.
Dias acima da média: Determinados comparando os valores de cada dia com a média.
Saída: Os resultados são exibidos no terminal, mostrando as estatísticas calculadas.

