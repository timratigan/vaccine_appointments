# Vaccine Appointments
Automatically searching for vaccine appointments

# Usage

To copy this package, run:

`git clone https://github.com/TheIronicCurtain/vaccine_apointments`

## Texas

Run the following in the command line:

` python texas.py [cities] `

Where `cities` are the cities you want to restrict your search to. If none are provided it will open all available appointments. e.g. if you're in the San Antonio area you might put: 

`python texas.py "San Antonio" Jourdanton Pleasanton Leming Poteet`

Once it starts running, it will ping HEB periodically until an appointment in one of those cities shows up, and then open it in your web browser. You still have to be quick from there!

The loop will stop running once it finds a page to open, so if you don't get the appointment on the first try just run it again!