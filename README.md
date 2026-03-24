#  Projetos de Cibersegurança — Criptografia + Keylogger (Lab Educacional)

Este repositório reúne dois projetos práticos desenvolvidos como parte de um desafio do curso de Cibersegurança, com foco em técnicas de segurança ofensiva e proteção de dados.

---

##  Sobre o Projeto

O objetivo deste laboratório é demonstrar, em ambiente controlado, conceitos fundamentais de cibersegurança, incluindo:

* Criptografia de arquivos (simulação de ransomware)
* Captura de entradas via keylogger
* Exfiltração de dados via e-mail (simulada)

**Importante:** Todos os testes foram realizados em ambiente controlado para fins exclusivamente educacionais.

---

##  Objetivos

* Compreender o funcionamento de ataques reais
* Praticar técnicas de segurança ofensiva (Pentest)
* Entender vulnerabilidades em sistemas
* Demonstrar importância de proteção de dados e senhas
* Desenvolver pensamento crítico em segurança da informação

---

##  Projetos incluídos

###  1. Malware Criptográfico (Ransomware Simulado)

Projeto responsável por:

* Gerar chave de criptografia
* Criptografar arquivos de um diretório
* Simular comportamento de ransomware
* Restaurar arquivos (via script de descriptografia)

📁 Pasta: `malware_cripto/`

---

###  2. Keylogger com Envio de E-mail

Projeto responsável por:

* Capturar teclas digitadas
* Armazenar logs localmente
* Enviar dados por e-mail periodicamente

📁 Pasta: `keylogger/`

---

##  Tecnologias Utilizadas

* Python 3
* Biblioteca `cryptography` (Fernet)
* Biblioteca `pynput`
* `smtplib` (envio de e-mail)
* Sistema operacional: Windows / Kali Linux

---

## ▶ Como Executar

###  1. Clonar o repositório

```bash
git clone https://github.com/seu-usuario/projetos-ciber.git
cd projetos-ciber
```

---

###  2. Criar ambiente virtual (recomendado)

```bash
python -m venv venv
venv\Scripts\activate   # Windows
```

---

###  3. Instalar dependências

```bash
pip install cryptography pynput
```

---

###  4. Executar projetos

####  Malware Criptográfico

```bash
cd malware_cripto
python ransomware.py
```

####  Descriptografia

```bash
python descriptografar.py
```

---

####  Keylogger

```bash
cd ../keylogger
python keylogger.py
```

---

##  Aprendizados

Durante o desenvolvimento deste projeto, foram adquiridos conhecimentos em:

* Criptografia simétrica (Fernet)
* Manipulação de arquivos em Python
* Captura de eventos do teclado
* Automação de envio de e-mails
* Estruturação de projetos
* Uso de Git e versionamento
* Boas práticas de segurança

---

##  Aviso

Este projeto foi desenvolvido exclusivamente para fins educacionais como parte de um curso de Cibersegurança.

🚫 Não utilize essas técnicas em sistemas reais sem autorização.
🚫 O uso indevido pode ser considerado crime.

---

##  Boas Práticas Aplicadas

* Uso de ambiente controlado
* Separação de arquivos sensíveis
* Uso de `.gitignore` para proteção de dados

---

## 👨 Autor

Luiz Antônio Azevedo

---

## ⭐ Considerações Finais

Este projeto representa a aplicação prática de conceitos fundamentais de cibersegurança, sendo uma base importante para evolução na área de Segurança da Informação.

---
