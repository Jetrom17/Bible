![search](https://github.com/Jetrom17/Bible/assets/72875404/920fab7d-13c6-4c68-b79d-f5acd404386f)

Você pode pesquisar de forma simples um trecho da bíblia. O livro contém o idioma `portuguese` chamado de `AA.txt`. AA = Almeida Atualizada, versão do autor. Praticidade e leveza, leva ao usuário a pesquisar uma passagem bíblica escolhida. Tudo isso acontece no `client`, isto é, sem necessidade de `api` ou uso da internet.
> Fonte da versão AA: https://bible4u.net/en/download#pt

Requisitos:

- Terminal com Shell (bash - padrão).
- Amber. (Linguagem de programação para Bash).
- BC. (Requisito para Amber).
- Curl.
- Git.
- Sudo (Caso use um emulador pelo Termux).
- WSL 2 (Caso do Windows).

[Instalação: Linux ou Mac]

```bash
sudo apt install bc -y && curl -s "https://raw.githubusercontent.com/Ph0enixKM/AmberNative/master/setup/install.sh" | bash && git clone https://gist.github.com/60f312ba91cb0c2fd2b06f72a7dd3d38.git && mv 60f312ba91cb0c2fd2b06f72a7dd3d38 search_bible && cd search_bible && clear && ls && echo "Execute amber sc.ab"
```
> Instalação automática.

[Instalação não suportada para Windows diretamente]

- Etapa 1.
```bash
sudo apt install curl bc
sudo mkdir /opt /usr/local/bin
```
- Etapa 2.
```bash
git clone https://gist.github.com/60f312ba91cb0c2fd2b06f72a7dd3d38.git && mv 60f312ba91cb0c2fd2b06f72a7dd3d38 search_bible && cd search_bible && clear && ls && echo "Execute amber sc.ab"
```
