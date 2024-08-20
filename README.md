def calcular_imc(peso, altura):
  """Calcula o IMC com base no peso e altura fornecidos.

  Args:
    peso: Peso da pessoa em quilogramas.
    altura: Altura da pessoa em metros.

  Returns:
    O valor do IMC.
  """

  imc = peso / (altura ** 2)
  return imc

def classificar_imc(imc):
  """Classifica o IMC de acordo com os valores padrões.

  Args:
    imc: Valor do Índice de Massa Corporal.

  Returns:
    Uma string com a classificação do IMC.
  """

  if imc < 18.5:
    return "Abaixo do peso"
  elif 18.5 <= imc < 25:
    return "Peso normal"
  elif 25 <= imc < 30:
    return "Sobrepeso"
  elif 30 <= imc < 40:
    return "Obesidade"
  else:
    return "Obesidade grave"

# Solicita os dados do usuário
peso = float(input("Digite seu peso em kg: "))
altura = float(input("Digite sua altura em metros: "))

# Calcula o IMC
imc_calculado = calcular_imc(peso, altura)

# Classifica o IMC
classificacao = classificar_imc(imc_calculado)

# Imprime o resultado
print(f"Seu IMC é: {imc_calculado:.2f}")
print(f"Classificação: {classificacao}")- 👋 Hi, I’m @R1card0-01
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
R1card0-01/R1card0-01 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
