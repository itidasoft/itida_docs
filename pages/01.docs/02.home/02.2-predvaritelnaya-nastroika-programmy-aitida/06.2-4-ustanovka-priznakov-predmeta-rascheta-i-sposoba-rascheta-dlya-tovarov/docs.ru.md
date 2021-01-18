---
title: "2.4.\tУстановка признаков предмета расчета и способа расчета для товаров."
media_order: danger.svg
taxonomy:
    category:
        - docs
    tag:
        - 54fz
---

<p>Для выполнения данного требования потребуется создать необходимое количество групп ресурсов (Справочники &ndash; Классификаторы &ndash; Группы ресурсов) и указать в карточке групп ресурсов необходимые признаки предмета расчета и способа расчета.</p>
<p>&nbsp;</p>
<div class="notices green">
<p style="text-align: center;"><img src="danger.svg" alt="danger" />Пример заполнения карточек групп ресурсов представлен на следующих рисунках:</p>
</div>
<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp;</p>
<p><em>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (обычный товар)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (подакцизный товар)</em></p>
<p>В карточке ТМЦ в поле &laquo;Группа товара&raquo; необходимо выбрать группу ресурсов, с заполненными признаками предмета и способа расчета.</p>
<p><em>(упрощенная карточка товара)</em></p>
<p><em>&nbsp;</em></p>
<p><em>(обычная карточка товара)</em></p>
<p>&nbsp;</p>
<p>Для ускорения процесса установки групп ресурсов для товаров можно воспользоваться механизмом установки общих реквизитов (см. подробнее <a href="http://itida.ru/download/docs/2.99/itida_admin_29940.pdf">http://itida.ru/download/docs/2.99/itida_admin_29940.pdf</a> , стр. 127).</p>
<p>&nbsp;</p>
<p>Ниже представлены доступные для выбора варианты признаков &laquo;предмет расчета&raquo; и &laquo;способ расчета&raquo;, а также их соответствие признакам предмета расчета и способа расчета по ФФД.</p>
<p>&nbsp;</p>
<table width="599">
<tbody>
<tr>
<td width="165">
<p><strong>Наименование предмета расчета Айтида</strong></p>
</td>
<td width="293">
<p><strong>Наименование предмета расчета по ФФД</strong></p>
</td>
<td width="142">
<p><strong>Значение реквизита по ФФД</strong></p>
</td>
</tr>
<tr>
<td width="165">
<p>1 &ndash; товар</p>
</td>
<td width="293">
<p>ТОВАР</p>
</td>
<td width="142">
<p>1</p>
</td>
</tr>
<tr>
<td width="165">
<p>2 &ndash; акцизный товар</p>
</td>
<td width="293">
<p>ПОДАКЦИЗНЫЙ ТОВАР</p>
</td>
<td width="142">
<p>2</p>
</td>
</tr>
<tr>
<td width="165">
<p>3 &ndash; работа</p>
</td>
<td width="293">
<p>РАБОТА</p>
</td>
<td width="142">
<p>3</p>
</td>
</tr>
<tr>
<td width="165">
<p>4 &ndash; услуга</p>
</td>
<td width="293">
<p>УСЛУГА</p>
</td>
<td width="142">
<p>4</p>
</td>
</tr>
<tr>
<td width="165">
<p>5 &ndash; собранный товар</p>
</td>
<td width="293">
<p>СОСТАВНОЙ ПРЕДМЕТ РАСЧЕТА</p>
</td>
<td width="142">
<p>11</p>
</td>
</tr>
<tr>
<td width="165">
<p>6 &ndash; иной товар</p>
</td>
<td width="293">
<p>ИНОЙ ПРЕДМЕТ РАСЧЕТА</p>
</td>
<td width="142">
<p>12</p>
</td>
</tr>
<tr>
<td width="165">
<p>7 &ndash; аванс, предоплата</p>
</td>
<td width="293">
<p>ПЛАТЕЖ или ВЫПЛАТА</p>
</td>
<td width="142">
<p>10</p>
</td>
</tr>
</tbody>
</table>
<p>&nbsp;</p>
<table>
<tbody>
<tr>
<td width="165">
<p><strong>Наименование способа расчета Айтида</strong></p>
</td>
<td width="293">
<p><strong>Наименование способа расчета по ФФД</strong></p>
</td>
<td width="122">
<p><strong>Значение реквизита по ФФД</strong></p>
</td>
</tr>
<tr>
<td width="165">
<p>0 &ndash; не используется</p>
</td>
<td colspan="2" width="415">
<p>Определяется исходя из сценария пробития чека</p>
</td>
</tr>
<tr>
<td width="165">
<p>1 &ndash; аванс</p>
</td>
<td width="293">
<p>АВАНС</p>
</td>
<td width="122">
<p>3</p>
</td>
</tr>
<tr>
<td width="165">
<p>2 &ndash; полный расчет</p>
</td>
<td width="293">
<p>ПОЛНЫЙ РАСЧЕТ</p>
</td>
<td width="122">
<p>4</p>
</td>
</tr>
</tbody>
</table>