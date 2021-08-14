## Основаная информация:
Пространство имен: `Migliore.RPGSystem.Models.Data`
Имя класса: `PlayerAbilitiesData`

## Ссылки на документацию других файлов
[PerkInfo](https://github.com/DevInc0/DI.Migliore.PluginDocumentation/blob/main/RPGSystem/PerkInfo.md)

## Поля
`ushort CurrentLevel` - текущий уровень игрока

`ushort PointsAmount` - количество очков навыков игрока

`uint ExperienceToNewLevel` - требуемое количество опыта до нового уровня

`List<string> TraitNames` - имена всех текущих черт игрока

`List<PerkInfo> PerkInfos` - имена и описания всех текущих перков игрока<br>

## Конструкторы
`PlayerAbilitiesData(ushort currentLevel, ushort pointsAmount, uint experienceToNewLevel, List<string> traitNames, List<PerkInfo> perkInfos)`

`PlayerAbilitiesData(RPGComponent component)`














