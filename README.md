# Desafio de Cálculo de Imposto em Java

Este projeto é a minha solução para um desafio de lógica em Java, focado no cálculo de impostos sobre salários. O objetivo foi criar uma aplicação simples que determina o imposto de renda com base em faixas salariais, aplicando as alíquotas corretas e apresentando o valor final (salário líquido).


## Habilidades e Aprendizados

Durante a construção deste projeto, tive a oportunidade de aprimorar e demonstrar as seguintes competências técnicas:

✅ **Lógica Condicional e Estruturas de Controle:** Utilizei a estrutura `if-else if-else` para implementar as regras de negócio de forma eficiente e precisa. Isso me permitiu garantir que apenas a alíquota correta fosse aplicada a cada faixa salarial, evitando erros de cálculo e sobreposição de condições.

✅ **Manipulação de Entrada e Saída (I/O):** Trabalhei com a classe `Scanner` para ler dados de entrada do usuário (salário e benefícios) e com `System.out.println` para exibir o resultado. Aprendi a lidar com a formatação de números de ponto flutuante, garantindo que a saída fosse apresentada com duas casas decimais, conforme o padrão monetário.

✅ **Boas Práticas de Código:**
   - **Clareza e Legibilidade:** Escrevi um código limpo, com nomes de variáveis significativos (`valorSalario`, `valorImposto`).
   - **Gerenciamento de Recursos:** Incluí a instrução `leitorDeEntradas.close()` para fechar o `Scanner`, uma prática essencial para evitar vazamento de memória e garantir a gestão eficiente dos recursos do sistema.

✅ **Versionamento de Código com Git/GitHub:** O projeto completo foi estruturado para ser versionado e publicado no GitHub. Isso envolveu a criação de um `.gitignore` para ignorar arquivos desnecessários, a organização da estrutura de pastas padrão e a elaboração deste `README` detalhado.


## Funcionalidade do Projeto

O programa solicita o salário bruto e os benefícios, e então calcula o valor final com base nas seguintes regras de imposto:

| Faixa Salarial        | Alíquota de Imposto |
| --------------------- | ------------------- |
| Até R$ 1.100,00       | 5%                  |
| R$ 1.100,01 a R$ 2.500,00 | 10%                 |
| Acima de R$ 2.500,00  | 15%                 |

O resultado final é o salário bruto menos o imposto, somado aos benefícios.


## Como Rodar o Projeto

### Pré-requisitos
- **Java Development Kit (JDK) 8+** instalado.

### Execução
1. Clone o repositório: `git clone [URL_DO_REPOSITORIO]`
2. Navegue até o diretório do projeto.
3. Compile o código: `javac src/main/java/Desafio.java`
4. Execute o programa: `java -cp src/main/java Desafio`
5. Insira os valores de salário e benefícios quando solicitados.


## Contato
Você pode encontrar mais dos meus projetos e me conectar através do meu perfil no GitHub.

### Pré-requisitos
- Java Development Kit (JDK) 8 ou superior instalado.

### Passos

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/SEU-USUARIO/DesafioCalculoImposto.git](https://github.com/SEU-USUARIO/DesafioCalculoImposto.git)
   cd DesafioCalculoImposto
