# Food Truck Navigator

This project is developed using Drupal. It provides a platform for managing and displaying information about mobile food facility permits. The key features of this project include a custom content type called "Vendor," a taxonomy term for defining facility types, and a view that filters and displays vendor information in a user-friendly manner.

## Features

### Content Type: Vendor
The Vendor content type contains all the information of the applicants. This includes:
- Vendor Name
- Address
- CNN
- Facility Type
- Location description
- Permit
- Status

### Taxonomy Term: Facility Type
A taxonomy term called "Facility Type" is used to categorize the type of facilities. This helps in organizing and filtering the vendors based on the type of facility they operate.

### View with Filters
A custom view is created to display the vendors. This view includes the following features:
- Filters by Applicant: Allows users to filter the vendors based on the applicant's name.
- Filters by Facility Type: Allows users to filter the vendors based on the facility type.

### Grid of Cards
The view displays the vendors in a grid of cards. Each card corresponds to an applicant and contains the following information:
- Vendor Name
- Location
- Type
- Status

Additionally, each card includes a "See More" link that directs the user to a detailed page with more information about the applicant.

## Demo
http://foodtrucknavigator.docksal.site
