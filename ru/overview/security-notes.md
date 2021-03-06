# Заметки о безопасности

# SEED & Пароль

Прежде чем создавать учетную запись, вам необходимо обратить внимание на способ хранения средств в Waves приложениях.
В Waves приложении нет файла .dat, который хранил бы ваши приватные ключи. Вместо этого, в системе содержится SEED, который предоставляет
вам доступ к ключам. По умолчанию, SEED представляет собой строку из 15 английских слов -
**ВНИМАНИЕ: если вы потеряете SEED, вы потеряете доступ к своей учетной записи**.

Мы настоятельно рекомендуем создать резервную копию SEED фразы на листе бумаги и сохранить его в надежном месте.
Секретная фраза состоящая из 15 английских слов является максимально безопасной с точки зрения криптографии и, в настоящий момент, не существует технологии, способной её взломать \(вероятность того, что кто-то может подобрать секретную фразу, созданную в Waves приложении, составляет 1:(2048^15)\). Каждый SEED привязан только к одной учетной записи Waves. Каждая цифра, символ, символ и пробел учавствуют в генерации Waves адреса: стоит добавить всего один символ к SEED фразе и сгенерируется другой Waves адрес. Если некорректно ввести оригинальную фразу, в таком случае вы получите совершенно другой Waves аккаунт.

## Не забудьте создать резервную копию seed фразы! Как это сделать:

* [Онлайн/Настольное приложение](https://docs.wavesplatform.com/ru/waves-client/account-management/creating-an-account.html#предупреждение)
* [iOS приложение](https://docs.wavesplatform.com/ru/waves-client/mobile-apps/iOS/account-management/creating-an-account.html#предупреждение)
* [Android приложение](https://docs.wavesplatform.com/ru/waves-client/mobile-apps/android/account-management/creating-an-account.html#предупреждение)

Во время создания учетной записи вам также будет предложено задать пароль для вашего адреса.

Создание пароля для аккаунта имеет следующие цели:

1. Пароль шифрует SEED локально для безоопасного обращения с приватными данными.  
2. Ваша учетная запись будет зашифрована паролем и хранится в кеше вашего устрофства, поэтому вам не нужно импортировать SEED при каждом входе в систему.
Пароль гарантирует, что вы можете войти в свою учетную запись. Если вы потеряете свой пароль, вы можете просто удалить аккаунт из кэша и восстановить его, используя ваш SEED.

**Примечания:**

* Если вы забыли пароль, вы можете легко создать новый, используя следующую инструкцию для
[восстановления аккаунта](/waves-client/account-management/restore-an-account.md).
* Секретная фраза не может быть изменена. Если вы случайно скомпрометировали ее или подозреваете, что фраза оказалась в руках мошенника, немедленно создайте новый Waves аккаунт и переведите все средства на него, не забыв сохранить новую секретную фразу.

## Персональный аккаунт

* Не используйте для доступа к своей учетной записи браузеры с установленными расширениями и плагинами, в которых вы не уверены на 100%: они могут получить доступ к вашей секретной кодовой фразе.
* Защитите аккаунт паролем в операционной системе.
* Вы используете свой кошелек анонимно, ваша учетная запись не привязана к электронной почте или другой идентифицирующей вас информации.
* Пароль защищает вашу учетную запись с привязкой к определенному устройству или браузеру.
* Проверьте, находится ли соединение в безопасном SSL режиме - в адресной строке вашего веб-браузера вы должны увидеть значок закрытого
замочка \(справа или слева, в зависимости от браузера\).

* В качестве дополнительного способа защиты используйте [**Ledger Nano S**](/waves-client/account-management/ledger-nano.md) и/или [**Waves Keeper**](/waves-client/account-management/waves-keeper.md).

## Общие замечания

* Пользуйтесь только [официальными Waves ресурсами ](/overview/waves-official-resources.md)\(группами в соц.сетях, сайтами,
приложениями\).
* Перед тем как ввести куда-то свой SEED или скачать приложение, внимательно проверьте адрес в адресной строке браузера. Убедитесь, что вы используете официальные ресурсы компании.
* Используйте официальное программное обеспечение. Не устанавливайте программы из неизвестных источников или взломанные программы.
* Не открывайте письма от незнакомых вам отправителей.
* Регулярно проверяйте обновления операционной системы и браузера
* Не заходите в кошелёк, используя публичную Wi-Fi сеть или с чужого устройства.
