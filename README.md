
# Estudos de Comando NASM


![NASM](https://img.shields.io/badge/nasm-000000)




### Olá! Eu sou Thiago Sanches 😐,  sou iniciante na área de T.I 💻


💰 #Ajude o projeto Upgrade no PC para realização de conteúdo no YOUTUBE

💰 #Chave PIX do projeto:
6ba1c342-ccdd-4896-a1d3-d50cf0925

🚀 #Minhas redes sociais

[![MEU SITE](https://img.shields.io/badge/website-000000?style=for-the-badge&logo=About.me&logoColor=white)](https://sanchessky.github.io/meu-site/)
[![Linkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/thiagosanches07)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/espetacular_sanches7/)








### Primeiros Comandos


* Programa Hello World

```Assembly
global _start 
    section .text
    _start:
        mov rax,1
        mov rdi,1
        mov rsi,message
        mov rdx,13
        syscall 
        mov rax,60
        xor rdi,rdi
        syscall

        section .data
        massage:db "Hello,World',10
```

