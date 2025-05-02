# python11
# dictionary operations
person= {'name':'Siddhu','age':21,'city':'Goa'}
print(person)
print("accessing and modify the person age:")
person["age"]= 22
print(person)
print("Adding and removing items")
person['email']= 'gundalas158@gmail.com'
print(person)
del person['city']
print(person)
print("All keys & values")
print(person.keys())
print(person.values())
print(person.items())
print(person.get("age"))
