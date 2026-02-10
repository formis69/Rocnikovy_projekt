# Stavba stolního počítače


## Potřebné díly a mé komponenty


1. Základní deska - Gigabyte B550M K
2. Procesor - AMD Ryzen 5 5500
3. Chladič procesoru - Endorfy Fera 5
4. PSU [Power supply (zdroj)] - Nevím jaká značka to byla
5. Case - DEEPCOOL CC560 LIMITED V2
6. RAM - 1x Patriot 16 Gb 2600MHz
7. Grafická karta - MSI Nvidia RTX 5050 8Gb VRam
8. SSD nebo HDD - 1x 528GB SATA 3 SDD a 1x 1Tb SATA 3 HDD


---

## Příprava na stavbu


  Je potřeba mí po ruce ideálně 2x plochý šroubovák (jeden menší a druhý větší) a 2x křížový šroubovák (také jeden menší a druhý větší). Krabici od základní desky, takže nevyhazovat a nechat si věci na cabel managment co byli dodány s základní deskou např. stahovací pásky nebo spínací pásky na suchý zip.
  

---

## Stavba

  První krok je vybalit MoBo.Před vyjmutím z krabice se ujistíme dotknutím např. topení, že se zbavíme statické elektřiny, aby nebyla možnost si MoBo vyzkratovat.  Po vyjmutí z krabice a proti statického obalu si ji odložím na krabici.
  
  Připravíme si CPU, ale ještě nevytahujeme z boxu a ujistíme se že v balení s chladičem je termální pasta. V mém případě byla dodána v balení, takže o problém méně, ale pokud v balení není tak nemůžeme pokračovat a musíme si ji koupit. Po kontrole si můžeme otevřít socket na CPU na MoBo. Na socketu si najdeme kde se nachází malinká šipka na rohu socketu a srovnáme CPU tak, aby šipka korespondovala s šipkou na socketu. Pokud jsme si sto procentně jistí tak můžeme CPU vložit, ideálně nechat gravitaci udělat práci za nás a netlačit moc na CPU, ale pokud nechce zapadnou a 100% víme, že je správně tak můžeme použít trochu síly, ale je potřeba být velmi opatrný, abychom neohli žádné piny. Teď můžeme uzavřít socket pomocí malé páčky na boku, tím že zatlačíme dolů a trochu do strany, v tomto případě nevadí použít sílu.
  
  Dalším krokem je instalace RAM. Instalace RAM je sama o sobě velmi jednoduchá, ale je potřeba dát si pozor na pár věcí. Jedna z nich je instalovat je do správných slotů. Každá MoBo má jina sloty na dual channel (když máme 2 RAM) tak v mém případě by to byl slot 2 a 4. Při tomto kroku je vždy potřeba si zkontrolovat schéme tak, aby byli RAM ve správných slotech jinak riskujeme zhořšení jejich výkonu nebo i taktování. V mém případě bude pouze 1x RAM a na mé MoBo patří do slotu 2. Před instalací musíme otevřít oba zámky na ramky tak, aby byli otevřený a mohli jsme zacvakout RAM do slotu. Zámky se sami zavřou po zastrčení RAM sticku. Při této praci lze použít sílu, ale přiměřeně.
  
  V tuhle chvíly už máme vše připravené na to abychom mohli přidat chladič CPU. V balení s chladičem, pokud není s CPU, tak je skoro vždy mount kit na Intel i AMD AM4 a AM5 socket. V mém případě mám socket AMD AM4 a proto si z balení chladiče vytáhnu, vyvyšovací šrouby, šrouby na přidělání framu na chladič a samo utahovací šrouby přímo na chladič. Prvním krokem při instalaci AMD AM4 je sundat plastové držáky na chladič a vyměnit každou díru na šroub s vyvýšenými šrouby, které mají díru na šrouby které budou držet frame chladiče. přiděláme bracket na chladič a pevně utáhneme, ale ne tak abychom poničili MoBo. Teď si na vrch procesoru naneseme termální pastu do křízku a do káždého trojúhelníku dáme jednu tečku termální pasty a sundáme plastovou pásku co je na spodu chladiče a přiložíme chladič na CPU. A teď budeme postupně a vždy rovnoměrně utahovat samo utahovací šrouby tak aby chladič držel a zároveň nebyl dotáhnutý úplně na krev.
  
  Konečně si můžeme vytáhnout náš case. Ve spodní časti case kde je i kabeláž na reset, power on/off, jack 3,5 a USB 3,2, tam také najdeme všechny šrouby ke case a montáži všech komponentů. První ale přiděláme na case IO shield tak baychom měli konektroy kryté. Poté si dáme MoBo na slot v case a přišroubujeme spacer kde klasický šroub nedosáhne a přišroubujeme pevně, ale ne na krev a ne volně. Začneme se zapojováním konektorů přímo na case ot znamená power on/off, reset, atd. Poté připojíme CPU fan na 4 pinový konektor přímo u RAM a CPU.
  
  Dalším krokem je instalace PSU. PSU má vždy své přiřazené místo kde bude přišroubováno a tam to dotáhneme co nejvíce, aby PSU nebyla volně. Pokud máte modulárni PSU tak připojit všechny potřebné kabely před přiděláním PSU! A můžeme začít s kabeláží. Připojíme 8 a 16 pinový konektor na MoBo. Pokud chcete mít dobrý cabel managment tak u modulárního zdroje doporučuji nopoužít všchny a kabel a pouze ty potřebné.
  V tuhle chvíly se dostáváme do nejjednuší části stavby a to je přidělání GPU. Předtím než budeme dávat GPU do slotu musíme odstranit dust cover většinou 2 sloty někdy i více, vždy podle PCiE 16 slotu a výšky GPU. Dust cover je většinou na odlomení někdy je na odšroubování na to vždy pozor. Nyní si otevřeme slot lock na PCiE a vložíme GPU a zatlačíme tak, aby to cvaknulo. Teď připojíme 8 pinový konektor z PSU do GPU a pokud má naše GPU 2 sloty na 8 pin doporučuju použí oba pro stabilitu systému.
  
  Jedním z posledních kroků je přidělání našeho storage v mém případě 1x SATA 3 SSD a 1x SATA 3 HDD, tím pádem si připravým 2 konektory z PSU na SATA a 2 SATA 3 konektory na MoBo. HDD vložím do racku na 3,5 HDD a přišroubuju. SSD jsem si dal na vnitřní část case na bočnici a přišrouboval jsem. Po přidělání zapojím všechny kabely a pro některé z nás to je vše. 
  
  Pokud máte rádi pořádek a máte třeba prosklenou bočnici u case tak se můžete vrhnout na cabel managment. Já jsem se pouze zaměřil na kabely co jsou viditelné skrz prosklenou bočnici a kabely co jsou vidět pouze po sundání zadní bočnice jsem nechal více méně na volno jelikož stejně nejsou vidět.
  
  A už můžeme zkusit zapnout počítač. Pokud se zapne do BIOSu gratuluju máte postavený svůj první PC pokud ne tak jste někde v postupu udělali chybu a musíte začít backtrackovat svoje kroky. V mém případě PC fungoval an první pokus a rovnou jsem se vrhnul na instalaci Windows.
  

