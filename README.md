# show-Balupari
# Vamshi Krishna Balupari
### Sambar Rice is my favourite food
Sambar Rice is my favourite dish because of its rich flavours, it is a fusion of variety of spices with **Dal** and **Basmati rice**. Its a combination of various spieces to give it a hot spicy flavour.
The basmati rice addes more flavours to the dal and spices. It's one of the famous dishes of Hyderabad.

----
### Favourite Food Places
1. It's available in nearby restaurants (easy to find )
2. It's available in Ahaa and Desi bytes near Kansas. (moderate time taking)
3. We can make the dish at home.(easy to make the dish)

* Pappads or Thin Indian wafer,
* Gobi Fry
* Chicken Fry

[Link of MyMovie-](https://github.com/Vamshi6665/show-Balupari/blob/main/MyMovie.md)
---
## Alternative Actors for Spiderman
Tom Holland has done a great job in the movie. Apart form that there are some other actors i would like to see in the same character are below.
| Preferred Actor Name |  Reason for the Selection of actor      | Age of Actor|
|----------------------|-----------------------------------------|-------------|
| Chiris Hemsworth     | The actor has musuclar physic           |      41     | 
|  Tom Cruise          | The actor is known for the action stunts|      62     | 
|  Christian Bale      | he has a matured acting style           |      50     |
|  Hrithik Roshan      | Charming and engertic actor             |      51     |
---
####  Favorite Quotes
> "It is never too late to be what you might have been. " *- George Eliot*

>"Arise, awake and do not stop until the goal is reached." *- Swami Vivekananda*

#### How to parse data from a CSV file in Python
The below code is the to parse data from the CSV file to the python. Atr the start of the code it import csv packages then there is the csv_mapping_list empty list. After that the csv reader variable we are reading the my_data and then using if ,else  condition. At  the last we are using the append to add to the list. 

```python
import csv

def parse_csv_data(csv_path):
	csv_mapping_list = []

	with open(csv_path) as my_data:
	    csv_reader = csv.reader(my_data, delimiter=",")
	    line_count = 0
	    for line in csv_reader:
	        if line_count == 0:
	            header = line
	        else:
	            row_dict = {key: value for key, value in zip(header, line)}
	            csv_mapping_list.append(row_dict)
	        line_count += 1 
```
Quick Link of the snippet source-<https://code.pieces.app/collections/python>




