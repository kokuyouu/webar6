# Задание 6 — Unity WebXR

Готовая WebGL-сборка. Установка Unity для публикации не требуется.

## GitHub Pages

Загрузите содержимое этой папки в корень репозитория ar6, включая Build и .nojekyll.
Settings → Pages → Deploy from a branch → main → /(root) → Save.
Для аккаунта kokuyouu адрес будет https://kokuyouu.github.io/ar6/.

## Локальный запуск

`python3 -m http.server 8000`

Откройте http://localhost:8000. Не запускайте index.html через file://.
В обычном браузере доступен 3D-предпросмотр; AR требует поддержки WebXR immersive-ar и HTTPS (localhost разрешён для разработки).
Куб следует за взглядом на расстоянии 0,7 м, а не привязывается к поверхности.

На Mac для эмуляции можно использовать Immersive Web Emulator в Chrome:
https://chromewebstore.google.com/detail/immersive-web-emulator/cgffilbpcibhmcfbgggfhfolhkfbhmik
Эмуляция не заменяет проверку на физическом мобильном устройстве.

build-info.json содержит исходные сведения о сборке. Изменение сцены и C#-логики требует пересборки Unity-проекта.
