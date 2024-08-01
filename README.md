
# Vaccine Proximity Database Management

This is an app designed through the integration of Python, Python’s in-built module Tkinter and MySQL. I have utilized Tkinter module for its user friendly GUI with the record maintenance provisions available on MySQL.


## General Explanation
The app is divided into 2 major subdivisions – one
for vaccine camps who administer the vaccine, the
other for people who want to get their vaccine (the
vaccinee).

Before entering amidst the sub-categories, it is
essential to note that this app in no way is entitled
to any organization but is only a medium for the
various vaccine camps (Hospitals, NGO’s etc.) to
communicate with common people like us to
ensure vaccination is provided at their disposal at
the right time.

When users open the app for the first time, they
will be shown two options – Vaccinee and Vaccine
Camp. Users are to choose according to their need.

Choosing any of these options takes the user to a
sign in and sign up page, where new users can
create their account through the sign up page and
existing users could log in to their account through
the sign in page.

While signing up users are shown the rules which
they should follow to fill up their details.

After users sign in to their accounts, they are
shown their account details and the option to
modify them if needed.

Here, Vaccine Camp users can enter the vaccine
stock available at their camp for the next day.
They will not be allowed to enter or modify current
day’s vaccine stock as all eligible vaccinee will
already be notified about the vaccine availability.

Here, Vaccinee users can check whether they are
eligible to get the vaccine for that day, if they are
eligible, they will be shown the details of the
vaccine camp from where they could get their
vaccine.

The eligibility of a vaccinee is calculated by
prioritizing who needs the vaccine most by
considering factors such as the job they do, their
age, past medical conditions, the vaccine they took
for their first dose (if any) and the date they got
their first dose.

All the details entered by the users are stored in a
MySQL database in a usable form. All other
functions are done by python with the help of
inputs from the MySQL server.
