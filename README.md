Describe: roboger()

Test: "It will return an array from 0 to the user's input number."
Code: roboger(5)
Expected Output: [0, 1, 2, 3, 4, 5]

Test: "It will iterate through the array and replace numbers that contain '1' with 'Beep!'."
Code: roboger(1)
Expected Output: [0, "Beep!"]

Test: "It will iterate through the array and replace numbers that contain '2' with 'Bop!'."
Code: roboger(2)
Expected Output: [0, "Beep!", "Bop!"]

Test: "It will iterate through the list and replace numbers that contin '3' with 'Won't you be my neighbor?'."
Code: roboger(3)
Expected Output: [0, 1, "Beep!", "Bop!", "Won't you be my neighbor?"]

Test: "It will combine the array into a string, with each element separated by a comma and a space. 
Code: roboger(3)
Expected Output: 0, 1, "Beep!", "Bop!", "Won't you be my neighbor?"