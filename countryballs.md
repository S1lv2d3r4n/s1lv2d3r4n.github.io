# Countryballs

![A countryball icon](images/blankico.png) **Countryballs** are characters in [Luces Siegas](lsgamepage.md) that are the primary characters and the
only playable characters in the game. Countryballs are either controlled by the [player's](player.md) country or the game's AI.


![Image Warning](images/warningimg.png)

## Jump To
![A countryball icon](images/blank.png) [Behavior and Mechanics](#behavior-and-mechanics)  
![Animated Countryball Icon](images/animico.gif) [List of Countryballs and IDs](#list-of-countryballs-and-idsinternal-names)

## Behavior and Mechanics
A random quantity of 0-5 other countryballs spawns alongside the player during World Generation.   
There is a `50%` chance for one of these countryballs to be a blank white "Blankball" (id: `127`) which can be added to the Player's country.

### Stats
A countryball has four primary stats: `H` (Health), `F` (Strength), `E` (Endurance) and `V` (Speed)
These stats can be any integer between `0` and `17` with `0` being the worst and `17` being the best.
Maximum HP (Hit Points) are calculated using this formula, where the minimum HP is `60` and the maximum is `264`:
maximumHP = (h*12) + 60

When breeding, stats are mixed between the two parents and merged down. The formula for breeding is listed below, where a is the first parent's stat and b is the second parent's stat:
(a+b) / 2 

### Flag
All Countryballs have an internal `pais` variable that controls their flag type
To see a list of all possible appearances see [List of Countryballs and IDs/Internal Names](#list-of-countryballs-and-idsinternal-names)

### Breeding
You can breed ![A male countryball](images/male.png) ![A female countryball](images/female.png) Countryballs of the opposite gender together
(countryball type does NOT matter) by going near the other Countryball and pressing `B` on your keyboard

#### In Asylum Mode
In [Asylum Mode](lsasylum.md), all Countryballs that did not spawn as a part of your country or as Blankballs are hostile towards the Player.  
Breeding is disabled in Asylum Mode and therefore, more countryballs for your country are impossible to obtain unless you can find Blankballs.

#### In Imperial Mode*
In [Imperial Mode](lsimperialmode.md), Breeding works like in regular gameplay, however you cannot breed with the Bosses or the Empires themselves due to them not being considered 
regular countryballs.


## List of Countryballs and IDs/Internal Names
There are a total of 189 Countryballs in the game and 191 total IDs (189 Countryballs and 2 special IDs)
|Name|Image|ID|Internal Name|
|----|----|----|----|
|El Salvador|![El Salvadorball](images/elsalvador.png)|`1`|elsalvador|
|Guatemala|![Guatemalaball](images/guatemala.png)|`2`|guatemala|
|Mexico|![Mexicoball](images/mexico.png)|`3`|mexico|
|Belize|![Belizeball](images/belize.png)|`4`|belice|
|United States|![United Statesball](images/usa.png)|`5`|america|
|Honduras|![Hondurasball](images/honduras.png)|`6`|honduras|
|Nicaragua|![Nicaraguaball](images/nicaragua.png)|`7`|nicaragua|
|Canada|![Canadaball](images/canada.png)|`8`|canada|
|Costa Rica|![Costa Ricaball](images/costarica.png)|`9`|costarica|
|Panama|![Panamaball](images/panama.png)|`10`|panama|
|Colombia|![Colombiaball](images/colombia.png)|`11`|colombia|
|Chile|![Chileball](images/chile.png)|`12`|chile|
|Venezuela|![Venezuelaball](images/venezuela.png)|`13`|venezuela|
|Ecuador|![Ecuadorball](images/ecuador.png)|`14`|ecuador|
|Peru|![Peruball](images/peru.png)|`15`|peru|
|Bolivia|![Boliviaball](images/bolivia.png)|`16`|bolivia
|Paraguay|![Paraguayball](images/paraguay.png)|`17`|bolivia
|Argentina|![Argentinaball](images/argentina.png)|`18`|argentina|
|Suriname|![Surinameball](images/suriname.png)|`19`|suriname|
|Guyana|![Guyanaball](images/guyana.png)|`20`|guyana|
|Uruguay|![Uruguayball](images/uruguay.png)|`21`|uruguay|
|Brazil|![Brazilball](images/brazil.png)|`22`|brasil|
|Cuba|![Cubaball](images/cuba.png)|`23`|cuba|
|Haiti|![Haitiball](images/haiti.png)|`24`|haiti|
|Dominican Republic|![Dominicanball](images/dominicanrepublic.png)|`25`|republicadominicana|
|Bahamas|![Bahamasball](images/bahamas.png)|`26`|bahamas|
|Trinidad and Tobago|![Trinidadball](images/trinidad.png)|`27`|trinidad|
|Spain|![Spainball](images/spain.png)|`28`|españa|
|Portugal|![Portugalball](images/portugal.png)|`29`|portugal|
|France|![Franceball](images/france.png)|`30`|france|
|Netherlands|![Netherlandsball](images/netherlands.png)|`31`|paisesbajos|
|Luxembourg|![Luxembourgball](images/luxembourg.png)|`32`|luxembourg|
|Belgium|![Belgiumball](images/belgium.png)|`33`|belgia|
|Italy|![Italyball](images/italy.png)|`34`|italia|
|Switzerland|![Switzerlandball](images/switzerland.png)|`35`|suiza|
|Austria|![Austriaball](images/austria.png)|`36`|austria|
|Germany|![Germanyball](images/germany.png)|`37`|alemania|
|Poland|![Polandball](images/poland.png)|`38`|polonia|
|Hungary|![Hungaryball](images/hungary.png)|`39`|hungria|
|Czechia|![Czechiaball](images/czech.png)|`40`|czech|
|Slovakia|![Slovakiaball](images/slovakia.png)|`41`|slovakia|
|Slovenia|![Sloveniaball](images/slovenia.png)|`42`|slovenia|
|Croatia|![Croatiaball](images/croatia.png)|`43`|croatia|
|Bosnia|![Bosniaball](images/bosnia.png)|`44`|bosnia|
|Serbia|![Serbiaball](images/serbia.png)|`45`|serbia|
|Montenegro|![Montenegroball](images/montenegro.png)|`46`|montenegro|
|Albania|![Albaniaball](images/albania.png)|`47`|albania|
|Greece|![Greeceball](images/greece.png)|`48`|greece|
|Macedonia|![Macedoniaball](images/macedonia.png)|`49`|macedonia|
|Türkiye (Turkey)|![Türkiyeball](images/turkiye.png)|`50`|turkiye|
|Bulgaria|![Bulgariaball](images/bulgaria.png)|`51`|bulgaria|
|Romania|![Romaniaball](images/romania.png)|`52`|romania|
|Moldova|![Moldovaball](images/moldova.png)|`53`|moldova|
|Ukraine|![Ukraineball](images/ukraine.png)|`54`|ukraine|
|Belarus|![Belarusball](images/belarus.png)|`55`|belarus|
|San Marino|![San Marinoball](images/sanmarino.png)|`56`|sanmarino|
|Russia|![Russiaball](images/russia.png)|`57`|russia|
|Lithuania|![Lithuaniaball](images/lithuania.png)|`58`|lithuania|
|Latvia|![Latviaball](images/latvia.png)|`59`|latvia|
|Estonia|![Estoniaball](images/estonia.png)|`60`|estonia|
|Denmark|![Denmarkball](images/denmark.png)|`61`|denmark|
|Sweden|![Swedenball](images/sweden.png)|`62`|sweden|
|Iceland|![Icelandball](images/iceland.png)|`63`|iceland|
|Finland|![Finlandball](images/finland.png)|`64`|finland|
|Norway|![Norwayball](images/norway.png)|`65`|norway|
|Ireland|![Irelandball](images/ireland.png)|`66`|ireland|
|United Kingdom (Britain)|![UKball](images/britain.png)|`67`|britain|
|Vatican City|![Vaticanball](images/vatican.png)|`68`|vatican|
|Georgia|![Georgiaball](images/georgia.png)|`69`|georgia|
|Armenia|![Armeniaball](images/armenia.png)|`70`|armenia|
|Azerbaijan|![Azerbaijanball](images/azerbaijan.png)|`71`|azerbaijan|
|Kazakhstan|![Kazakhstanbrick](images/kazakhstan.png)|`72`|kazakhstan|
|Kyrgyzstan|![Kyrgyzstanball](images/kyrgyzstan.png)|`73`|kyrgyzstan|
|Uzbekistan|![Uzbekistanball](images/uzbekistan.png)|`74`|uzbekistan|
|Tajikistan|![Tajikistanball](images/tajikistan.png)|`75`|tajikistan|
|Saudi Arabia|![Saudi Arabiaball](images/saudiarabia.png)|`76`|arabiasaudita|
|Afghanistan|![Afghanistanball](images/afghanistan.png)|`77`|afganistan|
|Iran|![Iranball](images/iran.png)|`78`|iran|
|Pakistan|![Pakistanball](images/pakistan.png)|`79`|pakistan|
|India|![Indiaball](images/india.png)|`80`|india|
|1ball|![1ball](images/1ball.png)|`81`|1ball|
|2ball|![2ball](images/2ball.png)|`82`|2ball|
|3ball|![3ball](images/3ball.png)|`83`|3ball|
|4ball|![4ball](images/4ball.png)|`84`|4ball|
|5ball|![5ball](images/5ball.png)|`85`|5ball|
|6ball|![6ball](images/6ball.png)|`86`|6ball|
|7ball|![7ball](images/7ball.png)|`87`|7ball|
|8ball|![8ball](images/8ball.png)|`88`|8ball|
|Iraq|![Iraqball](images/iraq.png)|`89`|irak|
|Yemen|![Yemenball](images/yemen.png)|`90`|yemen|
|United Arab Emirates|![UAEBall](images/uae.png)|`91`|eau|
|Oman|![Omanball](images/oman.png)|`92`|oman|
|Palestine|![Palestineball](images/palestine.png)|`93`|palestina|
|Lebanon|![Lebanonball](images/lebanon.png)|`94`|libano|
|Syria|![Syriaball](images/syria.png)|`95`|siria|
|Jordan|![Jordanball](images/jordan.png)|`96`|jordania|
|Kuwait|![Kuwaitball](images/kuwait.png)|`97`|kuwait|
|Bahrain|![Bahrainball](images/bahrain.png)|`98`|barein|
|Qatar|![Qatarball](images/qatar.png)|`99`|catar|
|Nepal|![Nepalrawr](images/nepal.png)|`100`|nepal|
|Bhutan|![Bhutanball](images/bhutan.png)|`101`|butan|
|Bangladesh|![Bangladeshball](images/bangladesh.png)|`102`|banglades|
|China|![Chinaball](images/china.png)|`103`|china|
|North Korea|![North Koreaball](images/northkorea.png)|`104`|coreadelnorte|
|South Korea|![South Koreaball](images/southkorea.png)|`105`|coreadelsur|
|Japan|![Japanball](images/japan.png)|`106`|japon|
|Mongolia|![Mongoliaball](images/mongolia.png)|`107`|mongolia|
|Myanmar|![Myanmarball](images/myanmar.png)|`108`|myanmar|
|Laos|![Laosball](images/laos.png)|`109`|laos|
|Cambodia|![Cambodiaball](images/cambodia.png)|`110`|camboya|
|Vietnam|![Vietnamball](images/vietnam.png)|`111`|vietnam|
|Malaysia|![Malaysiaball](images/malaysia.png)|`112`|malaysia|
|Thailand|![Thailandball](images/thailand.png)|`113`|tailandia|
|Indonesia|![Indonesiaball](images/indonesia.png)|`114`|indonesia|
|Philippines|![Philippinesball](images/phillippines.png)|`115`|filipinas|
|Israel|![Israelcube](images/israel.png)|`116`|israel|
|Australia|![Australiaball](images/australia.png)|`117`|australia|
|New Zealand|![New Zealandball](images/newzealand.png)|`118`|nuevazelanda|
|Egypt|![Egyptball](images/egypt.png)|`119`|egipto|
|Sudan|![Sudanball](images/sudan.png)|`120`|sudan|
|South Sudan|![South Sudanball](images/southsudan.png)|`121`|sudandelsur|
|Libya|![Libyaball](images/libya.png)|`122`|libia|
|Algeria|![Algeriaball](images/algeria.png)|`123`|argelia|
|Morocco|![Moroccoball](images/morrocco.png)|`124`|marruecos|
|Mauritania|![Mauritaniaball](images/mauritania.png)|`125`|mauritania|
|Tunisia|![Tunisiaball](images/tunisia.png)|`126`|tunez|
|Blankball|![Blankball](images/blank.png)|`127`|enblanco|
|Somalia|![Somaliaball](images/somalia.png)|`128`|somalia|
|Kenya|![Kenyaball](images/kenya.png)|`129`|kenia|
|Ethiopia|![Ethiopiaball](images/ethiopia.png)|`130`|etiopia|
|Eritrea|![Eritreaball](images/eritrea.png)|`131`|eritrea|
|Djibouti|![Djiboutiball](images/djibouti.png)|`132`|yibuti|
|Blankball|![Blank Blackball](images/blank2.png)|`133`|enblanco2|
|Niger|![Nigerball](images/niger.png)|`134`|niger|
|Nigeria|![Nigeriaball](images/nigeria.png)|`135`|nigeria|
|Chad|![Chadball](images/chad.png)|`136`|chad|
|Mali|![Maliball](images/mali.png)|`137`|mali|
|Senegal|![Senegalball](images/senegal.png)|`138`|senegal|
|Guinea|![Guineaball](images/guinea.png)|`139`|guinea|
|Cote d'Ivoire (Ivory Coast)|![IvoryCoastball](images/ivorycoast.png)|`140`|ivorycoast|
|Burkina Faso|![Burkinafasoball](images/burkinafaso.png)|`141`|burkinafaso|
|Sierra Leone|![SierraLeoneball](images/sierraleone.png)|`142`|sierraleone|
|Liberia|![Liberiaball](images/liberia.png)|`143`|liberia|
|Cameroon|![Cameroonball](images/cameroon.png)|`144`|cameroon|
|Ghana|![Ghanaball](images/ghana.png)|`145`|ghana|
|Benin|![Beninball](images/benin.png)|`146`|benin|
|Togo|![Togoball](images/togo.png)|`147`|togo|
|Gabon|![Gabonball](images/gabon.png)|`148`|gabon|
|Madagascar|![Madagascarball](images/madagascar.png)|`149`|madagascar|
|Botswana|![Botswanaball](images/botswana.png)|`150`|botsuana|
|Malawi|![Malawiball](images/malawi.png)|`151`|malaui|
|Republic of the Congo|![Congoball](images/congo.png)|`152`|congo|
|Democratic Republic of the Congo|![DRCball](images/drcongo.png)|`153`|congo2|
|Namibia|![Namibiaball](images/namibia.png)|`154`|namibia|
|Testball|![Testball](images/testball.png)|`155`|pruebas|
|Angola|![Angolaball](images/angola.png)|`156`|angola|
|Tanzania|![Tanzaniaball](images/tanzania.png)|`157`|tanzania|
|Mozambique|![Mozambiqueball](images/mozambique.png)|`158`|mozambique|
|Gambia|![Gambiaball](images/gambia.png)|`159`|gambia|
|Guinea-Bissau|![GuineaBissauball](images/guineabissau.png)|`160`|guineabissau|
|Equatorial Guinea|![EquatorialGuineaball](images/equatorialguinea.png)|`161`|guineaecuatorial|
|Lesotho|![Lesothoball](images/lesotho.png)|`162`|lesoto|
|South Africa|![SouthAfricaball](images/southafrica.png)|`163`|sudafrica|
|Eswatini|![Eswatiniball](images/eswatini.png)|`164`|esuatini|
|Zambia|![Zambiaball](images/zambia.png)|`165`|zambia|
|Uganda|![Ugandaball](images/uganda.png)|`166`|uganda|
|Zimbabwe|![Zimbabweball](images/zimbabwe.png)|`167`|zimbabue|
|Rwanda|![Rwandaball](images/rwanda.png)|`168`|ruanda|
|Burundi|![Burundiball](images/burundi.png)|`169`|burundi|
|Comoros|![Comorosball](images/comoros.png)|`170`|comoros|
|Seychelles|![Seychellesball](images/seychelles.png)|`171`|seychelles|
|Sao Tome and Principe|![Saotomeball](images/saotome.png)|`172`|saotome|
|Central African Republic|![Central African Republicball](images/centralafricanrepublic.png)|`173`|republicacentroafricana|
|Mauritius|![Mauritiusball](images/mauritius.png)|`174`|mauricio|
|Cape Verde|![Cape Verdeball](images/capeverde.png)|`175`|caboverde|
|Papua New Guinea|![Papua New Guineaball](images/papuanewguinea.png)|`176`|papuanuevaguinea|
|Palau|![Palauball](images/palau.png)|`177`|palau|
|Nauru|![Nauruball](images/nauru.png)|`178`|nauru|
|East Germany|![East Germanyball](images/ostdeutschland.png)|`179`|alemaniadeleste|
|Soviet Union|![Soviet Unionball](images/sovietunion.png)|`180`|unionsovietica|
|Civilian Ensign (El Salvador)|![ElSalvadorCivilianEnsignball](images/elsalvadorcivil.png)|`181`|elsalvador2|
|Austrian Empire|![AustrianEmpireball](images/austria2.png)|`182`|austria2|
|Yugoslavia|![Yugoslaviaball](images/yugoslavia.png)|`183`|yugoslavia|
|Federal Republic of Central America|![FRCAball](images/frca.png)|`184`|republicafederaldecentroamerica|
|Reichtangle|![Reichtangle](images/reichtangle.png)|`185`|reichtanglo|
|El Salvador (Old Flag)|![ElSalvador1840sball](images/elsalvadorold.png)|`186`|elsalvador3|
|Cabañas|![Cabañasball](images/cabanas.png)|`187`|cabanas|
|Scotland|![Scotlandball](images/scotland.png)|`188`|esocia|
|Antarctica|![Antarcticaball](images/antarctica.png)|`189`|antartida|   

## Special IDs
|Name|Image|ID|Internal Name|
|----|----|----|----|
|Boat|![Wooden Boat](images/boat.png)|`190`|barco|
|Iron Boat|![Iron Boat](images/ironboat.png)|`191`|barco2|  

