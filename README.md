# Prefix Tap

A quick-fire "hit the button" game for the National 5 Physics scientific prefixes, from nano to giga.
Built on the same engine as `Maths/FactTap`.

Open `index.html` in any browser. It's a single file, so there's no install or server.

## Sharing with students

`streamlit_app.py` loads `index.html` into a Streamlit page, so it can be shared from streamlit.app
(which works on the school network). Deploy it on Streamlit Community Cloud from this repo with
`streamlit_app.py` as the main file. Run it locally with `streamlit run streamlit_app.py`.

| Symbol | Name  | Power of ten |
|--------|-------|--------------|
| G      | giga  | ×10⁹         |
| M      | mega  | ×10⁶         |
| k      | kilo  | ×10³         |
| m      | milli | ×10⁻³        |
| μ      | micro | ×10⁻⁶        |
| n      | nano  | ×10⁻⁹        |

Centi is included as an optional extra, off by default.

Question types convert between symbol and power of ten, and between name and symbol, in either
direction (four types, all on by default). Name → power and power → name are also available.
Decimal numbers (e.g. 0.000 001) aren't tested; students use the powers of ten.

The **Learn the prefixes** button on the setup screen shows a reference table of every prefix with
its symbol, name and power of ten, ordered from giga down to nano.

Wrong answers are re-asked three questions later. The results screen lists the prefixes a student
got wrong. Best scores are saved in the browser for each combination of settings.

To change the prefixes, edit `PREFIX_ITEMS` in `index.html`.
