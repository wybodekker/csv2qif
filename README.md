# csv2qif
|     key | description
|     ---:|:---
|  script | csv2qif - convert bank transaction downloads from CSV to QIF
|    type | bash
|  author | Wybo Dekker
|   email | wybo@dekkerdocumenten.nl
| version | 2.07
| license | GNU General Public License

csv2gif converts bank transaction downloads to the QIF format, which can be
imported into GnuCash. CSV formats differ from one bank to the other.
Currently, the script recognizes ING, RABO and ICS (International Card
Services) formats only (on the basis of their field counts, 19 for RABO, 9
for ING, 7 for ICS). All formats may occur in one file.
