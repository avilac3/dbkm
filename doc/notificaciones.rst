Notificaciones del sistema
====================

Para mostrar las notificaciones del sistema, es necesario incluir en la primera línea de la vista la siguiente instrucción


.. code-block:: php

    <?php View::notify();?>



 

La Extension para el manejo de mensajes sin hacer uso del "echo" en los controladores o modelos. 
Al final en todos los flash va un TRUE ejemplo DwMessage::info('hola', TRUE);
el mensaje se almacenará como log en un .txt

.. code-block:: php
    
    <?php DwMessage::info('hola', TRUE); ?>
    <?php DwMessage::error('error en el sistema', TRUE); ?>
    <?php DwMessage::valid('operacion exitosa', TRUE); ?>
    <?php DwMessage::warning('precaucion', TRUE); ?>
    <?php DwMessage::get('precaucion', TRUE); ?>






    
