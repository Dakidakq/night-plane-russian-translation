# Night Plane — русификатор

Русификатор для лицензионной Steam-версии **Night Plane**.

## Установка

1. Откройте Steam → **Библиотека**.
2. Нажмите правой кнопкой мыши по **Night Plane** → **Свойства** → **Установленные файлы** → **Обзор**.
3. Откройте папку `NightPlane\Content`.
4. Создайте вложенные папки:

   ```text
   Localization\Game\ru
   ```

5. Скопируйте `Game.locres` в папку `ru`. Итоговый путь:

   ```text
   …\SteamLibrary\steamapps\common\Night Plane\NightPlane\Content\Localization\Game\ru\Game.locres
   ```

6. В Steam откройте **Свойства** игры → **Параметры запуска** и добавьте:

   ```text
   -culture=ru
   ```

7. Запустите игру через Steam.

## Удаление

Удалите `Game.locres` из папки `ru` и уберите `-culture=ru` из параметров запуска Steam.
