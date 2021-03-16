# lab-03-group-10
lab-03-group-10 created by GitHub Classroom

1. Olivia Daw
2. Benyamin Shahmohammadi
3. Yun-Ting Lin
4. Michael Shirley


Exercise 01

V1
GET words
Break the words into individaul letters
Display letters in reverse order

V2
GET string
IF isReversed = False
FOR each element
 starting from the end
 print elements
 SET isReversed = True
 
 V3
 GET string
IF isReversed = False
FOR each element
 starting from the end
 print elements
 SET isReversed = True
 
 V4
START
INPUT string
SET emptyString to nothing
FOR each character in string, starting from end
ADD character to end of emptyString
DECREMENT

RETURN emptyString

Exercise 02
V1
START
INPUT values 
FOR each element, compare with the next element 
IF higher than next, swap 
INCREMENT
IF no values higher than next
STOP 

v2
INPUT values
SET lastElement to be nothing
SET element as Current in value
FOR each element, compare with the next element
IF element is higher, swap

v3
START 
INPUT values
SET lastValue <--nothing
SET lastPosition <-- nothing

Exercise 03
V1
Get list 1
Get list 2
Init ListCN --commonNumber
IF the number is on both list 1 and list 2, add to ListCN
Get highest number from ListCN.

V2
Get list 1
Get list 2
Init ListCN --commonNumber
IF the number is on both list 1 and list 2, add to ListCN
For everyone number in list 1
IF in list 2
Add ListCN
Get highest number from ListCN.

V3 –- good enough, if have time, then work on better version next.
Get list 1
Get list 2
Init ListCN --commonNumber
IF the number is on both list 1 and list 2, add to ListCN
For everyone number in list 1
IF in list 2
Add ListCN
Get highest number from ListCN.
![image](https://user-images.githubusercontent.com/79881062/111242289-bdda0b80-8663-11eb-8954-4ce99ed8638c.png)


FOR each value Current in values
	IF lastValue == nothing
		SET lastValue <-- Current
		SET lastPosition <-- currentPosition
		INCREMENT
                ELSEIF lastValue > currentValue
		SET currentValue <-- lastPosition


