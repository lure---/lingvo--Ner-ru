﻿# lingvo--Ner-ru

<a target="_blank" href="http://ner-ru.apphb.com/index.html">[ live demo ]</a>

<div style="padding: 20px">
    <div>
        <div>
            <span>Под автоматическим определением именованных сущностей - (NER - Named-Entities Recognition) -
            понимается поиск и классификация имен собственных, названий событий, продуктов, топонимов и пр.
            <br />
            Например, это могут быть имена людей или названия компаний, названия географических объектов (города, реки, улицы и пр.). 
            </span>
            <br />
            <span>В приведенной системе представлена классификация именованных сущностей на пять типов:</span>
            <br />
            <ul style="margin-left: 30px">
                <li>1. физические лица (ФИО или любая составляющая ФИО, например, <span class="B_NAME" title="Физ. лица">Владимир</span> <span class="I_NAME" title="Физ. лица">Петров</span>)</li>
                <li>2. юридически лица (названия компаний, сообществ, союзов и т.п., например, ЗАО «<span class="B_ORG" title="Юр. лица">МТС Северо-Запад</span>»)</li>
                <li>3. географические названия, например, <span class="B_GEO" title="Географические объекты">Париж</span></li>
                <li>4. продукты (названия продуктов, их марок, в том числе брендов, например, <span class="B_PROD" title="Торговые марки/Продукты">iPhone</span>)</li>
                <li>5. события (именованные события: названия праздников, форумов, спортивных состязаний и т.п. мероприятий, например, <span class="B_ENTR" title="События">Рождество</span>)</li>
            </ul>
            <br />
            <span>Особенностью данной системы является то, что типы определяются не словарем, а на основе статистических алгоритмов.
            С одной стороны это может привести к ошибкам в определении типа сущности (например, <i>"Красная Москва - когда-то это были самые замечательные духи"</i> может  определиться как география), 
            но с другой стороны система способна корректно определить новый, ранее невстречавшийся тип.</span>
            <br />
            <span>Количество типов и описание их классов задается на этапе обучения (получения статистической модели).</span>
            <br />
            <br />
            <span>Данная система работает с русскоязычными текстами и классифицирует слова, содержащие хотя бы одну заглавную букву.</span>
            <span>Точность определения типов сущностей (по мере F1):
            <ul style="margin-left: 30px">
                <li>1. физические лица - около 95% </li>
                <li>2. юридически лица - около 87% </li>
                <li>3. географические названия - 92% </li>
                <li>4. продукты - 81% </li>
                <li>5. события - 79% </li>
            </ul>
            </span>
            <span>Скорость обработки текста данной системой состовляет порядка 400-450 кБайт/сек.</span>
        </div>
    </div>
</div>
