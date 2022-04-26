# Sorting-Algorithms
Times different sorting algorithms
Made in java: 

Student Class:
class that uses fields for sorting
  fields:
    id- creates a random int from 0 to 999999 with no duplicates
        :note - I used an array for this solution giving it a O(n) instead of using a hashset or map for a O(1)
                this is intensinal in order to limit imports. 
    standing- year of student with 10% being seniors, 20% being juniors, 30% being sophomores, 40% being freshmen
    gpa- two decimal floating point in range from 0.00 to 4.00, 5% have a 4.0, 20% have 3.00 to 3.99, 50%	have 2.00 to 2.99
         20% have 1.00 to 1.99, and 5% have 0.00 to 0.99

    first name- a string with 5 to 10 random chars and the first letter is capitalized
    last name - same requirement as first name

Sort:
adds implementation of Search, Merge, bubble, insertion, selection, radix and quick sort.

Comparator:
In order to allow for genaric types I implemented comparators for each field in the sudent class
and added them to the sorting algorithms

Client:
  test the time of each sort and places data into a ascii table
