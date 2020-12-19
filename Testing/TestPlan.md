# План тестирования  
## Содержание    

1. [Введение](#par1) 
2. [Объект тестирования](#par2)
3. [Риски](#par3)
4. [Аспекты тестирования](#par4)
5. [Подходы к тестированию](#par5)
6. [Представление результатов](#par6)
7. [Выводы](#par7)

## <a name="par1">1. Введение</a>
Основная цель данного документа состоит в том, чтобы описать план тестирования десктопное приложение "Klavatrainer". 
Эта информация предназначена для команды, которая будет тестировать данное программное обеспечение на соответствие.

## <a name="par2">2. Объект тестирования</a>
В качестве объекта тестирования следует выделить функциональное тестирование, а также тестирование удобства и простоты использования. 
К атрибутам качетсва относятся следующие характеристики:
1. Функциональная корректность.
2. Удобство использования.
3. Защищенность от ошибки пользователя.

## <a name="par3">3. Риски</a>
Для работы приложение необходимо наличие Windows и IntelliJ IDEA 2020.2.3 на компьютере. 

## <a name="par4">4. Аспекты тестирования</a>
В процессе тестирования предполагается проверить соответствие системы требованиям, на основе которых она была спроектирована и 
реализована. Для данного приложения являются следующие:
1. Проверить количество ошибок пользователя при неверно введенном символе
2. Проверить работу кнопок в программе
3. Проверить правильный ввод букв с клавиатуры
4. Настроить смену цвета общего фона
5. Проверить смену уровней тренировки
6. Проверить изменение шрифта букв при смене
7. Проверить языки раскладки клавиатуры
8. Проверить работу этапов сложности на каждом из уровней

      
Также необходимо проверить соответствие системы:  
1. Производительность
2. Взаимодействие
3. Надежность

## <a name="par5">5. Подходы к тестированию</a>
Для тестирования приложения необходимо использовать ручное тестирование, чтобы проверить все аспекты тестирования. 
Для тестирования необходимо скачать на компьютер установочный файл "Klavatrainer.jar". Далее необходимо найти скачанный файл на своем компьютере и 
запустить его двйным нажанием мышки. 

## <a name="par6">6. Представление результатов</a>
Результаты тестирования представлены в документе [TestResults]

## <a name="par7">7. Выводы</a>
Данный тестовый план позволяет протестировать основной функционал приложения. Успешное прохождение всех тестов не гарантирует 
полной работоспособности на всех платформах и архитектурах, однако позволяет полагать, что данное программное обеспечение работает корректно.