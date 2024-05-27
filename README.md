# aplicando-testes

## Conteúdo

### Foi realizado testes unitários na classe ConversorTemperatura, que converte temperaturas de Fahrenheit para Celsius, utilizando três frameworks diferentes: xUnit, NUnit e MSTest. A classe temp contém um método estático FahrenheitParaCelsius que realiza a conversão e arredonda o resultado para duas casas decimais. Foram implementados testes para este método em cada framework, demonstrando como definir dados de teste e verificar os resultados esperados.

### Os testes utilizam o atributo Theory com InlineData para especificar múltiplos conjuntos de dados. O atributo Test cumpre a mesma função. Os testes são parametrizados usando DataRow com DataTestMethod. Cada framework tem sua própria sintaxe para realizar asserções, mas todos confirmam se o método FahrenheitParaCelsius retorna os valores esperados. Resultados de testes mostram que o método funciona corretamente, exceto quando uma falha foi simulada propositalmente para demonstrar o comportamento dos testes ao encontrar erros.

