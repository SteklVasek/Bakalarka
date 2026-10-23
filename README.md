# První konzultace k BP 22.10.2026
Zde je kompletní a doslovný přepis celé proběhlé konzultace:
•	Vedoucí: Výborně, já. 

•	Václav: Jo. 

•	Vedoucí: Můžem si to i založit někam do toho repozitáře. 

•	Václav: Jo. 

•	Vedoucí: Tak, to, co teď děláme s tou termokamerou, je, že když... Tak, kamera kouká, před ní stojí nebo sedí člověk. 

•	Václav: Jo, já pak... Jasně. 

•	Vedoucí: Kouká do tý kamery. Takže vidíme frame, na kterým je něco takovýhohle, dejme tomu. 

•	Václav: Jo. 

•	Vedoucí: To, co tou termokamerou v tuhle chvíli děláme, je, že detekujem obličej. Někde pod úrovní vlasů, po bradu a detekujem tam tuším i nějaký jako landmarky, jako oči, nos. Nejsem si teď úplně jistej, ale myslím si, že jo. A detekujem, jestli vlastně člověk je přítomnej, jako před tou kamerou takhle. A pak měříme... V podstatě jenom detekujem tu oblast, pro výpočet. Jestli je přítomnej a to, co nás... Jedna z věcí, co nás zajímá, je tady ta vejška. Odměření, jak je člověk vysoko... Jak je jakoby vysokej, jak je vysoká ta úroveň, kde mu začínají vlasy. 

•	Václav: Jo. 

•	Vedoucí: Používáme na to model, kterej už je předtrénovanej, nějakej, co prostě byl na... na internetu. Ale byl u toho i dataset, je možný si natrénovat vlastní lepší model. To, co by nás dál zajímalo, je... Jaký všechny informace by z toho obličeje šly zjistit, když máme ten snímek a dokážem... dokážem v podstatě takhle voříznout ten snímek z tý termovize a vidět fakt jako termovizní obrázek prostě obličeje... co všechno dokážem zjistit. Takže podívat se, jaký jsou články na tohle téma publikovaný na internetu. Budou, co jsem koukal, tak jsou snad nějaký jako detekce zánětů prostě a takovýhle věci. Tak... Co k tomu všechno je... 

•	Václav: Jo. 

•	Vedoucí: Co se dá najít. Vybrat si z toho, co vypadá jako nejvíc proveditelný s touhle kamerou v tomhle rozlišení. Já zkusím sehnat nějaký obrázky přímo z tý naší kam... Pošlu vám odkaz na ten dataset, co je veřejnej. 

•	Václav: Ok. 

•	Vedoucí: Ten je velkej, že tam je jako hromada, hromada snímků. A pak zkusím pořídit i nějakej obrázek s tou naší termokamerou, nebo v dohledný době bych měl mít nějaký snímky. Ať víme, jaký máme rozlišení, jak... kolik bude vycházet pixelů na ten obličej a podobně. A... No, kdybyste zkusil zjistit, co jsou ty věci... nejvíc perspektivní věci, co by s tím šly dělat. Ještě... Ta kamera úplně nedává absolutní teploty. Což může bejt limitace pro řadu aplikací. Ale v tý komoře by mělo bejt umístěný někde absolutně černý těleso s konstantní teplotou. 

•	Václav: Jo, tím pádem to jako... 

•	Vedoucí: Tím pádem by to mohlo vyřešit problém. Otázka je, jestli je... jako jeden tenhle bod bude stačit, nebo jestli bude potřeba to ještě nějak kalibrovat jako... nafotit stovky obličejů se změřenou teplotou a napočítat jako tu kalibraci... nevím. To jako další věc, to bude potřeba zjistit. Jestli stačí to absolutně černý těleso, nebo jestli bude potřeba ještě provýst nějakou kalibraci. Takže todle jsou ty úlohy, který tam jsou. Takže máte relativně velkou svobodu si vybrat, co vám bude, nebo... budem postupně jako konzultovat, co bude vypadat jako ty životaschopný zajímavý věci, co všechno by v tu chvíli ještě šlo zjistit vo tom člověku... Mimo toho, že tam sedí prostě a že jeho obličej je před kamerou. 

•	Václav: Jo. 

•	Vedoucí: Dává to smysl takhle? 

•	Václav: Jo. To vlastně začnu nějakou prostě rešerší, co se obecně dá zjistit z termokamery a... 

•	Vedoucí: Přesně tak. Přesně tak. Takže první krok zeptat se AI, co se dá zjistit z... Jaký, jaký směry jako toho jsou zajímavý... 

•	Václav: Jo, pak... 

