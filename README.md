# Bangla BSTI Mobile Keyboard Layout

> Bangla BSTI Mobile layout based on National Keyboard Standard (Revised) BDS 1738:2018, enhanced with usability improvements for smooth mobile typing.

**Bangla BSTI Mobile** is an optimised Bengali mobile keyboard layout derived from the National Keyboard Standard (Revised) **BDS 1738:2018** (BSTI). While preserving the canonical placement of standard consonants, this layout introduces practical mobile-first adaptations tailored for touchscreens—including intuitive long-press access to full vowels, direct high-frequency conjunct overlays on the Shift layer, and streamlined long-press behaviour.

---

## 🖼️ Layout Overview

| Normal Mode | Shift Mode |
| :---: | :---: |
| ![Normal Layout](images/normal.png) | ![Shift Layout](images/shift.png) |

---

## 🚀 Key Usability Enhancements

1. **Adherence to Logical Unicode Input Order:**
   * The legacy desktop standard in BDS 1738:2018 inherited visual typing conventions rooted in traditional typewriters and pre-Unicode layout mechanisms (such as Bijoy), where characters were keyed in visually before the consonant (e.g. `ে` + `ক` + `া` = `কো`). This contradicts standard Unicode phonetic behaviour. In **Bangla BSTI Mobile**, input strictly adheres to the standard Unicode logical sequence: **Consonant + Dependent Vowel** (e.g. `ক` + `ো` = `কো`).
2. **Intuitive Long-Press Vowels Replacing Complex Desktop Sequences:**
   * Whilst multi-key desktop shortcuts like `্` + `ে` = `এ` may be practical on a physical keyboard, executing composite multi-tap sequences on a mobile touchscreen is cumbersome, slow, and prone to error. To streamline touch typing, full independent vowels are mapped directly to intuitive long-press actions on their respective vowel signs (kar). For instance, long-pressing `া` yields `আ`, `ি` yields `ই`, `ে` yields `এ`, and `ো` yields `ও`.
3. **Pre-composed Conjunct Overlays for Accessible Touch Typing:**
   * Entering complex Bengali conjuncts via the canonical Virama/Hasanta sequence requires an explicit understanding of grammatical decomposition (such as `ক` + `্` + `ষ` = `ক্ষ` or `জ` + `্` + `ঞ` = `জ্ঞ`), which many everyday mobile users find unintuitive. To eliminate typing friction, high-frequency ligatures (e.g. ঙ্ক, ঞ্চ, ঞ্জ, জ্ঞ, ঙ্গ, ক্ষ, ষ্ণ, হ্ম, ব়্য) are readily accessible via direct long-press overlays on corresponding Shift keys.
4. **Dedicated O-Kar (`ো`) and AU-Kar (`ৌ`) Key Placements:**
   * To prevent awkward multi-sign combinations, the base layer features `ো` directly on the `X` key (with `ও` on long-press), whilst the Shift layer accommodates `ৌ` on `Shift + X` (with `ঔ` on long-press).
5. **Streamlined Long-Press Logic:**
   * Khanda-Ta (`ৎ`) is mapped exclusively to the long-press overlay of the primary character **'ত' (K)**. The redundant duplicate long-press assignment on **'থ' (Shift + K)** has been purged to keep the keyboard uncluttered.

---

## ⌨️ Key Mapping & Unicode Specification

---

### 🟢 1. Normal Mode Layer

#### Top Row (Q – P)

| Key | Output | Unicode | Long-Press / Overlay | Unicode Sequence | Description |
| :---: | :---: | :---: | :---: | :---: | :--- |
| **Q** | ঙ | `U+0999` | — | — | Bengali Letter NGA |
| **W** | য | `U+09AF` | — | — | Bengali Letter YA |
| **E** | ড | `U+09A1` | — | — | Bengali Letter DDA |
| **R** | প | `U+09AA` | — | — | Bengali Letter PA |
| **T** | ট | `U+099F` | — | — | Bengali Letter TTA |
| **Y** | চ | `U+099A` | — | — | Bengali Letter CA |
| **U** | জ | `U+099C` | — | — | Bengali Letter JA |
| **I** | হ | `U+09B9` | — | — | Bengali Letter HA |
| **O** | গ | `U+0997` | — | — | Bengali Letter GA |
| **P** | ড় | `U+09DC` | — | — | Bengali Letter RRA |

#### Home Row (A – L)

