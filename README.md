# HavalDargo

# Android ADB Команды и сервисные пароли

## Внешний USB GPS-приёмник

Разрешить приложению GNSS Commander использовать фиктивные координаты (Mock Location):

```bash
adb shell appops set de.pilablu.gnsscommander android:mock_location allow
```

---

## Раздача GPS-координат со смартфона

Разрешить приложению GPS Tether использовать фиктивные координаты (Mock Location):

```bash
adb shell appops set com.ryanandbrenda.gpstether android:mock_location allow
```

---

## Полноэкранный режим для Яндекс Музыки

Скрыть навигационную панель Android:

```bash
adb shell settings put global policy_control immersive.navigation=ru.yandex.music
```

---

## Полноэкранный режим для Яндекс Навигатора

Скрыть навигационную панель Android:

```bash
adb shell settings put global policy_control immersive.navigation=ru.yandex.yandexnavi
```

---

## Отмена полноэкранного режима

Вернуть отображение навигационной панели и стандартный интерфейс Android:

```bash
adb shell settings put global policy_control null
```

---

# Инженерное меню

## Пароль №1

```text
*#4435ab
```

## Пароль №2

```text
aZ10&*+30
```
