Installation
------------

To install MoleKing run, under the main project directory:


.. code-block:: bash

   pip3 install ./MoleKing


For **Debbugging** and **Testing**:

.. code-block:: bash

   mkdir build
   cd build
   cmake ../ -DBuild_Python=OFF
   cmake --build . 

For **Python testing and debugging**:

.. code-block:: bash

   mkdir build
   cd build
   cmake ../ -DBuild_Python=ON
   cmake --build . 