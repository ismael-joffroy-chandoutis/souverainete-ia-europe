# Souveraineté numérique européenne et intelligence artificielle

## État des lieux 2024-2026

*🇬🇧 [Read in English](en.md)*

> Texte critique compagnon, sur le mot « souveraineté » lui-même : [« Souveraineté numérique » : critique d'un concept et lexiques alternatifs](https://github.com/12georgiadis/souverainete-numerique-critique).

---

## Résumé

La « souveraineté numérique » européenne en matière d'intelligence artificielle se heurte à une chaîne de production mondialisée et hautement concentrée. L'Europe additionne des briques réelles, parfois de premier rang, mais ne maîtrise aucune chaîne complète, de la puce au modèle. Un seul maillon lui est véritablement irremplaçable : la lithographie d'ASML, aux Pays-Bas. Sur la conception des accélérateurs d'IA, la fabrication de pointe, l'échelle du cloud et le financement, la dépendance reste structurelle. Le discours politique d'une autonomie « de bout en bout » contraste avec cette réalité, ce qui constitue l'un des objets de débat les plus documentés du sujet. Ce rapport décrit les positions des promoteurs et des critiques sans trancher.

---

## 1. Le concept : souveraineté numérique et autonomie stratégique

La **souveraineté numérique** désigne la capacité d'un État ou de l'Union à contrôler ses infrastructures, services et données, et à « choisir à chaque couche de la pile », du matériel aux services (Atlantic Council). L'**autonomie stratégique**, concept né dans la défense, a été étendu au numérique. La Commission emploie la formule d'**autonomie stratégique ouverte**, qui privilégie l'ouverture commerciale et le *friendshoring* plutôt que l'autarcie (Clingendael).

Le terme a été popularisé par Emmanuel Macron à partir du discours de la Sorbonne (26 septembre 2017), puis érigé en pilier de la Commission von der Leyen, avec une vice-présidente exécutive dédiée à la « souveraineté technologique » depuis décembre 2024, Henna Virkkunen, qui résume l'objectif par la formule « We want to be sure nobody has a kill switch » (TechPolicy.Press). Le 3 juin 2026, la Commission a dévoilé un « European Technological Sovereignty Package » (Cloud and AI Development Act, Chips Act 2.0, stratégie open source) (Commission européenne).

La littérature académique reste critique. Le concept est qualifié de **« flou par nature »** (*fuzzy concept*), au sens variable (Tandfonline). Plusieurs chercheurs (Pohle, Broeders) notent que cette indétermination même facilite la construction de coalitions politiques (Wiley, JCMS 2025), tout en masquant l'écart entre le poids réglementaire de l'UE et son mandat industriel limité (Broeders et al., JCMS 2023). Une partie de la littérature y voit un protectionnisme déguisé. Les États membres sont divisés : la France et l'Allemagne portent une version interventionniste, tandis que les pays nordiques redoutent un glissement protectionniste (CEPA). Il n'existe pas de consensus sur l'atteignabilité de la souveraineté numérique : c'est l'objet même du débat.

---

## 2. La couche silicium : puces, fonderies, lithographie

### 2.1 Une dépendance trilatérale

La chaîne des semi-conducteurs avancés repose sur trois maillons concentrés et difficilement substituables, qu'aucun acteur ne maîtrise dans leur ensemble.

- **Conception (États-Unis).** Nvidia détient de l'ordre de 80 à 90 % du marché des accélérateurs d'IA selon le périmètre et l'année (Carbon Credits ; SiliconAnalysts), sa domination tenant autant au matériel qu'à l'écosystème logiciel propriétaire **CUDA**. Les outils de conception (EDA), indispensables, sont dominés par les américains Synopsys et Cadence devant l'allemand Siemens EDA (MarketsandMarkets).
- **Fabrication (Taïwan).** TSMC concentre environ 70 % du marché de la fonderie et plus de 90 % de la production de pointe (nœuds 3 nm et 5 nm) ; sa production de masse du 2 nm a démarré fin 2025, premier client Apple (TrendForce ; TechSpot).
- **Lithographie (Pays-Bas).** ASML est le seul fabricant au monde de scanners à ultraviolet extrême (EUV), indispensables aux puces les plus avancées (The Motley Fool).

### 2.2 SiPearl et le processeur Rhea1

SiPearl, société française issue de l'European Processor Initiative, industrialise le CPU haute performance européen Rhea1, doté de 80 cœurs Arm Neoverse V1 (SiPearl ; EE Times). Point essentiel souvent confondu dans la presse : **Rhea1 est un processeur central (CPU), non un accélérateur d'entraînement d'IA**. La puce est elle-même **gravée chez TSMC, en 6 nm** : même le processeur « souverain » européen dépend de Taïwan (The Register). Son tape-out final a été confié à TSMC en juillet 2025, plusieurs années après la cible initiale de 2023, le premier allumage du silicium étant annoncé pour le printemps 2026 (DataCenterDynamics ; itdaily). SiPearl a clôturé une série A de 130 M€ en juillet 2025 et prépare une série B d'environ 200 M€ (HPCwire).

### 2.3 RISC-V : l'accélérateur souverain au stade prototype

La voie d'un accélérateur d'IA européen passe par l'architecture ouverte **RISC-V**, distincte de SiPearl. L'European Processor Initiative a produit la puce de test EPAC, fabriquée chez GlobalFoundries, restée au stade prototype (European Processor Initiative). Le projet **DARE** (*Digital Autonomy with RISC-V in Europe*), lancé en mars 2025 et coordonné par le Barcelona Supercomputing Center, vise un processeur généraliste, un accélérateur vectoriel et une unité d'inférence IA, avec des résultats échelonnés jusqu'en 2030 (EuroHPC JU). À ce jour, aucun accélérateur RISC-V européen n'est en production dans le supercalcul, et un acteur clé, le tchèque Codasip, a lancé un processus de vente en juillet 2025 malgré d'importants financements (EE Times).

### 2.4 ASML : le seul verrou européen

ASML détient un monopole de fait sur la lithographie EUV (et environ 90 % de la lithographie avancée), après l'abandon de Nikon et Canon (The Motley Fool). TSMC, Intel et Samsung en dépendent : aucune puce de pointe n'existe sans ses machines. La génération **High-NA EUV** (TWINSCAN EXE:5000, puis EXE:5200) vise les nœuds sous-2 nm, pour un prix unitaire de l'ordre de 350 M€, la production de volume n'étant pas attendue avant 2027-2028 (Tom's Hardware). ASML est ainsi qualifiée de « principale monnaie d'échange de l'UE » dans les négociations transatlantiques (IEP Bocconi). En 2025, la société a réalisé 32,7 Md€ de ventes et 9,6 Md€ de résultat net (ASML). **Aucun système EUV n'a jamais été vendu à la Chine**, conformément aux restrictions néerlandaises et américaines, et les Pays-Bas ont étendu en septembre 2024 leur régime de licences à certaines machines DUV (ASML ; TrendForce).

### 2.5 Le trou : pas de fonderie de pointe sur le sol européen

L'Europe n'a aucune usine de logique de pointe. Le seul projet « pointe » envisagé, la méga-fab d'Intel à Magdebourg (~30 Md€), a été **annulé en juillet 2025**, les ~10 Md€ de subventions allemandes n'ayant jamais été débloqués (Xinhua ; Heise). Le projet ESMC à Dresde (coentreprise TSMC, Bosch, Infineon, NXP, plus de 10 Md€) produira des **nœuds matures** (28/22 nm et 16/12 nm), avec une production de masse ciblée en 2027 (NXP ; TrendForce). En France, la gigafactory STMicroelectronics-GlobalFoundries de Crolles (~7,5 Md€, jusqu'à 2,9 Md€ d'aides d'État autorisées) relève elle aussi d'une technologie mature, le FD-SOI (Le Journal des Entreprises).

L'**European Chips Act** (règlement 2023/1781, entré en vigueur le 21 septembre 2023) vise à porter la part de l'UE dans la production mondiale de ~10 % à 20 % d'ici 2030, en mobilisant plus de 43 Md€ public-privé (Commission européenne). La **Cour des comptes européenne** (rapport spécial 12/2025) juge cet objectif « très improbable », projetant une part plafonnant à **11,7 % en 2030** (ECA). Dix États membres ont demandé en mai 2025 de revoir les objectifs à la baisse, et un « Chips Act 2.0 » a été présenté en juin 2026 (Euronews ; Commission européenne).

### 2.6 Pas de GPU d'entraînement souverain

Aucun accélérateur d'entraînement d'IA souverain européen n'existe à l'échelle. Les GPU d'entraînement (Nvidia, gravés chez TSMC) n'ont pas d'équivalent européen ; les acteurs du continent se positionnent sur l'inférence et le *edge*, comme le néerlandais Axelera AI (puces Metis puis Europa), soutenu par EuroHPC, mais pas sur l'entraînement de grands modèles (Axelera ; SiliconAnalysts).

---

## 3. La couche modèles et logiciel

### 3.1 Mistral AI

Mistral AI (Paris), fondée en 2023 par d'anciens de Google DeepMind et Meta, applique une stratégie de poids ouverts **graduée** : ses petits et moyens modèles (Mistral 7B, Mixtral, Mistral Small, Magistral Small) sont publiés sous licence Apache 2.0, tandis que ses modèles les plus avancés relèvent de licences restrictives ou d'un accès par API seulement (Mistral ; platform-docs). La société a levé en septembre 2025 une **série C de 1,7 Md€**, portant sa valorisation à 11,7 Md€, dans un tour mené par **ASML** (environ 11 % du capital) : c'est la plus haute valorisation d'IA d'Europe (Mistral ; ASML). En janvier 2026, le ministère français des Armées lui a attribué un accord-cadre pour déployer ses modèles sur infrastructure contrôlée par la France (Raconteur).

### 3.2 Kyutai

Kyutai, présenté comme le premier laboratoire de recherche européen indépendant dédié à l'open science en IA, est une structure à but non lucratif financée par Xavier Niel, Rodolphe Saadé et Eric Schmidt, dotée d'environ 300 M€ (TechCrunch ; Fortune). Ses modèles (Moshi, modèle vocal full-duplex ; Helium ; modules de synthèse et reconnaissance vocale) sont publiés sous licence ouverte, les poids étant sous CC-BY 4.0 (GitHub kyutai-labs).

### 3.3 La thèse de la « couche ouverte »

L'angle de souveraineté le plus souvent jugé réaliste consiste à miser sur les **poids ouverts**. Un rapport de la Commission (« Europe's Open-Source AI Landscape », décembre 2025) soutient que l'open source permet de déployer l'IA sans dépendre de modèles propriétaires et recommande de « mener via une IA ouverte, multilingue et sectorielle » plutôt que de courir après l'échelle (Commission européenne). Arthur Mensch (Mistral) a averti devant l'Assemblée nationale que l'Europe risquait de devenir un « État vassal » sans IA propre, les poids ouverts permettant un *fine-tuning* local impossible avec des modèles fermés (Cybernews). Cette thèse est contestée : l'International Center for Law & Economics dénonce une « trappe de la souveraineté numérique » consistant à bloquer l'accès plutôt qu'à construire (ICLE). Il faut noter que le rapport Draghi (2024) prône investissement et souveraineté sans trancher explicitement le débat ouvert/fermé.

### 3.4 La dépendance logicielle

La couche logicielle reste largement américaine : l'écosystème CUDA de Nvidia verrouille les développeurs, et les principaux cadres d'apprentissage (PyTorch, TensorFlow) sont d'origine américaine (Quartz France). Le « modèle souverain » Mistral s'entraîne sur des dizaines de milliers de puces Nvidia (inasp.fr).

---

## 4. La couche cloud et données

### 4.1 Une asymétrie d'échelle

OVHcloud (Roubaix), coté à Paris, a dépassé pour la première fois le milliard d'euros de chiffre d'affaires en 2025 (1 084,6 M€) avec 44 data centers (OVHcloud). Scaleway (groupe Iliad) exploite un supercalculateur de 1 016 GPU H100 et a été retenu par Nvidia pour le *compute* souverain de DGX Cloud Lepton (Scaleway). Mais l'échelle reste sans commune mesure avec les hyperscalers : les trois géants américains (AWS, Azure, Google) contrôlent environ **70 % du marché cloud européen**, la part des fournisseurs européens étant tombée de 29 % (2017) à 15 % (Synergy/TelecomTV). Un seul hyperscaler dépense davantage en *capex* IA annuel que la totalité du marché cloud européen (ValueAdd VC). À titre de repère, chaque « AI gigafactory » européenne prévue doit héberger au moins 100 000 GPU équivalents H100, soit environ cent fois le cluster de Scaleway (STL Partners).

### 4.2 Le US CLOUD Act et l'extraterritorialité

Le **CLOUD Act** (2018) oblige tout fournisseur sous juridiction américaine à remettre les données qu'il détient sur mandat américain, quel que soit le lieu de stockage (Exoscale). Héberger dans un data center européen d'AWS, Azure ou Google ne suffit donc pas à y échapper, ce qui crée un conflit documenté avec l'article 48 du RGPD (Kiteworks). Le Data Privacy Framework EU-US (2023) ne neutralise ni le CLOUD Act ni la surveillance FISA 702, et a été fragilisé début 2025 par le retrait de membres de l'organe de contrôle américain PCLOB (Clifford Chance). Au plan technique, la **Foreign Direct Product Rule** soumet à la juridiction américaine tout produit utilisant une technologie américaine contrôlée, même fabriqué hors des États-Unis (Scowcroft).

### 4.3 Gaia-X et les « clouds de confiance »

L'initiative franco-allemande **Gaia-X** (2020) a connu un développement lent et critiqué ; la présence de membres non européens (Microsoft, AWS, Google, Huawei) a nourri l'accusation de *sovereignty-washing*, Scaleway ayant quitté le projet dès 2021 pour ce motif (Computer Weekly). Les « clouds de confiance » français **Bleu** (Capgemini-Orange sur Azure) et **S3ns** (Thales sur Google Cloud) illustrent la tension : S3ns a obtenu la qualification SecNumCloud de l'ANSSI fin 2025, qui selon l'agence le soustrairait au CLOUD Act, mais de nombreux observateurs estiment qu'aucun n'est réellement souverain puisque la technologie vient à 100 % de Microsoft ou Google (Usine Digitale ; Journal du Net). Le 17 avril 2026, la Commission a attribué un premier accord-cadre de cloud souverain à quatre groupements (plafond 180 M€ sur six ans), tout en suscitant une polémique car l'un d'eux repose sur Google Cloud (Commission européenne ; Clubic).

---

## 5. Le calcul public européen

### 5.1 EuroHPC

L'entreprise commune **EuroHPC** co-finance et possède le réseau de supercalculateurs publics du continent. **JUPITER** (Jülich, Allemagne), inauguré le 5 septembre 2025, est le **premier supercalculateur exascale d'Europe** et figurait au 4e rang mondial fin 2025 (EuroHPC JU ; TOP500). Fait notable pour la souveraineté : sa puissance exascale repose aujourd'hui sur le module « Booster » à base de superpuces **Nvidia GH200 Grace Hopper**, le module CPU à base de Rhea1 de SiPearl étant une extension prévue ultérieurement (DataCenterDynamics). Même le fleuron européen tourne donc d'abord sur du Nvidia. **LUMI** (Kajaani, Finlande) est alimenté à 100 % par de l'hydroélectricité, sa chaleur résiduelle couvrant environ 20 % du chauffage urbain de la ville (LUMI). Les systèmes pré-exascale **Leonardo** (Italie) et **MareNostrum 5** (Espagne) complètent le réseau (EuroHPC JU).

### 5.2 Jean Zay

En France, **Jean Zay** (IDRIS/CNRS, opéré par GENCI) est le supercalculateur d'IA public national. Son extension de 2024 lui a ajouté 1 456 GPU Nvidia H100, portant sa puissance crête à 125,9 PFlop/s (IDRIS ; GENCI). Présenté comme le supercalculateur d'IA le plus utilisé d'Europe, il est déjà décrit comme **saturé** par la demande (Clubic).

### 5.3 AI Factories et gigafactories

EuroHPC a structuré en 2025 un réseau d'**AI Factories** adossées aux supercalculateurs publics, porté à 19 unités dans 16 États membres en octobre 2025 (Silicon Saxony). À l'étage supérieur, l'initiative **InvestAI** (février 2025) a engagé jusqu'à 20 Md€ pour établir jusqu'à cinq **« AI gigafactories »**, visant chacune environ 100 000 puces de dernière génération (Conseil de l'UE). Le nombre final, les sites et le calendrier de ces gigafactories ne sont pas arrêtés.

---

## 6. Énergie et climat

### 6.1 La consommation

Selon l'Agence internationale de l'énergie (rapport *Energy and AI*, 2025), la consommation électrique mondiale des data centers devrait **doubler pour atteindre environ 945 TWh en 2030** (contre ~415 TWh en 2024), soit un peu moins de 3 % de l'électricité mondiale, l'IA étant le principal moteur d'une croissance d'environ 15 % par an (AIE ; Data Center Dynamics).

### 6.2 Le mix et le débat

En 2024, le mix mondial alimentant les data centers se répartissait approximativement entre charbon (~30 %), renouvelables (~27 %), gaz (~26 %) et nucléaire (~15 %), la situation européenne, et a fortiori française, étant nettement plus décarbonée (AIE). Plusieurs géants américains se tournent vers le nucléaire pour une production continue : Microsoft (redémarrage de Three Mile Island), Amazon, Google et Meta ont signé des accords en 2024-2025 (Trellis). Une mise en garde s'impose ici : le nucléaire est **faiblement émetteur de CO2 à l'usage, mais ne saurait être qualifié de « propre »**, la question des déchets radioactifs de longue durée n'étant pas résolue ; il s'agit d'un débat politique et non d'un fait technique tranché. À l'inverse, l'hydroélectricité (cas de LUMI) peut être présentée comme renouvelable et bas carbone.

### 6.3 L'effet rebond

Le « paradoxe de Jevons numérique » indique que les gains d'efficacité algorithmique et matérielle peuvent **augmenter** plutôt que réduire l'empreinte énergétique de l'IA, la baisse des coûts stimulant l'usage total ; les modèles rapportent des magnitudes de rebond souvent comprises entre 30 et 60 % (Nature ; arXiv). Le sixième rapport d'évaluation du GIEC (groupe de travail III) souligne le potentiel des mesures « côté demande » tout en relevant l'ambivalence de la numérisation (efficacité contre effets rebond) ; la formulation exacte de l'AR6 est à reciter depuis le texte avant citation définitive (GIEC).

---

## 7. Le quantique

### 7.1 Une compétitivité française réelle sur le matériel

Contrairement à l'IA générative, la France dispose, sur le **matériel quantique**, de champions de rang mondial répartis sur plusieurs architectures : **Alice & Bob** (*cat qubits*, série B de 100 M€ en janvier 2025), **Pasqal** (atomes neutres), **Quandela** (photonique), auxquels s'ajoutent Quobly et C12 (HPCwire ; The Next Web). Le pays finance ainsi cinq architectures en parallèle, là où les États-Unis se concentrent sur les circuits supraconducteurs. Le **Plan Quantique national** (2021, 1,8 Md€) a été complété par le programme PROQCIMA (2024, 500 M€), qui vise un démonstrateur à 128 qubits logiques tolérant aux fautes d'ici 2030, et par une rallonge d'environ 1 Md€ annoncée en mai 2026 (Wikipedia ; PostQuantum). Ces objectifs sont des cibles politiques ambitieuses, non des résultats acquis : aucun acteur n'a démontré un calculateur quantique tolérant aux fautes à cette échelle.

### 7.2 La cryptographie post-quantique

Le NIST a finalisé en août 2024 ses trois premiers standards de cryptographie post-quantique (FIPS 203 ML-KEM, FIPS 204 ML-DSA, FIPS 205 SLH-DSA) (NIST). La menace dite **« harvest now, decrypt later »** consiste à intercepter et stocker dès aujourd'hui des données chiffrées pour les déchiffrer rétroactivement le jour où existeront des ordinateurs quantiques pertinents (Palo Alto). L'horizon d'un tel calculateur capable de casser RSA est estimé par certains autour de 2035, mais cette date est très incertaine et contestée.

---

## 8. Investissements publics et décalage discours/réalité

### 8.1 Les grands chiffres d'annonces

Plusieurs sommets ont produit des montants record. À l'AI Action Summit de Paris (février 2025), Emmanuel Macron a annoncé **109 Md€** d'investissements privés (Émirats/MGX, Brookfield, Fluidstack, Bpifrance), présentés comme la réponse européenne au plan américain Stargate (au moins 500 Md$ sur quatre ans) (franceinfo ; CNews). Au sommet Choose France de juin 2026, le total annoncé a atteint **93 Md€**, dont l'engagement phare de SoftBank pour des data centers d'IA en France : sur 75 Md€ évoqués, **seuls 45 Md€ sont fermes**, les 30 Md€ restants étant conditionnés à la réussite d'une première phase (DGE ; actuIA). En parallèle, la Commission a annoncé mobiliser 200 Md€ pour l'IA (InvestAI). Un avertissement transversal s'impose : ces montants sont des **annonces ou engagements**, souvent pluriannuels, parfois conditionnels et révisables, à distinguer des investissements réalisés.

### 8.2 Le campus IA et les data centers

Une coentreprise MGX, Bpifrance, Mistral et Nvidia prévoit le plus grand campus d'IA d'Europe à Fouju (Seine-et-Marne), d'une puissance de 1,4 GW, opérationnel visé pour 2028 (Polytechnique ; DataCenterDynamics). La **loi de simplification de la vie économique du 26 mai 2026** permet de qualifier un data center de « projet d'intérêt national majeur », ouvrant des procédures d'urbanisme et de raccordement électrique accélérées, avec un garde-fou en cas de ressource en eau insuffisante (Légifrance ; Gossement Avocats).

### 8.3 Annoncé n'est pas réalisé

Le cas de **Fluidstack** illustre l'écart : annonce phare du sommet 2025 (10 Md€, environ un quart de l'édition), le projet a été **abandonné début 2026**, l'entreprise réorientant ses investissements vers les États-Unis (Usine Nouvelle). Le bilan historique de Choose France fait état de « 120 projets opérationnels, 12 abandonnés, le reste en cours », Business France invoquant la confidentialité (franceinfo).

