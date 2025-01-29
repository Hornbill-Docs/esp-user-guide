# Company Home
You and all your organization's employees can visit the Employee Portal --- also known as Company Home, or <*Your Company*> Home. Here, you can access your services, communicate with the Service Desk, submit and view requests, chat with support staff, and access shared documents. All employees who have been added to Hornbill can access the portal.

The Employee Portal is highly configurable. Your administrator can [add widgets and enable features for your organization's users](/esp-config/customize/employee-portal/employee-portal-configuration).

Basic and full users can access the portal through [the main Hornbill browser app](/esp-user-guide/company-home#browser-version), as well as through [the Hornbill mobile catalog app](/esp-user-guide/company-home#mobile-version).

## Topics covered
* [Browser version](/esp-user-guide/company-home#browser-version)
* [Mobile version](/esp-user-guide/company-home#mobile-version)
* [Knowledge content in the portal](/esp-user-guide/company-home#knowledge-content-in-the-portal)

## Browser version
### Accessing
You can access Hornbill using any web browser. Navigate to `live.hornbill.com/<Your_Instance>`. If you don't know your instance name, contact your IT support team. 

Users who are not subscribed to any Hornbill applications (basic users) are taken directly to the Employee Portal when they log in. Users who are subscribed to one or more apps can access the Employee Portal through the Company Home option under the Home Icon in the left-hand menu bar.

::: tip
If you are a full user, you can set the Company Home as your default starting point (i.e. your landing page). While on the Company Home page, click your profile photo, then click **Make this my default view**. With a default view like this selected, now when you click on the Hornbill logo in the top banner, you are also returned here.
:::

### Navigation
**Header.** To navigate between pages, the top section of the page contains links to other business areas that have been defined. Each of these areas can have its own page or may link to a dedicated service. Within the header, there is also a breadcrumb that gives you a link back to previous pages and to the Company Home page.

**Body.** The main body of each page consists of one or more widgets that have been added and configured by a page manager. These widgets provide information, links, and the ability to interact with one or more service desks.

**Footer.** At the bottom of the page, an optional section may be displayed that provides details about your company, including contact information and social media links.


## Mobile version
Hornbill has provided a progressive web app (PWA) to give users a fast and UI-rich solution to accessing their company's home page, which can be packed full of valuable information and Service Catalog access.

![Mobile](/_books/esp-user-guide/images/mobile-home.png)

### Accessing
You can access the mobile app using your mobile phone's browser. Navigate to `mcatalog.hornbill.com/<Your_Instance>/`. If you don't know your instance name, contact your IT support team.

A login button displays when you first connect. In most cases, you will need to use your login credentials for your company's network.

### Home screen
Once you are logged in, you can add the Employee Portal to your mobile device's home screen.

* **Android.** On an Android device, you may get a prompt (*Add the Hornbill App to your Home Screen*). If you do this, an application icon will be added to your phone; this provides quick access back to Hornbill and also opens the app in a full screen.
* **iOS.** On an iOS device, you can select from the Safari options when on the Employee Portal page to add the site to your home screen.

### Navigation
In the top right of the mobile app, use the menu button to view and navigate to other available pages and options.

**Domain pages.** A list of the available pages that you can navigate to are listed here. These pages normally represent the main business areas within your company. A link back to the main page is provided in the header.

**Settings.**

* **Your Profile Information.** See your logged-in profile along with picture and job title. Not you? Click **Log Out**.
* **Versions.** This may be asked for by Hornbill Support for any issues that are reported, to ensure you are on the latest version.
* **Clear Cache.** This clears any locally cached files. Clearing the cache may correct issues caused by out-of-date cached files.
* **Log Out.** This logs you out of your session.

**About.** Your company's contact information.

## Knowledge content in the portal

When a user searches the portal or completes a Summary field in a new request, Knowledge content is dynamically presented as the user types. This content can be in the form of FAQs, Known Issues, Catalog Items, and Requests.

Possible Knowledge matches are continually filtered based on the inputs to different Intelligent Capture forms in the IC flows. Users can view and interact with potential Knowledge content in Intelligent Capture.

This dynamic presentation of Knowledge content is set to ON by default.

**To disable the presentation of Knowledge content in the Employee Portal:**
1. Navigate to **Configuration > Platform Configuration > Core Settings**.
1. Find the setting called `guest.anonymous.employeePortal.core.disable-knowledge-search-in-pro-cap`.
1. Click the switch to toggle the setting to ON.