---


## Instalace Windows


Potřebné věci:


  1. USB Flash disk aspoň 16Gb

  
  2. Windows klíč (doporučené)


Postup:


  Po zapnutí počítače se Vám automaticky otevře BIOS. V BIOSu si najděte BOOT možnosti a vyberte si svůj flash disk na kterém je ISO nebo přímo instalace Windows z jiného zařízení. Po vybrání BOOT zařízení se dostanete do instalačky Windows. Tam si nastavte vše dle svých periférií. Pozor až se dostanete do části kam chcete dát systém tak je nutné vědět, že ten disk bude formátovaný a uložený data se vymažou. Pokud chcete data zálohovat doporučuji předem udělat klon disku a po instalaci windows dát klon disku na nový nebo ten stajný, ale nikdy neklonovat disk se starým sytémem! Já si osobně vždy formátuju všechny disky a partitiony, abych se s tím nemusel starat. A tohle je vš k instalaci až takhle jendoduché to je!

---

## Legenda slov

- GPU -> Graphic processor unit -> Grafická karta
- CPU -> Central processor unit -> Procesor
- MoBo -> Motherboard -> Základní deska
- PSU -> Power supply -> Zdroj
- HDD -> Hard disk
- SSD -> Solid state drive

---

## Citace
ZTT EXTRAS. How to Build a $1,400 Gaming PC Build (Ryzen 7 5800XT and RX 9060 XT). Online. 2026. Dostupné z: https://www.youtube.com/watch?v=QFWmvjTaJ8o&t=1324s. [cit. 2026-02-10].
LINUS TECH TIPS. How to Build a PC, the last guide you’ll ever need! (2024 Update). Online. 2024. Dostupné z: https://www.youtube.com/watch?v=s1fxZ-VWs2U. [cit. 2026-02-10].
IGABYTE TECHNOLOGY CO., LTD. (2023). B550M-K User’s Manual (Rev. 1001). Gigabyte. Staženo z https://download.gigabyte.com/FileList/Manual/mb_manual_b550m-k_e_1001.pdf?v=87bba5603e0f20b147063e0eea0c7e40
