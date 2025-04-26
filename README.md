# cmsc216-project-2--document-manager-solved
**TO GET THIS SOLUTION VISIT:** [CMSC216 Project 2#-Document Manager Solved](https://www.ankitcodinghub.com/product/cmsc216-project-2-document-manager-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;86521&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMSC216 Project 2#-Document Manager Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 138px;">
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
            5/5 - (3 votes)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
In this project you will implement a document manager program. The program will allow us to add para- graphs, lines to paragraphs, to replace text and edit a document. There are two deadlines associated with the project. Those deadlines are:

2.1 Good Faith Attempt

Remember that you need to satisfy the good faith attempt for every project in order to pass the class (see syllabus). The good faith attempt information for this project (e.g., requirements and deadline) will be posted on the class web page later on.

2.2 Obtain the project files

To obtain the project files copy the folder project2 available in the 216 public directory to your 216 directory.

We have supplied three files for your use in this project: (a) document.h, which provides prototypes for the functions you must implement; (b) .submit, which is necessary to submit the project to the submit server; and a (c) Makefile, which will help you work on your project more efficiently.

3 Specifications 3.1 Use of a Makefile

Makefiles will be covered more in-depth in class, but instead of issuing gcc commands every time you want to recompile your program, you can simply execute “make” from the command line. Make recompiles the public tests provided. Without the makefile you can compile a public tests by compiling the test and document.c. For example, gcc public01.c document.c.

3.2 Functions

You must implement the functions described below. Notice that for 0 and -1 you should use the macros SUCCESS and FAILURE defined in document.h.

<ol>
<li>int init_document(Document *doc, const char *name)Initializes the document to be empty. An empty document is one with 0 paragraphs. The function will initialize the document’s name based on the provided parameter value. The function will return FAILURE if doc is NULL, name is NULL, or if the length of the name provided exceeds MAX_STR_SIZE; otherwise the function will return SUCCESS.</li>
<li>int reset_document(Document *doc)Sets the number of paragraphs to 0. The function returns FAILURE if doc is NULL; otherwise the func- tion will return SUCCESS.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
<ol start="3">
<li>int print_document(Document *doc)Prints the document’s name, number of paragraphs, followed by the paragraphs. Each paragraph is separated by a blank line. The following illustrates an example of printing a document whose title is ”Exercise Description” and has two paragraphs:
<pre>  Document name: "Exercise Description"
  Number of Paragraphs: 2
  First Paragraph, First line
  First Paragraph, Second line
</pre>
<pre>  First Paragraph, Third line
</pre>
<pre>  Second Paragraph, First line
  Second Paragraph, Second line
  Second Paragraph, Third line
</pre>
The function returns FAILURE if doc is NULL; otherwise the function will return SUCCESS.
</li>
<li>int add_paragraph_after(Document *doc, int paragraph_number)Adds a paragraph after the specified paragraph number. Paragraph numbers start at 1. If paragraph number is 0 the paragraph will be added at the beginning of the document. The function will return FAILURE

if doc is NULL, the document has the maximum number of paragraphs allowed (MAX PARAGRAPHS)

or if the paragraph number is larger than the number of paragraphs available; otherwise, the function will return SUCCESS.</li>
<li>int add_line_after(Document *doc, int paragraph_number, int line_number, const char *new_line)Adds a new line after the line with the specified line number. Line numbers start at 1. If the line number is 0, the line will be added at the beginning of the paragraph. The function will return FAILURE if doc is NULL, the paragraph number exceeds the number of paragraphs available, the paragraph already has the maximum number of lines allowed, the line number is larger than the available number of lines or if new line is NULL; otherwise, the function will return SUCCESS.</li>
<li>int get_number_lines_paragraph(Document *doc, int paragraph_number, int *number_of_lines)Returns the number of lines in a paragraph using the number of lines out parameter. The function will return FAILURE if doc or number of lines is NULL or if the paragraph number is larger than the number of paragraphs available; otherwise, the function will return SUCCESS.</li>
<li>int append_line(Document *doc, int paragraph_number, const char *new_line)

Appends a line to the specified paragraph. The conditions that make the add line after fail apply to thisfunction as well. The function will return SUCCESS if the line is appended.</li>
<li>int remove_line(Document *doc, int paragraph_number, int line_number)Removes the specified line from the paragraph. The function will return FAILURE if doc is NULL, the paragraph number exceeds the number of paragraphs available or line number is larger than the number of lines in the paragraph; otherwise the function will return SUCCESS.</li>
<li>int load_document(Document *doc, char data[][MAX_STR_SIZE + 1], int data_lines)The function will add the first data lines number of lines from the data array to the document. An empty string in the array will create a new paragraph. Notice that by default the function will create the first paragraph. You can assume that if data lines is different than 0, the appropriate number of lines will be present in the data array. The function will return FAILURE if doc is NULL, data is NULL or data lines is 0; otherwise the function will return SUCCESS.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
<ol start="10">
<li>int replace_text(Document *doc, const char *target, const char *replacement)The function will replace the text target with the text replacement everywhere it appears in the docu- ment. You can assume the replacement will not generate a line that exceeds the maximum line length; also you can assume the target will not be the empty string.
The function will return FAILURE if doc, target or replacement are NULL; otherwise the function will return SUCCESS.
</li>
<li>int highlight_text(Document *doc, const char *target)The function will highlight the text associated with target everywhere it appears in the document by surrounding the text with the strings HIGHLIGHT START STR and HIGHLIGHT END STR (see doc- ument.h). You can assume the highlighting will not exceed the maximum line length; also you can assume the target will not be the empty string. The function will return FAILURE if doc or target are NULL; otherwise the function will return SUCCESS.</li>
<li>int remove_text(Document *doc, const char *target)The function will remove the text target everywhere it appears in the document. You can assume the tar- get will not be the empty string. The function will return FAILURE if doc or target are NULL; otherwise the function will return SUCCESS.</li>
</ol>
3.3 Important Points and Hints

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
<div class="column">
<ol>
<li>You must create a file named document.c that includes the file document.h.</li>
<li>You must use the constants defined in document.h (e.g. MAX_PARAGRAPHS_LINES). Our tests will define different values for these constants.</li>
<li>IMPORTANT: Data should only be allocated statically. You may not use dynamic memory allocation functions (malloc(), calloc()) etc. If you do, you will lose all the points associated with public, re- lease, and secret tests.</li>
<li>If you are having trouble with your code read the debugging guide available at:
<pre>  http://www.cs.umd.edu/~nelson/classes/resources/cdebugging/
</pre>
</li>
<li>Do not modify document.h.</li>
<li>Run valgrind as you develop your code. It will help you identify memory problems</li>
</ol>
</div>
</div>
</div>
