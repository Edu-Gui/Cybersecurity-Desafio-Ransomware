🔐 Cybersecurity-Desafio-Ransomware

Simulação educacional de criptografia de arquivos em Python para fins de aprendizado em Cibersegurança.

⚠️ Aviso Legal

Este projeto foi desenvolvido exclusivamente para fins educacionais.
Seu objetivo é demonstrar, de forma controlada, como funciona a criptografia simétrica e a lógica básica utilizada por ransomwares.

🚫 Não utilize este conhecimento para fins maliciosos.
O uso indevido pode configurar crime.

📌 Visão Geral

Este laboratório prático demonstra:

Criptografia simétrica utilizando AES

Manipulação de arquivos binários em Python

Exclusão e recriação de arquivos

Processo de criptografia e descriptografia controlado

Importância de backups e boas práticas de segurança

🛠️ Tecnologias Utilizadas

Python 3.x

Biblioteca pyaes

Ambiente Linux / WSL / Git Bash

📦 Instalação de Dependências

Antes de executar o projeto, instale a biblioteca necessária:

pip install pyaes


Ou, caso utilize Python 3:

pip3 install pyaes

🚀 Guia de Execução
1️⃣ Criar a pasta do projeto
mkdir Projeto_ransomware

2️⃣ Acessar o diretório
cd Projeto_ransomware

3️⃣ Criar os arquivos necessários
touch arquivo_teste.txt
touch encrypt.py
touch decrypt.py

<img width="636" height="402" alt="estrutura" src="https://github.com/user-attachments/assets/808ed181-175a-4e56-a93f-904e4d62dc0a" />
✏️ Implementação
🔒 Script de Criptografia – encrypt.py

Abra o arquivo:

nano encrypt.py

<img width="1305" height="698" alt="encrypt" src="https://github.com/user-attachments/assets/60bbb3af-516d-425c-924d-ce547a69fd0e" />

Insira o código de criptografia fornecido anteriormente, salve e saia.

🔓 Script de Descriptografia – decrypt.py

Abra o arquivo:

nano decrypt.py

<img width="1310" height="688" alt="decrypt" src="https://github.com/user-attachments/assets/b6813a28-94eb-4150-8f80-f37abc158f6a" />

Insira o código de descriptografia correspondente.

▶️ Testando o Funcionamento
🔐 Executar a Criptografia
python encrypt.py


O arquivo original será removido e substituído por sua versão criptografada.

🔓 Executar a Descriptografia
python decrypt.py


O arquivo original será restaurado.

<img width="644" height="508" alt="execucao" src="https://github.com/user-attachments/assets/ecd17940-cfd8-4959-af99-8b780b859109" />
