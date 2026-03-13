# List-ADT-
Practice program 
def insert_element():
    n = int(raw_input("Enter element to insert: "))
    arr.append(n)
    Print( "Element inserted")
def delete_element():
    n = int(raw_input("Enter element to delete: "))
    if n in arr:
        arr.remove(n)
        print "Element deleted"
    else:
        print "Element not found"
def search_element():
    n = int(raw_input("Enter element to search: "))
    if n in arr:
        print "Element found at position", arr.index(n) + 1
    else:
        print "Element not found"
def display():
    if len(arr) == 0:
        print "List is empty"
    else:
        print "List elements are:"
        for i in arr:
            print i,
while True:
    print "\n--- List ADT using Array ---"
    print "1. Insert"
    print "2. Delete"
    print "3. Search"
    print "4. Display"
print "5. Exit"
    choice = int(raw_input("Enter your choice: "))
    if choice == 1:
        insert_element()
    elif choice == 2:
        delete_element()
    elif choice == 3:
        search_element()
    elif choice == 4:
       display()   
   elif choice == 5:
        print "Exit"
        break
    else:
        print "Invalid choice"
  Output:
  
1. Insert
2. Delete
3. Search
4. Display
5. Exit
Enter your choice: 1
Enter element to insert: 10
Element inserted

Enter your choice: 4
List elements are:
10
