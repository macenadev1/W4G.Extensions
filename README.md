# W4G.Extensions

Este repositório contém uma coleção de extensões para facilitar o desenvolvimento em diversas plataformas. 

Atualmente em construção, o objetivo é fornecer uma biblioteca de recursos úteis e comuns para agilizar o processo de desenvolvimento.

## Recursos Disponíveis (em constante atualização)

### Extensões para Números
- **[ToCurrency](https://github.com/wagnerpt/W4G.Extensions/wiki/ToCurrency)**: Formatação de valores monetários. Aplica-se a: tipos int, double ou decimal.
- **[ToExtensionMoneyBRL](https://github.com/wagnerpt/W4G.Extensions/wiki/ToExtensionMoneyBRL)**: Retorna o valor por extenso em reais (R$). Aplica-se a: tipos int, long, double ou decimal.
- **[ToExtensionValueBR](https://github.com/wagnerpt/W4G.Extensions/wiki/ToExtensionValueBR)**: Retorna o número por extenso em português. Aplica-se a: tipos int, long, double ou decimal.

### Extensões para Strings
- **[NoAccents](https://github.com/wagnerpt/W4G.Extensions/wiki/NoAccents)**: Remove acentos e "ç" de uma string.
- **[OnlyNumbers](https://github.com/wagnerpt/W4G.Extensions/wiki/OnlyNumbers)**: Retorna somente os números contido em uma string.

## Como Utilizar

**Instalação via NuGet**: Você pode instalar as extensões via NuGet Package Manager executando o seguinte comando no Console do Gerenciador de Pacotes:

```bash	
dotnet add package W4G.Extensions
```

Depois de instalar o pacote, você pode usar as extensões em seu código. Veja um exemplo de uso do método ToCurrency():

```csharp
using W4G.Extensions;

class Program
{
	static void Main(string[] args)
	{
		double value = 1234.56;
		string formattedValue = value.ToCurrency(); // R$ 1.234,56
		Console.WriteLine(formattedValue);
	}
}
```

## Contribuindo
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues para relatar bugs, sugerir novas funcionalidades ou enviar pull requests com melhorias.

## Licença
Este projeto é licenciado sob a MIT License.

Este README.md fornece uma visão geral do repositório, lista os recursos disponíveis, explica como instalar e usar as extensões, e também encoraja contribuições.
