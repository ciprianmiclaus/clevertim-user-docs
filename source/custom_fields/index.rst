
Custom fields
=============

What are they?
--------------

Clevertim CRM allows you to define custom fields for storing data that is not already available in the system. For example, you might want to allocate an Account Manager for every contact. Since there is no field to store the name of the account manager for every contact, you can define a custom field. Ideally, an Account Manager should provide a list of valid account managers to choose from, rather than your users having to type the name every time, and potentially making mistakes in the process. Custom fields support all of that.

You can create custom fields for contacts, companies, cases and opportunities. You can reuse the same field name and definition and make it applicable to multiple items. For example, you can make the Account Manager field in our example to be applicable to contacts and companies.

The custom fields have a type and they do some basic validation and prevent common data entry problems. In our Account Manager example, the field is of type Select, which presents the data as a list of values to choose from, minimizing manual data entry errors.

Your custom fields can either store a single value or multiple values. In the Account Manager custom field in our earlier example, you probably want a single value, a single account manager who looks after a contact or company. However, in some cases you might want multiple values for the same field. For example, if you would like to store the products or services purchased by a certain contact or company, then you might want to add a field called Products/Services that allows multiple values, so you can enter multiple values under it.

You can define and manage your own custom fields in the `Settings/Custom fields <https://www.clevertim.com/welcome/#custom-fields>`_ section.


Adding a new custom field
-------------------------

When you create your Clevertim CRM account and you go to the `Settings/Custom fields <https://www.clevertim.com/welcome/#custom-fields>`_ section for the first time, you will see there are no custom fields. The Custom fields section will look like this:

.. image:: /_static/custom_fields_empty.png

To add your first custom field, type a name for the custom field in the input text box which shows **Custom field name** and press the **Add new custom field** button. The field will then appear in the Custom fields section.

The next step is to define what this field is applicable to. In the **Where is it shown?** column, you can choose to make this field shown for contacts, companies, cases, opportunities or combinations. You can have fields that are shown for multiple items. Click on the Edit link to choose what this field is applicable to and therefore, where it is shown.

The next column allows you to select the type of the custom field. The supported types for the custom fields are described in the next section. When you select the type of the field, the **Appearance** column will show you how the custom field is displayed to the users. For fields of type Select, the Edit link in the Appearance column allows you to specify what values are allowed in the Select field.

The **Allowed multiple values** is a simple checkbox which allows you to select if the fields will only allow a single value for the field, or, when ticked, the custom field will allow multiple values.

When you are done making changes to your custom field, do not forget to click the Save button next to it, on the right. If you do not save the changes and refresh the page or move to another page, your changes will be lost and you might have to re-apply them. When the Save button is disabled, it means that all your changes are already saved.

When you add your custom fields, the custom fields section will be populated and you will see all your custom fields in one place. See an example below for illustration purposes (your actual set up will be different based on the custom fields you need):

.. image:: /_static/custom_fields_example.png

You can always come back to this section and make changes or delete some of your existing custom fields.

Types of custom fields
----------------------

Custom fields have a type which determines how the field will appear when displayed to the users and what kind of data it can contain.


Editing an existing custom field
--------------------------------

To edit an existing custom field, go to the `Settings/Custom fields <https://www.clevertim.com/welcome/#custom-fields>`_ section, make the changes you need to the custom fields you want changed and press the Save button on the right which corresponds to the custom field you are changing (i.e. the Save button located on the same row).

Once saved, the new definition of the field will be visible to your other users in the system. You might have to refresh your browser to pick up the updated custom field if it is not picked up automatically.

.. warning::

When changing the type of a custom field, some values for the custom field might become invalid. For example, if you have a custom field of type Country and you change the type to US State, some values for the previous definition of the custom field will be invalid and might not be displayed correctly under the contacts, companies, cases or opportunities that have the custom field set to those values. Think carefully about the data before making changes to the type of the custom field.


Deleting a custom field
-----------------------

To delete an existing custom field, go to the `Settings/Custom fields <https://www.clevertim.com/welcome/#custom-fields>`_ section and press the Delete button on the same row with the custom field that you do not need anymore. Once deleted, the custom field will no longer be displayed in the system.

.. warning::

All the data entered in this field for all the contacts, companies, opportunities or cases where the custom field is display **will be lost**.

Data entry
----------

Data entry in bulk
------------------


Importing custom fields data
----------------------------

Exporting custom fields data
----------------------------


Custom fields in filters
------------------------

Custom fields in reports
------------------------


Application specific custom fields
----------------------------------
