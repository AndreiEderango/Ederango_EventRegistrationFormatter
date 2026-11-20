first_name = str(input("Enter your first name: "))
last_name = str(input("Enter your last name:"))
section = str(input("Enter your section: "))
event = str(input("Enter the event name or title: "))
event_year = str(input("What year did/does the event start? "))
event_month = int(input("What month did/does the event start?(1 to 12, as in 1 as January, while 12 being December) "))
event_date = int(input("What date did/does the event start? "))
months = ["January", "Febuary", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December"]
def proper_full(first_name, last_name):
    print("Name: ",first_name.capitalize(), last_name.capitalize())
def proper_code(firstname, lastname):
    print("Name Code: ",firstname.upper(), lastname.upper())
def section_full(section):
    print("Section: ",section.upper())
def event_format(event):
    print("Event or title: ",event.capitalize())
def event_date_format(month, date, year):
    print("Event date: ",months[month], date, year)
print("--- Student Event Registration Summary ---")
proper_full(first_name, last_name)
proper_code(first_name, last_name)
section_full(section)
event_format(event)
event_date_format(event_month - 1, event_date, event_year)
print("Registration record created successfully.")
