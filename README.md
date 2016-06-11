# Sort Ruby Array Alphabetically and Convert to Hash

Write a function (named my_transform) which is capable of transforming the described input to the output. The program should be independent of the specifics of this example meaning that given a completely new set of input, the output would still be created correctly.


* Input: a list (Ruby array data structure) of strings

items = ["Apple", "Banana", "Carrot"]


* Output: a dictionary (ruby Hash data structure) providing a cross reference between an item and its list position (also called index) in the above list. Each key of your dictionary will correspond to a item in the above list, each value will correspond to an items position/index.

item_to_position = {"Apple"=>0, "Banana"=>1, "Carrot"=>2}


* Test: To test your method you can execute the following which should return True

my_transform(items) == item_to_position


More explanation.

The item "Apple" is stored at position 0 within the items list.
The item "Banana" is stored at position 1 within the items list.
The item "Carrot" is stored at position 2 within the items list.


