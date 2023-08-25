# Cambodia geographical data

Data (2023) from [db.ncdd.gov.kh](http://db.ncdd.gov.kh/gazetteer/view/index.castle)

## Data format support

- Json
- Mysql
- SQL Server
- Excel (xlsx)

## Example Json

```json
[
  {
    "type": "province",
    "code": "02",
    "parent_code": "855",
    "name_khmer": "បាត់ដំបង",
    "name_latin": "Battambang",
    "reference": "លេខ​៤៩៣ប្រ.ក",
    "official_note": "",
    "note_by_checker": ""
  },
  {
    "type": "district",
    "code": "0206",
    "parent_code": "02",
    "name_khmer": "មោងឫស្សី",
    "name_latin": "Moung Ruessei",
    "reference": "លេខ​៤៩៣ប្រ.ក",
    "official_note": "តាមប្រកាសរបស់ក្រសួងមហាផ្ទៃ",
    "note_by_checker": ""
  }
]
```

## Type

- capital
- province
- city
- district
- khan
- commune
- sangkat
- village

## parent_code

Reference to parent code, "02" is code of Battambang province

## License

[MIT](LICENSE)
