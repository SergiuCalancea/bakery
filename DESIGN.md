# Brutăria „Spic de Aur” — Design

## Concept
O brutărie artizanală de cartier: pâine cu maia, coaptă în cuptor cu vatră, în fiecare dimineață.
Tonul vizual e **cald, liniștit și meșteșugăresc**, ca hârtia de ambalaj, făina și coaja rumenită.
Fără fotografii stock: ilustrațiile sunt făcute din SVG și CSS, așa că site-ul se încarcă rapid și arată unitar.

## Paletă de culori
| Rol | Nume | Hex |
|---|---|---|
| Fundal principal | Făină | `#F7F1E6` |
| Fundal secundar | Aluat | `#EFE4D0` |
| Text principal | Espresso | `#2B1D14` |
| Text secundar | Scoarță | `#6B5444` |
| Accent principal | Coajă | `#B5652B` |
| Accent secundar | Spic | `#D9A441` |
| Accent rece | Salvie | `#7A8B6F` |

Regulă: accentul „Coajă” apare doar pe butoane, linkuri și prețuri, ca privirea să ajungă acolo.

## Tipografie
- **Titluri:** Fraunces (serif cu personalitate, amintește de etichetele tipărite vechi), greutate 600.
- **Text:** Work Sans, 400 / 500, 17px de bază, line-height 1.65.
- **Etichete mici:** Work Sans, majuscule, spațiere 0.14em.

## Elemente vizuale
- Colțuri rotunjite generoase (18–28px), ca o pâine.
- Umbre moi, maro, nu gri.
- Separatoare în formă de spic de grâu.
- Textură subtilă de „făină” (puncte radiale) pe fundalul secțiunii hero.

## Structura paginii
1. **Header:** logo, meniu (Produse, Despre, Program, Contact), buton „Comandă”
2. **Hero:** titlu mare, subtitlu, două butoane, ilustrație SVG cu o pâine
3. **Bandă de beneficii:** maia naturală · coaptă zilnic · ingrediente locale
4. **Produse:** grilă de 6 carduri (ilustrație, nume, descriere, preț)
5. **Despre noi:** poveste + statistici
6. **Cum lucrăm:** 4 pași (de la maia la cuptor)
7. **Testimoniale:** 3 citate
8. **Program și contact:** orar, adresă și formular de precomandă
9. **Footer**

## Responsive
- Desktop ≥ 960px: grile de 3 coloane, hero pe 2 coloane
- Tabletă 640–960px: 2 coloane
- Mobil < 640px: o coloană, meniu hamburger făcut doar din CSS (checkbox)
