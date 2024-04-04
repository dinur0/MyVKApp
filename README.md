## Описание

Этот проект реализует iOS приложение, которое демонстрирует работу с сетью, CoreData, пользовательскими UIView и UIKit. Включает функциональность смены темы приложения, сохранение данных пользователей и групп в локальную базу данных с использованием CoreData, отображение друзей, групп и фотографий пользователя из VK.

## Ключевые компоненты

- `AppDelegate` и `SceneDelegate` для настройки и жизненного цикла приложения.
- `ChangeThemeSubview` для смены тем приложения.
- `CoreData` для работы с локальной базой данных.
- `CustomCell` для настройки пользовательских ячеек в таблицах и коллекциях.
- `NetworkServiceClass` для работы с сетевыми запросами к API VK.
- `Themes` для реализации смены темы интерфейса.

## Зависимости

- UIKit
- CoreData
- WebKit
- SwiftUI (для использования Charts)

## Установка и запуск

Для работы с проектом необходим Xcode. Клонируйте репозиторий, откройте проект в Xcode и запустите на симуляторе или устройстве.
Авторизуйтесь на главной странице. После успешной авторизации вы сможете просмотреть информацию о ваших друзьях, группах и фото. При выборе друга в разделе `Friends` открывается окно друга.
