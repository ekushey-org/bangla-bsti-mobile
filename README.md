# Ekushey BSTI Mobile Keyboard Layout

> Ekushey BSTI Mobile layout based on National Keyboard Standard (Revised) BDS 1738:2018, enhanced with usability improvements for smooth mobile typing.

**Ekushey BSTI Mobile** is an optimised Bengali mobile keyboard layout based on the National Keyboard Standard (Revised) **BDS 1738:2018** published by the Bangladesh Standards and Testing Institution (BSTI). To deliver a swift, accurate, and comfortable touch typing experience on modern mobile screens, it retains the canonical standard whilst introducing ergonomic touch-layer refinements, including direct conjunct mapping on the Shift layer and streamlined long-press behaviour.

---

## 🚀 Key Usability Enhancements

1. **Direct Conjuncts on Shift Layer:**
   * Eliminates repetitive use of the Hasanta/Virama (`্`) key for frequent, complex ligatures. High-frequency conjuncts (such as ক্ষ, জ্ঞ, ঞ্জ, ঞ্চ, ষ্ণ, হ্ম, ঙ্ক, ঙ্গ) are readily accessible directly on the Shift layer or via long-press overlays.
2. **Optimised Long-Press Logic:**
   * Khanda-Ta (`ৎ`) is mapped exclusively to the long-press overlay of the primary character **'ত' (K)**. Redundant mapping on **'থ' (Shift+K)** has been removed to reduce cognitive clutter.
3. **Standard Vowel Formation:**
   * Adheres strictly to the BDS 1738:2018 composite vowel model using 'অ' (`Shift + F`) combined with appropriate vowel signs (kar).

---

## ⌨️ Key Mapping & Unicode Specification

### 1. Top Row (Q – P)

| Key | Normal | Unicode | Shift | Unicode | Shift Conjunct / Alt | Unicode Sequence | Description |
| :---: | :---: | :---: | :---: | :---: | :---: | :--- | :--- |
| **Q** | ঙ | `U+0999` | ং | `U+0982` | **ঙ্ক** (ঙ + ক) | `U+0999 U+09CD U+0995` | NGA / Anusvara / NG-KA |
| **W** | য | `U+09AF` | য় | `U+09DF` | — | — | YA / YYA |
| **E** | ড | `U+09A1` | ঢ | `U+09A2` | — | — | DDA / DDHA |
| **R** | প | `U+09AA` | ফ | `U+09AB` | — | — | PA / PHA |
| **T** | ট | `U+099F` | ঠ | `U+09A0` | — | — | TTA / TTHA |
| **Y** | চ | `U+099A` | ছ | `U+099B` | **ঞ্চ** (ঞ + চ) | `U+099E U+09CD U+099A` | CA / CHA / NYA-CA |
| **U** | জ | `U+099C` | ঝ | `U+099D` | **ঞ্জ** (ঞ + জ) | `U+099E U+09CD U+099C` | JA / JHA / NYA-JA |
| **I** | হ | `U+09B9` | ঞ | `U+099E` | **জ্ঞ** (জ + ঞ) | `U+099C U+09CD U+099E` | HA / NYA / JA-NYA |
| **O** | গ | `U+0997` | ঘ | `U+0998` | **ঙ্গ** (ঙ + গ) | `U+0999 U+09CD U+0997` | GA / GHA / NG-GA |
| **P** | ড় | `U+09DC` | ঢ় | `U+09DD` | — | — | RRA / RRHA |

---

### 2. Home Row (A – L)

| Key | Normal | Unicode | Shift | Unicode | Shift Conjunct / Long-Press | Unicode Sequence | Description |
| :---: | :---: | :---: | :---: | :---: | :---: | :--- | :--- |
| **A** | ৃ | `U+09C3` | ৃ (alt) | `U+09C3` | — | — | Vowel Sign Vocalic R |
| **S** | ু | `U+09C1` | ূ | `U+09C2` | — | — | Vowel Sign U / UU |
| **D** | ি | `U+09BF` | ী | `U+09C0` | — | — | Vowel Sign I / II |
| **F** | া | `U+09BE` | অ | `U+0985` | — | — | Vowel Sign AA / Letter A |
| **G** | ্ | `U+09CD` | ্‌ | `U+09CD` | — | — | Sign Virama (Hasanta) |
| **H** | ব | `U+09AC` | ভ | `U+09AD` | — | — | BA / BHA |
| **J** | ক | `U+0995` | খ | `U+0996` | **ক্ষ** (ক + ষ) | `U+0995 U+09CD U+09B7` | KA / KHA / KA-SSA |
| **K** | ত | `U+09A4` | থ | `U+09A5` | **ৎ** *(Long-press on ত only)* | `U+09CE` | TA / THA *(ৎ removed from থ)* |
| **L** | দ | `U+09A6` | ধ | `U+09A7` | — | — | DA / DHA |

