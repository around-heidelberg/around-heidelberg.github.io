# Вокруг Хайдельберга

![Вид на Хайдельберг](./images/Heidelberger_Ansicht_(Merian).png)
*Гравюра "Вид на Хайдельберг", Маттеус Мериан Старший, швейцарский художник и гравёр, 1620*

[О городе](./heidelberg/README.md)

## Книги:

* [Хайдельберг: Истории и анекдоты](./books/geschichten-und-anekdoten/README.md). Сюзанна Фик. 2013.
* [Хайдельберг в средневековье и ренессансе](./books/mittelalter-und-renaissance/README.md). Кристоф Маунтель, Карла Мейер и Ахим Вендт. 2014
* [Секреты Хайдельберга](./books/heidelberger-geheimnisse/README.md). Ева Мария Баст, Хайке Тиссен. 2018

```topojson
{
  "type": "Topology",
  "transform": {
    "scale": [0.0005000500050005, 0.00010001000100010001],
    "translate": [100, 0]
  },
  "objects": {
    "example": {
      "type": "GeometryCollection",
      "geometries": [
        {
          "type": "Point",
          "properties": {"prop0": "value0"},
          "coordinates": [4000, 5000]
        },
        {
          "type": "LineString",
          "properties": {"prop0": "value0", "prop1": 0},
          "arcs": [0]
        },
        {
          "type": "Polygon",
          "properties": {"prop0": "value0",
            "prop1": {"this": "that"}
          },
          "arcs": [[1]]
        }
      ]
    }
  },
  "arcs": [[[4000, 0], [1999, 9999], [2000, -9999], [2000, 9999]],[[0, 0], [0, 9999], [2000, 0], [0, -9999], [-2000, 0]]]
}
```