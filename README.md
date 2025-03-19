# iOS-Learning

#JSON Structs:
-When using a structure to decode json data, do not hard code ID using Identifiable protocol (let id = UUID()) unless absolutely necessary. If ID doesnt exist in original json structure, computer will try to decode a nil value and errors will show.
-When attempting to decode/access two objects in json, use root array to access second object 
