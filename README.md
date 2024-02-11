# Tagization

## Feature

When the compound criteria `minecraft.A:minecraft.B` increase, the tag `#minecraft:A.B` is triggered.

Only enabled tags can be triggered, to save performance.

## How to use

To enable the tag `#minecraft:A.B`, go to your pack which use this tag,

Create `data\minecraft\tags\functions\pre.json` with the following contents.

```json
{
  "values": [
    "minecraft:A/B/0a"
  ]
}
```

Create `data\minecraft\tags\functions\pro.json` with the following contents.

```json
{
  "values": [
    "minecraft:A/B/0b"
  ]
}
```

## License

"[Tagization](https://github.com/Windyera/Tagization)" by [Windyera](https://github.com/Windyera) is licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)