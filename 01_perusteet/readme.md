# Blender perusteet

## Pikanäppäimet

[Blender hotkey sheet by CGBOOST](https://www.dropbox.com/sh/49wv12ee9ioqnhf/AAA0petUow7AfNyh2Vsvmalaa?dl=0)

### Yleiset

| Pikanäppäin                     | toiminto                                                                                                                         | 
| ------------------------        |:--------------------------------------------------------------------------------------------------------------------------------:|
| T                               | Avaa / piilottaa vasemman reunan perustyökaluvalikon                                                                             | 
| N                               | Avaa / piilottaa oikean reunan "properties" valikon                                                                              | 
| CTRL + ALT + Q                  | Vaihtaa näkymäksi neljä pienempää ikkunaa, jossa projektiot eri suunnista pelkän scene näkymän sijasta (3DsMax tyylinen näkymä)  |
| SHIFT + A                       | Avaa "Add" valikon, josta voi lisätä uusia objekteja (plane, cube,cylinder yms.)                                                 |
| SHIFT + vasen hiiren nappi      | Valitsee useita objekteja                                                                                                        |
| A                               | Select all, valitsee kaikki scenessä olevat objektit                                                                             |
| G                               | Liikuttaa objekteja XYZ-suunnassa (G+X liikuttaa kappaletta vain X-suunnassa G+Y Y-suunnassa ja G+Z Z-suunnassa                  |
| R                               | Pyörittää objektia XYZ-akseleiden ympäri (voidaan myös pyörittää yhden akselin suuntaisesti samalla tapaan kuin G-komennossa     | 
| S                               | Skaalaa objektin kokoa kaikkien akseleiden suhteen (voidaan myös skaalata vain yhtä akselia syöttämällä perään X,Y tai Z         |
| SHIFT + X,Y,Z                   | Tekee muutoksen kaikille muille akseleille paitsi valitulle (esim. G + SHIFT X = liikuttaa kappaletta vain Y j Z -suunnassa      |
| SHIFT + D                       | Objektin monistaminen (duplicate) tekee kopion valitusta tai valituista objektista/objekteista                                   |
| ALT + D                         | Objektin monistaminen (linked duplicate) kappaleen geometria on linkitety alkuperäiseen objektiin                                |
| ALT + G                         | Nollaa objektin sijainnin origoon (X,Y,Z)                                                                                        |
| ALT + R                         | Nollaa objektin kiertymän (Rx, Ry, Rz)                                                                                           |  | SHIFT + S                       | 3D kursorin valikko (cursor align)                                                                                               |
| TAB                             | Vaihtaa näkymää object ja edit moodien välillä                                                                                   |
|  §                              | Vaihtaa näkymän global (kaikki mallit näkyvissä) local (vain valittu objekti näkyvissä) välillä                                  |
             

### Mallinnus (edit mode)
| Pikanäppäin                     | toiminto                                                                                                                         | 
| ------------------------        |:--------------------------------------------------------------------------------------------------------------------------------:|
| F                               | Create face or edge between selected                                                                                             |
| E                               | Extrude face or edge                                                                                                             |
| CTRL + B                        | Bevel vertex or edge                                                                                                             | 
| CTRL + R                        | Loopcut                                                                                                                          |
| CTRL + F                        | Avaa facen muokkamamiseen liittyvän työkaluvalikon                                                                               | 
| CTRL + E                        | Avaa edgen muokkaamiseen liittyvän työkaluvalikon                                                                                | 
| CTRL + V                        | Avaa verteksien muokkaamiseen liittyvän työkaluvalikon                                                                           | 
                                                                                                                      


## Yleistä

Blederin koordinaattiakselit ja niiden värit ovat seuraavat:
- X-akseli 🔴 (leveys)
- Y-akseli 🟢 (syvyys)
- Z-akseli 🔵 (korkeus)


<figure>
  <img src="/01_perusteet/img/blender_koordinaatiosto.jpg" alt="my alt text"/>
  <figcaption>Kuva 1. Blender koordinaatisto</figcaption>
  <br>
</figure>


### Object moode 

<figure>
  <img src="/01_perusteet/img/object_mode.jpg" alt="my alt text"/>
  <figcaption>Kuva 2. Blenderin näkymä object-moodissa (vasemman reunan työkaluja on näyvissä vain muutama). Object-moodissa näkymässä olevia kappaleita voi vain liikuttaa, skaalata tai pyöritää mutta kappaleen geometriaan ei pysty tekemään muutoksia</figcaption>
  <br>
</figure>

### Edit mode
<figure>
  <img src="/01_perusteet/img/edit_mode.jpg" alt="my alt text"/>
  <figcaption>Kuva 3. Blenderin näkymä EDIT-moodissa. Tässä näkymässä objektien rakennetta pystytään muokkaamaan erilaisten työkaluen avulla (TAB-näppäimellä voit vaihtaa näiden kahden eri moodin välillä) </figcaption>
  <br>
</figure>



