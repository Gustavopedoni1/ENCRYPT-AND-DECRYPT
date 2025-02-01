# ENCRYPT-AND-DECRYPT

🔐 Ransomware Simples em Python

Este projeto demonstra um ransomware educacional feito em Python, capaz de criptografar e descriptografar arquivos usando AES (Advanced Encryption Standard).

📌 Funcionalidades

✅ Criptografia de arquivos com AES-CTR
✅ Descriptografia dos arquivos criptografados
✅ Exemplo prático de como funciona um ransomware

🛠 Pré-requisitos

Antes de executar o projeto, instale a biblioteca necessária:

```
pip install cryptography
```

🚀 Como Usar

1️⃣ Criptografar um arquivo

Execute o script ```encrypter.py``` para criptografar o arquivo ```teste.txt```:

```
python3 encrypter.py
```
Isso criará um novo arquivo ```teste.txt.ransomwaretroll```.

2️⃣ Descriptografar um arquivo

Execute o script ```decrypter.py``` para restaurar o arquivo original:

```
python3 decrypter.py
```

Isso removerá o arquivo criptografado e recriará ```teste.txt```.

📂 Estrutura do Projeto

```
📁 Ransomware-Simples
│── encrypter.py  # Script de criptografia
│── decrypter.py  # Script de descriptografia
│── teste.txt     # Arquivo de teste
│── README.md     # Documentação do projeto
```



