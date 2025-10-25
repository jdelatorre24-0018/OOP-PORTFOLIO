Midterm Lab Task 2:

<img width="669" height="701" alt="image" src="https://github.com/user-attachments/assets/6de7e83b-f978-4866-ab7f-405697a61b6b" />

Source Code:

    product_name = str(input("Enter Product Name:"))
    category = str(input("Enter Category:"))
    quality = float(input("Enter Quality Rating:"))  
    price = float(input("Enter Price Rating:"))
    service = float(input("Enter Service Rating:"))  

    def calculate_average_rating(quality,price,service):  
      total = quality + price + service  avg = total / 3  return avg  
    
    def analyze_product():  
      print("Product Name: %s " %product_name )
      print("Category: %s" % category )
      print("Quality Rating: %.2f" % quality) 
      print("Price Rating: %.2f "% price)  
      print("Service Rating: %.2f" % service)  
      print("Overall Average Rating: %.2f" % calculate_average_rating(quality, price, service)) 
      
    analyze product()

Output:

Sample Output 1:

<img width="692" height="406" alt="image" src="https://github.com/user-attachments/assets/ec76dbe5-e325-45f7-93cb-4fcb7508cf51" />

Sample Output 2:

<img width="561" height="389" alt="image" src="https://github.com/user-attachments/assets/ca7dbd17-e32b-437b-b339-fc540bd2271b" />

