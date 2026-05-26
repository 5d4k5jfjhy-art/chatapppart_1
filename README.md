# Chatapp_Part_2

##Features

# MainApp
### 1. User Registration
- Asks the user to enter their **first name** and **last name**
- **Username validation** via 'login.checkUserName(username)':
- Must be <= 5 characters
- Must contain and underscore '_'
- **Password validation** viaa 'login.checkPassword(password)':
- must be atleast 8 characters lonh
- must include a capital letter and a special character
- **Phone number validation** via 'login.checkCellPhoneNumber(phone)':
- must contain an international dialing code (+27)
- once all inputs are all valid, the user is registered via 'login.registerUser()'
  
### 2. User Login
- Asks for userame and password 
- Authenticates via 'login.loginUser(loginUsername, loginPassword)'
- Login status is displayed via 'login.returnLogiunStatus(loggedIn)'

  ## 3. Chat Menu (shown after successfully logging in)
  Upon login, users are welcomed to **CHATAPP** and presented with a menu
  Options
  1. Send Messages
  2. Show recently sent messages
  3. Quit

#### Sending Messages (Option 1)
- User specifies how many messages to send
- For each message:
- Enter a **recipient number**
- Enter the **message body**
- Messsage is stored as " To <recipient>, <message> in an arayList<String>

#### View sent Messages (Option 2)
- Displayes all the previously sent messages from the session
- If no messages have been sent, displays "No messages sent yet"

#### Quit (Option 3)
- Sets 'running = false', exits the chat loop
- Prints "Logging out"




  
