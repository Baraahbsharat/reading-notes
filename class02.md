<h2> Text </h2>

<p>Tags added to the content in html document to provide additional information, this is known as markup, there are two types of them, structural markup that describe the headings and paragraphs and semantic markup that add extra information without changing the page's structure. The following list contain examples of these tags with their meanings:

h1 , h2 ...h6  are headings with different size, the largest one is h1 
< p  >  used to create a paragraph and b inside opening and closing tages make the character bold and we can use  b inside angled bracket to visually present a section in different way
< i > < / i >  make the character italic and i inside angled bracket used to present the section in the text that should be said in a different way. 
< sup > contain superscript characters while subinside angled bracket  contain subscript characters
< br /> used to add a line break within a paragraph 
< hr /> used to add horizontal rule between sections
< strong > indicates that the content has strong important
< em > indicates emphasis that minimal changes the meaning of the statement
< blockquote >  used for long quote
< q > used for short quote 
< cite > refers to the location of the citation
< dfn > refers to detention of a new term
< s > indicates something that is no longer accurate or relevant
</p>
<h2> CSS </h2>
<p> To understand the CSS we must assume that there is an invisible box around the HTML elements and  css rule determine  the style of these element, it consist of a selector (e.g. universal selector *{} that apply the style to all elements and type selector h1,h2 {} that matches element names)  and a declaration that wrote inside a curly brackets and consist of property and a value. We can use external css using <link> element which lives inside the head, in which href specifies the path to the css file and type attribute determine the type while rel specify the relationship between HTML page the file it is linked to. Also, we can add the css style inside the HTML page using <style> that lives inside the head.Writing css rules in a separate sheet had many advantages because there is no need to repeat the same code more than one time, we can change one css file to update all pages.</p>
<h2> Javascript </h2>

<p> JavascriptA script store the bits of information inside variables, we can change these information, declare the variable means creating it and giving it a name using a var as a keyword, after that we assign a value for that variable. We can store any type of information inside the variable which might be numeric ( any number ) or string ( any character inside ") or boolean which might be true or false.  The name of the variable must start with a letter and it can contain letters or numbers or dollar sign, it cannot be keywords and its case sensitive, it must indicate the kind of the information, if it consist of more than one word every word after the first one should start with capital letter. Arrays variables stores a list of values, we can access the values inside it only if they are a numbered list that start from 0. Expression result in a single value and rely on operators that might be mathematical, arithmetic or string.Decision consist of expression which is evaluated and give a value, on the other had a conditional statement which says what to do in a given  situation. We can evaluate a situation by comparing one value in the script to what we expect to be, the result will true or false, the operators include == equal to, != not equal to, === strict equal to, === strict not equal to, > greater than, < less than.Logical operators used to compare several comparison operators ( e.g. && AND, || OR, ! NOT). If statement evaluate a condition if it is true the code block executed, if .. else statement the first code executed while if it is false the second code block executed. Type coercion means the Javascript able to convert data type behind the scene to complete an operation. Loops check the condition and it runs the code as long the result is true (e.g. For, While, Do while), For loop use a counter that could be initialization, condition or update, switch statement compare a value to a predictive one, it can suggest default option of it doesn't  match.</p>