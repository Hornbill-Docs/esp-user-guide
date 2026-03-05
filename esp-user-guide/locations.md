# Locations

Use the **Locations** feature to view and manage your organization's physical locations. You can access this view from the **Home Menu**.

![Home Menu showing the Locations option highlighted](/_books/esp-user-guide/images/home-menu-locations.png)

## Permissions

The following roles provide different levels of access to location features:

* **User Role**: Users with this role can view the location list, details, nearby locations, and the users tab.
* **Sites Manager**: Users with this role can add and edit location details.

## Location list

The **Locations** list displays all registered locations. You can find specific locations by using the location filter. Once you select a location from the list, you can view and edit its details.

## Details

The **Details** tab contains specific information about a location, including the following sections:

### Basic details

View and update the primary attributes of a location.

* ID
* Name
* Location Code
* Type
* Company
* Building
* Floor
* Address
* City
* State
* Post Code
* Country
* Phone

### Extra details

View and update custom field values. A user with the [Form Designer Role](/esp-config/organizational-data/roles#system-roles) can add custom fields to the location record.

This section include the Latitude and Longitude values that are required for the **[Nearby](/esp-user-guide/locations#nearby)** tab to be displayed.

![Location coordinates displayed in the Extra details section](/_books/esp-user-guide/images/location-coordinates.png)

### Members

Add key users who are associated with the location. You can only add users with the **User** type as members. Common member roles include:

* Engineer
* Location Manager
* Area Manager
* Regional Manager

:::tip
You can look up member details in workflows to assign activities or notify key members automatically.
:::

### Activities

You can create and associate specific activities with a location to track tasks and progress.

### Activity stream

The **Activity Stream** is located in the right sidebar. Use this stream to discuss and collaborate on content related to the location. You can follow a location's activity stream to see updates in your **News Feed**.

## Nearby

If a location has defined latitude and longitude values in the **[Extra Details](/esp-user-guide/locations#extra-details)** section, the **Nearby** tab becomes available.

* **Interactive map**: This map displays other nearby locations. You can scale the map to adjust the view.
* **Nearby list**: A list of nearby locations appears next to the map for quick reference.

![Nearby tab showing an interactive map and a list of nearby locations](/_books/esp-user-guide/images/locations-nearby.png)

## Users

The **Users** tab displays a list of users who have this specific location defined in their user profile. You can update this list through **Platform Configuration** in the [Locations](/esp-config/organizational-data/locations) view, [Users](/esp-config/organizational-data/user-accounts/about-user-accounts) views, or by using user import utilities.