•	Vedoucí: Ona vám bude doporučovat články, tak podívat se prostě na ty články, jaký měli výsledky, jak to funguje, jakou měli termokameru, jestli měli nějakou termokameru za 5 milionů, tak pravděpodobně to asi nebudem schopný napodobit a... tyhle věci prostě začít, začít zkoumat. Ještě tam mimo rozlišení tý kamery... a jako přesnosti tý teploty, bude ještě zajímavá rychlost tý kamery. Já se pokusím zjistit jakou přesně termokameru tam máme, protože třeba aby šlo jako vidět pulzování toho obličeje, na... třeba na RGB kameře je to vidět. Když je dost rychlá, tak je vidět jak se mění barva a je možný určit tep člověka. Musí ta kamera bejt dostatečně rychlá, aby jako těch snímků bylo dost. A... pak se to dá prostě z toho dostat. U tý termokamery to bude možná podobný. Že když zjistíme, že je dostatečně rychlá, tak nám to otevře jako nový věci, který by šly číst vo tom... vo tom člověku... 

•	Václav: Jasně. 

•	Vedoucí: Ty, který ne. Dobrý. Dává to takhle smysl? 

•	Václav: Ok, jo. Předpokládám, že tam bude i normálně barevná kamera a že možná třeba nějaká úloha by mohla chtít oba ty snímky. Jo, jo, jo, o tom jsem si na to něco jenom, přes AIčko právě zeptal, co všechno se obecně z toho dá jako najít. A právě mi to říkalo, že někdy může bejt problém, když tam bude červenej prostě, tečka, tak jako, že je dobrý mít to srovnání s tou druhou kamerou, aby se třeba dokázalo, to, že to je jenom prostě povrchový škrábnutí, který... 

•	Vedoucí: Jo, jo, jo, jo, jasný. Že to může změnit vlastně i to, jak se ta tepelná stopa, jak bude jiná. 

•	Václav: Hm. 

•	Vedoucí: No, todle, todle by mohlo bejt zajímavý, a jako, kdybyste třeba přišel s tím, že je potřeba tam nutně mít RGB kameru, která bude co nejblíž tý termokameře, aby jako mířily společně, tak si myslím, že by to tam šlo nainstalovat. Kdybyste jako došel k tomu, že je to nutnost, že by to pomohlo s nějakejma zajímavejma věcma, tak asi je to možnost udělat. 

•	Václav: Jo, jasně. Ok. 

•	Vedoucí: Napadá vás ještě něco, co, co byste se chtěl zeptat, nebo co by vás zajímalo? 

•	Václav: Asi ne. 

•	Vedoucí: Ok. Když tak, můžete kdykoliv, kdykoliv pište, můžem se kdykoliv i sejít jako jindy. Není problém. 

•	Václav: Tak jo. Super. Děkuju. 

•	Vedoucí: Tak jsme domluvený. 

•	Václav: Jasně. 

•	Vedoucí: Ok. Takže to nějak rozchodím, abych vám co bych to mohl s váma sdílet takhle. To nevím ještě jak funguje. Když se tím přemýšlím, co bych vám k tomu řekl, abych vám ušetřil co nejvíc času. No asi když se jako asi když se zeptáte AI jak, jak začít používat GitHub a k čemu je, tak vám řekne to líp než já. Obávám se, že už jako jako učitelé budem v tomhle ohled pozadu. 

•	Václav: Jo. No tak ono je to stejně nejlepší mít to napsaný po těch krocích, když člověk má, co co udělat, a pak. 

•	Vedoucí: Přesně tak. Co bych jako jedna možná co rovnou asi dává smysl co bych doporučil používat Visual Studio Code. 

•	Václav: Jo to mám stažený. 

•	Vedoucí: Jo a v tom si můžete rovnou připojit AI Codex nebo Claude nebo cokoliv používáte, že tam můžete mít plugin a můžete si tam rovnou pustit terminál v kterým budete z toho Gitu si stahovat nebo updatovat ty... že tam vlastně všechny ty věci můžete mít zadarmo. Můžete si tam prohlížet ty Markdownový soubory, můžete tam programovat v Python nebo v něčem, můžete tam mít agenta kterým můžete říkat ať vám předělá ty Markdowny do jinýho jako pořadí a jinak přepíše vám obsah v nich, že tam můžete všechny tyhle věci dělat najednou. 

•	Václav: Jo. Ok. 

•	Vedoucí: Dobrý. Napadá vás ještě něco co abyste se chtěl zeptat nebo co by vás zajímalo? 

•	Václav: Asi ne. 

•	Vedoucí: Ok. Kdyžtak můžete kdykoliv pište můžem se kdykoliv i sejít jako jindy. Že není problém. 

•	Václav: Tak jo. Super. Děkuju. 

•	Vedoucí: Tak jsme domluvený. 

•	Václav: Jasně. 


