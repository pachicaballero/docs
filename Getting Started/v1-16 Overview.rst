.. |br| raw:: html

    <br>

Upgrade Overview (v1.16)
========================

.. raw:: html

    <div style="position: relative; padding-bottom: 2%; height: 0; overflow: hidden; max-width: 100%; height: auto;">
        <iframe width="560" height="315" src="https://www.youtube.com/embed/22dGWsXz-mA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>

PHP Requirements
----------------

Starting with version v1.16 we now require PHP 8.0 to install and upgrade osTicket. If you are not hosting your own server please check with your provider to ensure PHP 8.0 and all extensions are available before installing/upgrading.

Features Outlined in this Document
----------------------------------

- `Email Two Factor Authentication <Email Two Factor Authentication_>`_
- `Two Factor Authentication Plugin <Two Factor Authentication Plugin_>`_
- `Password Policies Plugin <Password Policies Plugin_>`_
- `Visibility Permissions <Visibility Permissions_>`_
- `Allow external images <Allow external images_>`_
- `Long Answer Field inline edit <Long Answer Field inline edit_>`_
- `SLA Plan Search Field <SLA Plan Search Field_>`_

We are very excited to share the latest version of osTicket with you! It's packed with awesome new features and plugins to improve how you use your helpdesk. You can download the latest version of osTicket and
osTicket plugins `here <https://osticket.com/download>`_.


:doc:`Email Two Factor Authentication <../../Features/Multifactor Authentication>`
----------------------------------------------------------------------------------

With email two factor authentication, Agents are sent an email with a code they must use to successfully log into the helpdesk. Admins also have the option to require staff to set up 2FA in order to use the helpdesk.

:doc:`Two Factor Authentication Plugin <../../Plugins/Two Factor Authentication>`
---------------------------------------------------------------------------------

The Two Factor Authentication plugin allows Agents to use an Authenticator App on their phone for 2FA. If configured, Agents will need to use the code displayed in the app to log into the helpdesk.

:doc:`Password Policies Plugin <../../Plugins/Password Management Policies>`
----------------------------------------------------------------------------

The Password Policy plugin allows an Admin to require certain rules for Agents and Users when setting their password like length, different types of characters, or password strength.


:doc:`Visibility Permissions <../../Features/Visibility Permissions>`
---------------------------------------------------------------------

New visibility permissions have been added to limit the visibility of Departments, Agents, and Help Topics based on an Agent’s Department access. When unchecked, Agents will not be able to see anything in the helpdesk related to Departments they do not have access to.

Allow External Images
---------------------

A new setting has been added to allow external images. It can be found by going to:

Admin Panel | Settings | Tickets | Allow External Images

The setting gives Admins the option to show or hide external inline images in Tickets. If Enabled, the system will allow external inline images that have a valid image extension of .png, .jpg, .jpeg, or .gif. If Disabled, external inline images will be hidden on Tickets.

Long Answer Field Inline Edit
-----------------------------

We’ve made improvements to how we display long answer fields on inline edits. Now, when the field is clicked, Agents will see a preview of what is stored in the field with the option to edit the contents.

SLA Plan Search Field
---------------------

We now have the option to do advanced searches and exports on the SLA Plan field. It can also be added as a column to queues.
