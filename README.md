# [Curso](https://www.youtube.com/watch?v=SZMIL87CyVE&list=PLuf64C8sPVT9L452PqdyYCNslctvCMs_n)
# Anotações e Dicas sobre o GNU e o Kernel Linux, e derivados

# GNU (Sistema operacional) <br>
- 1983, 100% softwares livres
- 1991 -> Kernel Linux / Hurd
- Componentes:
- Bootloader, kernel, bibliotecas
- [Distros endossadas](https://www.gnu.org/distros/free-distros.pt-br.html)

## História <br>

O Richard Stallman, pesquisador do MIT, anunciou em 1983 o projeto GNU (GNU's Not UNIX!), tendo como missão construir um software completo, compatível com UNIX, mas não é UNIX, e livremente para qualquer pessoa que queira usar <br>
O objetivo era construir um kernel completo, com todos os utilitários necessários para desenvolver programas em C, e posteriormente seriam adicionados um editor de texto, planilhas, e outras coisas, incluindo documentação, além de ser capaz de executar programas UNIX <br>
Richard Stallman começou a trabalhar no Laboratório de Inteligência Artificial do MIT em 1971. Ele já tinha experimentado os prejuízos de um acordo de confidencialidade quando não teve acesso ao código fonte do programa que controlava a impressora do laboratório para realizar melhorias no funcionamento dela <br>
Desenvolver todo o sistema é um projeto muito grande, para facilitar, Richard Stallman decidiu adaptar e usar partes existentes de software livre. Inicialmente ele utilizou o TeX como formatador de textos e o X Window System, como sistema de janelas <br>
O GNU inclui programas que não são software externos, programas que foram desenvolvidos por outras pessoas, ou projetos, mas que podem ser utilizados, por serem software livre <br>
Em 1987, Andrew Tanenbaum criou o MINIX, desenvolvido para o microcomputador IBM PC e IBM PC/AT, na Vrije Universiteit Amsterdam, como exemplo prático dos princípios transmitidos em seu livro. 12.000 linhas do código fonte C do kernel, gerenciador de memória e sistema de arquivos do MINIX 1.0 estão impressas no livro <br>
O GNU é um sistema operacional composto exclusivamente por softwares livres <br>
Distribuição é um conjunto de softwares (Distribuição do sistema operacional) <br>
O jeito que o sistema deve ser chamado é "GNU", também pode ser chamado de "GNU Linux" para dar os devidos créditos à Torvalds <br>

# Linux (Kernel) <br>
- Lançamento -> 1991
- Licenciado GPL 2 (GNU Public License verão 2) -> 1992
- Inclusão de Softwares não-livres (blobs) -> 1996
- Linux Libre -> 2006
- Separação da árvore -> 2008
- Linux Libre *GNU -> 2012

Em 1991, Linus Torvals, um estudante Finalndês de ciência da computação anunciou uma versão prévia de um kernel substituto para o MINIX; Atualmente ele continua coordenando o trabalho de várias centenas de programadores <br>
Linux é um kernel, qualquer sistema operacional tem um kernel, ela é a parte fundamental de um sistema operacional (O linux tem a licensa GPL 2) <br>
O kernel linux se mostrou muito promissor, e foi incorporado às distribuições, tendo assim um sistema operacional completo e funcional, contendo apenas softwares livres <br>
O linux é uma das partes que compõem o sistema operacional GNU <br>

## GNU/Linux <br>
O HURD, kernel do original GNU, não chegou a ficar pronto (e não se sabe se ficará um dia). Felizmente, o linux é compatível com o UNIX. A combinação do linux com os softwares do projeto GNU resultou em um sistema operacional livre completo. Assim a correta denominação é GNU/Linux, para expressar sua composição como a combinação do sistema GNU, e do núcleo (kernel) Linux <br>

# Debian <br>

<img style="center" src="https://i.pinimg.com/originals/b4/f8/85/b4f885be4e7f0688c968b5ff7ed91385.png" alt="Debain logo">

- Contrato Social

> O debian permanecerá 100% livre <br> 

> Nós iremos retribuir à comunidade softwares livres <br>

> Nós não escondemos problemas, tudo é aberto <br>

> Nossas prioridades são nossos usuários e o software livre <br>

## [DSFG](https://www.debian.org/social_contract) (Debian Free Software Guidelines) <br>
Definição própria do que o Debian considera software livre, contendo 10 itens em sua lista <br>

1- Redistribuição Livre <br>
- Ele tem de ser livre para ser redistribuído <br>

2- Código Fonte <br>
- Para poder entrar no debian, tem de ser permitido ou distribuir o código fonte, e distribuir a versão compilada (Código fonte E sua versão já compilada. Não basta só o código fonte) <br>

3- Trabalhos Derivádos <br>
- A licença deve permitir modificações e trabalhos derivados, e deve permitir que eles sejam distribuídos sob os mesmos termos da licença do software original. <br>

4- Integridade do Código Fonte do Autor <br>
- Se por acaso, o autor não quiser ser distribuído e modificado, ele tem que permitir que o software seja distribuído na versão original, e que também seja distribuídos as correções/modificações <br>

5- Não pode haver discriminação contra pessoas ou grupos <br>

6- Não pode haver discriminação contra fins de utilização <br>
- O software tem que ser usado para qualquer finalidade, independente do que seja <br>

7- Distribuição de Licensa <br>
- A liberdade não para no debian, ela continua adiante <br>

8- A licensa não pode ser específica pro Debian <br>
- Os direitos associados ao programa não devem depender do programa ser parte de um sistema Debian <br>

9- A licensa não deve contaminar outros softwares <br>
- A licença não deve impor restrições a outro software distribuído junto com o software licenciado. Por exemplo, a licença não deve exigir que todos os outros programas distribuídos no mesmo meio sejam software livre <br>

10- Licenças exemplo: <br>
- As licenças GPL, BSD e Artistic são exemplos de licenças que consideramos gratuitas <br>

## Seções <br>
Os pacotes que entram no debian, ficam distribuidos em seções diferentes <br>
- main -> A seção principal (exclusivamente softwares livres) <br>
A seção main é a seção que o Debian considera ser o Debian <br>

- contrib -> Também vão haverão softwares livres, mas também podem haver softwares livres cuja finalidade é carregar softwares que não são livres (Ex: FlashPlayer) <br>

- non-free -> Softwares que não são livres <br>

## Branches (Ramificações / versões) <br>
Uma versão do Debian quando é lançada, significa que ela tornou/considerou uma de suas versões como sendo estável (stable) <br>
Versão recomendada a ser usada por servidores, serviços, desktops corporativos, etc <br>

<img style="center" src="https://camo.githubusercontent.com/6f82308782d1adabf573fa32ac869109088844efa4e52ec413d57179febe7a3d/68747470733a2f2f63646e2e646973636f72646170702e636f6d2f6174746163686d656e74732f3735393434383737303830323438333230302f3932383338313932373032313437373839382f756e6b6e6f776e2e706e67" alt="Branches">

**old-stable** -> já foi estável <br>
**stable** -> é estável <br>
**testing** -> estágio de teste <br>
**unstable(sid)** -> não é estável <br>
**experimental** -> quando um mantenedor de pacotes deseja fazer testes <br>

## Arquiteturas <br>
- Oficiais: <br>
amd64, arm64, armel, armhf, i386, mips64el, mipsel, ppc64el, s390x <br>

- Ports: (Em andamento, não oficiais mas já podem ser utilizadas) <br>
m68k, powerpcspe, riscv64, sh4, sparc64, x32

- Não-Linux: (Port para distros que não usam o kernel linux) <br>
hurd-i386, kfreebsd-amd64, kfreebsd-i386 <br>

## Versões:
A versão mais atual, em 2022 -> Debian 11: 11.2 released (Codinome: Bullseye)

## Mitos:
Em quase todas as vezes, o Debian que você usa, não é o mesmo que eu uso, pois na hora da instalação temos a capacidade de decidir o que queremos dentro do nossos sistema Debian <br>

O debian é a segunda distribuição mais antiga, a mais antiga é o slackware (1 mês mais antiga) <br>
O debian não é endossado pela Free Software Foundation, porém o Debian é a única distro que distribui o kernel sem logs <br>
O debian pode ser utilizado sem se usar o Linux, tendo a ideia de ser um sistema universal, e por isso ele está a disposição do maior número de arquiteturas <br>
