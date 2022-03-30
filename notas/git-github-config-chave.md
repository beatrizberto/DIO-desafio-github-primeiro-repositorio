# Configurar chave SSH Github/Git

1. Instalar Git com Git Bash
2. Git Bash> ssh-keygen -t ed25519 -c + [EMAIL] > Git mostra o local
4. Navegar até a pasta onde está a chave (CD c/users/xxxx/.ssh)
5. cat d_ed25519.pub > exibe infos da chave pública > copiar
6. GitHub > setting > SSH > addnew > colar infos da chave pública e dar nome
7. GitBash: eval $(ssh-agent -s) > Git retorna agent pid XXXX
8. ssh-add id_ed25519 (chave privada)

Pronto! Só começar a clonar.