# Automação para entrar no meet
### Na quarentena tenho usado muito o meet, principalmente para aulas da faculdade, então fiz essa automação utilizando selenium para entrar automaticamente na hora certa, com microfone e vídeo desativados.
## O que o código faz é o seguinte:
- A cada minuto vê se está no horário da reunião;
  - Se não definir um horário, não compara com o horário atual, só conecta.
- Faz login no gmail;
- Abre o link do meet;
- Desativa o microfone e o vídeo;
- Pede para entrar na reunião.
## Como rodar:
### Você precisa baixar o chromedriver e colocar na pasta raiz do projeto, colocar no arquivo .env o seu email, senha, o link do meet e o horário da reunião, rodar o seguinte comando:
``` bash
pip install -r requirements.txt
```
### Depois disso, basta rodar o seguinte comando:
``` bash
python main.py
```