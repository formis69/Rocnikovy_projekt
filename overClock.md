# Optimalizace a přetaktování (Overclocking)

---

## Procesor (CPU)

U procesoru jsem se jako začátečník nepouštěl do riskantních manuálních změn napětí či násobiče, ale zaměřil jsem se spíše na optimalizaci chování systému.

Pro správu napájení jsem využil externí nástroj **ParkControl**. Zde jsem provedl manuální konfiguraci, jejímž cílem bylo zamezit zbytečnému „uspávání“ jader (core parking) při běžné práci, jako je prohlížení webu, ale zároveň zajistit, aby procesor nebyl nijak limitován při hraní her.

Dále jsem přímo v prostředí **BIOSu** aktivoval funkci pro automatické navyšování taktu (AMD CPU Boost / Precision Boost), která zajišťuje maximální možný výkon v zátěži. Součástí těchto úprav bylo i ladění chlazení – upravil jsem křivku ventilátorů (fan curve) tak, aby chlazení reagovalo efektivněji na změny teplot a procesor se nepřehříval.

---

## Grafická karta (GPU)

U grafické karty jsem si troufl na výraznější zásahy. Zaměřil jsem se na navýšení taktu jádra (Core Clock), kde se mi podařilo dosáhnout stabilního posunu o **+300 MHz**.

Dle mých měření toto přetaktování přineslo nárůst výkonu přibližně o **4 %**, což se pozitivně projevilo jak ve 3D renderingu (hry), tak ve 2D operacích. Ruku v ruce s vyšším výkonem jsem musel upravit i chování ventilátorů. Nastavil jsem vlastní křivku otáček v závislosti na využití GPU a teplotě, abych udržel kartu v bezpečných provozních podmínkách i při vyšší zátěži.

---

## Shrnutí a získané zkušenosti

Hlavním cílem tohoto procesu bylo zvýšení celkové rychlosti a odezvy systému. Jelikož jsem v oblasti overclockingu začátečník, volil jsem změny, které nevyžadují hluboké inženýrské znalosti a nepředstavují kritické riziko pro hardware.

Během procesu jsem se naučil pracovat s benchmarky a pochopil jsem, že overclocking není jen o honbě za „větším číslem“, ale o hledání rovnováhy. Důležité je, aby úpravy skutečně přinesly reálný výkon a stabilitu, nikoliv jen vyšší spotřebu nebo nestabilní systém.

---

## Citace

1. BLACKBIRD PC TECH. *How To Overclock Your GPU The Right Way!* [Video]. YouTube, 2024. Dostupné z: https://www.youtube.com/watch?v=VLL2jUSxf_M. [cit. 2026-02-10].
2. LESTRIPEZ. *Msi Afterburner: How To Overclock ANY GPU in 2025! ✅ (Easy OC Guide)* [Video]. YouTube, 2025. Dostupné z: https://www.youtube.com/watch?v=YuFGm5SWuwQ. [cit. 2026-02-10].
3. CODECADEMY TEAM. *How to Overclock a CPU: Risks and Benefits*. Online. Codecademy, 2025. Dostupné z: https://www.codecademy.com/resources/blog/how-to-overclock-cpu. [cit. 2026-02-10].
GOOGLE. Gemini [online]. Verze Gemini 3 Pro. Mountain View: Google, 2026 [cit. 2026-02-11]. Dostupné z: https://gemini.google.com.
