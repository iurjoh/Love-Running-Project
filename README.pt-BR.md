# Love Running walkthrough

Site estático de aula de clube de corrida, com home, galeria e cadastro. Clube e encontros são conteúdo demonstrativo, não eventos atuais verificados.

[English](README.md)

## Ideia e processo

Código revisado em 01/10/2026. Walkthrough educacional baseado em material do Code Institute. Não foram encontrados planejamento datado, wireframes ou diário pessoal de design nos arquivos revisados. Registro do exercício, não história original de produto.

## Arquitetura e design

index.html contém hero, benefícios, encontros e links sociais; gallery.html/signup.html compartilham navegação e estilos. assets/css/style.css define zoom hero, colunas de galeria, formulário e breakpoints 1200/950/800px. Home/cadastro revisados carregam kits Font Awesome, não index.js da raiz. Não há backend ou banco de membros nessa estrutura.

## Preview local

```bash
python3 -m http.server 8000
```

Abra `http://localhost:8000/`. Fontes/ícones/imagens externas precisam de rede. Preview não executado nesta atualização; deploy público atual não confirmado.

## Testes e limites

Suíte automatizada não encontrada na listagem revisada da raiz. Testes de navegador/manuais não executados. Cadastro envia nome, email e preferência ao formdump externo do Code Institute, não a sistema de membros. Não envie dados pessoais reais. signup.html contém forms aninhados e atributo methor; index.html tem fechamento extra de ícones e > solto. Revise HTML, formulário, imagens/contraste, teclado e responsividade. Nenhum formulário enviado.

## Capturas

Nenhuma captura de aplicação verificada ou adicionada. Arquivos futuros datados em `docs/assets/` devem mostrar estados reais desktop/mobile, sem dados pessoais de formulário. Só adicione links após arquivos existirem, sem inventar estado funcional.

## Créditos e licença

Material de curso/template Code Institute, bibliotecas e assets mantêm direitos originais. Nenhuma licença nova. README original mantido no [apêndice em inglês](README.md#original-readme), como fonte histórica.
