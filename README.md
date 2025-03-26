# Témakörök, amelyeket a program megtanít a diákoknak:

- szekvenciális vezérlés (több, egymás utáni parancsot tudunk definiálni szövegszerkesztőben magát a programkód szekvenciális futtatását teszi lehetővé)
- szelekciós vezérlés (feltételek megadása, több feltétel megadása, szövegszerkesztőben if / else if / else elágazások)
- eljárásvezérlés (függvény meghívása parancsorban, parancsok hozzáadása, szövegszerkesztőben függvények deklarálása, illetve ezek futtatása a main() függvénnyel)
- ismétléses vezérlések (loop {}, while(feltétel) {}, for(tartomány(elsődlegesen egész számok)) {}

# DOKUMENTÁCIÓ - DOCUMENTATION

## Parancsok - Commands:

- elore(pixelek száma, amivel előre kell mennie a teknősnek)
- forward(number of pixels that need to be travelled by the turtle)
#### Aliases: e(), elore(), f(), forward()

- jobbra(szög megadása fokban, hogy mennyit forduljon el a karakter jobb oldalára 0-360)
- right(angle in degrees, it specifies how much it needs to rotate to the characters right side 0-360)
#### Aliases: j(), jobb(), jobbra(), r(), right()


- balra(szög megadása fokban, hogy mennyit forduljon el a karakter bal oldalára 0-360)
- left(angle in degrees, it specifies how much it needs to rotate to the characters left side 0-360)
#### Aliases: b(), bal(), balra(), l(), left()

## Vezérlések - Execution controls:

- ha(boolean algebrai kifejezés - <, >, <=, >=, ==, !=, ! és aritmettikai kifejezések (+, -, *, /)) {parancsok}
- if(boolean algebraic expressions - <, >, <=, >=, ==, !=, ! and arithmetic expressions (+, -, *, /)) {commands}
#### Aliases: if() {}, ha() {}

- ismetles(ettől, addig (exkluzív határ - megadott SZÁM ELŐTTI SZÁMIG megy) / =addig(inkluzív határ - megadott SZÁMIG megy)) {parancsok}
- repeat(from, to (exclusive boundary - it goes until it hits the NUMBER BEFORE THE SPECIFIED number ) / =to(inclusive boundary - it goes until the SPECIFIED number)) {commands}
#### Aliases: i() {}, ism() {}, ismetles() {}, r() {}, rep() {}, repeat() {}, for() {}

- ismetles_eddig(feltétel - ha() - ameddig igaz értékű a feltétel, addig ismétlődik a ciklus) {parancsok}
- repeat_until(statement / requirement - if() - the loop executes if the statement is true) {commands}
#### Aliases: i_e() {}, ism_e() {}, ismetles_eddig() {}, r_u() {}, rep_u() {}, repeat_until() {}, while() {}