### 8.4 Voix critiques

Plusieurs analystes documentent le décalage. Ophélie Coelho (IRIS) estime que « l'Europe court après des technologies qui ne sont pas matures » et que ces data centers feront tourner des solutions d'acteurs américains dominants (Techniques de l'Ingénieur). Asma Mhalla (EHESS) diagnostique une « souveraineté normative défensive » (DSA, DMA, AI Act) sans stratégie industrielle structurée (Institut Montaigne). L'Observatoire des multinationales a enquêté sur le lobby des data centers, dont les acteurs français pèsent moins de 10 % du secteur, et La Quadrature du Net qualifie la loi de simplification de « déni de démocratie » (Observatoire des multinationales ; La Quadrature du Net). Un paradoxe est régulièrement formulé : les États poursuivent la souveraineté « en se rendant plus dépendants des mêmes entreprises étrangères dont ils prétendent se protéger » (Quartz France), l'Europe ne captant qu'environ 5 % du capital-risque mondial contre 52 % pour les États-Unis (Aqui).

### 8.5 Les rapports de référence

Le **rapport Draghi** (septembre 2024) fait du retard technologique la cause centrale de l'écart de productivité entre l'UE et les États-Unis : quatre seulement des cinquante premières entreprises technologiques mondiales sont européennes, et il recommande environ 800 Md€ d'investissement annuel (4 à 5 % du PIB), recommandation elle-même contestée (TechPolicy.Press ; ITIF). Le **rapport Letta** (avril 2024) propose une « cinquième liberté » de circulation de la connaissance (Conseil de l'UE).

