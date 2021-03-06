# Dex v0.3
Porter Libby, 2020
# CSV Data
![img](static/regular/darkrai.png) [Full International Dex (898) (CSV)](data/all.csv)

### Dex by Generation

![img](static/regular/charizard.png) [Generation 1 Dex (151) (CSV)](data/gen1.csv)
![img](static/regular/typhlosion.png) [Generation 2 Dex (100) (CSV)](data/gen2.csv)

![img](static/regular/blaziken.png) [Generation 3 Dex (136) (CSV)](data/gen3.csv)
![img](static/regular/infernape.png) [Generation 4 Dex (107) (CSV)](data/gen4.csv)

![img](static/regular/emboar.png) [Generation 5 Dex (156) (CSV)](data/gen5.csv)
![img](static/regular/delphox.png) [Generation 6 Dex (72) (CSV)](data/gen6.csv)

![img](static/regular/incineroar.png) [Generation 7 Dex (88) (CSV)](data/gen7.csv)
![img](static/shiny/cinderace.png) [Generation 8 Dex (89) (CSV)](data/gen8.csv)

### Dex by Game
![img](static/regular/eternatus.png) [Sword / Shield (400) (CSV)](data/sword_shield.csv)
![img](static/regular/urshifu.png) [Isle of Armor (211) (CSV)](data/isle_of_armor.csv)

![img](static/regular/calyrex.png) [Crown Tundra (210) (CSV)](data/crown_tundra.csv)
![img](static/regular/arceus.png) [Sw / Sh Non-Indexed (68) (CSV)](data/sword_shield_non_indexed.csv)

# Sprite Catalogues
![img](static/regular/rayquaza.png)[Regular Sprites (no Galar sprites)](normal_sprites.md) 
![img](static/shiny/rayquaza.png)[Shiny Sprites (no Galar sprites)](shiny_sprites.md) 

# Tools
![img](static/regular/lugia.png) [CSV Dex Scraping Tool (py)](tools/scrape_dex_csv.py)
![img](static/regular/ho-oh.png) [Dex Data Visualizer (py)](tools/vis_dex_data.py)

![img](static/regular/mew.png) [Stat Anylsis Tool (py)](tools/analysis.py)
![img](static/regular/articuno.png) [Gen8 Image Tool (py)](tools/scrape_gen8_img.py)

![img](static/regular/moltres.png) [Weakness/Resistance Chart (py)](tools/wr_chart.py)
![img](static/regular/zapdos.png) [Image Markdown Dex Tool (py)](tools/gen_sprite_md.py)

# Usage
## Installation 
1. Use `pip` to install the project dependencies. Make sure you are using the `python3` environment.
2. Clone this project to your local machine

# Web App 
www.combat-dex.herokuapp.com/

`python3 app.py` will start a Flask server running a web app version of the CSV data generated.

# Creating Data
`python3 dex_gen.py` will create a set of data CSV files, which are based on web scraped info from Serebii.

`python3 util/create_dex_md.py` will create a readme of a directory full of sprites, effectively creating a markdown version of a sprite sheet. Used this to create the `dex_images.md` resource.

`util/wr_chart.py` contains a python version of nintendos weakness and resistance matrix, which is used to comput combat values in `dex_gen.py`.

`util/vis.py` (coming soon) 

# Dependencies
- BeautifulSoup4 (4.8.1)
- Flask (1.0.3)
  
(full dependencies can be found in `requirements.txt`)


# References/Sources
- https://github.com/msikma/pokesprite
- https://www.serebii.net/

# Liscenses
The source icons are © Nintendo/Creatures Inc./GAME FREAK Inc.

Everything else, and usage of the programming code, is governed by the MIT license.