---

### 3. Bottom Row (Z – M)

| Key | Normal | Unicode | Shift | Unicode | Shift Conjunct / Mark | Unicode Sequence | Description |
| :---: | :---: | :---: | :---: | :---: | :---: | :--- | :--- |
| **Z** | ্য | `U+09CD U+09AF` | ্য | `U+09CD U+09AF` | — | — | Ya-phala (Subjoined Ya) |
| **X** | ৌ | `U+09CC` | ঔ | `U+0994` | — | — | Vowel Sign AU / Letter AU |
| **C** | ে | `U+09C7` | ঐ | `U+0990` | — | — | Vowel Sign E / Letter AI |
| **V** | র | `U+09B0` | ্র | `U+09CD U+09B0` | — | — | RA / Ra-phala |
| **B** | ন | `U+09A8` | ণ | `U+09A3` | **ঞ্চ** (alt) | `U+099E U+09CD U+099A` | NA / NNA |
| **N** | স | `U+09B8` | ষ | `U+09B7` | **ষ্ণ** (ষ + ণ) | `U+09B7 U+09CD U+09A3` | SA / SSA / SSA-NNA |
| **M** | ম | `U+09AE` | শ | `U+09B6` | **হ্ম** (হ + ম) | `U+09B9 U+09CD U+09AE` | MA / SHA / HA-MA |

---

## 🧩 Direct Conjunct Specification

The following frequently used conjuncts are accessible directly on the Shift layer or via long-press overlays:

| Conjunct | Canonical Decomposition | Unicode Sequence | Shift Key Reference |
| :---: | :--- | :--- | :---: |
| **ক্ষ** | ক + ্ + ষ | `U+0995` + `U+09CD` + `U+09B7` | `J` (adjacent to খ) |
| **জ্ঞ** | জ + ্ + ঞ | `U+099C` + `U+09CD` + `U+099E` | `I` (adjacent to ঞ) |
| **ঞ্জ** | ঞ + ্ + জ | `U+099E` + `U+09CD` + `U+099C` | `U` (adjacent to ঝ) |
| **ঞ্চ** | ঞ + ্ + চ | `U+099E` + `U+09CD` + `U+099A` | `Y` (adjacent to ছ) |
| **ষ্ণ** | ষ + ্ + ণ | `U+09B7` + `U+09CD` + `U+09A3` | `N` (adjacent to ষ) |
| **হ্ম** | হ + ্ + ম | `U+09B9` + `U+09CD` + `U+09AE` | `M` (adjacent to শ) |
| **ঙ্ক** | ঙ + ্ + ক | `U+0999` + `U+09CD` + `U+0995` | `Q` (adjacent to ং) |
| **ঙ্গ** | ঙ + ্ + গ | `U+0999` + `U+09CD` + `U+0997` | `O` (adjacent to ঘ) |

---

## 📝 Independent Vowel Formation (BDS 1738:2018)

In accordance with BDS 1738:2018 guidelines, independent vowels are formed by combining the base vowel letter 'অ' (`Shift + F`, `U+0985`) with their corresponding dependent vowel signs (kar):

* **অ:** `Shift + F` (`U+0985`)
* **আ:** `Shift + F` + `F` (`U+0986`)
* **ই:** `Shift + F` + `D` (`U+0987`)
* **ঈ:** `Shift + F` + `Shift + D` (`U+0988`)
* **উ:** `Shift + F` + `S` (`U+0989`)
* **ঊ:** `Shift + F` + `Shift + S` (`U+098A`)
* **ঋ:** `Shift + F` + `A` (`U+098B`)
* **এ:** `Shift + F` + `C` (`U+098F`)
* **ঐ:** Directly via `Shift + C` (`U+0990`)
* **ও:** `Shift + F` + (`ে` + `া`) (`U+0993`)
* **ঔ:** Directly via `Shift + X` (`U+0994`)

---

## 📄 Licence

This layout specification and documentation are licensed under the **[Creative Commons Attribution 4.0 International Licence (CC BY 4.0)](LICENSE)**.

You are free to share, adapt, and integrate this layout across all platforms (such as Gboard, OpenBoard, or bespoke IME implementations), provided that appropriate attribution is given to **Ekushey** as the original project.