---

## 9. Synthèse : ce que l'Europe tient, ce qui lui manque

L'Europe **tient** : un concepteur de CPU (SiPearl, gravé toutefois à Taïwan), un verrou de lithographie irremplaçable (ASML), une R&D de pointe (Imec), des modèles à poids ouverts compétitifs (Mistral, Kyutai), deux clouds souverains d'échelle modeste (OVHcloud, Scaleway), des supercalculateurs publics dont certains très propres (LUMI), et une vraie avance sur le matériel quantique.

Il lui **manque** : une fonderie de pointe sur son sol (le seul projet, Intel Magdebourg, est annulé ; ESMC Dresde reste sur des nœuds matures), un GPU d'entraînement d'IA souverain, une échelle de cloud comparable aux hyperscalers, une souveraineté des données face à l'extraterritorialité américaine, et un volume de financement à la hauteur.

Le levier réellement irremplaçable est en amont, chez ASML. Le reste est constitué de **briques vraies dans un mur qui n'est pas construit**. Le discours politique d'une autonomie complète « de la puce au modèle » survend cette situation, ce que documentent abondamment les sources critiques. La voie présentée comme la plus réaliste, par la Commission comme par les industriels, est celle de la **couche ouverte** (modèles, données, gouvernance) et du calcul public mutualisé, plutôt que la reconstruction d'une chaîne complète.

