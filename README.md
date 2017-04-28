## Programação concorrente

Consiste em  fazer diversas entidades em execução no computador, trabalharem juntas para resolverem um processo computacional, diminuindo processos maiores em vários processos menores e assim utilizando o máximo de recursos que o processador dispõe (threads do processador) sendo que é possível ter várias linhas de processamento de forma paralela e não uma de cada vez.

Exemplo:

* Numa linha de execução temos duas atividades a serem feitas, uma é escutar a porta 8540 e a outra é escutar a porta 60454. Se o programa desenvolvido não atentar os conceitos de programação concorrente, o processo fica travado na porta 8540 até que a mensagem chegue, conforme programado, mas com o conceito de programação concorrente é criada outra linha de execução onde as duas portas (8540 e 60454) são escutadas em paralelo e os processos não ficam travados por uma questão da atividade anterior não ter sido concluída.

---

## Multiprogramação

Quando se tem no computador vários programas instalados e tudo em uso ao mesmo tempo: player de música aberto, torrent aberto (enviando e recebendo), editor de texto aberto e copiando arquivos para um pendrive ou gravando um cd ou dvd.

O computador tem suas limitações, ele não faz tudo isso ao mesmo tempo, mesmo que aparente.
A multiprogramação faz com que várias coisas sejam executadas ao mesmo tempo, e o S.O faz com que os aplicativos dividam a memória disponível e ficam compartilhando o processador no momento que precisam do uso do processador e o S.O define as prioridades. Dependendo do processador ele consegue fazer 2, 4, 8 processos ao mesmo tempo, dependendo de quantos núcleos o processador tem mas cada processo divide cada núcleo conforme a necessidade e a determinação do S.O

#### Referências

[MAC0438 - Programação Concorrente](https://www.youtube.com/watch?v=6MBU5gdKbyA&t=533s)

[O problema dos 5 filósofos](https://www.youtube.com/watch?v=6ql4YW1LHC8&t=89s)

[Alura: Curso de Threads 1: Programação paralela em Java - Aula 1](https://www.youtube.com/watch?v=NAOkIbpsbzs&t=24s)

[Aula Threads](https://www.youtube.com/watch?v=A9h0K9lFBMQ&t=254s)

[Multiprogramação](https://www.youtube.com/watch?v=DpT9TDD45Vg&t=84s)
