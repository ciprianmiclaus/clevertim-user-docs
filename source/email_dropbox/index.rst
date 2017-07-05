The email dropbox
=================

Let's start with the problem the email dropbox is addressing and then focus on how it works.

The problem
-----------

Updating the CRM with notes and emails can sometimes be very tiring and many times it leads to a duplication of effort. For example, if you send an email to a potential customer, how does that email get added into the CRM? One option is to send that email from within the CRM itself, in each case it will end up in there, but what if you send the email from your own email address?

Another scenario is when you receive an email from your own email address from a potential customer. How do you add that email into the CRM? It's certainly not something you should be doing manually.

Also, wouldn't it be nice if contacts were created automatically for some of these emails exchanged with people who are not already in the CRM as contacts?


The solution
------------

To make these problem easier, we introduce the concept of the email dropbox. The email dropbox is just a dedicated email address @clevertim, available only to you as a user. You can forward emails you receive from your contacts to this dedicated email dropbox address and notes will be automatically attached under the respective contact in the CRM. You can also CC or BCC this email dropbox address on the emails you send to existing contacts or new contacts and notes will be created automatically.

Contacts in the CRM will be created for new contacts who are not already in the CRM.

There are a few other dedicated email addresses in the Email dropbox that will allow you to:
	* Add an email into the CRM and **create a case** at the same time
	* Add an email into the CRM and **create an opportunity** at the same time
	* Add a task
	* Add a task with a deadline of today
	* Add a task with a deadline of tomorrow


How to use it
-------------

Go to the `Settings/Email dropbox <https://www.clevertim.com/welcome/#email-dropbox>`_ section, available via the settings button in the upper right corner. Make a note of your main personal dropbox email address. This will be an email address that starts with dropbox...@clevertim.com

Go to your email system (e.g. Outlook, Gmail, etc.) and add this dropbox email address to your Contacts. The reason for doing this is to make it easily available in your email system. A lot of email systems have auto-completion of email addresses for example, where it will automatically be filled in for you when you type dropbox. This is just for your convenience, so you don't have to log into Clevertim CRM every time you need this email address.

When you send an email that you want to add into the CRM, make sure you add the dropbox email into the CC or BCC fields of the email. If you add it in the CC field, the recipient will see that the email was sent to the dropbox as well, whereas if you add the dropbox to the BCC, the recipient will not see that.

If you forget to add the dropbox email address to the CC or BCC when sending the email, you can forward that sent email from your Sent mail folder to the dropbox email address.

When you receive an email from a contact, you can forward it to the dropbox email address.

.. warning::

	When you forward the email to the dropbox, make sure to keep a reference to the email address of the recipient. The system identifies contacts by email and if no email for a contact is present, then it will not know where to attach the email. You will get back an error in that situation.

Identifying you
---------------

The system was designed to only accept emails sent to your email dropbox from recognized email addresses that belong to you. This restriction is in place in order to prevent abuse and spam.

The system will automatically accept email from the email address that you have used when you signed up for Clevertim CRM. That address is assumed to belong to you and implicitly trusted.

If you want to be able to send emails into your dropbox from other email addresses that belong to you (e.g. your gmail address in addition to your main work address), then you can add all your email addresses in the 'Your additional email addresses' sub-section of the `Settings/Email dropbox <https://www.clevertim.com/welcome/#email-dropbox>`_ section. If you Validate them, those email addresses will also become available to send email from via Clevertim CRM.

The thing to remember is: the email dropbox will only accept emails from you and you define what email addresses are yours (in addition to the one you signed up for Clevertim CRM with).


Identifying contacts
--------------------

When a new email is received into your dedicated personal dropbox email address, the system tries to identify which contact (or multiple contacts) the email should be filed under. The system identifies contacts by email addresses and therefore it will not be able to identify the contact if there is no email address in the email forwarded. 

The steps followed in identifying the contacts to attach the email under are the following:

	1. The system will extract all the email addresses from the email received (both in the headers and the body of the message)
	2. It will discard the ones which are identified to be yours or your colleagues (other users in Clevertim CRM)
	3. It will discard the email addresses that you have added to your exclusion list
	4. The rest of the emails are considered to be contacts
	5. If some of the contacts do not exist, they will be created
	6. The email will be filed under all those contacts

You can send any email into your dropbox, and as long as you include the email address of the contact you wanted it filed under, it will be created and filed correctly under the respective contact.

Sometimes, the process above will create contacts that should not be created in the CRM. For example, the system might create contacts for:
	* your own email addresses which the system doesn't recognize (e.g. you might have multiple gmail/outlook/yahoo email addresses)
	* users in your own company who are not on Clevertim CRM
	* generic email addresses that happened to have been CC-ed on the email: e.g. info@company, sales@company, support@company

To exclude your own email addresses, you can either add them to the 'Your additional email addresses' as explained in the `Identifying you`_ section, or you can add them to the exclusion list in the 'Email exclusion list' section in `Settings/Email dropbox <https://www.clevertim.com/welcome/#email-dropbox>`_.

To exclude users not onboarded in Clevertim or generic email addresses or anything else, add those email addresses to the 'Email exclusion list' section in `Settings/Email dropbox <https://www.clevertim.com/welcome/#email-dropbox>`_.

Any email address added to the exclusion list will be ignored by the dropbox when processing emails sent to it.


Identifying cases and opportunities
-----------------------------------

In the `Settings/Email dropbox <https://www.clevertim.com/welcome/#email-dropbox>`_ you will notice two additional dropbox email addresses, one for creating cases and one for creating opportunities (this is addition to creating contacts as explained in the previous section). In general, when you forward emails to these addresses, new cases and new opportunities get created respectively.

If you want to update existing cases or opportunities, make sure you include the case or opportunity reference number with a hash in front. The reference number is available in Clevertim CRM for every case or opportunity under the Ref No field.

For example, if you add #CO34322 in the subject or the body of the email to then, the opportunity with that reference number will be updated with the email, rather than a new opportunity being created. This mechanism works in a similar fashion for cases.

These two dropbox email addresses could be used to create cases and opportunity automatically. For example, you could forward your support@your_company emails to the case dropbox and your sales@your_company emails to the opportunity dropbox. This will ensure that all inquiries by email sent to those two email addresses will be automatically create cases and opportunities in Clevertim CRM.


Dealing with spam
-----------------

The dropbox email address is personal to you. If you share it widely, that might attract spam which might end up creating a lot of noise in your Clevertim CRM account.

As explained in the `Identifying you`_ section, emails to the dropbox sent from emails that are not yours will be ignored, however, a determined spammer can fake the email sender to pretend it is sent from one of your email addresses. If you detect a lot of spam in your account and suspect someone might have gotten hold of your dropbox email address, you can generate a new dropbox email address from the `Settings/Email dropbox <https://www.clevertim.com/welcome/#email-dropbox>`_ section.

If this happens repeatedly, please raise this with our support.
