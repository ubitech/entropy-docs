========
Register a new Building area
========

Register a new Building Area
------------------------

- In order register a new building area several consecutive steps have to be undertaken .
- Initially the user must login.

.. image:: assets/ENTROPY_cmdash.png

- Click on "Areas" Menu-item.

.. image:: assets/ENTROPY_newera.png

- Click on "New Area" button.

.. image:: assets/ENTROPY_newera_2.png

- Provide the new area details and click on "Save" button.
In order to get information about the energy waste of you building you should providing data for (see attached figure):
- the global energy performance (as made available in the energy certificate) in kWh/m3
- the heating energy performance (as made available in the energy certificate) in kWh/m3
- the cooling energy performance (as made available in the energy certificate) in kWh/m3
- the heating degree days for the previous year (e.g. 2017) as made available by wunderground.com (e.g. https://www.wunderground.com/history/airport/LERI/2018/4/30/CustomHistory.html?req_city=Murcia&req_statename=Spain&reqdb.zip=00000&reqdb.magic=248&reqdb.wmo=08429)
- the cooling degree days for the previous year (e.g. 2017) as made available by wunderground.com
Such data is used towards the calculation of the Heat Transfer Coefficient, as well as the estimated need for power for heating/cooling at each period of time.


.. image:: assets/areas_energy_certificates.png
.. image:: assets/ENTROPY_newera_3.png
.. image:: assets/ENTROPY_newera_4.png

- Upon successful addition, the new area  appears in area list.



Edit a Building Area
------------
- In order to edit an existing building area consecutive steps have to be undertaken .
- Initially the user must login.

.. image:: assets/ENTROPY_cmdash.png

- Click on "Areas" Menu-item.

.. image:: assets/ENTROPY_newera.png

- Click on "EDIT" button.

.. image:: assets/ENTROPY_addera.png

- Provide the edit area details and click on "Save" button.

.. image:: assets/ENTROPY_addera_2.png
.. image:: assets/ENTROPY_addera_3.png

- During editing the admin can move sensors from main areas to sub areas.

- It is also possible to define some main steams per area. Main streams have a default frequency of one hour and refer to indoor/outdoor temperature and consumption and production power. it is necessary to define this because serveral analytic packages make use of them so as to calculate the energy saving and waste compared with the calculated consumption baseline.

- Default main stream are declared by clicking on "Add stream" option as seen followingly:

.. image:: assets/defineMainStream.png

- Upon successful editing, the modified area appears in the list.

Delete Building Area
------------

- In order to delete a building area several consecutive steps have to be undertaken .
- Initially the user must login.

.. image:: assets/ENTROPY_cmdash.png

- Click on "Areas" Menu-item.

.. image:: assets/ENTROPY_newera.png

- Click on "DELETE" button.

.. image:: assets/ENTROPY_delera.png

- Upon successful delete of the selected area,the area list will be modified.
