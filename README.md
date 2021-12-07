# César Guedes Carneiro - Prova Larcom/Unicamp
### Disponivel em : https://github.com/czariv/Larcom
### 1)
~~~python
sexo = {"m":0,"f":0}
pessoas = {}
nome = input()
maisVelho = 0
maisNovo = 99999
while(nome):
    idade = int(input())
    if (idade>maisVelho):
        maisVelho = idade
    if (idade<maisNovo):
        maisNovo = idade
    pessoas[nome]=idade
    sex = input()
    if sex == "masculino":
        sexo["m"] += 1
    elif sex == "feminino":
        sexo["f"] += 1
    nome = input()
print("Total de Homens: "+ str(sexo["m"]))
print("Total de Mulheres: "+ str(sexo["f"]))
print("Idade do mais velho: "+ str(maisVelho))
print("Idade do mais novo: "+ str(maisNovo))
~~~
### 2)
~~~java
public class Pessoa {

	private String Nome;
	private int Idade;
	private int Sexo;
	
	public Pessoa(String nome, int idade, int sexo) {
		Nome = nome;
		Idade = idade;
		Sexo = sexo;
	}
	
	public Pessoa(String nome) {
		Nome = nome;
	}

	public String getNome() {
		return Nome;
	}

	public void setNome(String nome) {
		Nome = nome;
	}

	public int getIdade() {
		return Idade;
	}

	public void setIdade(int idade) {
		Idade = idade;
	}

	public int getSexo() {
		return Sexo;
	}

	public void setSexo(int sexo) {
		Sexo = sexo;
	}
}
~~~~
### 3)
~~~
*
**
***
****
*****
~~~
