# EN→PL Localization Portfolio — Veloren & Luanti

**Language pair:** English → Polish
**Methodology:** Every string below reflects my own editorial judgment as a native Polish speaker — terminology, register, and grammar decisions are documented in the notes alongside the translations, so the reasoning is visible, not just the output.

| Project | Type | Platform | Status |
|---|---|---|---|
| [Veloren](https://veloren.net/) | Fantasy voxel RPG (GPL-3.0) | Weblate (Codeberg) | 31 strings submitted, pending reviewer approval |
| [Luanti](https://luanti.org/) (fka Minetest) | Voxel sandbox engine (GPL/LGPL) | Hosted Weblate | Website: **100% complete**. Engine: ~70 strings translated, in progress |

---

# Part 1 — Veloren

## 1. Armor & Item Descriptions — Carapace Set

| Key | English | Polish |
|---|---|---|
| armor-hide-carapace-back | Carapace Cape | **Peleryna z Karapaksu** |
| | *Made from the hard shell that once protected a gigantic specimen.* | *Wykonana z twardej skorupy, która niegdyś chroniła gigantycznego okazu.* |
| armor-hide-carapace-belt | Carapace Belt | **Pas z Karapaksu** |
| | *The chitin clicks together neatly around your waist.* | *Chityna szczelnie zatrzaskuje się wokół twojej talii.* |
| armor-hide-carapace-chest | Carapace Cuirass | **Napierśnik z Karapaksu** |
| | *A thick thorax that has lived to fell many foes.* | *Gruby pancerz tułowia, który dożył chwili powalenia niejednego wroga.* |
| armor-hide-carapace-foot | Carapace Treads | **Buty z Karapaksu** |
| | *These no longer conceal your presence, but makes them known.* | *Te już nie skrywają twojej obecności — wręcz ją zdradzają.* |
| armor-hide-carapace-hand | Carapace Grips | **Rękawice z Karapaksu** |
| | *The heavy carapace adds weight to your swings.* | *Ciężki karapaks dodaje mocy twoim zamachom.* |
| armor-hide-carapace-pants | Carapace Leggings | **Nogawice z Karapaksu** |
| | *Your stride feels secure whilst covered in thick chitin.* | *Czujesz pewność każdego kroku, osłonięty grubą chityną.* |
| armor-hide-carapace-shoulder | Carapace Shoulderpads | **Naramienniki z Karapaksu** |
| | *The heavy carapace feels light compared to your burdens.* | *Ciężki karapaks wydaje się lekki w porównaniu z twoim brzemieniem.* |
| armor-hide-carapace-head | Carapace Kabuto | **Kabuto z Karapaksu** |
| | *A trophy nearing the heights of your ego.* | *Trofeum dorównujące wysokościom twojego ego.* |

**Translator's note:** Translated "Carapace" consistently as *Karapaks* (the correct Polish biological term for an exoskeletal shell) rather than the generic *pancerz* (armor), to preserve the set's insectoid-warrior theme across all 8 items. Left "Kabuto" (samurai helmet) untranslated — deliberate loanword in the English source, and dropping it into generic *hełm/kask* would flatten a specific aesthetic choice the developers made.

## 2. Armor & Item Descriptions — Primal & Leather Sets

| Key | English | Polish |
|---|---|---|
| armor-hide-primal-back | Primal Cape | **Pierwotna Peleryna** |
| | *The sturdy leather is still soaked in blood.* | *Wytrzymała skóra wciąż przesiąknięta jest krwią.* |
| armor-hide-primal-belt | Primal Sash | **Pierwotna Szarfa** |
| | *Hide drenched in blood to lure predators.* | *Skóra przesiąknięta krwią, by zwabić drapieżniki.* |
| armor-hide-primal-chest | Primal Cuirass | **Pierwotny Napierśnik** |
| | *Cages the ever thrumming bloodlust within.* | *Zamyka w sobie nieustannie pulsującą żądzę krwi.* |
| armor-hide-primal-foot | Primal Boots | **Pierwotne Buty** |
| | *The step of a monster to keep greenhorns from interfering.* | *Krok potwora, który trzyma żółtodziobów z dala od kłopotów.* |
| armor-hide-primal-hand | Primal Gauntlets | **Pierwotne Rękawice** |
| | *The blood on your hands will never wash out.* | *Krew na twoich dłoniach nigdy nie zejdzie.* |
| armor-hide-primal-pants | Primal Legs | **Pierwotne Nogawice** |
| | *Smithed from hide tougher than steel.* | *Wykute ze skóry twardszej niż stal.* |
| armor-hide-primal-shoulder | Primal Shoulders | **Pierwotne Naramienniki** |
| | *Sharp spikes ward off your conscience.* | *Ostre kolce trzymają twoje sumienie na dystans.* |
| armor-hide-primal-head | Primal Crest | **Pierwotny Grzebień** |
| | *No longer a trophy, but the crest of a monster.* | *Już nie trofeum, lecz grzebień potwora.* |
| armor-hide-leather-back | Leather Cloak | **Skórzany Płaszcz** |
| | *A thick cloak to mask the shape of a hunter from its prey.* | *Gruby płaszcz, który maskuje sylwetkę łowcy przed jego zdobyczą.* |
| armor-hide-leather-belt | Leather Belt | **Skórzany Pas** |
| | *A vicious hunter must never be caught with their pants down.* | *Zawzięty łowca nigdy nie może dać się złapać ze spuszczonymi spodniami.* |
| armor-hide-leather-chest | Leather Chestpiece | **Skórzany Napierśnik** |
| | *Thick, sturdy leather that conceals you in the dense forest.* | *Gruba, wytrzymała skóra, która ukrywa cię w gęstym lesie.* |
| armor-hide-leather-foot | Leather Boots | **Skórzane Buty** |
| | *Like a prowling cat, you approach silently.* | *Niczym skradający się kot, zbliżasz się bezszelestnie.* |

**Translator's notes:**
- **"Primal Crest" / grzebień:** verified against the in-game item icon before choosing between *grzebień* (anatomical crest/ridge) and alternatives like *grzywa* (mane) or *herb* (heraldic coat of arms) — *grzebień* matched both the visual and the "crest of a monster" wordplay. Also flagged a source/asset mismatch worth QA attention rather than silently resolving.
- **"Caught with their pants down" / ze spuszczonymi spodniami:** kept as a close calque rather than a fully native idiom, to preserve the pun connecting the idiom to the item itself being a belt.

## 3. NPC Dialogue — Randomized Speech Lines

**Translator's note — grammatical case:** Fluent inserts `{ $site }`, `{ $name }`, `{ $role }` as fixed, undeclined strings — there's no way for the engine to auto-decline them despite Polish requiring case agreement. Treated inserted names as fixed/undeclined nouns throughout, the standard professional convention for this exact engine limitation.

*Note: two related strings (`npc-speech-tell_site`, `npc-speech-tell_monster`) were intentionally held back — they use `{ $dir }` / `{ $dist }` variables whose exact source format needs confirming before the Polish grammar can be built correctly. Submitting a guess risked a grammatically broken sentence.*

## 4. Player Dialogue & Plural Handling

**dialogue-buy_hire_days** *(plural handling centerpiece)*:
```
.day = Dzień
.week = Tydzień
.unknown =
{ $days ->
    [one] { $days } dzień
    [few] { $days } dni
   *[other] { $days } dni
}
```

**Translator's note — Polish plurals:** English branches into two forms (`[one]`, `*[other]`). Polish requires **three**: `[one]` (1 dzień), `[few]` (2–4, and 22–24/32–34...), `*[other]` (5+, and 0). Added the `[few]` branch that doesn't exist in the English source — required for grammatically correct Polish. A direct copy of the English structure produces broken output like *"2 dzień"* instead of correct *"2 dni."*

## Veloren — Source Quality Notes

While reviewing source strings, caught and flagged (without altering) a typo in the English source (`interferring` → `interfering`) and a source/description mismatch on the "Primal Crest" item.

---

# Part 2 — Luanti (formerly Minetest)

Open-source voxel sandbox engine. Chosen as a second project specifically because it has a genuinely **active** Polish localization pipeline — real recurring contributors and periodic maintainer merges — a different situation from Veloren's currently-stale queue.

## 5. Website Localization (100% complete — 315/315 strings)

| Key context | English | Polish |
|---|---|---|
| Homepage hero | Show downloads for all platforms | Pokaż pliki do pobrania dla wszystkich platform |
| About/mission | An open-source voxel game creation platform. | Platforma open source do tworzenia gier wokselowych. |
| About/mission | Luanti is a member of Open Source Europe (OSE), a non-profit based in Belgium. | Luanti jest członkiem Open Source Europe (OSE) — organizacji non-profit z siedzibą w Belgii. |
| Games showcase (long-form) | There are many games to choose from. Explore exotic lands, jump into action, solve puzzles, survive and build, and more. You can customise your adventures by downloading content directly from the client. Or, if you want to play online, Luanti will automagically download all the resources needed to play on the server you've chosen. | Do wyboru jest wiele gier. Odkrywaj egzotyczne krainy, wskakuj w sam środek akcji, rozwiązuj zagadki, przetrwaj i buduj — i wiele więcej. Możesz dostosować swoją przygodę, pobierając zawartość bezpośrednio z poziomu klienta gry. A jeśli wolisz grać online, Luanti automagicznie pobierze wszystkie zasoby potrzebne do gry na wybranym serwerze. |
| Translation CTA (HTML tag) | Help translate Luanti using `<a href='...'>Weblate</a>`. | Pomóż przetłumaczyć Luanti za pomocą `<a href='...'>Weblate</a>`. |
| ContentDB mention (number agreement) | There are over `{{contentdb_mod_count}}` open source mods on [ContentDB], which are ready to be used, adapted or learned from. | Na platformie [ContentDB] dostępnych jest ponad `{{contentdb_mod_count}}` modów open source, gotowych do wykorzystania, dostosowania lub nauki na ich podstawie. |
| Funding page | Estimated monthly income of `{{amount}}` based on active recurring supporters and the last 3 months of donations | Szacowany miesięczny przychód w wysokości `{{amount}}`, obliczony na podstawie aktywnych stałych wspierających oraz darowizn z ostatnich 3 miesięcy. |
| Licensing footer | `<a>`MIT`</a>` for code, `<a>`CC BY-SA 3.0`</a>` for content, media under various licenses. | `<a>`MIT`</a>` dla kodu, `<a>`CC BY-SA 3.0`</a>` dla treści, materiały na różnych licencjach. |

**Translator's notes:**
- **"voxel" → "wokselowy"**: polonized spelling, matching the same pattern as pixel→piksel. Usage is genuinely split online — flagged as a judgment call, not a fixed rule.
- **"automagically" → "automagicznie"**: already-established Polish IT slang, so the playful tone survives untouched rather than needing a workaround.
- **"open source" kept as-is** rather than the formal calque "otwartoźródłowy" — more natural for a general-audience site, matches how the term is actually used in Polish gaming media.
- **`{{ }}` (Mustache-style) placeholders** treated as literal insertion points, same non-declining-noun logic as Veloren's Fluent variables.

**QA catch — pre-existing bug from another contributor:** found a URL path (`forums`) that had been auto-translated to `fora` inside an `<a href>` — a classic Google Translate artifact where the whole string, markup included, gets run through machine translation rather than treating the href as an untouchable literal. Identified and corrected. This is a materially different skill than catching a source typo: it's recognizing that a *link target* isn't translatable content at all, a mistake that produces a broken or misdirected link, not just an awkward sentence.

## 6. Engine / Core Settings Localization (in progress — ~70 strings this session)

A representative spread across mapgen/noise parameters, keybindings, rendering settings, and developer tooling — deliberately different register from both Veloren's flavor text and the website's marketing copy.

| English | Polish |
|---|---|
| Amplifies every octave by (amplitude of the previous octave * Persistence). | Wzmacnia każdą oktawę o (amplituda poprzedniej oktawy * Trwałość). |
| Scales every octave by (scale of the previous octave / Lacunarity). | Skaluje każdą oktawę o (skala poprzedniej oktawy / Lakunarność). |
| The random seed for the noise. The same seed results in the same noise. | Losowy seed szumu. Ten sam seed daje ten sam szum. |
| Maps noise gradient values onto a quintic S-curve before performing interpolation. | Mapuje wartości gradientu szumu na krzywą S piątego stopnia (kwintyczną) przed wykonaniem interpolacji. |
| `<empty>` *(UI label shown when a setting's default value is blank)* | `<puste>` |
| Key for digging, punching or using something.<br>(Note: The actual meaning might vary on a per-game basis.) | Klawisz do kopania, uderzania lub używania czegoś.<br>(Uwaga: rzeczywiste znaczenie może się różnić w zależności od gry.) |
| Key for placing an item/block or for using something.<br>(Note: The actual meaning might vary on a per-game basis.) | Klawisz do stawiania przedmiotu/bloku lub używania czegoś.<br>(Uwaga: rzeczywiste znaczenie może się różnić w zależności od gry.) |
| Applies a post-processing filter to detect and smoothen high-contrast edges. Provides balance between speed and image quality. fxaa can [be] used in combination with the other anti-aliasing methods | Stosuje filtr przetwarzania końcowego, który wykrywa i wygładza krawędzie o wysokim kontraście. Zapewnia równowagę między szybkością a jakością obrazu. FXAA można stosować w połączeniu z innymi metodami antyaliasingu |
| Number of emerge threads (responsible for map generation and loading) to use. If 0 then the engine will automatically choose a suitable value depending on the hardware and type of map generator. WARNING: There are known bugs in the default map generators (v6, v7, ...) when using more than 1 thread. The automatic choice will avoid this. | Liczba wątków emerge (odpowiedzialnych za generowanie i wczytywanie mapy) do wykorzystania. Jeśli ustawiono 0, silnik automatycznie dobierze odpowiednią wartość w zależności od sprzętu i typu generatora mapy. OSTRZEŻENIE: W domyślnych generatorach mapy (v6, v7, ...) występują znane błędy przy użyciu więcej niż 1 wątku. Automatyczny wybór pozwala tego uniknąć. |
| The kind of digging/placing controls used.<br>\* Tap — Long/short tap anywhere on the screen to interact. Interaction happens at finger position.<br>\* Tap with crosshair — same, interaction at crosshair position.<br>\* Buttons with crosshair — dedicated dig/place buttons, interaction at crosshair position. | Rodzaj używanych elementów sterujących kopaniem/stawianiem.<br>\* Dotknięcie — długie/krótkie dotknięcie w dowolnym miejscu ekranu, aby wejść w interakcję. Interakcja zachodzi w miejscu dotknięcia palcem.<br>\* Dotknięcie z celownikiem — jw., interakcja w miejscu celownika.<br>\* Przyciski z celownikiem — dedykowane przyciski kopania/stawiania, interakcja w miejscu celownika. |
| Set proxy to use by cURL. This is an URI just like the *_proxy environment variables. Note that this will not apply to Luanti's in-game protocol. | Ustaw serwer proxy używany przez cURL. To adres URI, podobnie jak zmienne środowiskowe *_proxy. Zwróć uwagę, że nie dotyczy to protokołu gry Luanti. |

**Translator's notes:**
- **Parallelism convention:** the family of "Key for..." keybinding descriptions was deliberately unified into one consistent Polish sentence pattern ("Klawisz do + gerund"), even where the English source varies its phrasing string-to-string — sibling settings in the same menu should read as a matched set.
- **Terminology calls (see Glossary, below), all made from scratch** since the project's Glossary component had no prior entries for these terms: *octave → oktawa*, *persistence → Trwałość* (capitalized, refers to a specific named setting), *eased* kept untranslated as a literal flag name. *Lacunarity → Lakunarność* is the one soft guess here — built by analogy to the existing Polish term *lakuna* (shared Latin root), flagged as provisional rather than settled.
- **"seed" kept as a loanword**, not translated to "ziarno" — matches how Polish gaming communities (Minecraft and by extension Luanti players) actually refer to world seeds.
- **Multi-line strings and bullet formatting preserved exactly** as structured in source — these are tooltip strings that wrap across lines in the actual settings UI, so line-break count is part of correctness, not just word choice.

**QA catch — genuine source typo:** *"fxaa can used in combination..."* is missing "be" in the English source. Flagged via comment rather than silently corrected.

**QA catch — own error, caught by tooling:** one draft dropped an entire clause mid-translation. Weblate's built-in checks (mismatched line-break count + mismatched terminal punctuation) flagged it immediately; corrected before saving. Concrete example of why automated checks are treated as a required review step, not an optional courtesy — and also why "zero failing checks" isn't the same as "definitely correct," since not every kind of error (e.g. a mistranslated URL) trips an automated check at all.

## 7. Luanti Glossary — Terminology Established

The project's Glossary component had no prior entries for the following mapgen-specific terms, so these submissions set the convention rather than following one:

| Term | Polish | Note |
|---|---|---|
| octave | oktawa | Noise-generation layer (Perlin/Simplex noise), not the music term |
| persistence | Trwałość | Mapgen noise parameter, capitalized — refers to a specific named setting |
| eased | *eased* (untranslatable) | Literal flag/parameter name, referenced in quotes in source |

---

## 8. Cross-Project Technical Literacy

Working across two engines with two different templating systems surfaced **five distinct placeholder/variable conventions** in EN→PL work so far — worth understanding each on its own terms rather than treating "insert the variable" as one uniform problem:

1. **Fluent `{ $variable }`** (Veloren) — undeclinable; Polish case agreement has to be worked around, not auto-generated.
2. **Mustache-style `{{ value }}`** (Luanti website).
3. **gettext positional `@1`** (Luanti engine).
4. **gettext numbered `$1`** (Luanti engine — coexists with `@1` within the same component; a source-side inconsistency, not something introduced by translation).
5. **printf-style `%s` / `%d`** (Luanti engine).

**Plural handling generalizes across formats:** Polish's requirement for 3 numeric-agreement forms (`[one]` / `[few]` / `*[other]`) — first documented on Veloren's Fluent-based `dialogue-buy_hire_days` — applies identically to gettext's `Plural-Forms` mechanism. Same linguistic rule, different engine syntax underneath.

**QA discipline applied consistently across both projects:** match source punctuation and line-break structure exactly, even when the English source is internally inconsistent about it; treat hrefs, environment-variable names, and code identifiers as literals never to be touched; flag source-side typos rather than silently fixing them; and don't assume "no automated warnings" means "verified correct" — some errors (mistranslated link targets, dropped nuance) require an actual human read, which is the whole point of doing this work as a native speaker rather than shipping raw MT output.

---

## 9. CAT Tool Experience

Hands-on practice using **OmegaT** (free, open-source CAT tool) — bilingual segment editor, translation memory, and built-in QA checks (LanguageTool integration for grammar/style).

**QA catch:** the built-in check flagged a Polish grammar issue — two independent clauses joined with only a comma, which reads fine in casual English but isn't valid Polish sentence construction without a conjunction or stronger punctuation break. Corrected before finalizing. Same underlying pattern as the Weblate and Luanti QA catches above — automated tooling catching what a fast pass misses — this time on a third, independent platform.
