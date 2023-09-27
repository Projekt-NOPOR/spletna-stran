---
layout: page
title: Udeleženci
---

<p class="message" >
  Na projektu poleg podjetja ORO orodjarna d.o.o sodeluje 10 študentov s Fakultete za računalništvo in informatiko ter Fakultete za strojništvo Univerze v Ljubljani ter pedagoški mentor iz Fakulete za računalništvo in informatiko.
</p>


### Pedagoški mentor

* doc. dr. Uroš Čibej

### Delavni mentor

* Tomaž Kavčič

### Študenti

#### Vanja Stojanović

#### Andjela Rajović

#### Urh Jamšek

#### Katarina Gojković

#### Manca Vavpotič

#### Maks Pustovrh

#### Aljaž Zakošek

#### Matej Bokal

#### Domen Knez

#### Gal Šubic


## Razdelitev dela

#### Aljaž, Domen, Matej, Urh
<p>
V 1. skupini smo se ukvarjali s analizo in razpoznavanjem strojniških odvzemov materiala. To smo počeli s pomočjo izdelave kriterijev. Ti unikatno ločujejo procese, ki se uporabljajo pri izdelavi posameznih kosov. Kriterije smo nato prevedli v enačbe. Velika količina našega dela je obsegala analizo datotek tipa STEP, katere smo uporabljali za pridobivanje meritev in potrebnih parametrov pri enačbah. S pomočjo enačb smo prišli do časovnih ocen trajanja procesov. Zahtevnejše odvzeme smo uspeli oceniti s kombinacijo osnovnih procesov. Za izračun časa smo kot osnovno količino uporabili kar volumen odvzema. Z največjimi težavami smo se soočali pri analizi STEP datotek, ki smo jih na konce le uspeli ukrotiti in pridobiti skoraj vse zastavljene parametre. Nadaljnjo delo pri analizi bi obsegalo kategorizacijo zelo razgibanih odvzemov, ki se v strojništvu označujejo z barvami in njihovo pretvorbo v matematični izraz za razpoznavo. Prav tako bi se lahko delo nadaljevalo na lepši in bolj natančnemu izrazu topoloških lastnosti za bolj natančne ocene časa.
</p>

#### Katarina, Manca
<p>
Na projektu na sva se ukvarjali z razvojem frontend dela aplikacije v Reactu. Naš cilj je bil ustvariti prototipno aplikacijo, ki bo omogočala nalaganje datoteke, nato pa prikaz rezultatov njene analize. Naša prvotna ideja je bila  prikaz odločitvenega drevesa in statistike. Za to sva razvili ustrezne funkcionalnosti, ki sta omogočali prikaz odločitvenega drevesa in ostlih rezultatov analize. Vendar smo se na koncu odločili, da opustimo to idejo in se osredotočimo na izdelavo seznama z podatki o posameznih komponentah, ki je bil bolj pregleden in enostaven za razumevanje. Ta pristop nam je omogočil jasen prikaz podatkov in boljšo uporabniško izkušnjo. Poleg tega smo dodali še funkcionalnost za prikaz 3D modela vsake komponente v seznamu. To je uporabnikom omogočilo ogled posamezne komponente in povečalo razumljivost podatkov.
</p>

#### Gal, Maks
<p>
Z delom sva začela na zalednem delu aplikacije (backendu). Najprej sva ustvarila Django strežnik, ki sva ga kasneje dopolnila še z začetnimi API končnimi točkami, ki so na tem mestu še vračale izmišljene podatke. Namen tega je bil olajšati z razvojem uporabniškega dela aplikacije (frontenda), še preden so bile narejene njene glavne funkcionalnosti.
V drugem delu sva delala na razvoju praktičnih primerov uporabe. Kodo, ki jo je spisal Aljaž, sva uporabila za pretvorbo step datotek, v katerih so bili shranjeni modeli orodij v t.i. negative, ki so prav tako bili step datoteke, le da so namesto orodja vsebovali odvzet material. Nadaljevala sva z izdelavo skripte za pretvorbo obeh variant step datotek v gltf (tekstovne) oz. glb (binarne) datoteke, ki se uporabljajo za vizualizacije trodimenzionalnih modelov.
</p>

#### Andjela, Vanja
<p>
Tekom projekta smo morali zagotavljati integracijsko komponento na strankini strani, saj produkt moramo nekako dostaviti in "integrirati" v njihovo že-obstoječo infrastrukturo.
Moduli projekta, ki so bili napisani ali v Python tehnologiji ali v Javascript, morajo biti združeni v eno skupno aplikacijo, ki bo delovala uporabniku brezhibno, kljub mešanju raznih komponent, za to je ekipa za integracijo uporabila Javascript-ino ogrodje Electron. Ta dopušča tako imenovano "pakiranje" programske kode v enostavno za uporabo, aplikacijo, ki jo lahko kdrokoli požene in uporablja.
</p>
