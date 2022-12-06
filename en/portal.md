# Portal

Web Portal [portal.eyetower.io](https://portal.eyetowers.io/) is the central hub for all
interactions with EyeTowers products.

## Overview Page

After logging into Portal, you get to an overview page, which lists organizations (1), sites (2),
and units (3) that you have granted access to.

![Overview Page](../_media/customers_overview.png)

Organizations that the user administers have the option for managing user and identifiers enabled
(4).

On the level of sites, there is an indicator of the alarm state for the entire site as either
`armed`, `disarmed`, or `partial`. Users that have been granted the corresponding permission change
the alarm state for the entire site (i.e., for all the units) by clicking on the indicator. In
addition, an administrator has the option to manage [user permissions](#user-permissions) for the
site (5).

Alarm state indicator is also present for each unit (3) and users with the necessary permission can
also click it arm or disarm the alarm for the single unit. Icons on the bottom of the unit preview
lead to the individual offered services:

- [Access](/en/access.md)
- [Alarm](/en/alarm.md)
- [Video](/en/video.md)
- Weather
- Statistics
- Tracking
- Timelapse

Color of the icon indicates:

- Blue: the service is subscribed and the user has the necesasry site permissions to use it.
- Red: the service is subscribed, but the user lacks the necesasry site permissions to use it.
- Grey: the service is not subscribed.

## User Management

Only the administrator of an organization can manage its users. The user management dialog lists
user of the organization with an indication of admin users (1) and actions for user editing (2),
identifier editing, e.g., an access card or a phone number (3), password reset (4), and permanent
user deletion (5). There is also an option to add new users to the organization (6).

![User Management](../_media/customers_users.png)

A new user is identified by their username (1) and email (4). Both these values must be unique for
the entire system. After an admin adds a user, they receive an email with a link for setting their
system password. The link validity is limitted. Should it expire, the "password reset" can be used
to generate a new email with a valid link.

Don't forget to grant the new user [permissions](#user-permissions) to sites that they need to work
with. Without those, the new user would not be able to see any sites in Portal.

![New User](../_media/customers_new_user.png)

## User Permissions

The administrator also sets user permissions for services in sites of the organizations they manage.

![User Permissions](../_media/sites_permissions.png)

The dialog for permission managements of a site list the users in the organization as rows and
indicates which users are administrators (1) and if they can even see the site with their current
permissions (2). The table columns correspond to permissions to use services in the given site:
[access](/en/access.md) (3), [alarm](/en/alarm.md) (4), [video](/en/video.md#video) (5),
[archive](/en/video.md#videoarchiv) (6), statistics (7), tracking (8) a timelapse (9). As a rule of
thumb, the greener the color, the stronger the permissions.
