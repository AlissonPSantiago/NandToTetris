# NandToTetris
- I take the course on [coursera](https://www.coursera.org/learn/build-a-computer/home/week/1), you can find all the course resources
on its [website](https://www.nand2tetris.org/).




O projeto Nand2Tetris é um curso e uma série de materiais didáticos que visa ensinar os fundamentos da ciência da computação e engenharia de computadores de uma maneira prática e envolvente. O projeto foi desenvolvido por Noam Nisan e Shimon Schocken e é baseado em seu livro "The Elements of Computing Systems: Building a Modern Computer from First Principles" (Os Elementos dos Sistemas de Computação: Construindo um Computador Moderno a partir dos Primeiros Princípios).

O curso Nand2Tetris é dividido em duas partes. A primeira parte foca no projeto e construção de um computador baseado em hardware, começando do zero com a porta lógica NAND, um componente básico da eletrônica digital. Os alunos aprendem sobre circuitos lógicos, memória, aritmética, e processadores, e gradualmente constroem um computador funcional chamado "Hack".

A segunda parte do curso aborda a construção de um sistema de software completo para o computador Hack. Os alunos desenvolvem um assembler, um sistema operacional, um compilador e uma linguagem de programação de alto nível chamada "Jack". Além disso, os alunos constroem aplicações gráficas e interativas usando a linguagem Jack.

O projeto Nand2Tetris é uma experiência de aprendizado única que desafia os alunos a construírem um computador moderno a partir dos princípios básicos. Ao longo do curso, os participantes adquirem habilidades importantes em ciência da computação e engenharia de computadores, enquanto são apresentados a conceitos fundamentais, como arquitetura de computadores, linguagens de programação e sistemas operacionais.

Foram construidas a partir de portas NAND as portas lógicas:

- NOT (Inversor)
- AND (E)
- OR (OU)
- NAND (Não E)
- NOR (Não OU)
- XOR (OU Exclusivo)
- XNOR (Não OU Exclusivo)
- MUX (Multiplexador)
- DMUX (Demultiplexador)
- Half Adder (Somador de meio bit): É um circuito que realiza a adição de dois bits, gerando uma soma de um bit e um bit de carry-out (vai um). Ele pode ser construído usando portas XOR e AND.
- Full Adder (Somador completo): É um circuito que realiza a adição de três bits (dois bits de entrada e um bit de carry-in) e gera uma soma de um bit e um bit de carry-out. Pode ser construído a partir de dois somadores de meio bit e uma porta OR.
- ALU (Unidade Lógico-Aritmética): É um componente essencial do processador que realiza operações aritméticas e lógicas em dados binários. A ALU é construída usando várias portas lógicas, somadores e multiplexadores.
- Registradores: São componentes de memória que armazenam valores binários temporariamente durante a execução de um programa. Registradores são construídos usando flip-flops, que são circuitos sequenciais construídos a partir de portas lógicas.
- Memória (RAM): A memória RAM (Random Access Memory) é um componente crucial para armazenar dados e instruções de programas. No projeto Nand2Tetris, a RAM é construída a partir de unidades de memória menores chamadas "registros de memória" e multiplexadores.
- CPU (Unidade Central de Processamento): A CPU é o cérebro do computador e é responsável por executar instruções de programas. No projeto Nand2Tetris, a CPU é construída a partir de vários componentes, incluindo a ALU, registradores e circuitos de controle.
- Controlador e caminho de dados: Esses componentes são responsáveis por coordenar a operação da CPU e gerenciar o fluxo de dados entre os diferentes componentes do computador. Eles são construídos a partir de várias portas lógicas e circuitos combinacionais e sequenciais.

