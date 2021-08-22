# Roteiro- instalação debian 10
## Passo a passo de como instalar a distro Debian
1. Acesse o site https://cdimage.debian.org/debian-cd/project/build/10.10.0/ e selecione a versão que condiz com seu processador
2. Após o download da iso ser concluido abra o virtual box
3. Clique em novo, escreva um nome e mude o tipo para linux e a versão debian x64
4. Clique em próximo, coloque a ram em 4096mb
5. Continue no processo de instalação, crie o HD com pelo menos 20gbs e clique em criar
6. Após a maquina virtual ser criada vá nas configurações dela e selecione a imagem virtual do debian que você fez o download e clique em ok
7. Agora clique em iniciar e ligue a máquina virtual
8. Selecione a forma que você prefere que a instalação ocorra
9. Nos próximos passos você irá
   - Selecionar a linguagem da instalação
   - Selecionar sua região
   - Selecionar o local da linguagem selecionada
   - Selecionar a configuração do teclado
10. Depois disso, clique em continue e aguarde o instalador carregar os componentes de instalação da ISO
11. No proximo passo selecione sua interface de rede primária, caso tenha mais de uma instalada
12. Agora defina o hostname e o dominio, pode deixar em branco e clique em continue
13. Defina a senha do usuário root e também defina o nome do usuário não-root
14. Clique em continue e selecione a timezone
15. No particionamento de disco selecione "Guided - use entire disk and set up LVM"
16. Selecione a partição
17. Agora selecione o esquema de particionamento, vamos selecionar usar o disco todo
18. Escreva as mudanças no disco, verifique as configs do disco e pressione continue para instalar o debian 10
19. Uma vez que a instalação termina, você será questionado para configurar o fornecedor de pacotes
20. Deixe o mirror padrão da debian para ser usado pelo gerenciador de pacotes
21. Na proxima etapa selecione o que deve ser instalado na distro
22. Vamos selecionar "web server, ssh server e standard system utilities"
23. Assim que a instalação de pacotes esteja concluida, você é questionado se deseja instalar o grub, clique em em sim e continue
24. após isso a instalação estará concluida
## Prova da instalação concluida com sucesso
![image](https://user-images.githubusercontent.com/54211710/130354546-82570795-a9b4-4048-933c-5dc53f0e8d29.png)
