✅ *Programming Basics – Part 7: Dictionaries (Maps)* 📚🧠

✅ *What is a Dictionary?*  
A *dictionary* (or *map*) stores data in *key-value* pairs — where each key maps to a specific value.

➊ *How to Create a Dictionary*

📍 *Python*  
```python
student = {"name": "Alice", "age": 21}
```

📍 *Java*  
```java
Map<String, Object> student = new HashMap<>();
student.put("name", "Alice");
student.put("age", 21);
```

➋ *Properties of Dictionaries*  
✔️ Keys are unique  
✔️ Values can be duplicated  
✔️ Fast data retrieval using keys

➌ *Access Values*

📍 *Python:* `student["name"]`  
📍 *Java:* `student.get("name")`  

➍ *Update Values*

📍 *Python:* `student["age"] = 22`  
📍 *Java:* `student.put("age", 22);`  
➎ *Loop Through a Dictionary*

📍 *Python:*  
```python
for key, value in student.items():
    print(key, value)
```

📍 *Java:*  
```java
for(Map.Entry<String, Object> entry : student.entrySet()) {
    System.out.println(entry.getKey() + ": " + entry.getValue());
}
```

```

➏ *Why Use Dictionaries?*

- Quick lookup by key
- Store related data in structured form  
- Useful for JSON-like data handling

➐ *Real-World Uses of Dictionaries*

- Storing user profiles  
- Configuration settings  
- Counting occurrences (word frequency)  
- Mapping IDs to record
