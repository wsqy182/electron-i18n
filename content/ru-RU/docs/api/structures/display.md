# Display Объект

* `id` Number - Уникальный числовой идентификатор дисплея.
* `rotation` Number - Число, которое представляет собой угол поворота экрана. Может быть 0, 90, 180, 270.
* `scaleFactor` Number - Матричный коэффициент пиксельного маштабирования выходного устройства.
* `touchSupport` String - Может быть `available`, `unavailable`, `unknown`.
* `bounds` [Rectangle](rectangle.md)
* `size` [Size](size.md)
* `workArea` [Rectangle](rectangle.md)
* `workAreaSize` [Size](size.md)

`Display` - объект представляет физический дисплей, подключенный к системе. Подделка `Display` может существовать в безголовой системе, или `Display` может соответствовать удаленному виртуальному дисплею.