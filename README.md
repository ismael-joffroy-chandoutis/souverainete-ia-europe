**English** · [Français](README.fr.md)

# European digital sovereignty and artificial intelligence

## State of play 2024-2026


> Companion critical text, on the word "sovereignty" itself (in French): [« Souveraineté numérique » : critique d'un concept et lexiques alternatifs](https://github.com/ismael-joffroy-chandoutis/souverainete-numerique-critique).

---

## Summary

European "digital sovereignty" in the field of artificial intelligence runs up against a globalized and highly concentrated production chain. Europe adds up real building blocks, some of them first-rate, but it controls no complete chain from chip to model. Only one link is genuinely irreplaceable to it: ASML's lithography, in the Netherlands. On the design of AI accelerators, leading-edge manufacturing, cloud scale and financing, dependence remains structural. The political discourse of an "end-to-end" autonomy contrasts with this reality, which is one of the most thoroughly documented points of debate on the subject. This report describes the positions of the promoters and the critics without taking sides.

---

## 1. The concept: digital sovereignty and strategic autonomy

**Digital sovereignty** refers to the capacity of a State or of the Union to control its infrastructure, services and data, and to "choose at every layer of the stack", from hardware to services (Atlantic Council). **Strategic autonomy**, a concept born in defense, has been extended to the digital domain. The European Commission uses the formula **open strategic autonomy**, which favors commercial openness and *friendshoring* rather than autarky (Clingendael).

The term was popularized by Emmanuel Macron from the Sorbonne speech onward (26 September 2017), then established as a pillar of the von der Leyen Commission, with an executive vice-president dedicated to "technological sovereignty" since December 2024, Henna Virkkunen, who sums up the objective with the phrase "We want to be sure nobody has a kill switch" (TechPolicy.Press). On 3 June 2026, the Commission unveiled a "European Technological Sovereignty Package" (Cloud and AI Development Act, Chips Act 2.0, open source strategy) (European Commission).

The academic literature remains critical. The concept is described as **"fuzzy by nature"** (*fuzzy concept*), with a variable meaning (Tandfonline). Several researchers (Pohle, Broeders) note that this very indeterminacy makes it easier to build political coalitions (Wiley, JCMS 2025), while masking the gap between the EU's regulatory weight and its limited industrial mandate (Broeders et al., JCMS 2023). Part of the literature sees in it a disguised protectionism. Member States are divided: France and Germany champion an interventionist version, while the Nordic countries fear a protectionist drift (CEPA). There is no consensus on the achievability of digital sovereignty: that is precisely the object of the debate.

---

## 2. The silicon layer: chips, foundries, lithography

### 2.1 A trilateral dependence

The advanced semiconductor chain rests on three concentrated and hardly substitutable links, none of which any single actor controls in its entirety.

- **Design (United States).** Nvidia holds on the order of 80 to 90% of the AI accelerator market depending on scope and year (Carbon Credits; SiliconAnalysts), its dominance owing as much to hardware as to the proprietary **CUDA** software ecosystem. The design tools (EDA), which are indispensable, are dominated by the American firms Synopsys and Cadence ahead of the German Siemens EDA (MarketsandMarkets).
- **Manufacturing (Taiwan).** TSMC concentrates around 70% of the foundry market and more than 90% of leading-edge production (3 nm and 5 nm nodes); its 2 nm mass production began at the end of 2025, with Apple as first customer (TrendForce; TechSpot).
- **Lithography (Netherlands).** ASML is the only maker in the world of extreme ultraviolet (EUV) scanners, indispensable for the most advanced chips (The Motley Fool).

### 2.2 SiPearl and the Rhea1 processor

SiPearl, a French company spun out of the European Processor Initiative, is industrializing the European high-performance CPU Rhea1, equipped with 80 Arm Neoverse V1 cores (SiPearl; EE Times). A key point often confused in the press: **Rhea1 is a central processor (CPU), not an AI training accelerator**. The chip is itself **fabricated at TSMC, in 6 nm**: even the European "sovereign" processor depends on Taiwan (The Register). Its final tape-out was entrusted to TSMC in July 2025, several years after the initial 2023 target, with first silicon power-on announced for spring 2026 (DataCenterDynamics; itdaily). SiPearl closed a 130 M€ Series A in July 2025 and is preparing a Series B of about 200 M€ (HPCwire).

### 2.3 RISC-V: the sovereign accelerator at the prototype stage

The path toward a European AI accelerator runs through the open architecture **RISC-V**, distinct from SiPearl. The European Processor Initiative produced the EPAC test chip, fabricated at GlobalFoundries, which remained at the prototype stage (European Processor Initiative). The **DARE** project (*Digital Autonomy with RISC-V in Europe*), launched in March 2025 and coordinated by the Barcelona Supercomputing Center, aims at a general-purpose processor, a vector accelerator and an AI inference unit, with results staggered through 2030 (EuroHPC JU). To date, no European RISC-V accelerator is in production in supercomputing, and a key actor, the Czech firm Codasip, launched a sale process in July 2025 despite substantial funding (EE Times).

### 2.4 ASML: the only European lock

ASML holds a de facto monopoly on EUV lithography (and around 90% of advanced lithography), after Nikon and Canon withdrew (The Motley Fool). TSMC, Intel and Samsung depend on it: no leading-edge chip exists without its machines. The **High-NA EUV** generation (TWINSCAN EXE:5000, then EXE:5200) targets the sub-2 nm nodes, at a unit price on the order of 350 M€, with volume production not expected before 2027-2028 (Tom's Hardware). ASML is thus described as the "EU's main bargaining chip" in transatlantic negotiations (IEP Bocconi). In 2025, the company recorded 32.7 Bn€ in sales and 9.6 Bn€ in net income (ASML). **No EUV system has ever been sold to China**, in line with Dutch and American restrictions, and in September 2024 the Netherlands extended its licensing regime to certain DUV machines (ASML; TrendForce).

### 2.5 The gap: no leading-edge foundry on European soil

Europe has no leading-edge logic plant. The only "leading-edge" project considered, Intel's mega-fab in Magdeburg (~30 Bn€), was **cancelled in July 2025**, the ~10 Bn€ of German subsidies never having been released (Xinhua; Heise). The ESMC project in Dresden (a joint venture of TSMC, Bosch, Infineon, NXP, more than 10 Bn€) will produce **mature nodes** (28/22 nm and 16/12 nm), with mass production targeted for 2027 (NXP; TrendForce). In France, the STMicroelectronics-GlobalFoundries gigafactory in Crolles (~7.5 Bn€, up to 2.9 Bn€ of authorized State aid) likewise relies on a mature technology, FD-SOI (Le Journal des Entreprises).

The **European Chips Act** (regulation 2023/1781, in force since 21 September 2023) aims to raise the EU's share of global production from ~10% to 20% by 2030, by mobilizing more than 43 Bn€ of public and private funds (European Commission). The **European Court of Auditors** (special report 12/2025) judges this objective "highly unlikely", projecting a share peaking at **11.7% in 2030** (ECA). Ten Member States asked in May 2025 to revise the targets downward, and a "Chips Act 2.0" was presented in June 2026 (Euronews; European Commission).

### 2.6 No sovereign training GPU

No sovereign European AI training accelerator exists at scale. Training GPUs (Nvidia, fabricated at TSMC) have no European equivalent; actors on the continent position themselves on inference and the *edge*, like the Dutch firm Axelera AI (Metis chips then Europa), supported by EuroHPC, but not on the training of large models (Axelera; SiliconAnalysts).

---

## 3. The models and software layer

### 3.1 Mistral AI

Mistral AI (Paris), founded in 2023 by former staff of Google DeepMind and Meta, applies a **graduated** open-weights strategy: its small and medium models (Mistral 7B, Mixtral, Mistral Small, Magistral Small) are published under Apache 2.0 license, while its most advanced models fall under restrictive licenses or API-only access (Mistral; platform-docs). In September 2025 the company raised a **Series C of 1.7 Bn€**, bringing its valuation to 11.7 Bn€, in a round led by **ASML** (about 11% of the capital): this is the highest AI valuation in Europe (Mistral; ASML). In January 2026, the French Ministry of the Armed Forces awarded it a framework agreement to deploy its models on France-controlled infrastructure (Raconteur).

### 3.2 Kyutai

Kyutai, presented as the first independent European research laboratory dedicated to open science in AI, is a non-profit structure funded by Xavier Niel, Rodolphe Saadé and Eric Schmidt, endowed with about 300 M€ (TechCrunch; Fortune). Its models (Moshi, a full-duplex voice model; Helium; speech synthesis and recognition modules) are published under open license, the weights being under CC-BY 4.0 (GitHub kyutai-labs).

### 3.3 The "open layer" thesis

The angle of sovereignty most often judged realistic consists in betting on **open weights**. A Commission report ("Europe's Open-Source AI Landscape", December 2025) argues that open source makes it possible to deploy AI without depending on proprietary models and recommends "leading through open, multilingual and sectoral AI" rather than chasing scale (European Commission). Arthur Mensch (Mistral) warned before the National Assembly that Europe risked becoming a "vassal State" without AI of its own, open weights allowing local *fine-tuning* that is impossible with closed models (Cybernews). This thesis is contested: the International Center for Law & Economics denounces a "digital sovereignty trap" consisting in blocking access rather than building (ICLE). It should be noted that the Draghi report (2024) advocates investment and sovereignty without explicitly settling the open/closed debate.

### 3.4 The software dependence

The software layer remains largely American: Nvidia's CUDA ecosystem locks in developers, and the main learning frameworks (PyTorch, TensorFlow) are of American origin (Quartz France). The "sovereign model" Mistral is trained on tens of thousands of Nvidia chips (inasp.fr).

---

## 4. The cloud and data layer

### 4.1 An asymmetry of scale

OVHcloud (Roubaix), listed in Paris, exceeded one billion euros in revenue for the first time in 2025 (1,084.6 M€) with 44 data centers (OVHcloud). Scaleway (Iliad group) operates a supercomputer of 1,016 H100 GPUs and was selected by Nvidia for the sovereign *compute* of DGX Cloud Lepton (Scaleway). But the scale remains beyond all comparison with the hyperscalers: the three American giants (AWS, Azure, Google) control around **70% of the European cloud market**, the share of European providers having fallen from 29% (2017) to 15% (Synergy/TelecomTV). A single hyperscaler spends more on annual AI *capex* than the entirety of the European cloud market (ValueAdd VC). For reference, each planned European "AI gigafactory" is to host at least 100,000 H100-equivalent GPUs, that is about one hundred times Scaleway's cluster (STL Partners).

### 4.2 The US CLOUD Act and extraterritoriality

The **CLOUD Act** (2018) requires any provider under American jurisdiction to hand over the data it holds upon American warrant, regardless of the place of storage (Exoscale). Hosting in a European AWS, Azure or Google data center is therefore not enough to escape it, which creates a documented conflict with Article 48 of the GDPR (Kiteworks). The EU-US Data Privacy Framework (2023) neutralizes neither the CLOUD Act nor FISA 702 surveillance, and was weakened in early 2025 by the withdrawal of members of the American oversight body PCLOB (Clifford Chance). On a technical level, the **Foreign Direct Product Rule** subjects to American jurisdiction any product using controlled American technology, even if manufactured outside the United States (Scowcroft).

### 4.3 Gaia-X and the "trusted clouds"

The Franco-German initiative **Gaia-X** (2020) experienced a slow and criticized development; the presence of non-European members (Microsoft, AWS, Google, Huawei) fueled the accusation of *sovereignty-washing*, with Scaleway having left the project as early as 2021 for this reason (Computer Weekly). The French "trusted clouds" **Bleu** (Capgemini-Orange on Azure) and **S3ns** (Thales on Google Cloud) illustrate the tension: S3ns obtained the SecNumCloud qualification from ANSSI at the end of 2025, which according to the agency would shield it from the CLOUD Act, but many observers consider that none is truly sovereign since the technology comes 100% from Microsoft or Google (Usine Digitale; Journal du Net). On 17 April 2026, the Commission awarded a first sovereign cloud framework agreement to four consortia (a ceiling of 180 M€ over six years), while sparking controversy because one of them relies on Google Cloud (European Commission; Clubic).

---

## 5. European public computing

### 5.1 EuroHPC

The **EuroHPC** joint undertaking co-finances and owns the continent's network of public supercomputers. **JUPITER** (Jülich, Germany), inaugurated on 5 September 2025, is **Europe's first exascale supercomputer** and ranked 4th worldwide at the end of 2025 (EuroHPC JU; TOP500). A notable fact for sovereignty: its exascale power today rests on the "Booster" module based on **Nvidia GH200 Grace Hopper** superchips, the CPU module based on SiPearl's Rhea1 being an extension planned for later (DataCenterDynamics). Even the European flagship therefore runs first on Nvidia. **LUMI** (Kajaani, Finland) is powered 100% by hydroelectricity, its waste heat covering about 20% of the city's district heating (LUMI). The pre-exascale systems **Leonardo** (Italy) and **MareNostrum 5** (Spain) complete the network (EuroHPC JU).

### 5.2 Jean Zay

In France, **Jean Zay** (IDRIS/CNRS, operated by GENCI) is the national public AI supercomputer. Its 2024 extension added 1,456 Nvidia H100 GPUs, bringing its peak power to 125.9 PFlop/s (IDRIS; GENCI). Presented as the most heavily used AI supercomputer in Europe, it is already described as **saturated** by demand (Clubic).

### 5.3 AI Factories and gigafactories

In 2025 EuroHPC structured a network of **AI Factories** anchored to the public supercomputers, expanded to 19 units in 16 Member States in October 2025 (Silicon Saxony). At the upper tier, the **InvestAI** initiative (February 2025) committed up to 20 Bn€ to establish up to five **"AI gigafactories"**, each targeting around 100,000 latest-generation chips (Council of the EU). The final number, the sites and the timeline of these gigafactories are not settled.

---

## 6. Energy and climate

### 6.1 Consumption

According to the International Energy Agency (IEA) (*Energy and AI* report, 2025), global electricity consumption of data centers is expected to **double, reaching about 945 TWh in 2030** (against ~415 TWh in 2024), that is a little less than 3% of global electricity, with AI being the main driver of growth of about 15% per year (IEA; Data Center Dynamics).

### 6.2 The mix and the debate

In 2024, the global mix powering data centers was distributed approximately among coal (~30%), renewables (~27%), gas (~26%) and nuclear (~15%), the European situation, and a fortiori the French one, being markedly more decarbonized (IEA). Several American giants are turning to nuclear power for continuous generation: Microsoft (restart of Three Mile Island), Amazon, Google and Meta signed agreements in 2024-2025 (Trellis). A caveat is in order here: nuclear is **low-carbon at use but cannot be qualified as "clean"**, the question of long-lived radioactive waste not being resolved; this is a political debate and not a settled technical fact. Conversely, hydroelectricity (the case of LUMI) can be presented as renewable and low-carbon.

### 6.3 The rebound effect

The "digital Jevons paradox" indicates that gains in algorithmic and hardware efficiency may **increase** rather than reduce the energy footprint of AI, the fall in costs stimulating total usage; models report rebound magnitudes often comprised between 30 and 60% (Nature; arXiv). The IPCC's Sixth Assessment Report (Working Group III) underlines the potential of "demand-side" measures while noting the ambivalence of digitalization (efficiency versus rebound effects); the exact wording of AR6 should be re-quoted from the text before any definitive citation (IPCC).

---

## 7. Quantum

### 7.1 A real French competitiveness on hardware

Contrary to generative AI, France has, in **quantum hardware**, world-class champions spread across several architectures: **Alice & Bob** (*cat qubits*, a 100 M€ Series B in January 2025), **Pasqal** (neutral atoms), **Quandela** (photonics), to which Quobly and C12 are added (HPCwire; The Next Web). The country thus finances five architectures in parallel, where the United States concentrates on superconducting circuits. The national **Quantum Plan** (2021, 1.8 Bn€) was complemented by the PROQCIMA program (2024, 500 M€), which aims at a fault-tolerant 128 logical-qubit demonstrator by 2030, and by an additional allocation of about 1 Bn€ announced in May 2026 (Wikipedia; PostQuantum). These objectives are ambitious political targets, not acquired results: no actor has demonstrated a fault-tolerant quantum computer at this scale.

### 7.2 Post-quantum cryptography

In August 2024 NIST finalized its first three post-quantum cryptography standards (FIPS 203 ML-KEM, FIPS 204 ML-DSA, FIPS 205 SLH-DSA) (NIST). The so-called **"harvest now, decrypt later"** threat consists in intercepting and storing encrypted data today in order to decrypt them retroactively the day relevant quantum computers exist (Palo Alto). The horizon of such a computer capable of breaking RSA is estimated by some around 2035, but this date is very uncertain and contested.

---

## 8. Public investment and the discourse/reality gap

### 8.1 The big announcement figures

Several summits produced record amounts. At the AI Action Summit in Paris (February 2025), Emmanuel Macron announced **109 Bn€** of private investment (UAE/MGX, Brookfield, Fluidstack, Bpifrance), presented as the European response to the American Stargate plan (at least 500 Bn$ over four years) (franceinfo; CNews). At the Choose France summit in June 2026, the announced total reached **93 Bn€**, including SoftBank's flagship commitment for AI data centers in France: of the 75 Bn€ mentioned, **only 45 Bn€ are firm**, the remaining 30 Bn€ being conditioned on the success of a first phase (DGE; actuIA). In parallel, the Commission announced it would mobilize 200 Bn€ for AI (InvestAI). A cross-cutting warning is in order: these amounts are **announcements or commitments**, often multiyear, sometimes conditional and revisable, to be distinguished from investments actually carried out.

### 8.2 The AI campus and the data centers

A joint venture of MGX, Bpifrance, Mistral and Nvidia plans the largest AI campus in Europe at Fouju (Seine-et-Marne), with a power of 1.4 GW, targeted to be operational in 2028 (Polytechnique; DataCenterDynamics). The **law on the simplification of economic life of 26 May 2026** makes it possible to qualify a data center as a "major national interest project", opening accelerated planning and electrical connection procedures, with a safeguard in case of insufficient water resources (Légifrance; Gossement Avocats).

### 8.3 Announced is not realized

The case of **Fluidstack** illustrates the gap: a flagship announcement of the 2025 summit (10 Bn€, about a quarter of the edition), the project was **abandoned in early 2026**, the company redirecting its investments toward the United States (Usine Nouvelle). The historical record of Choose France reports "120 operational projects, 12 abandoned, the rest in progress", with Business France invoking confidentiality (franceinfo).

### 8.4 Critical voices

Several analysts document the gap. Ophélie Coelho (IRIS) considers that "Europe is chasing technologies that are not mature" and that these data centers will run solutions from dominant American actors (Techniques de l'Ingénieur). Asma Mhalla (EHESS) diagnoses a "defensive normative sovereignty" (DSA, DMA, AI Act) without a structured industrial strategy (Institut Montaigne). The Observatoire des multinationales investigated the data center lobby, whose French actors weigh less than 10% of the sector, and La Quadrature du Net describes the simplification law as a "denial of democracy" (Observatoire des multinationales; La Quadrature du Net). A paradox is regularly formulated: States pursue sovereignty "by making themselves more dependent on the very same foreign companies from which they claim to protect themselves" (Quartz France), Europe capturing only about 5% of global venture capital against 52% for the United States (Aqui).

### 8.5 The reference reports

The **Draghi report** (September 2024) makes technological lag the central cause of the productivity gap between the EU and the United States: only four of the top fifty global technology companies are European, and it recommends about 800 Bn€ of annual investment (4 to 5% of GDP), a recommendation itself contested (TechPolicy.Press; ITIF). The **Letta report** (April 2024) proposes a "fifth freedom" of movement of knowledge (Council of the EU).

---

## 9. Synthesis: what Europe holds, what it lacks

Europe **holds**: a CPU designer (SiPearl, though fabricated in Taiwan), an irreplaceable lithography lock (ASML), leading-edge R&D (Imec), competitive open-weights models (Mistral, Kyutai), two sovereign clouds of modest scale (OVHcloud, Scaleway), public supercomputers some of them very clean (LUMI), and a real lead on quantum hardware.

It **lacks**: a leading-edge foundry on its soil (the only project, Intel Magdeburg, is cancelled; ESMC Dresden remains on mature nodes), a sovereign AI training GPU, a cloud scale comparable to the hyperscalers, data sovereignty in the face of American extraterritoriality, and a volume of financing at the right level.

The truly irreplaceable lever is upstream, at ASML. The rest consists of **real bricks in a wall that is not built**. The political discourse of a complete autonomy "from chip to model" oversells this situation, which the critical sources document abundantly. The path presented as the most realistic, by the Commission as much as by industry, is that of the **open layer** (models, data, governance) and of pooled public computing, rather than the rebuilding of a complete chain.

---

## Zones of uncertainty

- **Prospective industrial timelines** (Rhea1/Rhea2, ramp-up of 2 nm, ESMC Dresden, AI gigafactories): targets liable to slip.
- **Investment amounts**: announcements and commitments, often conditional or revisable, sometimes abandoned; to be distinguished from amounts actually realized.
- **Market shares** (TSMC, Nvidia, ASML in China): variable depending on source, year and scope.
- **American export controls**: a highly volatile domain (AI Diffusion Rule repealed in 2025, MATCH Act and Chips Act 2.0 not adopted as of mid-2026).
- **Legal framework for data transfers**: the Data Privacy Framework is not invalidated as of mid-2026, but weakened; a "Schrems III" is pending.
- **Exact wording of the IPCC AR6** on digitalization: to be re-quoted from the source text.
- **French quantum objectives** (128 logical qubits in 2030): targets, not results.

---

## Sources

**Concept and discourse.** Atlantic Council, "Digital Sovereignty: Europe's Declaration of Independence"; Clingendael, "Open Strategic Autonomy"; Tandfonline / Wiley (Pohle, Broeders) on conceptual fuzziness; CEPA, "Divided Digital Europe"; TechPolicy.Press and European Commission (Tech Sovereignty Package, 3 June 2026); vie-publique.fr (Macron Berlin speech, 18 Nov. 2025).

**Silicon and hardware.** SiPearl (rhea1); EE Times, The Register, DataCenterDynamics, HPCwire (Rhea1, Series A); European Processor Initiative and EuroHPC JU / BSC (EPAC, DARE); EE Times (Codasip); European Commission and European Court of Auditors (Chips Act, special report 12/2025); Euronews (revision of targets); The Motley Fool, Tom's Hardware, IEP Bocconi, ASML (EUV, High-NA, 2025 results, export); TrendForce, TechSpot (TSMC 2 nm); NXP, TrendForce (ESMC Dresden); Xinhua, Heise, EENewsEurope (Intel Magdeburg); Carbon Credits, SiliconAnalysts, Axelera (Nvidia, accelerators).

**Models and software.** Mistral and ASML (Series C, partnership); platform-docs Mistral (licenses); TechCrunch (Mistral, history); TechCrunch, Fortune, iliad, GitHub kyutai-labs (Kyutai, Moshi); European Commission ("Europe's Open-Source AI Landscape"); Cybernews, AI Business (Mensch); ICLE (critique); Raconteur (Armed Forces framework agreement); Quartz France, inasp.fr (software dependence).

**Cloud and data.** OVHcloud (FY25 results); Scaleway, Nvidia (Nabuchodonosor, DGX Cloud Lepton); Synergy/TelecomTV, ValueAdd VC, STL Partners (scale asymmetry); Exoscale, Kiteworks, Clifford Chance, Scowcroft (CLOUD Act, FISA, FDPR); Gaia-X, Computer Weekly, Tandfonline (Gaia-X); Usine Digitale, Journal du Net, Clubic, European Commission (trusted clouds, 2026 framework agreement).

**Public computing.** EuroHPC JU, TOP500, DataCenterDynamics (JUPITER); LUMI (energy); IDRIS, GENCI, Clubic (Jean Zay); Silicon Saxony, Council of the EU (AI Factories, gigafactories, InvestAI).

**Energy and climate.** International Energy Agency, *Energy and AI* (2025); Data Center Dynamics; Trellis (Big Tech nuclear); Nature, arXiv (rebound effect); IPCC AR6 WG III.

**Quantum.** HPCwire (Alice & Bob), The Next Web, TechTimes (French champions); Wikipedia (Quantum Plan), PostQuantum, France 24 (PROQCIMA, 2026 additional allocation); NIST (PQC standards); Palo Alto Networks ("harvest now, decrypt later").

**Investment and discourse/reality.** DGE, actuIA, LeMagIT (Choose France 2026, SoftBank); franceinfo, Usine Digitale, CNews (AI Action Summit 2025, Stargate); European Commission, Euronews (InvestAI 200 Bn€); Polytechnique, DataCenterDynamics (Fouju campus); Légifrance, Gossement Avocats, dcmag (simplification law, PINM); Usine Nouvelle (Fluidstack); Techniques de l'Ingénieur (Coelho), Institut Montaigne (Mhalla), Observatoire des multinationales, La Quadrature du Net (critiques); Aqui (venture capital); TechPolicy.Press, TechHQ, ITIF (Draghi report), Council of the EU (Letta report).

---

Ismaël Joffroy Chandoutis, 2026. Text under a CC BY-NC-ND 4.0 license.

By [Ismaël Joffroy Chandoutis](https://ismaeljoffroychandoutis.com).
