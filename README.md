Témakörök, amelyeket a program megtanít a diákoknak:

- szekvenciális vezérlés (egy parancsban több, egymás utáni parancsot tudunk definiálni szövegszerkesztőben magát a programkód szekvenciális futtatását teszi lehetővé)
- szelekciós vezérlés (feltételek megadása, több feltétel megadása, szövegszerkesztőben if/else if/else elágazások)
- eljárásvezérlés (függvény meghívása parancsorban, parancsok hozzáadása, szövegszerkesztőben függvények deklarálása, illetve ezek futtatása a main() függvénnyel)
- ismétléses vezérlések (loop {}, while <feltétel> {}, for <iterációs változó> in <tartomány(elsődlegesen egész számok)>, goto/jump (ugrás a függvényen belül egy deklarált helyre))

#########################################################################################################################################################
# DOKUMENTÁCIÓ
# DOCUMENTATION
#########################################################################################################################################################

Parancsok:
Commands:

- elore(pixelek száma, amivel előre kell mennie a teknősnek)
- forward(number of pixels that need to be travelled by the turtle)
# Aliases: e(), elore(), f(), forward()

- megfordul(szög megadása fokban, megadható radiánban is a "radian" szóval, konstansok is megadhatóak pl. PI) --oramutato/--!oramutato (az --oramutato/--!oramutato flag specifikálja,
  hogy milyen irányban legyen számolva a szög, ha nincs ez a parancshoz hozzárendelve, akkor az óramutató járásának megfelelő irányban számolja a szöget a program)
- rotate(angle in degrees, it can be supplied as radian wih the "radian" word, constants are supported e.g. PI) --clockwise/--!clockwise (these flags are used to scify which way are we measuring the angles)
# Aliases: m(), megf(), megfordul(), r(), rot(), rotate()
# Flags: --cw, --!cw, --clockwise, --!clockwise --om, --!om, --oramutato, --!oramutato, 

Vezérlések:
Execution controls:

- ha(boolean algebrai kifejezés - <, >, <=, >=, ==, !=, ! és aritmettikai kifejezések (+, -, *, /)) {parancsok}
- if(boolean algebraic expressions - <, >, <=, >=, ==, !=, ! and arithmetic expressions (+, -, *, /)) {commands}
# Aliases: if() {}, ha() {}

- ismetles(ettől, addig (exkluzív határ - megadott SZÁM ELŐTTI SZÁMIG megy) / =addig(inkluzív határ - megadott SZÁMIG megy)) {parancsok}
- repeat(from, to (exclusive boundary - it goes until it hits the NUMBER BEFORE THE SPECIFIED number ) / =to(inclusive boundary - it goes until the SPECIFIED number)) {commands}
# Aliases: i() {}, ism() {}, ismetles() {}, r() {}, rep() {}, repeat() {}, for() {}

- ismetles_eddig(feltétel - ha() - ameddig igaz értékű a feltétel, addig ismétlődik a ciklus) {parancsok}
- repeat_until(statement / requirement - if() - the loop executes if the statement is true) {commands}
# Aliases: i_e() {}, ism_e() {}, ismetles_eddig() {}, r_u() {}, rep_u() {}, repeat_until() {}, while() {}
