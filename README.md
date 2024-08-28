# **EXPERIMENT 1 - Introduction to Python Programming**

## 1. ALPHABET SOUP PROBLEM: 
**Function Used:** *String_Sorter(s)*

**Description:** The function 'String_Sorter(s)' takes a string 's' as input and returns a new string where all the letters are sorted in alphabetical order.

**Function Used:** *char_list.sort()*

**Description:** The function 'char_list.sort()' sorts the elements of the list 'char_list' in place, meaning it arranges the elements in ascending order (from smallest to largest) within the original list so that they appear in alphabetical (or numerical) order.

**Function Used:** *sorted_string = ''.join(char_list)*

**Description:** The function 'sorted_string = ''.join(sorted(s))' creates a new string 'sorted_string' by arranging the letters of the original string 's' in alphabetical order.

**Function Used:** *return sorted_string*

**Description:** The function 'return sorted_string' simply sends back the value of 'sorted_string' as the output of the function, which is the new alphabetically sorted string.

    Example: alphabet_soup("hello")

    Output: "ehllo"

## 2. EMOTICON PROBLEM:
**Function Used:** *def Emotify(phrase):*

**Description:** This defines a function named 'emotify' that takes one input, called 'phrase.' This input is expected to be a string (a phrase) that we want to transform by replacing certain words with emoticons.

**Function Used:**            

    emoticon_library = {"smile": ":)", "grin": ":D", "sad": ":((", "mad": ">:("}   

**Description:** This function creates a dictionary called 'emoticon_library'. A dictionary is like a list of pairs, where each word (like "smile") is matched with a specific symbol (like ":)"). This dictionary tells the function which words to replace with which emoticons.

**Function Used:** *words = phrase.split()*

**Description:** This function splits the phrase into individual words. For example, If the phrase is "I am mad", It will turn into a list of words: ["I", "am", "mad"]. 

**Function Used:** 

    replaced_words = [emoticon_library[words] if words in emoticon_library else words for words in words]

    new_phrase = ' '.join(replaced_words)

**Description:** This function goes through each word in the list. If the word is in the dictionary, It gets replaced by the emoticon. If not, the word stays the same. The 'join' part then puts all the words (and emoticons) back together into a single phrase, with spaces in between.

**Function Used:** *return new_phrase*

**Description:** This function sends back the new phrase with the emoticons in place of the original words.

    Example: emotify(“Make me smile”) 

    Output: Make me :)

    Example: emotify(“I am mad”)

    Output: I am >:(

## 3. UNPACKING LIST PROBLEM:

**Function Used:** *writeyourcodehere = [1, 2, 3, 4, 5, 6]*

**Description:** This function creates a list named 'writeyourcodehere' with six numbers in it.

**Function Used:** *first, *middle, last = writeyourcodehere*

**Description:** This function splits the list into three parts: 'first' takes the first number (1), '*middle' collects all the numbers in between (2, 3, 4, 5), and 'last' takes the last number (6).

**Function Used:** *print("Example:", "  ", "1st =", writeyourcodehere)*

**Description:** This function prints the value of the list 'writeyourcodehere', which is [1, 2, 3, 4, 5, 6], along with the message "Example:   1st =".

    Example:    lst = [1, 2, 3, 4, 5, 6] 

    Output:     first: 1    middle: [2,3,4,5]    last: 6
