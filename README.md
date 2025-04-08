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


- tollszin(piros szín megadása 0-255, zöld szín megadása 0-255, kék szín megadása 0-255, alfa csatorna megadása 0-255) - megadja a vonal színét RGBA színként pl.(0,0,0,255) - fekete, (255,255,255,255) - fehér. (255,255,255,255) - átlátszó
- pencolor(red channel 0-255, green channel 0-255, blue channel 0-255, alpha channel 0-255) - specifies the color of the line e.g. (0,0,0,255) - black, (255,255,255,255) - white. (255,255,255,255) - transparent
#### Aliases: tsz(), tollszin(), szin(), pc(), pencolor(), color()


- tollvastagsag(toll vastagsága pixelekben, minnél nagyobb, annál vastagabb a vonal)
- penwidth(width of the pen in pixels, greater the value the thicker the line left behind)
#### Aliases: tv(), tollvastagsag(), vastagsag(), pw(), penwidth(), width()


- tollfel - felveszi a tollat a vászonról, így a teknős nem hagy maga után nyomot
- penup - the turtle lifts up it's pen from the canvas so it doesn't paints it's path on the canvas
#### Aliases: tf, tollfel, pu, penup


- tollle - lerakja a tollat a vászonra, így a teknős újra nyomot hagy
- pendown - the turtle puts down it's pen so it leaves it's path behind

#### Aliases: tl, tollle, pd, pendown

## Vezérlések - Execution controls:

- ha(boolean algebrai kifejezés - <, >, <=, >=, ==, !=, ! és aritmetikai kifejezések (+, -, *, /)) {parancsok}
- if(boolean algebraic expressions - <, >, <=, >=, ==, !=, ! and arithmetic expressions (+, -, *, /)) {commands}
#### Aliases: if() {}, ha() {}

- ismetles(ettől, addig (exkluzív határ - megadott SZÁM ELŐTTI SZÁMIG megy) / =addig(inkluzív határ - megadott SZÁMIG megy)) {parancsok}
- repeat(from, to (exclusive boundary - it goes until it hits the NUMBER BEFORE THE SPECIFIED number ) / =to(inclusive boundary - it goes until the SPECIFIED number)) {commands}
#### Aliases: i() {}, ism() {}, ismetles() {}, r() {}, rep() {}, repeat() {}, for() {}

- ismetles_eddig(feltétel - ha() - ameddig igaz értékű a feltétel, addig ismétlődik a ciklus) {parancsok}
- repeat_until(statement / requirement - if() - the loop executes if the statement is true) {commands}
#### Aliases: i_e() {}, ism_e() {}, ismetles_eddig() {}, r_u() {}, rep_u() {}, repeat_until() {}, while() {}