| Key | Output | Unicode | Long-Press / Overlay | Unicode Sequence | Description |
| :---: | :---: | :---: | :---: | :---: | :--- |
| **A** | ৃ | `U+09C3` | **ঋ** | `U+098B` | Bengali Vowel Sign Vocalic R / Letter Vocalic R |
| **S** | ু | `U+09C1` | **উ** | `U+0989` | Bengali Vowel Sign U / Letter U |
| **D** | ি | `U+09BF` | **ই** | `U+0987` | Bengali Vowel Sign I / Letter I |
| **F** | া | `U+09BE` | **আ** | `U+0986` | Bengali Vowel Sign AA / Letter AA |
| **G** | ্ | `U+09CD` | — | — | Bengali Sign Virama (Hasanta) |
| **H** | ব | `U+09AC` | — | — | Bengali Letter BA |
| **J** | ক | `U+0995` | — | — | Bengali Letter KA |
| **K** | ত | `U+09A4` | **ৎ** | `U+09CE` | Bengali Letter TA / Letter Khanda Ta |
| **L** | দ | `U+09A6` | — | — | Bengali Letter DA |

#### Bottom Row (Z – M)

| Key | Output | Unicode | Long-Press / Overlay | Unicode Sequence | Description |
| :---: | :---: | :---: | :---: | :---: | :--- |
| **Z** | ্য | `U+09CD U+09AF` | — | — | Ya-phala (Subjoined YA) |
| **X** | ো | `U+09CB` | **ও** | `U+0993` | Bengali Vowel Sign O / Letter O |
| **C** | ে | `U+09C7` | **এ** | `U+098F` | Bengali Vowel Sign E / Letter E |
| **V** | র | `U+09B0` | — | — | Bengali Letter RA |
| **B** | ন | `U+09A8` | — | — | Bengali Letter NA |
| **N** | স | `U+09B8` | — | — | Bengali Letter SA |
| **M** | ম | `U+09AE` | **ঃ** | `U+0983` | Bengali Letter MA / Sign Visarga |

---

### 🔵 2. Shift Mode Layer

#### Top Row (Q – P)

| Key | Output | Unicode | Long-Press / Overlay | Unicode Sequence | Description |
| :---: | :---: | :---: | :---: | :---: | :--- |
| **Q** | ং | `U+0982` | **ঙ্ক** | `U+0999 U+09CD U+0995` | Bengali Sign Anusvara / NG-KA Conjunct |
| **W** | য় | `U+09DF` | — | — | Bengali Letter YYA |
| **E** | ঢ | `U+09A2` | — | — | Bengali Letter DDHA |
| **R** | ফ | `U+09AB` | — | — | Bengali Letter PHA |
| **T** | ঠ | `U+09A0` | — | — | Bengali Letter TTHA |
| **Y** | ছ | `U+099B` | **ঞ্চ** | `U+099E U+09CD U+099A` | Bengali Letter CHA / NYA-CA Conjunct |
| **U** | ঝ | `U+099D` | **জ্ঞ** | `U+099C U+09CD U+099E` | Bengali Letter JHA / JA-NYA Conjunct |
| **I** | ঞ | `U+099E` | **ঞ্জ** | `U+099E U+09CD U+099C` | Bengali Letter NYA / NYA-JA Conjunct |
| **O** | ঘ | `U+0998` | **ঙ্গ** | `U+0999 U+09CD U+0997` | Bengali Letter GHA / NG-GA Conjunct |
| **P** | ঢ় | `U+09DD` | — | — | Bengali Letter RRHA |

#### Home Row (A – L)

| Key | Output | Unicode | Long-Press / Overlay | Unicode Sequence | Description |
| :---: | :---: | :---: | :---: | :---: | :--- |
| **A** | ঽ | `U+09BD` | — | — | Bengali Sign Avagraha |
| **S** | ূ | `U+09C2` | **ঊ** | `U+098A` | Bengali Vowel Sign UU / Letter UU |
| **D** | ী | `U+09C0` | **ঈ** | `U+0988` | Bengali Vowel Sign II / Letter II |
| **F** | অ | `U+0985` | — | — | Bengali Letter A |
| **G** | ্‌ | `U+09CD` | — | — | Bengali Sign Virama (Hasanta alternate) |
| **H** | ভ | `U+09AD` | — | — | Bengali Letter BHA |
| **J** | খ | `U+0996` | **ক্ষ** | `U+0995 U+09CD U+09B7` | Bengali Letter KHA / KA-SSA Conjunct |
| **K** | থ | `U+09A5` | — | — | Bengali Letter THA |
| **L** | ধ | `U+09A7` | — | — | Bengali Letter DHA |

