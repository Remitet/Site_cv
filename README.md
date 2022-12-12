#Автотесты проекта Polymatica Dashboards

Тесты работаю на зависимостях Node.js + Cypress 10.6.0. Установить Node.js можно скачав по ссылке [ссылке](https://nodejs.org/en/), остальные зависимости можно установить командой <npm -i --force> выполнив ее из папки репозитория. 

Репозиторий включает в себя ui и e2e тесты имеющие общие вспомогательные модуль helpers. 
- Запуск тестов выполняется командой <npx cypress run --spec integration/e2e/**/*.spec.js> или <npx cypress run --spec integration/ui/**/*.spec.js> в зависимости от вида тестов. 
- Открыть тесты в open режиме <npx cypress open --env users_reset=true>
