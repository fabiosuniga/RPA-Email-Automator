# 🤖 RPA Email Automator (PyAutoGUI)

Este projeto é um script de Automação Robótica de Processos (RPA) desenvolvido em Python. Ele simula a interação física de um usuário com o computador para automatizar o envio de uma atividade em PDF por e-mail, utilizando a interface web do Gmail. 

O código foi estruturado e convertido para um executável autônomo (`.exe`), permitindo que a rotina inteira seja disparada com apenas dois cliques direto do desktop.

## 🎯 O que o robô faz?
Quando executado, o script toma o controle do mouse e do teclado para realizar a seguinte sequência de ações:
1. Localiza, clica e copia um arquivo PDF específico na Área de Trabalho.
2. Abre o navegador (Google Chrome) e maximiza a janela.
3. Acessa o Gmail através da barra de endereços.
4. Clica em "Novo E-mail", preenche o destinatário e o assunto ("Atividade para entrega").
5. Cola o arquivo como anexo, aguarda o upload e clica em "Enviar".

## 🛠️ Tecnologias e Bibliotecas
* **Python 3**
* **PyAutoGUI:** Para mapeamento de tela (coordenadas) e controle de eventos de mouse e teclado.
* **Time:** Para gerenciar os intervalos de espera (`sleep`) entre as ações físicas e o tempo de carregamento das páginas web.
* **PyInstaller:** Para empacotar o script e suas dependências em um único arquivo `.exe`.

## ⚠️ Nota Técnica (Disclaimer)
Este projeto utiliza cliques baseados em **coordenadas absolutas de tela (x, y)**. Isso significa que ele foi calibrado especificamente para a minha resolução de monitor e para a organização de ícones da minha Área de Trabalho.

## Vídeo em execução
https://github.com/user-attachments/assets/69d0a942-b04e-415f-827f-4649f8eaa4a6



