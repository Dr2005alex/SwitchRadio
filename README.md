Демонстрация Switch Radio в стиле iOS
=====================================
Это css правила, для замены обычных кнопок type=radio на переключатель в стиле iOS.
--------------------
Как использовать:
Скопируйте css файлы на свой сайт.
Оберните радиокнопки <span class="switchradio"></span>
Используйте конструкцию как на примере ниже:
<span class="switchradio">
  <label>
    <input type="radio" name="test1" value="1"  checked="checked" />
    <span><label>Да</label></span>
    </label>
  <label>
    <input type="radio" name="test1" value="0" />
    <span><label>Нет</label></span>
  </label>
</span>

По умолчанию переключатель имеет скругленные углы. Если вы хотите придать более квадратный вид, то добаьте класс swbox к вашему span.

<span class="switchradio swbox">
  <label>
    <input type="radio" name="test1" value="1"  checked="checked" />
    <span><label>Да</label></span>
    </label>
  <label>
    <input type="radio" name="test1" value="0" />
    <span><label>Нет</label></span>
  </label>
</span>
