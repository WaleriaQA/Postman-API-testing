Hello guys!

In this mini-project, I am testing the Yandex schedules API. You will find below all the used links.

1. https://yandex.ru/dev/rasp/doc/concepts/about.html 
Introduction
The Yandex Schedules API is a tool for programmatic access to the service's data on the routes and times of vehicles.

2. https://rasp.yandex.ru/search/?fromId=c10522&fromName=%D0%91%D0%B5%D0%BB%D0%B3%D1%80%D0%B0%D0%B4&toId=c213&toName=%D0%9C%D0%BE%D1%81%D0%BA%D0%B2%D0%B0&when=31+%D0%B8%D1%8E%D0%BB%D1%8F  
The user interface of the transport schedules.

3. https://yandex.ru/dev/rasp/doc/concepts/access.html
To get access to the API, we need to generate a key in the Developer's account (choose API Яндекс расписаний).
Copy the key. Go to the GET request in Postman, choose Authorization. Type- API Key. Key - apikey. Value - (paste the key generated before). Add to - Query Params.

4. https://yandex.ru/dev/rasp/doc/reference/stations-list.html
List of all available stations. See the GET request example. Remove the API key from the request as we have it in the Authorization tab.
