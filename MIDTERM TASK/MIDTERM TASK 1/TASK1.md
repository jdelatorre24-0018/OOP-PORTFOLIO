Midterm Lab Task 1


Problem 1. Use Appropriate Escape Sequence( \n, \t \b \ ..etc) for the problem below


<img width="1036" height="593" alt="image" src="https://github.com/user-attachments/assets/009aa376-8676-403d-9be6-4d553ef236c2" />


Source Code:


      print("Database Record\n")
      print("\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\\")
      print("Name:\t\tJohn Doe")
      print("Email:\t\tjohn.doe@example.com")
      print("University:\tABC University")


  Output:

  <img width="517" height="193" alt="image" src="https://github.com/user-attachments/assets/226f96c1-ec64-44fa-8535-1309f31dd026" />

Problem 2. Using Placeholders for Email Details: Use appropriate type specifiers %s, %d, %f etc… for this task

<img width="833" height="568" alt="image" src="https://github.com/user-attachments/assets/0e6863cf-5d82-4ad1-b5c4-b5abf05ce7ae" />


Source Code:

    sender = "Jane"
    subject = "Greetings"
    version = 1.2
    discount = 10.50
    status = "A"
    code = "ABCD123"
    location = "City XYZ"
    age = 30
    company = "ABC Corporation"
    website = "www.example.com"
    phone = "+1 123-456-7890"
    job_title = "Software Engineer"
    department = "Engineering"
    
    print("Dear John, I hope this email finds you well.")
    print("I wanted to reach out and say hello.")
    print("I hope you are doing well and enjoying your day.")
    print("It's been a while since we last spoke, and I wanted to catch up with you.")
    print("Let's plan to meet up soon and have a great time together!")
    print(f"Subject: {subject}")
    print(f"Sender: {sender}")
    print(f"Version: {version}")
    print(f"Discount: {discount:.2f}%")
    print(f"Status: {status}")
    print(f"Code: {code}")
    print(f"Location: {location}")
    print(f"Age: {age}")
    print(f"Company: {company}")
    print(f"Website: {website}")
    print(f"Phone: {phone}")
    print(f"Job Title: {job_title}")
    print(f"Department: {department}")

Output:

<img width="759" height="469" alt="image" src="https://github.com/user-attachments/assets/f1789f81-a51a-4175-930f-27276a649f86" />


Problem 3. Book Reservation; Accept User Input

<img width="770" height="278" alt="image" src="https://github.com/user-attachments/assets/aad20dd3-fb35-4ad8-ae71-bb287fb9cc13" />


Source Code:

    title = input("Enter the book title: ")
    author = input("Enter the author: ")
    year = int(input("Enter the year of publication: "))
    genre = input("Enter the genre: ")
    library = input("Enter the library: ")
    member_id = input("Enter your member ID: ")
    return_date = input("Enter the return date: ")
    
    print(f"\nYou have successfully reserved the book '{title}' by {author}.")
    print(f"Year of Publication: {year}")
    print(f"Genre: {genre}")
    print(f"Library: {library}")
    print(f"Member ID: {member_id}")
    print(f"Return Date: {return_date}")

Output:

<img width="757" height="422" alt="image" src="https://github.com/user-attachments/assets/928de67e-f4db-4369-8a28-d49e78215259" />


Problem 4. Day Identifier

<img width="714" height="603" alt="image" src="https://github.com/user-attachments/assets/eae9a57e-5548-487e-b8c5-6f89a4e18364" />

Source Code:

    day = int(input("Enter day: "))
    
    if day == 1:
        print("Monday")
    elif day == 2:
        print("Tuesday")
    elif day == 3:
        print("Wednesday")
    elif day == 4:
        print("Thursday")
    elif day == 5:
        print("Friday")
    elif day == 6:
        print("Saturday")
    elif day == 7:
        print("Sunday")
    else:
        print("Invalid input")

Output:

<img width="224" height="179" alt="image" src="https://github.com/user-attachments/assets/1bb866f1-0c12-466b-9be9-860183ad528a" />
















