# About
This is a beginner's GOlang project.
I have written a program using which you can order food in a restaurant.
# Prerequisite
You should have basic knowledge of Go language like data types, if-else statement, loops, switch-statement, slices, maps and structures.
# Overview
Want to order food!? Well, you have come to the right place.

This is a program which will help you order food in a restaurant named "Jaipur Bhojanalya".

You can order any item that is there in the menu, and as many times as you want. This program also lets you modify your order by allowing you to update quantity of an item, add an item in the order or delete an item from the order; before generating the final bill.

# Learnings
There are several things that I learnt while building this project. I am sharing it, so that you can refer it if you get stuck.
1. __How to append in a slice of struct?__
		
    Let say struct type name is NewStruct and we defined a new variable with the name a. 
        
        type NewStruct struct{
				   itemName string
				   price uint
				   quantity uint
				}
        
        //To append use the below code: 
      
        a = append(a, NewStruct{itemName: name, price: bill, quantity: noOfPlates}
        
 2. __What happens when you loop through an string, slice, map?__
  
    Read [for-loop range](https://yourbasic.org/golang/for-loop-range-array-slice-map-channel/) and [unexpected values range](https://yourbasic.org/golang/gotcha-unexpected-values-range/) to clear your doubts.
 3. __Time function__   : E.g., `time.Now()` 
      * Read [this](https://www.golangprograms.com/get-current-date-and-time-in-various-format-in-golang.html) article to gain more insights.
 4. __Random function__ : E.g.,`randIntn(500)`, `rand.Seed(time.Now().Unix())`;
      * Refer to [this](https://stackoverflow.com/questions/68203678/golang-rand-int-why-every-time-same-values) if you get stuck
 5. __Delete from a map__ : `delete(mapName, key)`

# Sneak peek
Here are some screenshots of the program in running. 

![Screenshot 2024-11-22 222526](https://github.com/user-attachments/assets/3b5cf85a-aa30-495b-a96e-3bf537db67f1)
  ![image](https://user-images.githubusercontent.com/106534693/176141902-8845a817-9367-4dd6-8fc9-762cc1ec992f.png)
  ![image](https://user-images.githubusercontent.com/106534693/176142141-79db608e-af78-4dcb-bd77-76a7d7910aa5.png)
  ![Screenshot 2024-11-22 222702](https://github.com/user-attachments/assets/1774c4b6-6586-432e-8ca9-5a25530b1622)
