# Droid-hacking :robot:

- Guia e ferramentas hacking kali-linux para dispositivos Android na implementação de Pentests 

***A forma como você irá usar essas ferramentas é totalmente sua responsabilidade***

## Preparando seu Dispositivo:

- Para ter um terminal linux rodando no seu dispositivo, você terá que instalar algumas ferramentas
- Entre no site [F-Droid.org](https://f-droid.org/), baixe o aplicativo dele e instale em seu celular. Se aparecer algum alerta de não aceitar fontes desconhecidas, basta clicar em Configurações e habilitar essa opção.
  
  ***O F-Droid é um tipo de play store para aplicativos especiais Android.***

-  Assim que tiver instalado o aplicativo do F-Droid, abra ele e na lupa pesquise por Termux
-  Baixe e instale o Termux (Emulador)
-  Assim que você abrir o aplicativo do Termux, ele habilita o seu terminal do Android

***O termux da Google Play foi descontinuado e não funciona***

## Comandos e Diretórios do Termux:

- São os mesmos que você utiliza em sua distribuição linux: Para limpar a tela clear, listar ls, conferir diretório pwd, ...

## Atualizando o sistema

- Para instalar qualquer ferramenta no terminal do termux, usamos o ***pkg***
- Então vamos atualizar o nosso sistema termux, digitando o comando:
  
  ```
  pkg update
  ```
  - Depois precisamos instalar o git para clonar algumas ferramentas hacking do Github, então digite:
  
  ```
  pkg install git
  ```
  
  ## Preparando o ambiente para o Pentest:
  
- Primeiro instale a ferramenta de investigação de Osint a mr.holmes
- Vá até o repositório: [https://github.com/Lucksi/Mr.Holmes](https://github.com/Lucksi/Mr.Holmes) e siga todos os passos do Readme da instalação para o Termux
- Digite "1" para instalar todas as dependências do projeto 
- A medida que foram sendo instaladas as dependências ele pergunta se quer instalar algum serviço especifico: Digite 1 para sim e 2 para não
- Não é recomendável instalar serviços de email e proxy, então escolha a opção 2
- Para rodar a aplicação, digite:

```
python MrHolmes.py
```

