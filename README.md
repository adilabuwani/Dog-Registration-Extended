# Dog-Registration-Extended #
### Database to manage NYC  Dog Registration. This project uses Oracle SQL to answer queries. ###

# Objective #
- Create a database to manage NYC dog registration
- Create reports

# Dog database requirements #
- Dog owner information including name, full address, email and phone. Owners can have multiple phone numbers.
- Dog owners can own many dogs. Track all dogs owned, including current and previously owned.
- Dog information including dog name, breed, gender, weight, date of birth, age, owner.
- A dog has one current owner, but can have many previous owners.
- A dog has many photos. Identify the photo name and date of photo. For instance rover_running.jpg
- Dog owners can receive tickets with violations. Tickets include the owner, dog, violation type, fine, date of violation and current status of violation. Dog owners can receive many tickets.
- Tickets are limited to specific types of violations. For instance, violation 1 (no leash); violation 2 (loud barking), etc.
Data
You must enter at least the following data
- At least 20 dog owners.
- At least 50% of the owners will own more than one dog. Create one owner with at least 10 dogs. One dog can’t be simultaneously owned by the same owner.
- At least 5 violation types
- At least 10 tickets
- Import at least 1,000 dog records from NYC Open Data

# Questions #
- Generate SQL to answer the following queries.
- Replace underlined items with values of your own choosing. For instance, replace three months with your own date range.
- Create data to insure all questions generate output.
- Format all output. For instance, all numbers will display with commas, dollar values will display with a $ prefix and create descriptive labels for all columns.

# Additional Design Requirements #

- Create your database using Oracle. Utilizing other databases requires prior instructor approval.
- Normalize your database to third normal form.
- Output for all questions must include at least one row displayed.
- All multi value columns must be saved to their own table.
- Identify and create primary keys for each table.
- Create foreign keys to enforce referential integrity. For instance, you must have foreign keys with references to at least the following:
a. Dogs and owners
b. Owner and phones
c. Owner and tickets
d. Ticket and violation
- Include the question, SQL command to answer the question and output from the SQL command.
- Include all SQL commands to create your database and answer questions including create tables, search, update, insert data, alter column names and alter column types.
- Create descriptive column labels for all output.
- Clearly label each question and answer.
