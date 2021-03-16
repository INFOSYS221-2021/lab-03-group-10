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

FOR each value Current in values
	IF lastValue == nothing
		SET lastValue <-- Current
		SET lastPosition <-- currentPosition
		INCREMENT

	ELSEIF lastValue > currentValue
		SET currentValue <-- lastPosition


