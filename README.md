# BMKGINFO

BMKGINFO is a Python library for getting information about latest earth quake and wheather forecast in Indonesia base on BMKG | Meteorological, Climatological, and Geophysical Agency Website.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
pip install bmkginfo
```

## Usage

```python
from bmkginfo import WeatherForecast, LatestEarthQuake

wf = WeatherForecast()
print(wf.get_data())

leq = LatestEarthQuake()
print(leq.get_data())

```

output:

```json
[
    {
        "city": "Banda Aceh",
        "hour": "16:00 WIB",
        "wheather": "Cerah",
        "temp": "32°C"
    },
    {
        "city": "Serang",
        "hour": "16:00 WIB",
        "wheather": "Berawan",
        "temp": "30°C"
    },
    {
        "city": "Bengkulu",
        "hour": "16:00 WIB",
        "wheather": "Berawan",
        "temp": "27°C"
    },
    {
        "city": "Yogyakarta",
        "hour": "16:00 WIB",
        "wheather": "Berawan",
        "temp": "27°C"
    },
    {
        "city": "Jakarta",
        "hour": "16:00 WIB",
        "wheather": "Cerah Berawan",
        "temp": "29°C"
    },
    {
        "city": "Jambi",
        "hour": "16:00 WIB",
        "wheather": "Hujan Ringan",
        "temp": "29°C"
    },
    {
        "city": "Bandung",
        "hour": "16:00 WIB",
        "wheather": "Hujan Ringan",
        "temp": "27°C"
    },
    {
        "city": "Semarang",
        "hour": "16:00 WIB",
        "wheather": "Berawan",
        "temp": "30°C"
    },
    {
        "city": "Surabaya",
        "hour": "16:00 WIB",
        "wheather": "Cerah Berawan",
        "temp": "31°C"
    },
    {
        "city": "Pontianak",
        "hour": "16:00 WIB",
        "wheather": "Cerah Berawan",
        "temp": "27°C"
    },
    {
        "city": "Palangkaraya",
        "hour": "16:00 WIB",
        "wheather": "Hujan Ringan",
        "temp": "29°C"
    },
    {
        "city": "Pangkal Pinang",
        "hour": "16:00 WIB",
        "wheather": "Cerah Berawan",
        "temp": "29°C"
    },
    {
        "city": "Tanjung Pinang",
        "hour": "16:00 WIB",
        "wheather": "Hujan Ringan",
        "temp": "29°C"
    },
    {
        "city": "Lampung",
        "hour": "16:00 WIB",
        "wheather": "Berawan",
        "temp": "27°C"
    },
    {
        "city": "Pekanbaru",
        "hour": "16:00 WIB",
        "wheather": "Cerah Berawan",
        "temp": "30°C"
    },
    {
        "city": "Padang",
        "hour": "16:00 WIB",
        "wheather": "Cerah Berawan",
        "temp": "26°C"
    },
    {
        "city": "Palembang",
        "hour": "16:00 WIB",
        "wheather": "Cerah Berawan",
        "temp": "32°C"
    },
    {
        "city": "Medan",
        "hour": "16:00 WIB",
        "wheather": "Cerah Berawan",
        "temp": "30°C"
    },
    {
        "city": "Denpasar",
        "hour": "17:00 WITA",
        "wheather": "Cerah Berawan",
        "temp": "29°C"
    },
    {
        "city": "Gorontalo",
        "hour": "17:00 WITA",
        "wheather": "Cerah",
        "temp": "29°C"
    },
    {
        "city": "Banjarmasin",
        "hour": "17:00 WITA",
        "wheather": "Hujan Petir",
        "temp": "28°C"
    },
    {
        "city": "Samarinda",
        "hour": "17:00 WITA",
        "wheather": "Cerah Berawan",
        "temp": "28°C"
    },
    {
        "city": "Tanjung Selor",
        "hour": "17:00 WITA",
        "wheather": "Cerah",
        "temp": "31°C"
    },
    {
        "city": "Mataram",
        "hour": "17:00 WITA",
        "wheather": "Cerah Berawan",
        "temp": "29°C"
    },
    {
        "city": "Kupang",
        "hour": "17:00 WITA",
        "wheather": "Berawan",
        "temp": "28°C"
    },
    {
        "city": "Mamuju",
        "hour": "17:00 WITA",
        "wheather": "Hujan Lebat",
        "temp": "30°C"
    },
    {
        "city": "Makassar",
        "hour": "17:00 WITA",
        "wheather": "Berawan",
        "temp": "30°C"
    },
    {
        "city": "Palu",
        "hour": "17:00 WITA",
        "wheather": "Berawan",
        "temp": "25°C"
    },
    {
        "city": "Kendari",
        "hour": "17:00 WITA",
        "wheather": "Berawan",
        "temp": "30°C"
    },
    {
        "city": "Manado",
        "hour": "17:00 WITA",
        "wheather": "Berawan",
        "temp": "28°C"
    },
    {
        "city": "Ambon",
        "hour": "18:00 WIT",
        "wheather": "Cerah Berawan",
        "temp": "28°C"
    },
    {
        "city": "Sofifi",
        "hour": "18:00 WIT",
        "wheather": "Cerah",
        "temp": "29°C"
    },
    {
        "city": "Jayapura",
        "hour": "18:00 WIT",
        "wheather": "Cerah Berawan",
        "temp": "30°C"
    },
    {
        "city": "Manokwari",
        "hour": "18:00 WIT",
        "wheather": "Berawan",
        "temp": "26°C"
    }
]
```

```json
{
    "time": "11 Oktober 2021, 10:09:56 WIB",
    "magnitude": "4.9",
    "depth": "70 km",
    "coordinate": "9.03 LS - 122.50 BT",
    "location": "Pusat gempa berada diLaut 55 km Tenggara Maumere Sikka",
    "felt": "Dirasakan (Skala MMI): II Lembata, II Ende, II Maumere"
}
```

## License

[MIT](https://choosealicense.com/licenses/mit/)