#### Bottom Row (Z – M)

| Key | Output | Unicode | Long-Press / Overlay | Unicode Sequence | Description |
| :---: | :---: | :---: | :---: | :---: | :--- |
| **Z** | ্য | `U+09CD U+09AF` | — | — | Ya-phala (Subjoined YA) |
| **X** | ৌ | `U+09CC` | **ঔ** | `U+0994` | Bengali Vowel Sign AU / Letter AU |
| **C** | ৈ | `U+09C8` | **ঐ** | `U+0990` | Bengali Vowel Sign AI / Letter AI |
| **V** | ল | `U+09B2` | **ব়্য** | `U+09AC U+09BC U+09CD U+09AF` | Bengali Letter LA / Subjoined Ref-Ya Conjunct |
| **B** | ণ | `U+09A3` | **ঞ্চ** | `U+099E U+09CD U+099A` | Bengali Letter NNA / NYA-CA Conjunct (Alternate) |
| **N** | ষ | `U+09B7` | **ষ্ণ** | `U+09B7 U+09CD U+09A3` | Bengali Letter SSA / SSA-NNA Conjunct |
| **M** | শ | `U+09B6` | **হ্ম** | `U+09B9 U+09CD U+09AE` | Bengali Letter SHA / HA-MA Conjunct |

---

## 🧩 Direct Conjunct Reference Table

| Conjunct | Canonical Decomposition | Unicode Codepoint Sequence | Shift Key Position |
| :---: | :--- | :--- | :---: |
| **ঙ্ক** | ঙ + ্ + ক | `U+0999` + `U+09CD` + `U+0995` | `Q` (long-press on ং) |
| **ঞ্চ** | ঞ + ্ + চ | `U+099E` + `U+09CD` + `U+099A` | `Y` (ছ) or `B` (ণ) |
| **জ্ঞ** | জ + ্ + ঞ | `U+099C` + `U+09CD` + `U+099E` | `U` (long-press on ঝ) |
| **ঞ্জ** | ঞ + ্ + জ | `U+099E` + `U+09CD` + `U+099C` | `I` (long-press on ঞ) |
| **ঙ্গ** | ঙ + ্ + গ | `U+0999` + `U+09CD` + `U+0997` | `O` (long-press on ঘ) |
| **ক্ষ** | ক + ্ + ষ | `U+0995` + `U+09CD` + `U+09B7` | `J` (long-press on খ) |
| **ষ্ণ** | ষ + ্ + ণ | `U+09B7` + `U+09CD` + `U+09A3` | `N` (long-press on ষ) |
| **হ্ম** | হ + ্ + ম | `U+09B9` + `U+09CD` + `U+09AE` | `M` (long-press on শ) |
| **ব়্য** | ব + ় + ্ + য | `U+09AC` + `U+09BC` + `U+09CD` + `U+09AF` | `V` (long-press on ল) |

---

## 📝 Independent Vowel Input Methods

Independent vowels can be entered effortlessly either through swift long-press overlays or standard logical combinations:

* **অ:** Directly via `Shift + F` (`U+0985`)
* **আ:** Long-press on `f` (`া`) (`U+0986`)
* **ই:** Long-press on `d` (`ি`) (`U+0987`)
* **ঈ:** Long-press on `Shift + D` (`ী`) (`U+0988`)
* **উ:** Long-press on `s` (`ু`) (`U+0989`)
* **ঊ:** Long-press on `Shift + S` (`ূ`) (`U+098A`)
* **ঋ:** Long-press on `a` (`ৃ`) (`U+098B`)
* **এ:** Long-press on `c` (`ে`) (`U+098F`)
* **ঐ:** Long-press on `Shift + C` (`ৈ`) (`U+0990`)
* **ও:** Long-press on `x` (`ো`) (`U+0993`)
* **ঔ:** Long-press on `Shift + X` (`ৌ`) (`U+0994`)

---

## 📄 Licence

This layout specification and documentation are published under the **[Creative Commons Attribution 4.0 International Licence (CC BY 4.0)](LICENSE)**.

You are free to share, adapt, and integrate this layout across all platforms (such as Gboard, OpenBoard, or bespoke IME implementations), provided that appropriate attribution is given to **Bangla BSTI Mobile** (Ekushey project).
