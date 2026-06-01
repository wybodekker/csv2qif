# csv2qif

convert bank transaction downloads from CSV to QIF

## Properties

|key|value|
|-:|:-|
|  script:|csv2qif|
|   short:|convert bank transaction downloads from CSV to QIF|
|    type:|bash|
|  author:|Wybo Dekker|
|   email:|[wybodekker@me.com](mailto:wybodekker@me.com)|
| version:|2.09|
| license:|GNU General Public License|
|   intro:|csv2gif converts bank transaction downloads to the QIF|
|         |format, which can be imported into GnuCash. CSV formats|
|         |differ from one bank to the other.  Currently, the script|
|         |recognizes ING, RABO and ICS (International Card Services)|
|         |formats only (on the basis of their field counts, 19 for|
|         |RABO, 9 for ING, 7 for ICS). All formats may occur in|
|         |one file.|

## Options

|option|description|
|:-|:-|
|-h,--help	|print this help and exit|
|-H,--Help	|print full documentation via less and exit|
|-V,--version	|print version and exit|
|-y,--year=X	|convert data for year X only|
|-l,--lower	|convert description field to lower case|
|-t,--test	|run in test mode|
|-v,--verbose	|print warning for unfound categories|
