# Mrrakc
Mrrakc is a project to

## Contributing

### How to install
Mrrakc is built using Hugo.
1. Install Hugo
2. Clone the project and the theme's submodule
3. Run Hugo development server and Open the link in the browser (http://localhost:1313 by default)
```
hugo server -Dw
```

### Adding a new location
To add a new location execute the following command
```
hugo new --kind="<archetype> locations/<location-name>.md
```

> Make sure to replace <archetype> with an existing archtype in `archetypes`

### Guidelines
#### Location names
- To make location names unique we suggest the following format `CATEGORY_PREFIX-location-name-seperated-by-hyphens.md` for example `museum-bab-el-oqla.md` or `mount-toubkal.md`

#### Front Matter
- Make sure to include your name in the `author` field as well as the location category in `categories`. Make sure the category figures in the categories list below, if not add it to the list bellow (And let's discuss in the PR).
- Make sure to add the region as it is mentionned in this [Wikipedia page](https://en.wikipedia.org/wiki/Regions_of_Morocco)
- Add relevant Tags
- Add and image in jpg format
    - Make sure to compress it if possible
    - Make sure you own the copyrights or there are none on it.
    - Add the image in `/static` folder and reference it in the `cover.image` field.
    - Modify the alt and/or the Caption if needed
- For `gmaps` field, go to the location in Google Maps, click on the share button and select `embed`. Copy the link from the embed code into `gmaps` field.

#### Main Content
- Each archetype contains a generic General Information section. Make sure to fill the table and add a description bellow it.
- Add a small description on how to get to the location.
- Add links to articles, media, papers, or any relevant material in the References Section.

#### Supported categories

| Category                      | Description                                   | Example Category Prefixes                  | Archetype |
| ---                           | ---                                           | ---                                        | ---       |
| Ancient Rock Workes           | Ancient caves, Rock Drawings and quarries ... | cave, site, tombs, cromlech, carvings, ... | hsite     |
| Historic Cities and Regions   | Prehistoric or historical cities              | city                                       | hsite     |
| Mosques and Islamic Buildings | Historic Mosques or Madrassas                 | mosque, madrassa, zawya ...                | hsite     |
| Tombs and Necropolises        | Historic tombs, mausoleums and necropolises   | tombs, mausoleum, necropolise ...          | hsite     |
| Jewish Temples                | Historic Jewish buildings                     | synagogue, temple                          | hsite     |
| Churches and Monasteries      | Historic Christian buildings                  | church, monastry                           | hsite     |
| Castles and Fortresses        | Castles, Fortresses and city gates            | gate, castle, tour, kasbah, ...            | hsite     |
| Museums                       | Museums                                       | museum                                     | museum    |
| Mountains                     | Mountains                                     | mount                                      | mountain  |
| Lakes                         | Lakes                                         | lake                                       | lake      |

#### Example Tags
- Ancient Rock Workes: You may add the prehistoric ages and cultures related to the location.
- Mountains: You may add altitude range in thousands meters (e.g. 2000m, 4000m), the National Park and the Mountain range the mountain belongs to (e.g. High Atlas)
