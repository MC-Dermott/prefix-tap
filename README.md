# Prefix Tap

A quick-fire "hit the button" game for the National 5 Physics scientific prefixes, from nano to giga.
Built on the same engine as `Maths/FactTap`.

Open `index.html` in any browser. It's a single file, so there's no install or server.

| Symbol | Name  | Power of ten | Number          |
|--------|-------|--------------|-----------------|
| G      | giga  | ×10⁹         | 1 000 000 000   |
| M      | mega  | ×10⁶         | 1 000 000       |
| k      | kilo  | ×10³         | 1000            |
| m      | milli | ×10⁻³        | 0.001           |
| μ      | micro | ×10⁻⁶        | 0.000 001       |
| n      | nano  | ×10⁻⁹        | 0.000 000 001   |

Centi and deci are included as an optional extra group, off by default.

Question types convert between any two of symbol, power of ten and number, in either direction
(six types, all on by default). Name → symbol and symbol → name are also available.

Wrong answers are re-asked three questions later. The results screen lists the prefixes a student
got wrong. Best scores are saved in the browser for each combination of settings.

To change the prefixes, edit `PREFIX_ITEMS` in `index.html`.
