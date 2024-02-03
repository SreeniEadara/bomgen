# bomgen
Sreenivas Eadara

BOM generator for KiCad that can ignore a specified set of fields.

## Usage

Identical to bom_csv_grouped_by_value. Additional optarg is the full path to a .csv file containing fields to ignore. Fields can be listed on newlines, comma-separated, or both (but it is whitespace sensitive).

Example:
```
/Applications/KiCad/KiCad.app/Contents/Frameworks/Python.framework/Versions/Current/bin/python3 "/Users/sreenieadara/Documents/bomgen/bomgen.py" "%I" "%O.csv" "/Users/sreenieadara/Documents/bomgen/fields_avoid.csv"
```
