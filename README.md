# Мобильные операционные системы / Mobile Operating Systems / Mobile Systeme

## Описание / Description / Beschreibung

### Русский
Это приложение показывает список актуальных мобильных операционных систем с их версиями и ссылками на официальные сайты. В приложении реализована архитектура MVI (Model-View-Intent) с использованием Jetpack Compose и Kotlin.

### English
This application shows a list of current mobile operating systems with their versions and links to official websites. The app implements MVI (Model-View-Intent) architecture using Jetpack Compose and Kotlin.

### German
Diese Anwendung zeigt eine Liste aktueller mobiler Betriebssysteme mit ihren Versionen und Links zu den offiziellen Websites. Die App implementiert die MVI-Architektur (Model-View-Intent) mit Jetpack Compose und Kotlin.

## Технологии / Technologies / Technologien

### Русский
- Jetpack Compose — современный UI-фреймворк для Android
- Kotlin — основной язык программирования
- MVI архитектура — разделение ответственности между слоями
- ViewModel — управление состоянием UI
- StateFlow — реактивное обновление данных
- Coroutines — асинхронные операции

### English
- Jetpack Compose — modern UI framework for Android
- Kotlin — primary programming language
- MVI architecture — separation of concerns between layers
- ViewModel — UI state management
- StateFlow — reactive data updates
- Coroutines — asynchronous operations

### German
- Jetpack Compose — modernes UI-Framework für Android
- Kotlin — primäre Programmiersprache
- MVI-Architektur — Trennung der Verantwortlichkeiten zwischen Schichten
- ViewModel — UI-Zustandsverwaltung
- StateFlow — reaktive Datenaktualisierung
- Coroutines — asynchrone Operationen

## Список операционных систем / List of operating systems / Liste der Betriebssysteme

| ОС / OS / Betriebssystem | Версия / Version / Version | Ссылка / Link / Link |
|--------------------------|----------------------------|---------------------|
| Android 15 | https://www.android.com/ |
| iOS 18 | https://www.apple.com/ios/ |
| HarmonyOS 5.0 | https://www.harmonyos.com/ |
| Windows Mobile 10 | https://www.microsoft.com/mobile/ |
| KaiOS 3.0 | https://www.kaiostech.com/ |
| BlackBerry OS 10 | https://www.blackberry.com/ |
| Sailfish OS 4.5 | https://sailfishos.org/ |
| Tizen 7.0 | https://www.tizen.org/ |

## Установка / Installation / Installation

1. Склонируйте репозиторий / Clone the repository / Repository klonen:
```bash
git clone https://github.com/invweb/mobile-operating-systems.git
```

2. Откройте проект в Android Studio / Open the project in Android Studio / Öffnen Sie das Projekt in Android Studio

3. Синхронизируйте Gradle / Sync Gradle / Gradle synchronisieren

4. Запустите приложение / Run the app / App ausführen

## Архитектура / Architecture / Architektur

### Модуль MVI / MVI Module / MVI Modul

**MobileSystemsIntent.kt** — действия пользователя (например, загрузка данных)
**MobileSystemsState.kt** — состояние UI (загрузка, данные, ошибка)
**MobileSystemsViewModel.kt** — обрабатывает интенты и управляет состоянием
**MobileSystemsConfig.kt** — конфигурация систем с ID ресурсов и URL

## Лицензия / License / Lizenz

Этот проект создан в образовательных целях.

## История разработки / Development History / Entwicklungsgeschichte

### Русский
Этот проект был разработан с использованием GigaCode AI-ассистента, разработанного Sber. GigaCode помог в следующих задачах:

- Настройка проекта Android с нуля
- Создание архитектуры MVI (Model-View-Intent)
- Реализация Jetpack Compose UI с Kotlin
- Управление конфликтами слияния Git
- Организация ресурсов для многоязычной поддержки (RU, EN, DE)
- Публикация на GitHub

**Как я это сделал:**
1. Создал новый проект Android Studio с Jetpack Compose
2. Настроил MVI архитектуру с ViewModel и StateFlow
3. Добавил конфигурацию операционных систем в MobileSystemsConfig.kt
4. Реализовал UI с Jetpack Compose
5. Настроил многоязычную поддержку (RU, EN, DE)
6. Опубликовал проект на GitHub

### English
This project was developed using the GigaCode AI assistant developed by Sber. GigaCode assisted with the following tasks:

- Setting up Android project from scratch
- Implementing MVI (Model-View-Intent) architecture
- Developing Jetpack Compose UI with Kotlin
- Managing Git merge conflicts
- Organizing resources for multi-language support (RU, EN, DE)
- Publishing to GitHub

**How I did it:**
1. Created a new Android Studio project with Jetpack Compose
2. Set up MVI architecture with ViewModel and StateFlow
3. Added operating systems configuration in MobileSystemsConfig.kt
4. Implemented UI with Jetpack Compose
5. Configured multi-language support (RU, EN, DE)
6. Published the project to GitHub

### German
Dieses Projekt wurde mit dem GigaCode AI-Assistenten von Sber entwickelt. GigaCode half bei folgenden Aufgaben:

- Einrichtung des Android-Projekts von Grund auf
- Implementierung der MVI-Architektur (Model-View-Intent)
- Entwicklung der Jetpack Compose UI mit Kotlin
- Verwaltung von Git-Merge-Konflikten
- Organisation der Ressourcen für mehrsprachige Unterstützung (RU, EN, DE)
- Veröffentlichung auf GitHub

**Wie ich es gemacht habe:**
1. Erstellt ein neues Android Studio-Projekt mit Jetpack Compose
2. Konfigurierte MVI-Architektur mit ViewModel und StateFlow
3. Fügte Konfiguration der Betriebssysteme in MobileSystemsConfig.kt hinzu
4. Implementierte UI mit Jetpack Compose
5. Konfigurierte mehrsprachige Unterstützung (RU, EN, DE)
6. Veröffentlichte das Projekt auf GitHub

## Ссылки / Links / Links

- GitHub: https://github.com/invweb/mobile-operating-systems
- Android: https://www.android.com/
- iOS: https://www.apple.com/ios/
- HarmonyOS: https://www.harmonyos.com/
