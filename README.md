# Úloha 3D

1. Vytvor si clone Unity projektu z gitu (TODO: add link), vytvor si vlastnú vetvu, na ktorej budeš pracovať
1. V priečinku Scenes vytvor scénu s názvom "Level{MenoPriezvisko}" bez diakritiky (napr. LevelPeterMaly)
1. Uprav svoju scénu tak, aby predstavovala western mestečko
    1. Vytvor terén veľkosti 300x300 (v projekte už máte Terrian tools a Terrian tools samples pre zjednodušenie práce)
    2. Aplikuj na terén textúry (využi minimálne 3 rôzne layers, môžeš používať dostupné layers alebo vytvoriť nové)
    3. Na teréne vytvor vlastné western mestečko z dostupných assetov (Models/Wild West Western folder, môžeš stiahnuť aj dalšie, ale nie je to vôbec nutné a pozor na nekvalitné assety). Z hotového mestečka sprav prefab (nech sú assety mesta pod prázdnym game objectom). Pozor: assety budov obsahujú jeden zbytočný komponent, ktorý treba odstrániť (alebo minimálne vypnúť) pre správne fungovanie pri spustenej hre
1. Pridaj do scény autíčko (Models/ARCADE FREE Racing Car obsahuje ich viacero). Rozanimuj autíčko, aby prešlo cez mesto (alebo aby zastavila pred niektorým domov atď.), nech z toho vznikne cca 3-5 sekundová animácia.
1. Pridajte ďalšiu kamery, nech sú zábery z kamier renderované na dve polky obrazovky
    1. pomôcka1: keďže používame URP, treba hľadať vhodné nastavenie pri kamere v časti output
    2. pomôcka 2: v scéne majte iba jeden audio listener
1. Pridajte postprocessing na kamery, aby výsledný obraz pôsobil, ako zábery bezpečnostných kamier (Pomôcka: keďže používame URP, netreba sťahovať zvlášť package, stačí do scény vytvoriť global volume a tam nastaviť profil s postprocessing efektmi. Na kamerách je potrebné povoliť post processing). Pridajte minimálne 3 rôzne efekty.
1. Nastavte osvetlenie scény tak, aby sa dalo baknuť svetlo v scéne (bake nemusíš púštať kvôli času, ale aby to bolo nastavené)
1. Projekt nahrajte na git (do svojej vetvy) a vytvorte pull request do hlavnej vetvy
