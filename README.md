# Tarefa2_aula29-01
Repositório criado para versionamento da tarefa da aula  do dia 3 de fevereiro 


## Compilação e Execução

1. Certifique-se de que o SDK do Raspberry Pi Pico está configurado no seu ambiente.
2. Compile o programa utilizando a extensão **Raspberry Pi Pico Project** no VS Code:
   - Abra o projeto no VS Code, na pasta Tarefa_aula_03-02 
   - Vá até a extensão do **Raspberry pi pico project** e após importar os projetos  clique em **Compile Project** 
3. Coloque a placa em modo BOOTSEL e copie o arquivo `ws2832_1.uf2` que está na pasta build, para a BitDogLab conectado via USB.
4. Ao iniciar o serial monitor certifique-se que a opção 'Line ending' esteja com a caixa 'Nome' selecionada.


**OBS1:Ao iniciar o serial monitor o Display para de temporariamente de atualizar pois espera receber um caractere para aualização posterior**

**OBS2: Devem importar os projetos para gerar a pasta build, pois a mesma não foi inserida no repositório**

## Emulação com Wokwi

Para testar os programas sem hardware físico, você pode utilizar o **Wokwi** para emulação no VS Code:

1. Instale a extensão **Wokwi for VS Code**
3. Inicie a emulação:
   - Clique no arquivo `diagram.json` e inicie a emulação.
4. Teste o funcionamento do programa diretamente no ambiente emulado.
   
## Vídeo de demonstração no youtube 

https://youtu.be/Liiw_gezYSE?si=HI2fiTCb2FVzF0hg


## Colaboradores
- [PauloCesar53 - Paulo César de Jesus Di Lauro ] (https://github.com/PauloCesar53)