---

## Zones d'incertitude

- **Calendriers industriels prospectifs** (Rhea1/Rhea2, montée du 2 nm, ESMC Dresde, gigafactories IA) : cibles susceptibles de glisser.
- **Montants d'investissement** : annonces et engagements, souvent conditionnels ou révisables, parfois abandonnés ; à distinguer des sommes réalisées.
- **Parts de marché** (TSMC, Nvidia, ASML en Chine) : variables selon la source, l'année et le périmètre.
- **Contrôles à l'export américains** : domaine très volatil (AI Diffusion Rule abrogée en 2025, MATCH Act et Chips Act 2.0 non adoptés à mi-2026).
- **Cadre juridique des transferts de données** : le Data Privacy Framework n'est pas invalidé à mi-2026, mais fragilisé ; un « Schrems III » est pendant.
- **Formulation exacte du GIEC AR6** sur la numérisation : à reciter depuis le texte source.
- **Objectifs quantiques français** (128 qubits logiques en 2030) : cibles, pas résultats.

---

## Sources

**Concept et discours.** Atlantic Council, « Digital Sovereignty: Europe's Declaration of Independence » ; Clingendael, « Open Strategic Autonomy » ; Tandfonline / Wiley (Pohle, Broeders) sur le flou conceptuel ; CEPA, « Divided Digital Europe » ; TechPolicy.Press et Commission européenne (Tech Sovereignty Package, 3 juin 2026) ; vie-publique.fr (discours Macron Berlin, 18 nov. 2025).

