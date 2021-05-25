
:id: ps-desc-i-id

Sharing Simple Variables(I)
=======================================
Share code

.. code:: cpp

  double x = 0, y = 1;

:math:`p_0`

.. code:: cpp
  :number-lines:

  x = y + 4 ;
  y = x - 2 ;

:math:`p_1`

.. code:: cpp
  :number-lines:

  x = y + 4 ;
  y = x - 2 ;

.. class:: substep trace-code

#. :math:`P_0` 1 : x = 5, y = 1
#. :math:`P_0` 2 : x = 5, y = 3
#. :math:`P_1` 1 : x = 7, y = 3
#. :math:`P_1` 2 : x = 7, y = 5

.. class:: substep trace-code

#. :math:`P_1` 1 : x = 5, y = 1
#. :math:`P_1` 2 : x = 5, y = 3
#. :math:`P_0` 1 : x = 7, y = 3
#. :math:`P_0` 2 : x = 7, y = 5

.. class:: substep trace-code

#. :math:`P_0` 1 : x = 5, y = 1
#. :math:`P_1` 1 : x = 5, y = 1
#. :math:`P_0` 2 : x = 5, y = 3
#. :math:`P_1` 2 : x = 5, y = 3

.. class:: substep trace-code

#. :math:`P_1` 1 : x = 5, y = 1
#. :math:`P_0` 1 : x = 5, y = 1
#. :math:`P_0` 2 : x = 5, y = 3
#. :math:`P_1` 2 : x = 5, y = 3
