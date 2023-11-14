Финальный тестовый проект SkillFactory курса QAP

Автоматизированное тестирование UI сайта: https://b2c.passport.rt.ru/ с использованием PyTest и Selenium.

С тест-кейсами можно ознакомиться по ссылке: https://docs.google.com/spreadsheets/d/1_-k8H95FwfMsq5A2m0ILAXo8VD147xa7MgREnfcacqc/edit?usp=sharing

В файле main_page.py находится конструктор webdriver и общие для всех тестируемых страниц методы.

В файлах main_page.py, recovery_page.py, passwordrecovery_page.py, registration_page.py находятся методы для соответствующих тестируемых страниц.

В файле "locators.py находятся все локаторы.

В файле conftest.py находится фикстура с функцией открытия и закрытия браузера. Для запуска тестов необходимо поменять путь до webdriver на свой.

В файлах test_main_page.py, test_recovery_page.py, test_passwordrecovery_page.py, test_registration_page.py находятся тесты. Все тесты идут по порядку в соответствии с номерами тест-кейсов. Во всех файлах с тестами находятся закомментированные команды для запуска тестов из командной строки (# pytest -v --tb=line test_main_page.py)
