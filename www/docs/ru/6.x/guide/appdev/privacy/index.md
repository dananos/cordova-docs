---
license: >
    Licensed to the Apache Software Foundation (ASF) under one
    or more contributor license agreements.  See the NOTICE file
    distributed with this work for additional information
    regarding copyright ownership.  The ASF licenses this file
    to you under the Apache License, Version 2.0 (the
    "License"); you may not use this file except in compliance
    with the License.  You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing,
    software distributed under the License is distributed on an
    "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
    KIND, either express or implied.  See the License for the
    specific language governing permissions and limitations
    under the License.

title: Руководство по конфиденциальности
---

# Руководство по конфиденциальности

Мобильная конфиденциальность является важным вопросом, который каждый разработчик приложения должен учитывать. Ваши пользователи ожидают, что их частная информация, будут собираться и обрабатываться вашим приложением надлежащим образом. Кроме того есть все большее число юрисдикций, которые сейчас имеют юридические требования в отношении конфиденциальности в отношении мобильных устройств.

Это руководство о конфиденциальности мобильных приложений следует рассматривать *заготовку* решающую некоторые наиболее значительные проблемы. Оно излагает некоторые общепринятые практики и предоставляет ссылки на другие более подробные руководства и материалы.

*   **Политика конфиденциальности**: Ваше приложение должно включать политику конфиденциальности которая описывает области, такие как, что за информацию приложение собирает от своих пользователей и о них, как эта информация используется, с кому она может быть передана, и как пользователели могут совершить выбор относительно своей конфиденциальности в рамках приложения. Чтобы помочь пониманию, вы должны использовать обычный язык и избегать использование технического жаргона. Вы должны сделать вашу политику конфиденциальности доступной пользователям для рассмотрения до загрузки, например в описании приложения в магазине приложений. Кроме того вы должны сделать вашу политику конфиденциальности доступной в рамках самого приложения. Ограниченный размер дисплеев мобильных устройств создает проблемы для отображения политик конфиденциальности для пользователей. Рассмотреть вопрос о разработке *краткой формы* политики, которая включает в себя наиболее важную информацию, а затем предоставить ссылку на «полную форму» политики для тех, кто заинтересован в более подробной информации. Некоторые группы пытаются разработать стандарты на основе значков для сообщения о применяемых практиках конфиденциальности, которые вы можете хотеть рассматривать после того, как эти стандарты будут достаточно зрелыми.

*   **Сбор конфиденциальной информации**: сбор конфиденциальной личной информации приложением поднимает важные конфиденциальности. Примеры конфиденциальной личной информации включая финансовую информацию, информацию о здоровье и информацию от ваших детей или о ваших детях. Это также включает информацию, полученную от некоторых датчиков и баз данных, как правило, находящихся на мобильных устройствах и таблетках, таких как информация о географическом положении, контакты/телефонной книги, микрофон/камера и сохраненных снимках/видео. Смотрите на следующих страницах документации для получения дополнительной информации: [Камера][1], [Захват аудио и видео][2], [Контакты][3]и [Геолокация][4]. Как правило следует получить разрешения пользователя прежде чем собирать конфиденциальную информацию и, если это возможно, предоставляет механизм управления, который позволяет пользователю легко изменить разрешения. Операционные системы где работают приложения могут в этом помогать в некоторых случаях, представляя диалоговые окна запрашивающие разрешение пользователя, непосредственно перед сбором информации. В этих случаях не забудьте воспользоваться любой возможностью для настройки текста диалогового окна для уточнения, как приложение использует и, если применимо, разделяет такую информацию с третьими лицами.

*   **Избегайте делать сюрпризы пользователю**: Если приложение собирает или использует информацию способом который может быть необычным для пользователей в свете основной цели вашего приложения (например, музыкальный плейер которые получает доступ к сохраненным изображениям), вы должны принять похожие шаги как при сборе личной информации. То есть настоятельно рекомендуется использование диалоговых окон появляющихся перед совершением действия, для информирования пользователя о сборе или использовани его информацию и, при необходимости, обеспечивать соответствующий контроль конфиденциальности.

*   **Сбор данных третьей стороной или обмена данными с третьими лицами**: Если ваше приложение собирает информацию, которая предоставляется другой компании--такой как социальная платформа или рекламная сеть (например, если ваше приложение отображает рекламу)--вы должны сообщить пользователям об этом сборе и обмена данными. Как минимум, ваша политика конфиденциальности должна описывать сбор информации и ее обмен и, если это уместно, предлагать пользователям возможность управления или отказа от такого сбора или обмена информацией.

*   **Ограничение сбора и безопасность**: пользователи доверяют вашему приложению свою информацию и они ожидают, что вы будете принимать соответствующие предосторожности, чтобы защитить ее. Один из лучших способов избежать компромиссов в безопасности личной информации в первую очередь является на собирать информацию, если ваше приложение не имеет конкретных и законных оснований для сбора. Для информации, которая должна быть получена, убедитесь, что вы применяете надлежащие мер безопасности для защиты этой информации, хранятся ли они на устройстве или на ваших серверах. Следует также разработать политику хранения соответствующих данных, которая осуществляется в пределах приложения и на ваших серверы.

 [1]: cordova_camera_camera.md.html
 [2]: cordova_media_capture_capture.md.html
 [3]: cordova_contacts_contacts.md.html
 [4]: cordova_geolocation_geolocation.md.html

Ниже приведены некоторые дополнительные полезные руководства по мобильной конфиденциальности для разработчиков:

*   Генеральный прокурор Калифорнии, [Конфиденциальность в движении: рекомендации для мобильных экосистем][5]

*   Центр демократии и технологии, Форум будущего конфиденциальности, [ лучшии практики для разработчиков мобильных приложений][6]

*   CTIA-Ассоциация беспроводной связи, [передовые практики и руководства для услуг на основе местоположение][7]

*   Федеральная торговая комиссия, [мобильная конфиденциальность информации: укрепление доверия через прозрачность][8]

*   Форум Будущее конфиденциальности, веб-сайт [Конфиденциальность приложения][9]

 [5]: http://oag.ca.gov/sites/all/files/pdfs/privacy/privacy_on_the_go.pdf
 [6]: http://www.futureofprivacy.org/wp-content/uploads/Best-Practices-for-Mobile-App-Developers_Final.pdf
 [7]: http://www.ctia.org/business_resources/wic/index.cfm/AID/11300
 [8]: http://www.ftc.gov/os/2013/02/130201mobileprivacyreport.pdf
 [9]: http://www.applicationprivacy.org