# Configurar chave SSH Github/Git

1. Abrir GIT Bash
2. ssh-keygib -t ed255919 -c [EMAIL]
3. Git mostra o local
4. Definir senha
5. GIT retorna local e fingerprint etc das chaves pública & privada
6. Navegar até a pasta: CD c/users/xxxx/.ssh
7. DIR
8. cat d_ed25519.pub
9. GIT exibe chave pública - copiar
10. GitHub: addnew
11. GITBash: eval $(ssh-agent -s)
12. Git retorna: agent pid XXXX
13. LS
14. ssh-add id_ed25519
15. GIT clone + caminho ssh