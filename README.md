# Vláčky na dřevěnou vláčkodráhu
<img width="800" height="507" alt="image" src="https://github.com/user-attachments/assets/48c956c4-d261-42b4-9638-c01768146c58" />

Cíl: Navrhnout lokomotivy pro dřevěné vláčkodráhy (Lidl, IKEA, BRIO) v kombinaci 3D tisku a jednoduché elektroniky. Případně i s variantou elektro pohonu.

## Design
- universální podvozek a střeva
- kastle podle vlaků, ale měřítkově zmršené ve stylu "eggplanes"

## Geometrie
- maximální průjezdný profil, vč. mostů
- minimální směrový oblouk (vč. 3D tištěných kolejnic s malým poloměrem)
- maximální vzdálenost soukolí vůči poloměrům zatáčení
- nízká hmotnost lokomotivy při jízdě do kopce, nutno vyřešit závaží (ideálně studené olovo pro lití do 3D tištěných forem)
- pro dlouhé lokomotivy je problém s geometrií a je třeba udělat dva samostatné podvozky

## Neelektrické verze
- čistě bez pohonu (defacto vagon)
- setrvačník
- natahovací (spíše ne)

## Motor
- DC 3V/1000 RPM (musím prověřit že tento je ten co mi vyšel jako akorát rychlost/výkon) (https://techfun.cz/produkt/dc-motorek-s-prevodem-ruzne-typy/?attribute_pa_motor=3v-1000rpm)

## Převod
- čelní kolo ozubené na osu
- šnek na hřídel motoru

## Kola
- běhouny nebo celá kola z TPU/TPE/Flex jinak to nejede do kopce

## Osy
- Pojezdy.EU, rozměry dohledat

## Zdroj
- Li-Pol baterie (https://www.laskakit.cz/geb-lipol-baterie-801454-580mah-3-7v-jst-ph-2-0/)
- USB-C nabíječka (https://www.laskakit.cz/nabijecka-li-ion-clanku-tp4056-s-ochranou-usb-c/)
- Posuvný přepínač na odpojení baterie (mega důležité!)

## Ovládání
- Kapacitní tlačítko, s pamětí (https://www.laskakit.cz/arduino-kapacitni-dotykove-tlacitko-ttp223/)
- Ovládání směru jízdy (vpřed/zastavit/vzad)?
- Mikrospínače?
- Integrace ESP32?
- Local webpage pro řízení více lokomotiv dle ID?
- Vlastní ovládací pult pro více lokomotiv?
- IR dioda a obecný ovladač

## Osvětlení
- LED diody (pokud bude řízení směru tak i RGB?)

## Spřáhla
- Čalounický hřeb, na konci zploštit (https://www.hornbach.cz/p/hrebik-calounicky-12-poniklovany-400-ks/8722101/)
- Magnet (https://www.unimagnet.cz/neodymovy-kruhovy-magnet-10-3-mm-v-5-mm-sila-2-2-kg_z644/)
- 3D tištěný kryt

## Kastle
- návrh pro 3D tisk z PLA
- jednoduchý tisk a instalace
- max. 2 vnější díly na šroubky do plastu

## Obecné problémy


## TODO list
- prověřit komplet geometrii kolejí a vláčků
# Příslušenství

## Přejezd
- 3D tištěný přejezd se závorami a výstrašným světlem, napájení  velkou Lipol, serva na závody, detekce vlaku magnetickcým spínačem

## Nádraží/zastávka
- 3D tištěný domeček s IR diodou která zastaví vlak a třeba časovačem který vlak pustí, nebo ovládání na tlačítko pro vyslání signálu

# Inspirace
- https://3dvlacky.cz/galerie
