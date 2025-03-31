# Conversor de Temperatura

Este é um simples conversor de temperatura desenvolvido em Java. Ele permite converter entre Celsius, Fahrenheit e Kelvin.

## Funcionalidades
- Converter de Celsius para Fahrenheit e Kelvin.
- Converter de Fahrenheit para Celsius e Kelvin.
- Converter de Kelvin para Celsius e Fahrenheit.

## Tecnologias Utilizadas
- Java 11+
- Spring Boot (se aplicável)

## Como Usar
1. Clone este repositório:
   ```sh
   git clone https://github.com/seu-usuario/conversor-temperatura.git
   ```
2. Navegue até o diretório do projeto:
   ```sh
   cd conversor-temperatura
   ```
3. Compile e execute o programa:
   ```sh
   javac ConversorTemperatura.java
   java ConversorTemperatura
   ```
   Ou, se for um projeto Spring Boot:
   ```sh
   mvn spring-boot:run
   ```

## Exemplos de Uso
```java
ConversorTemperatura conversor = new ConversorTemperatura();
double fahrenheit = conversor.celsiusParaFahrenheit(25);
System.out.println("25°C em Fahrenheit: " + fahrenheit);
```

## Contribuindo
Sinta-se à vontade para abrir issues ou enviar pull requests para melhorias.

