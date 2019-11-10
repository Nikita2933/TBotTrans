# TBotTrans 
Самый простой переводчик с русского на английский в Telegrame боте. Первый тестовый мини-проект для освоения.
На данный момент переводит только в одну сторону и только один язык.
Использует API яндекс-переводчика. 
# Необходимые зависимости: json и Bot API telegramm
Maven зависимости

     <dependency>
      <groupId>org.telegram</groupId>
      <artifactId>telegrambots-meta</artifactId>
      <version>4.0.1</version>
    </dependency>
 
 
    <dependency>
        <groupId>net.sf.json-lib</groupId>
        <artifactId>json-lib</artifactId>
        <version>2.4</version>
        <classifier>jdk15</classifier>
    </dependency>

Ссылки на библиотеки [Json](https://jar-download.com/artifacts/com.hynnet/json-lib/2.4/source-code) и [Bot API telegramm](https://github.com/rubenlagus/TelegramBots/releases/)


 
# Инструкция
В файле [Setter](https://github.com/Nikita2933/TBotTrans/blob/master/src/Setter.java) необходимо ввести свои данные для работы переводчика,
а именно:

1 - apikey яндекса - переходим по [ссылке](https://translate.yandex.ru/developers/keys) следуем простой инструкции

2 - tokenbot и botname - Получаем от [BotFather](https://web.telegram.im/?p=@botfather)

