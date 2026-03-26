# Meu-primeiro-projeto-em-Python

## Projeto 01: Quem sou eu? (apresentação via terminal)
Este é o meu primeiro contato prático com *Python*.
Em vez de fazer uma apresentação estática, decidi criar um script que interage com o usuário para contar um pouco sobre minha trajetóriae minhas habilidades atuais.
### Oque esse projeto representa:
#### Habilidade Profissional:
o código simula um sistema de triagem, mas o objetivo real é demonstrar como consigo aplicar lógica para estruturar informações.
#### Habilidades em construção :
Minha transição do portugol para sintaxe real do Python
### Oque você verá no código: (captura de tela 104839.png)
-Uso de *f-strings* para respostas personalizadas.

-Uso da biblioteca time para dar ritimo à interação.

-Estrutura de entrada e saída de dados aplicada a um cenário real de apresentação.
### Resultado final: (captura de tela 100915.png)
O terminal exibe uma conversa fluida onde apresento minha localização , minha graduação, e me objetivo de me torna uma profissional produtiva e resiliente na área de tecnologia.  


 

```python
"""
Projeto: Primeiro exercício solo em Python.
Objetivo: Demonstrar a transição de lógica e síntaxe básica.
Autor: Aline Bessa Santana
Data: 26/03/2026
Roteiro: Entrevista com o terminal.
"""
import time
if __name__ == "__main__":

   print("Iniciando processo de triagem de talentos...")
   time.sleep(2)

   nome = input("Olá, seja bem-vindo (a)ao portal de triagem. Para iniciarmos como devo lhe chamar?")

   cidade = input(f"Muito bem, {nome}. Onde mora atualmente?")

   modelo_trabalho = input(f"Entendido, {cidade} é uma localidade mais afastada dos grandes centros, você possui disponibilidade de mudança, ou seu foco atual são oportunidades 100% Home Office?")

   curso = input("Excelente, e qual graduação esta cursando no momento?")

   periodo = input("Em qual período ou semestre você está atualmente?")

   experiencia = input("A tecnologia exige mais do que apenas codigos, você tem alguma experiencia ou caracteristica especifica que possa agregar à empresa?")

   contato = input(f"Perfeito, {nome}! Para finalizarmos, qual seria a forma de contatá-la?")

   print("Excelente! Já deixei anotado. Qualquer novidade eu entro em contato, sucesso na sua jornada e boms estudos!")
```




