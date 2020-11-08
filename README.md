# Toketeru
<img src="https://img.shields.io/npm/v/toketeru"> <img src="https://img.shields.io/github/license/K-Rintaro/Toketeru">

Toketeru is the npm package.

You can check boiling points and melting points of elements.

npm page is https://npmjs.com/toketeru

## Elements that Toketeru supports
| Name chemical element     |     Symbol   |
| ----     |    ----   |
|Helium    |        He|
|Hydrogen   |    H|
|Neon	  |      Ne	|
|Nitrogen	|        Ni	|
|Fluorine	|        F	|
|Argon	  |     Ar	|
|Oxygen	   |    O	|
|Krypton	   |    Kr	|
|Xenon	   |    Xe	|
|Radon	   |    Rn	|
|Chlorine	|       Cl	|
|Bromine	   |    Br	|
|Iodine	    |    I	|
|Phosphorus  | 	P|
|Astatine	  |      At|
|Mercury	  |     Hg|
|Sulfur	  |     S|
|Arsenic	  |     As|
|Francium  |    	Fr|
|Cesium	  |      Cs|
|Selenium  |	Se|
|Rubidium  |	Rb|
|Potassium |	 K	|
|Cadmium	  |  Cd	|
|Potassium	|K	|
|Sodium	    |    Na|
|Zinc	   |     Zn	|
|Polonium	|Po	|
|Tellurium|	Te	|
|Magnesium|	Mg	|
|Barium	  |      Ba	|
|Lithium	  |      Li|
|Strontium	|Sr	|
|Thallium|	Tl	|
|Ytterbium|	Yb	|
|Calcium	  |      Ca	|
|Bismuth  |	Bi	|
|Europium|	Eu	|
|Thulium |	Tm	|
|Radium  |	Ra|
|Lead	|        Pb |
|Antimony|	Sb|
|Samarium|	Sm	|
|Manganese|	Mn|
|Indium	  |       In	|
|Silver     | 	Ag	|
|Tin       |  	        Sn	|
|Silicon	   |     Si	|
|Gallium	   |     Ga	|
|Aluminum|	Al	|
|Erbium	  |      Er	|
|Boron	 |       B	|
|Dysprosium|	Dy	|
|Copper	  |      Cu|
|Americium	|Am|
|Chromium	|Cr	|
|Holmium|	Ho|
|Nickel	  |      Ni|
|Iron	  |              Fe	|
|Gold	  |      Au	|
|Germanium|	Ge	|
|Scandium|	Sc	|
|Cobalt	  |      Co	|
|Palladium|	Pd	|
|Beryllium	 |       Be   |        
|Promethium	 |       Pm|
|Terbium	     |           Tb|
|Praseodymium|	Pr	|
|Neodymium	  |      Nd	|
|Actinium	  |      Ac	|
|Gadolinium|	Gd	|
|Plutonium	|Pu	|
|Cerium	   |     Ce	|
|Titanium|	Ti	|
|Lutetium|	Lu	|
|Yttrium	 |       Y	|
|Vanadium|	V	|
|Lanthanum	|La	|
|Rhodium	|Rh	|
|Uranium	   |     U	| 
|Platinum|	Pt	|
|Ruthenium|	Ru	|
|Neptunium|	Np	|
|Zirconium|	Zr	|
|Iridium	  |      Ir	|
|Molybdenum|	Mo	|
|Thorium	   |     Th	|
|Carbon	   |     C	|
|Technetium|	Tc	|
|Niobium	 |       Nb	|
|Osmium	 |       Os|
|Hafnium  |	Hf	|
|Tantalum|	Ta	|
|Rhenium	|Re|	
|Tungsten	|W	|

## Install
```
$ npm install toketeru
```

## Usage
```js
const toketeru = require('toketeru');
```
You can check boiling points and melting points from Symbol   (degrees celsius).
```js
var test = toketeru.Au("boil")
console.log(test)
// 2807

var test2 = toketeru.Fe("melt")
console.log(test2)
// 1535
```
You can check state of matter, too (degrees celsius).
```js
var test3 = toketeru.Ca(-100)
console.log(test3)
//solid

var test4 = toketeru.Ti(3287)
console.log(test4)
//liquid & gas
```

## License
This package is licensed under the MIT License.
