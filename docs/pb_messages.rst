========
Messages
========

Via the Messages menu tabs you can orchestrate the conditions upon which the personalized recommendations are triggered.

In short, during the definition of a recommendation template, the campaign manager is able to declare the points to be given to the end user as well as the associated badge (if any) and the percentage of the badge to be received. The percentage of the badge is given only if the total points associated with this recommendation are given to the end user.

Then, in the definition of rules for triggering the sending of a recommendation, the campaign manager is able to define whether the recommendation is validatable or not as well as if it is validatable by an action. In the last case, rules for validation have also to be provided.

Upon the consumption of the recommendations, during the receipt of feedback messages, the set of points to be allocated to the user are provided by the apps through an API. Then, calculation of total score, ranking and percentage of badges achieved is also made available trhough an API.

The following figure shows the overall process.

.. image:: assets/ENTROPY_recommendations_and_scoring_workflow.png


View list of generated recommendation messages
------------

- In order to view the list of generated recommendation messages  several consecutive steps have to be undertaken .
- Initially the user must login.

.. image:: assets/ENTROPY_cmdash.png

- Click on "Messages" menu-item.

.. image:: assets/ENTROPY_vm.png

- The generated recommendation messages appear in platform.

.. image:: assets/ENTROPY_vm_2.png

Recommendation Template
----------------------------------------

**Create a new recommendation Template**

- In order to create a new recommendation template several consecutive steps have to be undertaken .
- Initially the user must login.

.. image:: assets/ENTROPY_cmdash.png

- Click on "Messages" menu-item.

.. image:: assets/ENTROPY_vm.png

- Click on "Templates" button.

.. image:: assets/ENTROPY_crt.png

- Click on "New Template" button.

.. image:: assets/ENTROPY_crt_2.png

- Provide recommendation template details such us (friendly name,type,message, etc.)

.. image:: assets/ENTROPY_crt_3.png

- Click on "SAVE" button.

.. image:: assets/ENTROPY_crt_4.png

- You have successfully create a new recommendation template.

**Edit a recommendation Template**

- In order to edit a recommendation template several consecutive steps have to be undertaken .
- Initially the user must login.

.. image:: assets/ENTROPY_cmdash.png

- Click on "Messages" menu-item.

.. image:: assets/ENTROPY_vm.png

- Click on "Templates" button.

.. image:: assets/ENTROPY_crt.png

- Click on edit button(pencil object).

.. image:: assets/ENTROPY_ert.png

- Provide recommendation template details such us (friendly name,type,message, etc.)

.. image:: assets/ENTROPY_ert_2_.png

- Click on "SAVE" button.

.. image:: assets/ENTROPY_ert_3.png

- You have successfully edit the selected recommendation template.

**Delete a recommendation Template**

- In order to delete a recommendation template several consecutive steps have to be undertaken .
- Initially the user must login.

.. image:: assets/ENTROPY_cmdash.png

- Click on "Messages" menu-item.

.. image:: assets/ENTROPY_vm.png

- Click on "Templates" button.

.. image:: assets/ENTROPY_crt.png

- Click on delete button(bin object).

.. image:: assets/ENTROPY_drt.png

- You have successfully delete the selected recommendation template.

**View list of recommendation Template**

- In order to view a recommendation template list several consecutive steps have to be undertaken.
- Initially the user must login.

.. image:: assets/ENTROPY_cmdash.png

- Click on "Messages" menu-item.

.. image:: assets/ENTROPY_vm.png

- Click on "Templates" button.

.. image:: assets/ENTROPY_crt.png

- The recommendation template list appear in platform.

.. image:: assets/ENTROPY_vrt.png

Recommendation Rule
----------------------------------------

**Create a new Recommendation Rule**

- In order to create a new recommendation rule several consecutive steps have to be undertaken .
- Initially the user must login.

.. image:: assets/ENTROPY_cmdash.png

- Click on "Messages" menu-item.

.. image:: assets/ENTROPY_vm.png

- Click on "Recommendation rules" button.

.. image:: assets/ENTROPY_crr.png

- Click on "New Rule" button.

.. image:: assets/ENTROPY_crr_2.png

- Provide rules details such us (description,target users,etc.)

.. image:: assets/ENTROPY_crr_3.png

Defining the target users conditions can make the recomendation messages be personalized. End users demografic data, their behavioural properties and their responsiveness to previous recommendations are some of the conditions that may afect the recommendation send to them. Following figure depicts the workflow towards generating personalized content.

.. image:: assets/ENTROPY_personalized_recommendation.png

- Click on "SAVE" button.

.. image:: assets/ENTROPY_crr_4.png

- You have successfully create a new recommendation rule.

**Edit a Recommendation Rule**

- In order to edit a recommendation rule several consecutive steps have to be undertaken .
- Initially the user must login.

.. image:: assets/ENTROPY_cmdash.png

- Click on "Messages" menu-item.

.. image:: assets/ENTROPY_vm.png

- Click on "Recommendation rules" button.

.. image:: assets/ENTROPY_crr.png

- Click on edit button(pencil object).

.. image:: assets/ENTROPY_err.png

- Provide rules details such us (description,target users,stream conditions,etc.)

.. image:: assets/ENTROPY_err_2.png

- Click on "UPDATE" button.

.. image:: assets/ENTROPY_err_3.png

- You have successfully update a recommendation rule.

**Delete a Recommendation Rule**

- In order to edit a recommendation rule several consecutive steps have to be undertaken .
- Initially the user must login.

.. image:: assets/ENTROPY_cmdash.png

- Click on "Messages" menu-item.

.. image:: assets/ENTROPY_vm.png

- Click on "Recommendation rules" button.

.. image:: assets/ENTROPY_crr.png

- Click on delete button (bin object)

.. image:: assets/ENTROPY_drr.png

- You have successfully delete a recommendation rule.

**Enable/Disable a Recommendation Rule**

- In order to Enable/Disable a Recommendation Rule several consecutive steps have to be undertaken .
- Initially the user must login.

.. image:: assets/ENTROPY_cmdash.png

- Click on "Messages" menu-item.

.. image:: assets/ENTROPY_vm.png

- Click on "Recommendation rules" button.

.. image:: assets/ENTROPY_crr.png

- Slide the bar to the left in order to disable a recommendation rule.

.. image:: assets/ENTROPY_edr.png

- Slide the bar to the right in order to enable a recommendation rule.

.. image:: assets/ENTROPY_edr_2.png
