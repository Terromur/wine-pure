# PKGBUILDs

Это персональная коллекция PKGBUILDS от Ventureoo, но изменённая с агрессивными оптимизациями, кто хочет получить производительность выше после сборки. 
Так же были добавлены мои PKGBUILDS, которые я сопровожданию и форкнутый CachyOS-Settings.

Ссылка на официальный репозиторий PKGBUILDS Ventureoo - https://github.com/ventureoo/PKGBUILDs

Ссылка на официальный репозиторий CachyOS-Settings - https://github.com/CachyOS/CachyOS-Settings

Был добавлен dxvk-sarek-pure и dxvk-sarek-async-pure:
- Все теже изменения, которые есть в dxvk-pure-git
- Напомню, что dxvk-sarek-async-pure можно использовать тогда, когда вы не планируете использовать ntsync

Был добавлен Cachyos-Settings с изменениями:
- Оптимизация интернета, увеличение стабильности, улучшение работы прокси, прочие дополнительные оптимизации
- Включение опции перезагрузки системы после kernel panic через 10 секунд

Был изменён mesa-pure:
- Добавление агрессивной оптимизации -O3 и собирание пакета в native
- Включение llvm (без LTO)
- Включение бета Vulkan
- Добавление патчей на исправления старых видеокарт Radeon и другие исправления и оптимизация
- Отключение дополнительных ненужных опций
- Добавление опций на оптимизацию и ускорения сборки пакета
- Добавление комментария про -falign-functions=32 и -ftree-vectorize в PKGBUILD

Был изменён dxvk-pure-git:
- Агрессивная оптимизация -O3 и другие флаги
- Увеличение стабильности в других аспектах.
- Обновлённые флаги, взятые из Proton. Увеличение стабильности и корректное использование флагов для mingw 64 и 32 компиллятора

Был изменён wine-pure:
- Агрессивная оптимизация -O3 и другие флаги
- Добавление комментария про дополнительные включения флагов оптимизации

Был изменён mpv-pure:
- Был включён Vulkan для AMD

Если какой-то пакет собирается с ошибками, то, пожалуйста, проверьте сначала PKGBUILD от Ventureoo в его официальном репозитории, а потом сообщайте баг мне.
