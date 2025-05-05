# comp5421-assignment-2-custom-string-tokenzier-solved
**TO GET THIS SOLUTION VISIT:** [COMP5421 Assignment 2-Custom String Tokenzier Solved](https://www.ankitcodinghub.com/product/comp5421-assignment-2-custom-string-tokenzier-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;99986&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP5421 Assignment 2-Custom String Tokenzier Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

1 Objectives

In this assignment, you will redo Assignment 1 without getting involved with dynamic storage management. A major goal in this and the following assignments is to encourage you to leverage the C++ standard and popular libraries to do the work for you so you don’t ever have to reinvent the wheel.

Although assignment 1 can be ideally and conveniently implemented using associative containers such as std::map and std::set, this assignment requires that class IntList be replaced with std::vector&lt;int&gt;, class TList with std::list&lt;Token&gt;, and C-style text processing with std::string.

</div>
</div>
<div class="layoutArea">
<div class="column">
Token

1 1

std::list&lt;Token&gt; *

1

Tokenizer

</div>
<div class="column">
1 1 std::vector&lt;int&gt;

</div>
</div>
<div class="layoutArea">
<div class="column">
TokenizerApp

</div>
<div class="column">
1 1..*

</div>
</div>
<div class="layoutArea">
<div class="column">
In addition to implementing the bulk of the work in this assignment, the vector&lt;int&gt; and list&lt;Token&gt; classes also provide plenty opportunities for us to learn about container iterators, which we will use in class Tokenizer to iterate through and modify the container elements.

Class Tokenizer provides the functionalities of A1’s TList class that are not directly supported by std::list&lt;Token&gt;, plus a few more functionalities.

2 String tokens

In assignment 1, a string token is defined as a sequence of contiguous characters excluding

white-space characters such as space, tab, and newline characters.

Generalizing that definition in this assignment, we define a string token to be a sequence of

contiguous characters excluding those specified in a user defined set of separator characters.

The separator characters are those that we do not want in a token in this assignment, and they are represented using a std::string object. For example, the separators in assignment 1 can be defined as “\n\t\0 “; that is, the new line, tab, null, and blank characters separate tokens in a text.

</div>
</div>
<div class="layoutArea">
<div class="column">
Assignment 2, Summer 2021 page 1 of 14

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
3 Class TokenizerApp

TokenizerApp is the name of a C++ file that contains the main function, and possibly other functions, to test drive the functionality of a Tokenizer object. It is a simple menu-driven program that displays a menu of options for the user to choose from:

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Enter the name of an input file of text: input text file.txt Enter the seperator characters: ;. ,?!”=’:

Menu ======

<pre>    A - Print all input lines
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>P - Print indexed tokens
F - Print tokens sorted on frequency
L - Print tokens sorted on length
S - Search
X - Exit
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Enter your choice:
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
1 2 3 4 5 6 7 8 9

10 11 12

12 13 14 15 16 17 18 19 20 21 22 23 24 25 26 27 28 29 30 31 32 33 34

</div>
<div class="column">
3.1 Option A (or a)

Prints all of the input lines:

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre> Enter your choice: a
</pre>
<pre>1: Do you like green eggs and ham?
2:
3: I do not like them, Sam-I-am.
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>4: I do not like green eggs and ham!
5:
6: Would you like them here or there?
7:
</pre>
<pre>8: I would not like them here or there.
9: I would not like them anywhere.
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>10:
11: I do so like green eggs and ham!
12: Thank you! Thank you,
13: Sam-I-am!
</pre>
Menu

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>======
  A - Print all input lines
  P - Print indexed tokens
  F - Print tokens sorted on frequency
  L - Print tokens sorted on length
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
S – Search

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Assignment 2, Summer 2021 page 2 of 14

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
35 36

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>  X - Exit
Enter your choice:
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
3.2 Option P (or p)

Prints all tokens in alphabetic order, similar to that in assignment 1, with one noticeable difference: the numbers inside the parentheses, each indicating the frequency of the corresponding token in the input file.

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Enter your choice: p
</pre>
<pre>          and (3) 1 4 11
     anywhere (1) 9
</pre>
Do (4) 1 3 4 11

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre> eggs (3) 1 4 11
green (3) 1 4 11
  ham (3) 1 4 11
</pre>
<pre> here (2) 6 8
    I (5) 3 4 8 9 11
</pre>
<pre> like (7) 1 3 4 6 8 9 11
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>     not (4) 3 4 8 9
      or (2) 6 8
</pre>
<pre>Sam-I-am (2) 3 13
      so (1) 11
   Thank (2) 12
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre> them (4) 3 6 8 9
there (2) 6 8
Would (3) 6 8 9
</pre>
you (4) 1 6 12

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Menu ======

<pre>  A - Print all input lines
  P - Print indexed tokens
  F - Print tokens sorted on frequency
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>  L - Print tokens sorted on length
  S - Search
  X - Exit
</pre>
<pre>Enter your choice:
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
36 37 38 39 40 41 42 43 44 45 46 47 48 49 50 51 52 53 54 55 56 57 58 59 60 61 62 63 64 65 66

</div>
</div>
<div class="layoutArea">
<div class="column">
Notice that the user supplied separator characters ;.␣,?!”=’: defines a very limited number of separators, allowing, for example, the strings 123 and }1+2*3{ as tokens. For a C++ source file, the user might input something like ;.␣,?!”=’:|{}[]()&amp;+-*%$#!~&gt;^&lt;/\ for the separator characters.

</div>
</div>
<div class="layoutArea">
<div class="column">
Assignment 2, Summer 2021 page 3 of 14

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
3.3 Option F (or f)

Prints the tokens sorted in the ascending order of their frequencies in the input file:

66 67 68 69 70 71 72 73 74 75 76 77 78 79 80 81 82 83 84 85 86 87 88 89 90 91 92 93 94 95

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Enter your choice: F
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>anywhere (1) 9
      so (1) 11
</pre>
<pre>    here (2) 6 8
      or (2) 6 8
</pre>
<pre>Sam-I-am (2) 3 13
   Thank (2) 12
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>there (2) 6 8
  and (3) 1 4 11
 eggs (3) 1 4 11
green (3) 1 4 11
  ham (3) 1 4 11
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Would (3) 6 8 9
   Do (4) 1 3 4 11
</pre>
<pre>  not (4) 3 4 8 9
 them (4) 3 6 8 9
</pre>
<pre>  you (4) 1 6 12
    I (5) 3 4 8 9 11
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Menu ======

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>like (7) 1 3 4 6 8 9 11
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>A - Print all input lines
P - Print indexed tokens
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>  F - Print tokens sorted on frequency
  L - Print tokens sorted on length
  S - Search
  X - Exit
</pre>
<pre>Enter your choice:
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Knowing that sorting a linked list in general is not a trivial task, let alone sorting the list efficiently, we are happy to know that std::list&lt;Token&gt; can sort the list for us if we tell it how to compare two tokens.

See here for a quick example.

</div>
</div>
<div class="layoutArea">
<div class="column">
Assignment 2, Summer 2021 page 4 of 14

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
3.4 Option L (or L)

Prints the tokens sorted on the length of each string tokens, with tokens of equal lengths sorted alphabetically.

95 96 97 98 99

100 101 102 103 104 105 106 107 108 109 110 111 112 113 114 115 116 117 118 119 120 121 122 123 124

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Enter your choice: l
            I (5) 3 4 8 9 11
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre> Do (4) 1 3 4 11
 or (2) 6 8
 so (1) 11
</pre>
<pre>and (3) 1 4 11
ham (3) 1 4 11
not (4) 3 4 8 9
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre> you (4) 1 6 12
eggs (3) 1 4 11
here (2) 6 8
like (7) 1 3 4 6 8 9 11
them (4) 3 6 8 9
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>   Thank (2) 12
   Would (3) 6 8 9
   green (3) 1 4 11
   there (2) 6 8
</pre>
<pre>Sam-I-am (2) 3 13
anywhere (1) 9
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Menu ======

<pre>  A - Print all input lines
  P - Print indexed tokens
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>  F - Print tokens sorted on frequency
  L - Print tokens sorted on length
  S - Search
  X - Exit
</pre>
<pre>Enter your choice:
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Again, the std::list&lt;Token&gt; class can sort the list for us as long as we tell it how to compare two tokens.

</div>
</div>
<div class="layoutArea">
<div class="column">
Assignment 2, Summer 2021 page 5 of 14

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
124 125 126 127 128 129 130 131 132 133 134 135 136 137 138 139 140 141 142 143 144 145 146 147 148 149 150 151 152 153 154

</div>
</div>
<div class="layoutArea">
<div class="column">
3.5 Option P (or p), Again

Let us note that printing the tokens sorted on some attributes must not disturb the order of the tokens in the original indexed list. In other words, selecting option P now should print the original indexed list:

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Enter your choice: p
</pre>
<pre>          and (3) 1 4 11
     anywhere (1) 9
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>   Do (4) 1 3 4 11
 eggs (3) 1 4 11
green (3) 1 4 11
  ham (3) 1 4 11
</pre>
<pre> here (2) 6 8
    I (5) 3 4 8 9 11
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>    like (7) 1 3 4 6 8 9 11
     not (4) 3 4 8 9
</pre>
<pre>      or (2) 6 8
Sam-I-am (2) 3 13
</pre>
so (1) 11

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Thank (2) 12
 them (4) 3 6 8 9
</pre>
<pre>there (2) 6 8
Would (3) 6 8 9
</pre>
you (4) 1 6 12

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Menu ======

<pre>  A - Print all input lines
  P - Print indexed tokens
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>  F - Print tokens sorted on frequency
  L - Print tokens sorted on length
  S - Search
  X - Exit
</pre>
<pre>Enter your choice:
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Assignment 2, Summer 2021 page 6 of 14

</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
3.6 Option S (or s)

Prompts the user for a token to search for; if found, prints the input lines on which the token appears; otherwise, displays the message “token not found”.

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>  Enter your choice: s
Enter the text to search for: you
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre> 1: Do you like green eggs and ham?
</pre>
<pre> 6: Would you like them here or there?
12: Thank you! Thank you,
</pre>
Menu

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>======
  A - Print all input lines
  P - Print indexed tokens
  F - Print tokens sorted on frequency
  L - Print tokens sorted on length
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
S – Search

<pre>  X - Exit
Enter your choice:
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
154 155 156 157 158 159 160 161 162 163 164 165 166 167 168 169 170

170 171 172 173

</div>
<div class="column">
3.7 Option X (or x)

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>  Enter your choice: x
Thank you for trying my program.
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Goodbye.

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Assignment 2, Summer 2021 page 7 of 14

</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="layoutArea">
<div class="column">
4 Class Token 4.1 Representation

<pre>    string theText{};
    vector&lt;size_t&gt; theLineNumbers{}; // this token’s list of (non-negative) line numbers
    size_t theFrequency{1};          // the frequency of this token in the input file
</pre>
We choose size t over int as the type of the line numbers, because in this application we only deal non-negative line numbers and size t represents non-negative (unsigned) integers.

The size of theLineNumbers is at least 1, because a string token must reside on some line in the input file, and every input line has a number ≥ 1.

Note that the size of theLineNumbers may not necessarily represt the frequency because a string token can appear multiple times on a single input line.

4.2 Normal constructors

This is the only normal (non-special) constructor of the class; it sets the frequency to 1, and initializes the text and line number of the token being constructed with the corresponding supplied argument values.

<pre>    Token(string text, size_t linenum);         // a normal constructor
</pre>
4.3 Default constructor

Since a token cannot exist without a text and associated line number, we decide to disallow default construction; so we make our decision visible to both the human reader as well as the compiler by explicitly declaring the default constructor deleted.

8 9

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>class Token
{
private:
</pre>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
1 2 3 4 5 6

</div>
<div class="column">
<pre>// the text of this token
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
7

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>public:
   Token()                             = delete; // disable default construction
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
Note that disabling the default constructor of a class, in turn, disables creating an array of objects of that class. That is fine in this application, but it may not be an option in another application, forcing us to define a default Token object.

</div>
</div>
<div class="layoutArea">
<div class="column">
Assignment 2, Summer 2021 page 8 of 14

</div>
</div>
</div>
<div class="page" title="Page 9">
<div class="layoutArea">
<div class="column">
4.4 Other Special Member Functions: The Big Five

Modern C++ programming style encourages that these members be explicitly either defined, deleted, or defaulted. Since Token is not involved directly in dynamic resource allocation, the compiler-generated versions of these members are most appropriate for Token objects.

10 11 12 13 14 15 16 17

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>// the big five: three choices (either default, delete, or define);
// avoid relying on implicit generation of special member functions
Token&amp; operator=(const Token&amp; rhs)  = default; // copy op=
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Token&amp; operator=(Token&amp;&amp; rhs)
Token(const Token&amp; source)
Token(Token&amp;&amp; source)
~Token()
</pre>
</div>
<div class="column">
<pre>= default; // move op=
= default; // copy ctor
= default; // move ctor
= default; // dtor
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Consequently,

􏰀 copy/move constructors copy/move the source token’s theFrequency, theText, and theLineNumbers members to theFrequency, theText, and theLineNumbers of the Token object being constructed. Note that these data members in turn propagate and apply copy/move construction internally to their respective members, recursively.

􏰀 copy/move assignments copy/move-assign the right-hand side token’s theFrequency, theText, and theLineNumbers members to the left-hand side token theFrequency, theText, and theLineNumbers members. Note that the data members in turn propagate and apply the copy/move assignment internally to their respective members, recursively.

4.5 Comparison operations

In this assignment we use case insensitive comparison to compare the text of the tokens.

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>// comparison member function (returns -1, 0, +1, as in A1)
int compareIgnoreCase(const Token&amp; t)  const;   // case insensitive comparison
</pre>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
18 19 20

</div>
</div>
<div class="layoutArea">
<div class="column">
See Here for an example of a case insensitive comparison function.

</div>
</div>
<div class="layoutArea">
<div class="column">
Assignment 2, Summer 2021 page 9 of 14

</div>
</div>
</div>
<div class="page" title="Page 10">
<div class="layoutArea">
<div class="column">
4.6 Other Self-Explanatory Operations

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>// getter members; each is doubly safe!
// since each is const, the invoking object remains intact, and,
// returning by value, each adheres to the principle of information hiding
string      getTheText()              const;
vector&lt;size_t&gt; getTheLineNumberList() const;
</pre>
</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
21 22 23 24 25 26 27 28 29 30 31 32 33 34 35

</div>
<div class="column">
<pre>size_t
size_t
</pre>
</div>
<div class="column">
<pre>getFrequency()
getLineNumber(size_t = 1) const; // line number is 1-based
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
<div class="column">
<pre>                                             // to provide user friendly interface
void pushBackLineNumber(size_t lineNum);  // append the suppled line number
</pre>
Class Tokenizer

</div>
</div>
<div class="layoutArea">
<div class="column">
A Tokenizer object provides a minimal set of services, allowing a typical menu-driven program to produce an interactive session as shown above.

5.1 Representation

</div>
</div>
<div class="layoutArea">
<div class="column">
const;

</div>
</div>
<div class="section">
<div class="layoutArea">
<div class="column">
<pre>   void print(ostream&amp; sout) const;          // print this token to sout
};
</pre>
<pre>#endif
ostream&amp; operator&lt;&lt;(ostream&amp; sout, const Token&amp; arr);
</pre>
</div>
</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>class Tokenizer
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
{ private:

<pre>   const string theSeparators;
   list&lt;Token&gt; theTokenList;
   vector&lt;string&gt; theLines;
</pre>
</div>
<div class="column">
<pre>// the separator characters in a std::string
// the list of tokens managed by this tokenizer
// the lines in the input file
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
1 2 3 4 5 6

</div>
</div>
<div class="layoutArea">
<div class="column">
5.2 Default constructor

Since a Tokenizer cannot exist without an input file of text, we decide to disallow default construction; so we make our decision visible to both the human reader as well as the compiler by explicitly declaring the default constructor deleted.

</div>
</div>
<div class="layoutArea">
<div class="column">
7 8

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>public:
   Tokenizer()    = delete;      // disable default constructor
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
Assignment 2, Summer 2021 page 10 of 14

</div>
</div>
</div>
<div class="page" title="Page 11">
<div class="layoutArea">
<div class="column">
5.3 Normal constructor

Supplied with the name of an input file of text and with a string of separator characters, this constructor extracts the lines from the input file one line at at a time, delegating the pro- cess of extracting the tokens in a line and keeping track of the associated line numbers to ProcessTokensInLine(text, line number), a private facilitator member function.

<pre>     Tokenizer(const string&amp; filename, const string&amp; separators);
</pre>
5.4 Other Special Member Functions: The Big Five

Modern C++ programming style encourages that these members be explicitly either defined, deleted, or defaulted. Since our class is not involved directly in dynamic resource allocation, the compiler-generated versions of these members are most appropriate to use.

10 11 12 13 14

</div>
</div>
<div class="layoutArea">
<div class="column">
9

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>~Tokenizer()   = default;     // dtor
</pre>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>Tokenizer(const Tokenizer&amp;)   = default; // copy ctor
Tokenizer(Tokenizer&amp;&amp;)        = default; // move ctor
Tokenizer&amp; operator=(const Tokenizer&amp;) = default; // copy op=
Tokenizer&amp; operator=(Tokenizer&amp;&amp;)      = default; // move op=
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
5.5 Private Facilitators 5.5.1 15

16

Outsources the process of extracting the tokens in line and inserting them each into the token list to two private facilitator (helper) member functions:

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
private:

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<pre>void ProcessTokensInLine(const string&amp; line, size_t linenum);
</pre>
</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
1. 2.

5.5.2 17

returning them all in a std::vector of std::strings.

Requirement Yourimplementationofthismemberfunctionmayonlyusethestd::string class, which offers a useful set of string operations, including substr, find first of, find first not of, and a few more.

</div>
</div>
<div class="layoutArea">
<div class="column">
Toextractsthetokensfromline,itdelegatestomemberfunctionsplitLineIntoTokens, which in turn returns the extracted tokens in a std::vector&lt;string&gt;, say, vec.

To turn the string tokens in vec into Token objects and to store the resulting objects in the token list, it delegates to the member function insert, one vec element at time.

</div>
</div>
<div class="layoutArea">
<div class="column">
vector&lt;string&gt; splitLineIntoTokens(const string&amp; line) const;

Using the separator characters, it splits the given line of text into string tokens, storing and

</div>
</div>
<div class="layoutArea">
<div class="column">
Assignment 2, Summer 2021 page 11 of 14

</div>
</div>
</div>
<div class="page" title="Page 12">
<div class="layoutArea">
<div class="column">
5.5.3 18 void insert(string text, size_t linenum);

This function is equivalent to the addSorted member function in the TList class in A1.

Specifically, it first creates a Token object using the supplied text and line number; it then compares that object against the Token objects in the token list, which are already sorted in ascending order; if found, it updates the number list of that object; otherwise, it inserts the newly created Token object into the token list.

Requirement To scan and to insert into the token list, your implementation of this member function must use list&lt;Token&gt;::iterators.

5.5.4 19 vector&lt;size_t&gt; search(const string&amp; str)const;

Searches the token list for a token object whose text is equal (case insensitive) to that of the given string str. If found, it returns a copy of that object’s line number list; otherwise, it returns an empty number list.

5.5.5 20 void printSomeInputLines(const vector&lt;size_t&gt;&amp; vec)const;

Given a std::vector of line numbers, prints the input lines corresponding to those line

numbers.

5.6 Public Interface 5.6.1 21

22

Searches the token list for a token object whose text is the same as the given string str; if found, it prints the input lines that contain str.

5.6.2 23 24

Prints all input lines.

5.6.3 25 26

Prints the token list to the given output stream sout. 5.6.4 27

28

Prints the token list sorted on frequencies of the tokens in the input file.

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>public:
   void searchAndPrint(string&amp; str)const;
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>public:
   void printAllInputLines()const;
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>public:
   void print(ostream&amp; sout)const;
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>public:
   void sortOnFrequecy()const;
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
Assignment 2, Summer 2021 page 12 of 14

</div>
</div>
</div>
<div class="page" title="Page 13">
<div class="layoutArea">
<div class="column">
Requirements

<ol>
<li>Since the token list must remain intact, we need to copy it into another linear sequence and then sort that linear sequence.
Our options here are limited to std::list, std::vector, and std::forward list.

Familiar with std::list and std::vector, we take advantage of this opportunity to use std::forward list, which already comes equipped with a sort member fuction ( std::vector does not).
</li>
<li>This member function must use std::forward list’s sort member.

(Hint: simply implement the compareFrequency function given in 5.7.3 below and pass it

to std::forward list’s sort member function as the argument.)
</li>
</ol>
5.6.5 29

30

Prints the token list sorted on the text of the tokens..

Requirements

Similar to 5.6.4 above, copy the token list into a std::forward list and then sort that forward list using std::forward list’s own sort member function.

This member function must use std::forward list’s sort member.

(Hint: simply implement the compareLength function given in 5.7.2 below and pass it to

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>   void sortOnTokenLength()const;
};
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
1. 2.

</div>
</div>
<div class="layoutArea">
<div class="column">
std::forward list’s sort member function.) Free (top-level) helper functions

</div>
</div>
<div class="layoutArea">
<div class="column">
5.7

5.7.1 31 ostream&amp; operator&lt;&lt;(ostream&amp;, const Tokenizer&amp;);

</div>
</div>
<div class="layoutArea">
<div class="column">
Writes a given token to a given stream

5.7.2 32 bool compareLength(const Token&amp; t1, const Token&amp; t2);

Determines whether t1 is less than t2, comparing their lengths; if they are of equal length, then determines whether t1 is less than t2, alphabetically (using std::string’s operator&lt;).

5.7.3 33 bool compareFrequency(const Token&amp; t1, const Token&amp; t2); Comparing the frequencies of t1 and t2, determines whether t1 is less than t2.

</div>
</div>
<div class="layoutArea">
<div class="column">
Assignment 2, Summer 2021 page 13 of 14

</div>
</div>
</div>
<div class="page" title="Page 14">
<div class="layoutArea">
<div class="column">
6 Deliverables

Create a a new folder that contains the files listed below, then compress (zip) your folder, and submit the compressed (zipped) folder as instructed in the course outline.

</div>
</div>
<div class="layoutArea">
<div class="column">
7

</div>
</div>
<div class="layoutArea">
<div class="column">
1. 2. 3. 4.

5.

</div>
<div class="column">
Header files: Token.h, and Tokenizer.h

Implementation files: Token.cpp, Tokenizer.cpp, and TokenizerApp.cpp

Input file input file A1.txt

Output file output file A1.txt (copy output from cmd window and paste it into this file)

A README.txt text file (see the course outline). Grading scheme

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Functionality

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
􏰀 Correctness of execution of your program,

􏰀 Proper implementation of all specified requirements, 􏰀 Efficiency

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
60%

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
OOP style

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
<ul>
<li>􏰀 &nbsp;Encapsulating only the necessary data inside your objects,</li>
<li>􏰀 &nbsp;Information hiding,</li>
<li>􏰀 &nbsp;Proper use of C++ constructs and facilities.</li>
<li>􏰀 &nbsp;No global variables</li>
<li>􏰀 &nbsp;No use of the operator delete.</li>
<li>􏰀 &nbsp;No C-style memory functions such as malloc, alloc, realloc,
free, etc.
</li>
</ul>
</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
20%

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Documentation

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
􏰀 Description of purpose of program,

􏰀 Javadoc comment style for all methods and fields, 􏰀 Comments for non-trivial code segments

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
10%

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Presentation

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
􏰀 Format, clarity, completeness of output, 􏰀 User friendly interface

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
5%

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Code readability

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Meaningful identifiers, indentation, spacing

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
5%

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Assignment 2, Summer 2021 page 14 of 14

</div>
</div>
</div>
