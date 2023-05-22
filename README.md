# Logicfirstproblems

name = "Robert Andrew George"

list_convert= name.split(" ")
print(list_convert)

empty_list=[ list_convert[i][0].upper() for i in range(len(list_convert))]
print(empty_list)

result=''.join(empty_list)
print(result)
    
