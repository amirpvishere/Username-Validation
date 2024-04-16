def username_validation(username):
    if len(username) < 4:
        print('Your username must be at least 4 character')
    else:
        print('Your username has been created successfully)

while True:
    username = input('Enter your username: ')
    username_validation(username)

def username_validation(Uname):
    if len(username) > 8:
        return True
    else:
        return False

while True:
    username = input('Enter Your Username: ')
    if username_validation(username):
        print('Your username has been successfully created.')
    else:
        print('Choose another username.')
