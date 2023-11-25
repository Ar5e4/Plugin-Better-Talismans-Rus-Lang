# Plugin-Better-Talismans-Rus-Lang
Плагин Better Talismans На Русском Языке (Ручной Перевод)

В Плагине Всё Переведено!!! Самостоятельный перевод карается поломкой/отключения плагина (делайте на свой страх и риск)

В Файле Config.yml я решил добавить уже готовые вещи (там есть как и сферы так и талисманы)

Не Забывайте Что Плагин Был Платный А Я ЕГО ПЕРЕВЁЛ БЕСПЛАТНО!!! так что пожалуйста поделитесь плагином с кем нибудь для его продвижения!!!

Для Измены Названий И Тд у Предметов В Файле Talismans.yml Есть Строки: 

Fugu:
    Item:
      #You can use any item you want, if you want a CUSTOM textured head. you need to use: "CUSTOM_HEAD" and specify a value in "Texture"
      #You can get textures from website https://minecraft-heads.com/custom-heads
      #Choose one and use "Value" value.
      Material: "TOTEM_OF_UNDYING"
      #Only available if Material is "CUSTOM_HEAD"
      #This option adds enchantment to talisman to make it glow.
      Glow: true
      #Recommended to leave this enabled if equip slots in "Modifiers" list is more than 1.
      #If you disable this, i recommend you to remove {ATTRIBUTES} lines from lore as it will be duplicated.
      #Disabling this WONT display enchantments. This is just for attributes.
      Hide-attributes: true
      #This option adds custom model in case you wanna make a texture for it.
      #Set it to 0 to disable. This option is only available in 1.14 and newer, will not apply if Material is "CUSTOM_HEAD"
      CustomModelData: 0
      Displayname: "&c&l[★] &6Талисман Фугу"
      Lore:
      # {ATTRIBUTES} will be replaced with ALL modifiers defined in "Modifiers" section.
      #You can always remove that placeholder and add your own lore.
      - "&5+4 Урон"
      - "&c-2 Максимальное здоровье"
      - "&c-4 Твёрдость брони"
      - "&c-4 Броня"
    #This is the list of modifiers. Keep in mind some modifiers are not compatible with others.
    Modifiers:
    # Follow the format: MODIFIER_NAME|AMOUNT
    # It can be used also a format to specify slots where the modifier takes effect, otherwise it will available only for main hand and off hand (if available)
    # Example: "HEALTH_BOOST|10|MAIN_HAND,OFF_HAND,HEAD,CHEST,LEGS,FEET" or "HEALTH_BOOST|10|MAIN_HAND,OFF_HAND"
    # Modifiers won't work in version below 1.9, please read all this file before using the plugin to know which boosts work in which versions.
    - "ATTACK_DAMAGE|+4|OFF_HAND"
    - "HEALTH_BOOST|-2|OFF_HAND"
    - "ARMOR_TOUGHNESS|-4|OFF_HAND"
    - "ARMOR|-4|OFF_HAND"
    Recipe:
      #Should the talisman be craftable?
      Enabled: false
      #Title of the recipe inventory.
      Title: "&8Life Talisman recipe"
      #Permission to craft this talisman. If removed or "none", then no permission will be required.
      #This permission is also used to show players recipes for talismans using /bettertalismans talismans
      #NOTE: This permission is NOT TO BE ABLE TO USE THE TALISMAN. All players can use all talismans if they have
==============================================================================================================================================================================
Это Был Примерный Тест

Там В Строке: #Only available if Material is "CUSTOM_HEAD" можно сделать сферу

А В СТРОКЕ: Displayname: "&c&l[★] &6Талисман Фугу"
Укажи Название Предмета

Строки:
      - "&5+4 Урон"
      - "&c-2 Максимальное здоровье"
      - "&c-4 Твёрдость брони"
      - "&c-4 Броня"
      Указываем тут параметры того что хотим сделать (&c - нужен для обозначения предмета в майнкрафте (не трогаем))

      Дальше Можно Разобраться Самому Плагин Очень Простой И Удобный
      Повторяю Пожалуйста Поделитесь этим с другом или кодером для продвижения!!!
