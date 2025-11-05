# Устранение проблем в работе турбины (недодув/передув/потеря мощности)
## Демонстрация проблемы

Видео: [ссылка на видео в группе ТГ](https://t.me/Kia_Sportage_5_Turbo/1/120742)

Также может появится чек и ошибка Р2563.

## Порядок действий:
1. Даем машине остыть.
2. Открываем капот.
3. Откручиваем 2 болта сверху теплозащиты турбины и отводим её в сторону. Получаем доступ к тяге геометрии турбины.
4. На штоке есть 2 контргайки, по одной с каждой стороны, отжимаем их.
5. Регулировка:
    - подключаем диагностический комп к машине, выбираем блок упраления геометрией и смотрим напряжение, которое выдает шток при полном открытии геометрии, если оно больше 4.2V (± 0.1V), крутим шток, чтобы стало 4.2V (± 0,1V).
    - если нет софта на компе, то берем иголку и пробиваем ей желтый (оранжевый) провод около фишки которая подключается к механизму управления геометрией турбины (нужен 3 провод с лева в нижнем ряду см. фото ниже). К иголке присоединяем "+" от тестера, "-" от тестера на "-" АКБ. Включаем зажигание. Двигаем шток, в самом крайнем положении(в водительскую сторону) показания вольтметра должны быть 4.2V (±0.1V), если показания больше, то крутим шток, тем самым регулируя длину его хода.
    ??? note "Фото"
        ![Image title](../../images/turbo_00.jpg){ loading=lazy}
        ![Image title](../../images/turbo_photo_1.jpg){ loading=lazy}
        ![Image title](../../images/turbo_photo_2.jpg){ loading=lazy}
        ![Image title](../../images/turbo_photo_3.jpg){ loading=lazy}
        ![Image title](../../images/turbo_photo_4.jpg){ loading=lazy}
        ![Image title](../../images/turbo_photo_5.jpg){ loading=lazy}
        ![Image title](../../images/turbo_photo_7.jpg){ loading=lazy}
        ![Image title](../../images/turbo_photo_6.jpg){ loading=lazy}
        ![Image title](../../images/turbo_photo_9.jpg){ loading=lazy}
        ![Image title](../../images/turbo_photo_8.jpg){ loading=lazy}
6. Выставили 4.2V (±0.1V), контрим шток гайками и убираем провода.
7. Прикручиваем теплозащиту турбины.
8. Закрываем капот.

Желательно сделать адаптацию педали газа по данной [инструкции](./gas-adaptation.md)

![Image title](../../images/photo_2025-09-14_10-42-54.jpg){ loading=lazy }
/// caption
Параметры из мануала "собрата"
///

??? note "Скриншоты процесса из официальной документации"
    <center>
    ![Image title](../../images/turbo_1.jpg){ loading=lazy }
    ![Image title](../../images/turbo_2.jpg){ loading=lazy }
    ![Image title](../../images/turbo_3.jpg){ loading=lazy }
    ![Image title](../../images/turbo_4.jpg){ loading=lazy }
    </center>

??? note "Еще скриншоты процесса из официальной документации"
    <center>
    ![Image title](../../images/turbo_5.jpg){ loading=lazy }
    ![Image title](../../images/turbo_6.jpg){ loading=lazy }
    </center>

[Официальная инструкция из TIS](https://kiagds.ru/?mode=SHOP&marke=KM&year=2025&model=9988&mkb=191__29720&docId=1154828&page=)