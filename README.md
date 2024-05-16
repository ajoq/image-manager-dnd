[![Build status](https://ci.appveyor.com/api/projects/status/1hqquh2pbb2bco79?svg=true)](https://ci.appveyor.com/project/ajoq/image-manager-dnd)

https://ajoq.github.io/js-image-manager-dnd/

#### Описание

Интерфейс:

![](./pic/image.png)

Схема работы:
1. При переносе изображения (Native DnD) с компьютера пользователя в блок Drag and Drop должна происходить загрузка файла (если это изображение) и отображение его внизу (превью с крестиком)
1. При клике на блок Drag and Drop должна открываться стандартная форма выбора файлов (как для native `<input type="file">`) после выбора файла также должна происходить загрузка с отображение его внизу (превью с крестиком)

Если пользователь два раза подряд выбрал один и тот же файл (не важно каким способом), этот файл оба раза загрузился и отображался внизу в превью (т.е. должно их быть два).
