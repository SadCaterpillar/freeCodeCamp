---
title: Comments in HTML
localeTitle: Комментарии в HTML
---
## Комментарии в HTML

Комментарий - это тег, используемый для добавления заметок, как правило, связанных с проектом или веб-сайтом. Этот тег часто используется, чтобы объяснить что-то в коде или оставить рекомендации по проекту. Комментарий также дает разработчику возможность спустя какое-то время вернуться назад и понять ранее написанный код. Кроме того, его можно использовать для превращения в комментарий секции кода в целях отладки.

Рекомендуется добавлять комментарии к коду, особенно если вы работе в команде или в компании.

Комментарии начинаются с `<!--`, заканчиваются на `-->` и могут охватывать несколько строк. Они содержат код или текст, и пользователь сайта их не видит. Вы можете просматривать комментарии через Inspector Console или просматривая код страницы.

### пример

```html

<!-- You can comment out a large number of lines like this. 
 Author: xyz 
 Date: xx/xx/xxxx 
 Purpose: abc 
 --> 
 Read more: https://html.com/tags/comment-tag/#ixzz4vtZHu5uR 
 <!DOCTYPE html> 
 <html> 
    <body> 
        <h1>FreeCodeCamp web</h1> 
        <!-- Leave some space between the h1 and the p in order to understand what are we talking about--> 
        <p>FreeCodeCamp is an open-source project that needs your help</p> 
            <!-- For readability of code use proper indentation --> 
    </body> 
 </html> 
```

## Условные комментарии

Условные комментарии определяют, какие теги HTML будут приведены в исполнение при выполнении определенного условия.

Условные комментарии распознаются только в Internet Explorer в версиях от 5 до 9 (IE5 - IE9).

### пример

```html

<!DOCTYPE html> 
 <html> 
    <body> 
        <!--[if IE 9]> 
                <h1>FreeCodeCamp web</h1> 
            <p>FreeCodeCamp is an open-source project that needs your help</p> 
        <![endif]--> 
    </body> 
 </html> 
```

### IE условные комментарии

Эти комментарии доступны только в Internet Explorer и могут использоваться до версии IE9. Велика вероятность, что в настоящее время вы никогда их не увидите, но хорошо знать об их существовании. Условные комментарии - это способ создать различный пользовательский опыт для разных клиентских браузеров. Например:

```html

<!--[if lt IE 9]> <p>Your browser is lower then IE9</p> <![endif]--> 
 <!--[if IE 9]> <p>Your browser is IE9</p> <![endif]--> 
 <!--[if gt IE 9]> <p>Your browser is greater then IE9</p> <![endif]--> 
```

[Об условных комментариях](https://msdn.microsoft.com/en-us/library/ms537512(v=vs.85).aspx)