**Silicium et matériel.** SiPearl (rhea1) ; EE Times, The Register, DataCenterDynamics, HPCwire (Rhea1, série A) ; European Processor Initiative et EuroHPC JU / BSC (EPAC, DARE) ; EE Times (Codasip) ; Commission européenne et Cour des comptes européenne (Chips Act, rapport spécial 12/2025) ; Euronews (révision des objectifs) ; The Motley Fool, Tom's Hardware, IEP Bocconi, ASML (EUV, High-NA, résultats 2025, export) ; TrendForce, TechSpot (TSMC 2 nm) ; NXP, TrendForce (ESMC Dresde) ; Xinhua, Heise, EENewsEurope (Intel Magdebourg) ; Carbon Credits, SiliconAnalysts, Axelera (Nvidia, accélérateurs).

**Modèles et logiciel.** Mistral et ASML (série C, partenariat) ; platform-docs Mistral (licences) ; TechCrunch (Mistral, historique) ; TechCrunch, Fortune, iliad, GitHub kyutai-labs (Kyutai, Moshi) ; Commission européenne (« Europe's Open-Source AI Landscape ») ; Cybernews, AI Business (Mensch) ; ICLE (critique) ; Raconteur (accord-cadre Armées) ; Quartz France, inasp.fr (dépendance logicielle).

**Cloud et données.** OVHcloud (résultats FY25) ; Scaleway, Nvidia (Nabuchodonosor, DGX Cloud Lepton) ; Synergy/TelecomTV, ValueAdd VC, STL Partners (asymétrie d'échelle) ; Exoscale, Kiteworks, Clifford Chance, Scowcroft (CLOUD Act, FISA, FDPR) ; Gaia-X, Computer Weekly, Tandfonline (Gaia-X) ; Usine Digitale, Journal du Net, Clubic, Commission européenne (clouds de confiance, accord-cadre 2026).

**Calcul public.** EuroHPC JU, TOP500, DataCenterDynamics (JUPITER) ; LUMI (énergie) ; IDRIS, GENCI, Clubic (Jean Zay) ; Silicon Saxony, Conseil de l'UE (AI Factories, gigafactories, InvestAI).

**Énergie et climat.** Agence internationale de l'énergie, *Energy and AI* (2025) ; Data Center Dynamics ; Trellis (nucléaire Big Tech) ; Nature, arXiv (effet rebond) ; GIEC AR6 WG III.

**Quantique.** HPCwire (Alice & Bob), The Next Web, TechTimes (champions français) ; Wikipedia (Plan Quantique), PostQuantum, France 24 (PROQCIMA, rallonge 2026) ; NIST (standards PQC) ; Palo Alto Networks (« harvest now, decrypt later »).

**Investissements et discours/réalité.** DGE, actuIA, LeMagIT (Choose France 2026, SoftBank) ; franceinfo, Usine Digitale, CNews (AI Action Summit 2025, Stargate) ; Commission européenne, Euronews (InvestAI 200 Md€) ; Polytechnique, DataCenterDynamics (campus Fouju) ; Légifrance, Gossement Avocats, dcmag (loi de simplification, PINM) ; Usine Nouvelle (Fluidstack) ; Techniques de l'Ingénieur (Coelho), Institut Montaigne (Mhalla), Observatoire des multinationales, La Quadrature du Net (critiques) ; Aqui (capital-risque) ; TechPolicy.Press, TechHQ, ITIF (rapport Draghi), Conseil de l'UE (rapport Letta).

---

Ismaël Joffroy Chandoutis, 2026. Texte sous licence CC BY-NC-ND 4.0.

Par [Ismaël Joffroy Chandoutis](https://ismaeljoffroychandoutis.com).
