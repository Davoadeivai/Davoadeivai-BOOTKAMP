# daneshkar_python_project
This repository was created with ❤️ for Daneshkar's Python Bootcamp project.
# Cinema Ticket

This project is a cinema ticket reservation system implemented in Python. It allows users to create accounts, manage their profiles, view available movie sessions, and reserve seats. The system also supports different subscription types and offers various discounts based on user's membership duration and birthday.

## Features

- User registration with mandatory birthdate
- Automatic registration date storage
- Users can have multiple bank accounts
- Bank accounts support deposit, withdrawal, and transfer operations
- Enhanced security with account password and CVV2
- Users can charge their wallet and purchase different subscription types
  - Bronze: Basic default service with no special benefits
  - Silver: 20% cashback on the next three purchases
  - Gold: 50% cashback and a free energy drink for one month
- Users can view and reserve movie sessions
- Birthday discounts and membership-based discounts
- Restrictions on reserving past sessions or sessions with full capacity
- Age restrictions on viewing and reserving movies for higher age ratings
- Separate script for cinema managers to set up movie sessions
- Two approaches for differentiating managers and users:
  - Using an Enum field in the User model class
  - Inheriting from an abstract base Human model
- Modular design with separate modules for each functionality
- Test-driven development (TDD) using a `tests` package
- Custom exceptions and exception handling
- Logging events in `cinematicket.log`
- Data persistence using Pickle or JSON files
- Recommended Git Workflow for team collaboration
- Additional features are acceptable after completing the main scenario

## Installation

1. Clone the repository:

```
git clone git@github.com:
```

2. Change to the project directory:

```
cd daneshkar_python_project
```

3. Install the required dependencies:

```
pip install -r requirements.txt
```

## Usage

1. Run the main script:

```
python main.py
```

## Testing

To run the tests, execute the following command:

```
python -m unittest discover tests
```
#   D a v o a d e i v a i - D a v o a d e i v a i - p y t h o n _ p r o j e c t - _ d a n e s h k a r 2 0 2 4  
 #   D a v o a d e i v a i - D a v o a d e i v a i - p y t h o n _ p r o j e c t - _ d a n e s h k a r 2 0 2 4  
 #   D a v o a d e i v a i - p y t h o n _ p r o j e c t - _ d a n e s h k a r 2 0 2 4  
 #   D a v o d E i v a z k h a n i _ d a n e s h k a r _ p r o j e c t  
 #   D a v o a d e i v a i - B O O T K A M P  
 