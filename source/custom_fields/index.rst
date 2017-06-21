
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

Input fields
++++++++++++

* Appearance
	- Input fields are displayed as free text input boxes
* Data & Validation
	- Users can type any alphanumeric or special characters
	- There is no validation on the data entered
* Pros:
	- Input fields are very versatile and can support any type of data
* Cons:
	- Lack of validation means the values might not be consistent
	- Users might enter the same values with different spelling, capitalization or spacing


Select fields
+++++++++++++

* Appearance
	- Select fields are displayed as drop-down control
* Data & Validation
	- Users have to select a value from a list of pre-defined values
	- You define the allowed values when you create the custom field
* Pros:
	- Manual data entry are minimized as users select the data, rather than type it
* Cons:
	- If new values need to be added, the custom field needs to be edited, which only an administrator has permissions to do


Date fields
+++++++++++

* Appearance
	- Displays a date and it has a calendar control for users to easily pick a date
* Data & Validation
	- Can only contain a calendar date
* Pros:
	- The calendar date picker offer a user friendly way for users to choose dates
	- Has special support for date lookups in filters and reports (e.g. after date, before date, in the last X days/weeks, etc.)
* Cons:
	- None


Country fields
++++++++++++++

* Appearance
	- Displays a list of countries for users to select from
* Data & Validation
	- Can only contain a country from a pre-defined list of countries
* Pros:
	- The list of countries is maintained by the system, you do not need to maintain it
* Cons:
	- None


Region fields
+++++++++++++++

* Appearance
	- Displays a list of regions by country for users to select from
* Data & Validation
	- Can only contain a region/country from a pre-defined list of countries
* Pros:
	- The list of regions by countries is maintained by the system, you do not need to maintain it or type it in
* Cons:
	- It contains regions for all countries, so it might be a bit more difficult to find the right value (it allows users to search though)


US State fields
+++++++++++++++

* Appearance
	- Displays a list of US states for users to select from
* Data & Validation
	- Can only contain a US state from a pre-defined list
* Pros:
	- The list of US states is available in the system, you do not need to type it in
* Cons:
	- None


Currency fields
+++++++++++++++

* Appearance
	- Displays a list of world currencies for users to select from (e.g. US Dollar, Euro, British pound)
* Data & Validation
	- Can only contain a currency from a pre-defined list
* Pros:
	- The list of currencies is available in the system, you do not need to type it in
* Cons:
	- None


User fields
+++++++++++

* Appearance
	- Displays a list of your own users in Clevertim to select from
* Data & Validation
	- All your users onboarded onto Clevertim will be available to select from
* Pros:
	- Supports any use case that requires one or multiple of your users to be associated with a contact, company, opportunity, case (e.g. Account Manager, Service Rep, Assigned user)
* Cons:
	- Any of your employees/colleagues not onboarded into Clevertim will not be available for selection


Contact fields
++++++++++++++

* Appearance
	- Displays a list of your own contacts in Clevertim to select from
* Data & Validation
	- All your contacts entered into Clevertim will be available to select from
* Pros:
	- Supports any use case that requires one or multiple of your contacts to be associated with another contact or a company, an opportunity or a case (e.g. Manager, Spouse, Related, etc.)
* Cons:
	- None

Company fields
++++++++++++++

* Appearance
	- Displays a list of your own companies in Clevertim to select from
* Data & Validation
	- All your companies entered into Clevertim will be available to select from
* Pros:
	- Supports any use case that requires one or multiple of your companies to be associated with a contact or another company, an opportunity or a case (e.g. Additional Company, Parent Group, Holding Company, Branch, etc.)
* Cons:
	- None

Opportunity fields
++++++++++++++++++

* Appearance
	- Displays a list of your own opportunities in Clevertim to select from
* Data & Validation
	- All your opportunities entered into Clevertim will be available to select from
* Pros:
	- Supports any use case that requires one or multiple of your opportunities to be associated with a contact, a company, another opportunity or a case (e.g. Previous tender, Previous inquiry, etc.)
* Cons:
	- None

Case fields
+++++++++++

* Appearance
	- Displays a list of your own cases in Clevertim to select from
* Data & Validation
	- All your cases entered into Clevertim will be available to select from
* Pros:
	- Supports any use case that requires one or multiple of your cases to be associated with a contact, a company, a opportunity or another case (e.g. Previous inquiry, Previous problem, Related issue, etc.)
* Cons:
	- None


Editing an existing custom field
--------------------------------

To edit an existing custom field, go to the `Settings/Custom fields <https://www.clevertim.com/welcome/#custom-fields>`_ section, make the changes you need to the custom fields you want changed.

To change the name of the custom field, just click on the name of the custom field. See illustration below:

.. image:: /_static/custom_fields_name_edit.png

Once clicked, the name of the field becomes editable and you can change it. When you're happy with the changes, just press the button with the tick.

.. image:: /_static/custom_fields_name_edit2.png

If you want to discard your changes to the name field, just press the button with the X.

.. image:: /_static/custom_fields_name_edit3.png


To change which items the fields are shown under, click the Edit link in the "Where is it shown?" column, like in the illustration below:

.. image:: /_static/custom_fields_appearance_edit.png

Once clicked, you will see a dropdown that will allow you to select what items this field should be shown under. You can select to show the custom fields under multiple type of items.

.. image:: /_static/custom_fields_appearance_edit2.png

For Select type of custom fields, you will need to select the values that are allowed into the field. Click on the Edit link under the Appearance column.

.. image:: /_static/custom_fields_appearance_edit3.png

Once clicked, you can select the values that are allowed in the Select field. Enter one value per line and then click Ok to accept the values or Cancel to discard the changes you have made:

.. image:: /_static/custom_fields_appearance_edit4.png

Once you are happy with your changes made to the custom fields, make sure you press the Save button on the right which corresponds to the custom field you are changing (i.e. the Save button located on the same row). See screenshot below for illustration purposes:

.. image:: /_static/custom_fields_edit_save.png

Once saved, the new definition of the field will be visible to your other users in the system. You might have to refresh your browser to pick up the updated custom field if it is not picked up automatically.

.. warning::

	When changing the type of a custom field, some values for the custom field might become invalid. For example, if you have a custom field of type Country and you change the type to US State, some values for the previous definition of the custom field will be invalid and might not be displayed correctly under the contacts, companies, cases or opportunities that have the custom field set to those values. Think carefully about the data before making changes to the type of the custom field.

If you decide you don't need the changes you have just made, you can revert to the last saved version of the custom field by pressing the Reset field. You will lose any unsaved changes.
See the screenshot below for the location of the Reset button.

.. image:: /_static/custom_fields_edit_reset.png
	
	

Deleting a custom field
-----------------------

To delete an existing custom field, go to the `Settings/Custom fields <https://www.clevertim.com/welcome/#custom-fields>`_ section and press the Delete button on the same row with the custom field that you do not need anymore. See a screenshot below for illustration purposes.

.. image:: /_static/custom_fields_edit_delete.png


Once deleted, the custom field will no longer be displayed in the system.

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
