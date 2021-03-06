# BMKGINFO

BMKGINFO is a Python library for getting information about latest earth quake and wheather forecast in Indonesia base on BMKG | Meteorological, Climatological, and Geophysical Agency Website.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install bmkginfo.

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
        "wheather": "Cerah Berawan",
        "temp": "31°C",
        "image": "https://www.bmkg.go.id/asset/img/icon-cuaca/cerah%20berawan-am.png"
    },
    {
        "city": "Serang",
        "hour": "16:00 WIB",
        "wheather": "Hujan Ringan",
        "temp": "29°C",
        "image": "https://www.bmkg.go.id/asset/img/icon-cuaca/hujan%20ringan-am.png"
    },
    {
        "city": "Bengkulu",
        "hour": "16:00 WIB",
        "wheather": "Berawan",
        "temp": "28°C",
        "image": "https://www.bmkg.go.id/asset/img/icon-cuaca/berawan-am.png"
    },
    {
        "city": "Yogyakarta",
        "hour": "16:00 WIB",
        "wheather": "Berawan",
        "temp": "28°C",
        "image": "https://www.bmkg.go.id/asset/img/icon-cuaca/berawan-am.png"
    },
    {
        "city": "Jakarta",
        "hour": "16:00 WIB",
        "wheather": "Berawan",
        "temp": "30°C",
        "image": "https://www.bmkg.go.id/asset/img/icon-cuaca/berawan-am.png"
    },
    {
        "city": "Jambi",
        "hour": "16:00 WIB",
        "wheather": "Berawan",
        "temp": "30°C",
        "image": "https://www.bmkg.go.id/asset/img/icon-cuaca/berawan-am.png"
    },
    {
        "city": "Bandung",
        "hour": "16:00 WIB",
        "wheather": "Hujan Petir",
        "temp": "22°C",
        "image": "https://www.bmkg.go.id/asset/img/icon-cuaca/hujan%20petir-am.png"
    },
    {
        "city": "Semarang",
        "hour": "16:00 WIB",
        "wheather": "Berawan",
        "temp": "30°C",
        "image": "https://www.bmkg.go.id/asset/img/icon-cuaca/berawan-am.png"
    },
    {
        "city": "Surabaya",
        "hour": "16:00 WIB",
        "wheather": "Cerah Berawan",
        "temp": "32°C",
        "image": "https://www.bmkg.go.id/asset/img/icon-cuaca/cerah%20berawan-am.png"
    },
    {
        "city": "Pontianak",
        "hour": "16:00 WIB",
        "wheather": "Cerah Berawan",
        "temp": "26°C",
        "image": "https://www.bmkg.go.id/asset/img/icon-cuaca/cerah%20berawan-am.png"
    },
    {
        "city": "Palangkaraya",
        "hour": "16:00 WIB",
        "wheather": "Hujan Ringan",
        "temp": "29°C",
        "image": "https://www.bmkg.go.id/asset/img/icon-cuaca/hujan%20ringan-am.png"
    },
    {
        "city": "Pangkal Pinang",
        "hour": "16:00 WIB",
        "wheather": "Berawan",
        "temp": "29°C",
        "image": "https://www.bmkg.go.id/asset/img/icon-cuaca/berawan-am.png"
    },
    {
        "city": "Tanjung Pinang",
        "hour": "16:00 WIB",
        "wheather": "Berawan",
        "temp": "30°C",
        "image": "https://www.bmkg.go.id/asset/img/icon-cuaca/berawan-am.png"
    },
    {
        "city": "Lampung",
        "hour": "16:00 WIB",
        "wheather": "Hujan Ringan",
        "temp": "28°C",
        "image": "https://www.bmkg.go.id/asset/img/icon-cuaca/hujan%20ringan-am.png"
    },
    {
        "city": "Pekanbaru",
        "hour": "16:00 WIB",
        "wheather": "Cerah Berawan",
        "temp": "34°C",
        "image": "https://www.bmkg.go.id/asset/img/icon-cuaca/cerah%20berawan-am.png"
    },
    {
        "city": "Padang",
        "hour": "16:00 WIB",
        "wheather": "Cerah Berawan",
        "temp": "28°C",
        "image": "https://www.bmkg.go.id/asset/img/icon-cuaca/cerah%20berawan-am.png"
    },
    {
        "city": "Palembang",
        "hour": "16:00 WIB",
        "wheather": "Hujan Ringan",
        "temp": "29°C",
        "image": "https://www.bmkg.go.id/asset/img/icon-cuaca/hujan%20ringan-am.png"
    },
    {
        "city": "Medan",
        "hour": "16:00 WIB",
        "wheather": "Cerah Berawan",
        "temp": "31°C",
        "image": "https://www.bmkg.go.id/asset/img/icon-cuaca/cerah%20berawan-am.png"
    },
    {
        "city": "Denpasar",
        "hour": "17:00 WITA",
        "wheather": "Cerah Berawan",
        "temp": "29°C",
        "image": "https://www.bmkg.go.id/asset/img/icon-cuaca/cerah%20berawan-am.png"
    },
    {
        "city": "Gorontalo",
        "hour": "17:00 WITA",
        "wheather": "Cerah",
        "temp": "28°C",
        "image": "https://www.bmkg.go.id/asset/img/icon-cuaca/cerah-am.png"
    },
    {
        "city": "Banjarmasin",
        "hour": "17:00 WITA",
        "wheather": "Berawan",
        "temp": "28°C",
        "image": "https://www.bmkg.go.id/asset/img/icon-cuaca/berawan-am.png"
    },
    {
        "city": "Samarinda",
        "hour": "17:00 WITA",
        "wheather": "Cerah Berawan",
        "temp": "29°C",
        "image": "https://www.bmkg.go.id/asset/img/icon-cuaca/cerah%20berawan-am.png"
    },
    {
        "city": "Tanjung Selor",
        "hour": "17:00 WITA",
        "wheather": "Cerah Berawan",
        "temp": "27°C",
        "image": "https://www.bmkg.go.id/asset/img/icon-cuaca/cerah%20berawan-am.png"
    },
    {
        "city": "Mataram",
        "hour": "17:00 WITA",
        "wheather": "Hujan Ringan",
        "temp": "29°C",
        "image": "https://www.bmkg.go.id/asset/img/icon-cuaca/hujan%20ringan-am.png"
    },
    {
        "city": "Kupang",
        "hour": "17:00 WITA",
        "wheather": "Berawan",
        "temp": "29°C",
        "image": "https://www.bmkg.go.id/asset/img/icon-cuaca/berawan-am.png"
    },
    {
        "city": "Mamuju",
        "hour": "17:00 WITA",
        "wheather": "Hujan Ringan",
        "temp": "30°C",
        "image": "https://www.bmkg.go.id/asset/img/icon-cuaca/hujan%20ringan-am.png"
    },
    {
        "city": "Makassar",
        "hour": "17:00 WITA",
        "wheather": "Hujan Ringan",
        "temp": "30°C",
        "image": "https://www.bmkg.go.id/asset/img/icon-cuaca/hujan%20ringan-am.png"
    },
    {
        "city": "Palu",
        "hour": "17:00 WITA",
        "wheather": "Cerah Berawan",
        "temp": "27°C",
        "image": "https://www.bmkg.go.id/asset/img/icon-cuaca/cerah%20berawan-am.png"
    },
    {
        "city": "Kendari",
        "hour": "17:00 WITA",
        "wheather": "Berawan",
        "temp": "29°C",
        "image": "https://www.bmkg.go.id/asset/img/icon-cuaca/berawan-am.png"
    },
    {
        "city": "Manado",
        "hour": "17:00 WITA",
        "wheather": "Cerah Berawan",
        "temp": "29°C",
        "image": "https://www.bmkg.go.id/asset/img/icon-cuaca/cerah%20berawan-am.png"
    },
    {
        "city": "Ambon",
        "hour": "18:00 WIT",
        "wheather": "Cerah Berawan",
        "temp": "28°C",
        "image": "https://www.bmkg.go.id/asset/img/icon-cuaca/cerah%20berawan-pm.png"
    },
    {
        "city": "Sofifi",
        "hour": "18:00 WIT",
        "wheather": "Berawan",
        "temp": "30°C",
        "image": "https://www.bmkg.go.id/asset/img/icon-cuaca/berawan-pm.png"
    },
    {
        "city": "Jayapura",
        "hour": "18:00 WIT",
        "wheather": "Cerah Berawan",
        "temp": "28°C",
        "image": "https://www.bmkg.go.id/asset/img/icon-cuaca/cerah%20berawan-pm.png"
    },
    {
        "city": "Manokwari",
        "hour": "18:00 WIT",
        "wheather": "Cerah Berawan",
        "temp": "28°C",
        "image": "https://www.bmkg.go.id/asset/img/icon-cuaca/cerah%20berawan-pm.png"
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
