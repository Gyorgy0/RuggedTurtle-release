# Témakörök, amelyeket a program megtanít a diákoknak:

- szekvenciális vezérlés (több, egymás utáni parancsot tudunk definiálni szövegszerkesztőben magát a programkód szekvenciális futtatását teszi lehetővé)
- változók deklarálása, és alapvető aritmetikai műveletek támogatása
- terminál alapvető parancsai (clear(), print(), eval())
- ismétléses vezérlések (for(változó, tartomány(elsődlegesen egész számok)) {}

# DOKUMENTÁCIÓ - DOCUMENTATION

## Változók - Variables:
-   <változó_neve> = változó értéke (megadható más változó is, plusz aritmetikai műveletek (+, -, *, /, :, %))
-   <variable_name> = variable value (it can be an another variable, and it supports +, -, *, /, :, % )


## Aritmetikai műveletek - arithmetic operations:
- '+' - összeadás (összead két számot, vagy változót)
-     - addition (it adds two numbers or variables together)

- '-' - kivonás (kivon egy számot egy másik számból, vagy változót)
-     - subtraction (it subtracts a number from another number or variable)

- '*' - szorzás (összeszoroz egy számot egy másik számmal, vagy változót)
-     - multiplication (it multiplies a number with another number or variable)

- '/' - teljes osztás (eloszt egy számot egy másik számmal, vagy változóval, nem feltétlen egész szám az eredmény)
-     - full division (it divides a number with another number or variable, it doesn't neccesarily produce an integer)

- ':' - egész osztás (eloszt egy számot egy másik számmal, vagy változóval, egész szám az eredmény)
-     - integer division (it divides a number with another number or variable, it produces an integer)

- '%' - maradékos osztás (eloszt egy számot egy másik számmal, vagy változóval, ennek az osztásnak a maradékát adja vissza)
-     - remainder division (it divides a number with another number or variable, it gives back the remainder)


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


- kiertekeles(<változó>) - egyszerűsíti és kiírja a megadott változó értékét
- evaluate(<variable>) - simplifies and prints out the value of the specified variable


#### Aliases: kier(), kiertekeles(), kiszamolas(), eval(), calc(), calculate(), evaluate()


- kiiratas(<változó>) - kiírja a megadott változót
- print(<variable>) - prints out the specified variable


#### Aliases: ki(), kiir(), kiiratas(), print()


- torol - kitörli a terminál kimenetét
- clear - clears the terminal output


#### Aliases: trl, torol, clr, clear


- alaphelyzet - alaphelyzetbe rakja az alkalmazást
- reset - resets the application


#### Aliases: trl, torol, clr, clear


- segitseg - kiírja a parancsokat és azok használatát
- help - prints out the commands and their usage


#### Aliases: ?, segitseg, help


## Vezérlések - Execution controls:

- ismetles(változó, ettől, addig (exkluzív határ - megadott SZÁM ELŐTTI SZÁMIG megy)) {parancsok}
- repeat(variable, from, to (exclusive boundary - it goes until it hits the NUMBER BEFORE THE SPECIFIED number )) {commands}
#### Aliases: i() {}, ism() {}, ismetles() {}, r() {}, rep() {}, repeat() {}, for() {}
