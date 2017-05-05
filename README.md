#Introduction 
Programmet ska analysera input och utföra calculationerna som användaren har skrivit.
Använderen ska till exempel mata in sin(2 + pi^5) för att göra en sinusberäkning på (2 + (pi * pi * pi * pi * pi)).
Det finns en calculatorklass Calculator där input ska tolkas av methoden double Calculator.ParseFormula(string input). 
Om input är ogiltig ska en exception kastas som beskriver vad felet är.
Alla calculationer är tillgängliga som en subklass av AbstractCalculation och registreras med CalculationFactory.
Man får en viss calculation, till exempel en addition, genom att be om den fran CalculationFactory.Instance.CreateCalculation(string nyckel), 
där nyckel är calculationens operator. För en addition blir det alltså CalculationFactory.Instance.CreateCalculation("+").
Calculationer har en method, double Calc(double[] factors) som ger calculationens resultat på arrayn.

#Getting Started
TODO: Guide users through getting your code up and running on their own system. In this section you can talk about:
1.	Installation process
2.	Software dependencies
3.	Latest releases
4.	API references

#Build and Test
TODO: Describe and show how to build your code and run the tests. 

#Contribute
TODO: Explain how other users and developers can contribute to make your code better. 

If you want to learn more about creating good readme files then refer the following [guidelines](https://www.visualstudio.com/en-us/docs/git/create-a-readme). You can also seek inspiration from the below readme files:
- [ASP.NET Core](https://github.com/aspnet/Home)
- [Visual Studio Code](https://github.com/Microsoft/vscode)
- [Chakra Core](https://github.com/Microsoft/ChakraCore)