# Отчёт о тестировании приложения KeyValidator

## Краткое описание

26.10.2020 проведено функциональное тестирование приложения KeyValidator в соответствии с руководством использования.

На тестирование затрачено: 10 минут

В результате тестирования выявлены следующие дефекты:
* [Валидные ключи из примеров "80b427f8-92cd-3aae-ba04-3927fbe17c6" и "387eedc6-12e9-3b32-9881-63b6b5e85317" не проходят валидацию в KeyValidator](https://github.com/Alex-nikiforova/java_HW_1.1_1/issues/2)
* [Невалидный ключ "2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1" прошел валидацию в KeyValidator](https://github.com/Alex-nikiforova/java_HW_1.1_1/issues/3)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* [Руководство использования KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)

В качестве тестовых данных использовались данные из [Руководства использования KeyValidator](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md):
* Руководство использования с примерами валидных и невалидных ключей

Тестирование производилось в следующем окружении:
* Windows 10 Pro
* openjdk ver.11.0.9
* Google Chrome ver.86.0.4240.111
