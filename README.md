# SwimmingPoolRes

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.2.4.

#### Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

#### Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Project Scope

The user has a swimming pool which is too hard to manage via a single person. Normally user has to store data on swimming pool bookings, user registered details to check whether he is a regular customer or not and as well as pool calendar to store swimming pool sessions or sometimes bookings also. Pool bookings can be happened in two ways. One is online (but at this moment customers will use phone calls to book pool) and other is come to the pool and book.

So the user requires a web based computer system to manage pool bookings as well as manage user details. There should be pool calendar to store booking and as well as some usual pool sessions. And there should be an admin panel to manage pool calendar, generate some analytical reports  and user details. As well as a third party payment gateway for online payments to be handled.

As well as an attractive front page for make website clean and beautiful.

### Functional Requirements

> - User Registration
 - There can be only two kind of users to the system. One is the customer and the other is admin.
 - Admin will be already registered with the system and only customer can register with the system.
 - Registration can be done using facebook and google also.

> - User login
 - Both admin and user can login to the system via same login page, but will be redirected to different pages,
 - And login can be done using facebook and google also.

> - Pool Booking
 - Customer either can be a member of the system or not. Customer can book pool for 1 or more people. There are few packages also. Normal and Premium packages available. Admin can change the package details and price. In premium package no one other than reserved people can reserve the pool after reserved some period.
 - Also customer able to cancel their reservation any time if payment hasn’t made
 - Upon the successful reservation with or  without payment user will get an email with QR code with some number. When arriving the customer , He/She can show their phone to confirm reservation.
 - Admin can confirm user by scanning qr code, entering number or entering email/id.
 
> - View analytics
 - Logged in users could see daily traffic of pool roughly with graph or some other technique. Then user can select preferable time period. Also admin can view advanced reports. Such as income,registered user count, more regular customers.

> - Logout
 - Admin and user can logout from the system

> - Payments
 - Payments can be done using two methods. If the customer book the pool via online he/she should deals with a payment gateway.
 - To do so the customer should be logged into the system.
 - Online payment is optional to customer, customer can pay on arrival also

### Non - Functional Requirements

> - Security
 - We have to consider about security as we are going to dealing with a payment gateway. So the security holes should be covered properly and make sure that no one can dealing with the payment gateway rather than the payment gateway provider.
