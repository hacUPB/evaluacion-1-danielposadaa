
In this directory, you should write the program `wcat.c` and compile it into
the binary `wcat` (e.g., `gcc -o wcat wcat.c -Wall -Werror`).

After doing so, you can run the tests from this directory by running the
`test-wcat.sh` script. If all goes well, you will see:

```sh

<h1>EVALUACIÓN 1</h1>

1.Cree una carpeta en la cual pudiera clonar el git con sus diferentes archivos.
2.Modifique el archivo wcat.c.
3.Le tome foto y le cree un commit explicando los diferentes pasos que realize.
4.Luego modifique el archivo README.md
5.Adicione un titulo un texto corto, una imagen, un hipervinculo, y los respectivo comandos que utilize.

<img src="img/linux.jpg" alt="">
<a href="https://github.com/github">Nueva pagina</a>

Comandos git que utilize:
ls
cd Documents/
mkdir Parcial1
cd Parcial1/
git clone https://github.com/hacUPB/evaluacion-1-danielposadaa.git
ls
cd evaluacion-1-danielposadaa/
cd dirTest/
cd project/
code .
git status
git init
git status
git add wcat.c
git status
git commit -m""
git log
git status
git add README.md
git commit -m""
git config --global user.email 
git config --global user.name 
git commit -m""
git branch -M main
git remote add origin 
git push -u origin main


prompt> ./test-wcat.sh
test 1: passed
test 2: passed
test 3: passed
test 4: passed
test 5: passed
test 6: passed
test 7: passed
prompt>
```

The `test-wcat.sh` script is just a wrapper for the `run-tests.sh` script in
the `tester` directory of this repository. This program has a few options; see
the relevant
[README](https://github.com/remzi-arpacidusseau/ostep-projects/blob/master/tester/README.md)
for details.



