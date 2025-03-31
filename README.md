def list_operations():
    my_list = []  # Create an empty list
    
    # Append elements
    my_list.append(10)
    my_list.append(20)
    my_list.append(30)
    my_list.append(40)
    
    # Insert 15 at the second position
    my_list.insert(1, 15)
    
    # Extend list with another list
    my_list.extend([50, 60, 70])
    
    # Remove the last element
    my_list.pop()
    
    # Sort the list in ascending order
    my_list.sort()
    
    # Find and print the index of 30
    index_30 = my_list.index(30)
    print(f"Sorted List: {my_list}")
    print(f"Index of 30: {index_30}")

list_operations()
