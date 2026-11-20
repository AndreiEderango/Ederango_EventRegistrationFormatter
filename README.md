first_name = str(input("Enter your first name: "))
last_name = str(input("Enter your last name:"))
section = str(input("Enter your section: "))
event = str(input("Enter the event name or title: "))
event_year = str(input("What year did/does the event start? "))
event_month = int(input("What month did/does the event start?(1 to 12, as in 1 as January, while 12 being December) "))
event_date = int(input("What date did/does the event start? "))
months = ["January", "Febuary", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December"]
def proper_full(first_name, last_name):
    print(first_name.capitalize(), last_name.capitalize())
def proper_code(firstname, lastname):
    print(firstname.upper(), lastname.upper())
def section_full(section):
    print(section.upper())
def event_format(event):
    print(event.capitalize())
proper_full(first_name, last_name)
proper_code(first_name, last_name)
section_full(section)
event_format(event)
print("Year: ",event_year)
print("Month: ",event_month)
print("Day: ",event_date)
