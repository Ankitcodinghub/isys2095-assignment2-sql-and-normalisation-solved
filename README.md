# isys2095-assignment2-sql-and-normalisation-solved
**TO GET THIS SOLUTION VISIT:** [ISYS2095 Assignment2-SQL and Normalisation Solved](https://www.ankitcodinghub.com/product/isys2095-assignment2-sql-and-normalisation-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;69790&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ISYS2095 Assignment2-SQL and Normalisation Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
The objective of this assignment is to measure your understanding of SQL querying and your ability to apply your knowledge of normalisation to improve database designs.

<h1>Part A: SQL Programming</h1>
<ol>
<li>Write non-nested queries</li>
<li>Nested queries</li>
<li>Set Operators</li>
</ol>
<h1>Part B: Normalisation</h1>
<ol start="4">
<li>Identify design shortcomings and schema writing errors and suggesting improvements.</li>
</ol>
<h2>Assessment criteria</h2>
This assessment will measure your ability to:

<ul>
<li>Write SQL statements for retrieving data for specific user requirements,</li>
<li>Write various forms of SQL queries to demonstrate your understanding of the main concepts; and</li>
<li>Identify and understand design problems and suggesting improvements.</li>
</ul>
<h2>Course learning outcomes</h2>
This assessment is relevant to the following course learning outcomes:

<table width="649">
<tbody>
<tr>
<td width="66"><strong>CLO3 </strong></td>
<td width="583">Identify issues with, compare and justify relational database designs using the functional dependency concepts.</td>
</tr>
<tr>
<td width="66"><strong>CLO 4 </strong></td>
<td width="583">Apply SQL as a programming language to define database schemas and update database contents.</td>
</tr>
</tbody>
</table>
<strong>&nbsp;</strong>

<strong>Assessment details </strong>

<h1>Part A: SQL Programming</h1>
<h2>Preliminaries</h2>
Tasks 1, 2 and 3 utilise a (fictional) ‘research’ database instance with the following schema.

<table width="618">
<tbody>
<tr>
<td width="618">Department(DeptNum, Descrip, Instname, DeptName, State, Postcode)

Academic(AcNum, DeptNum*, FamName, GiveName, Initials, Title)

Paper(PaNum, Title)

Author(PaNum*, AcNum*)

Field(FieldNum, ID, Title)

Interest(FieldNum*, AcNum*, Descrip)
</td>
</tr>
</tbody>
</table>
The following must also be noted.

<ol>
<li>Each Academic belongs to one Department and is the Author of some (or no) Papers.</li>
<li>Each Paper has at least one Author, but there could be several Authors for a Paper.</li>
<li>Each Academic works in some (or no) Fields (i.e., research areas) described in the table Fields.</li>
<li>The Interest table stores data about the fields of research an academic is interested in and the Descrip attribute provides a more detailed description of an academic’s work.</li>
</ol>
The research database instance is available on Canvas under Modules-&gt;Sample Databases and Tools.

<strong>Important Requirements </strong>

For all the questions in Part A, it is essential that you note the following items.

<ol>
<li>Write only one query for each question. Providing more than one query per question will not earn any marks. Note that where nested queries are required, all the nested queries will be considered as one query. 2. The provided queries must be valid and free from syntactical errors.</li>
<li>In addition to providing the query, you must also provide a snapshot of the first 10 results of your query. The snapshot must also show the total number of results. A sample snapshot is provided below for your reference.s</li>
</ol>
&nbsp;

<h2>Task 1: Non-Nested Queries</h2>
Provide SQL queries that answer the following questions. The queries must be non-nested. Providing nested queries in this section will not receive any marks. Views are not to be used. The LIMIT clause is not to be used. Your SQL statements must be valid for SQLite Studio environment and free of any errors.

<strong>QUESTION 1.1 </strong>How many times the same department name is used across multiple institutions? Write a query that only lists department names and the number of times, named DeptNameCount, each unique name has been used across multiple institutions. Empty names are not meaningful and should be removed from the output. Sort the results by, firstly, the number of times of use of each name from large to small and, secondly, department names in alphabetical order.

<strong>QUESTION 1.2</strong> We would like to know if there are academics who are doctors, whose work description in one of their fields of interest (i.e. Interest.Descrip) contains the keyword “database”, and who also have more than one paper with titles containing the same keyword. Write a query that only lists academic title, first name, surname, and the number of papers containing the keyword “database” (named PaperCount) for such academics. Sort the results by, firstly, the number of papers from large to small and, secondly, surname and first name in alphabetical order.

&nbsp;

<h2>Task 2: Nested Queries</h2>
Provide nested SQL queries that answer the following questions. Providing non-nested queries in this section will not receive any marks. Views are not to be used. Set operators are not to be used. The LIMIT clause is not to be used.

<strong>Question 2.1</strong> Which departments in Queensland or Victoria do not have any academics? List the department number, institution name, department name, and state. <strong>Use IN or NOT IN</strong> as part of your query.

<strong>Question 2.2</strong> Which departments in Queensland or Victoria do not have any academics? List the department number, institution name, department name, and state. <strong>Use EXISTS or NOT EXISTS</strong> as part of your query.

<strong>Question 2.3</strong> Find the academic number and full name of academics who have written one or more papers with Adam Kilg. Do not include Adam Kilg in the results. Do not include duplicates. Sort the results by surname and then first name in alphabetical order.

<strong>Question 2.4</strong> Find and list the most common department name. The LIMIT clause must not be used.

&nbsp;

<h2>Task 3: Set Operators</h2>
In this section, all questions must be answered with only one query that uses one or more set operators. Writing multiple separate queries to answer one question will not receive any marks.

<strong>Question 3.1 </strong>List the academic number of academics who have five or more interests and yet have not authored any papers. Use a set operator as part of your query.

<strong>Question 3.2</strong> List the academic number of academics whose interests include all the interests of academic number 114. Do not report duplicates. Do not report academic 114. Use a set operator as part of your query.

&nbsp;

<h1>Part B: Normalisation</h1>
<h2>Task 4: Relational Database Design</h2>
The ER diagram shown in Figure 2 is designed according to the business rules for the operation of offering courses in a university and shows the interaction between courses, their offerings, staff assigned to deliver the course and staff’s contracts.

As a result of <strong>incorrect</strong> application of the mapping process, the ER diagram shown in Figure 2 is mapped into the following relations.

Course(<u>CCode</u>, Name)

CourseOffering(<u>CCode *</u>, <u>OCode</u>, Start Date, Weeks, Has Break)

Contract(<u>CNumber</u>, Start Date, End Date, Salary, Is Full Time, Is Casual, SNo*, Staff Name*)

Staff(<u>SNo</u>, Staff Name, Academic Level)

Lecture(<u>CCode*, OCode*, SNo*</u>)

Tutor(<u>CCode*, OCode*, SNo*</u>, Hours, Rate)

Coordinate(<u>CCode*, OCode*, SNo*</u>, Hours)

<strong>Question 4.1</strong> Complete the following tasks and show all your work.

4.1.1 For each of the relations written in the schema, write down all functional dependencies (FDs) shown in the schema. Do not write down trivial functional dependencies, such as CCode→CCode.

4.1.2 Compare the FDs created in step 5.1.1 with the business rules shown in Figure 2 and, if there are any mismatches between the two, correct the FDs and provide explanation for why the correction is made.

<strong>Question 4.2</strong> Complete the following tasks and show all your work.

4.2.1 Write down the highest normal form each of the relations shown in the schema is in. For each of the relations, state the reasons why it does not meet the next normal form requirements. This is not required if the relation is in 3NF.

4.2.2 Write the final and corrected schema as the result of your analysis in the previous sections.

<h3>Referencing guidelines</h3>
Use <a href="https://www.rmit.edu.au/library/study/referencing/referencing-guides-for-printing">RMIT Harvard</a> referencing style for this assessment.

You must acknowledge all the courses of information you have used in your assessments.

Refer to th<a href="https://www.lib.rmit.edu.au/easy-cite/">e RMIT Easy Cite</a> <a href="https://www.lib.rmit.edu.au/easy-cite/">r</a>eferencing tool to see examples and tips on how to reference in the appropriated style. You can also refer to the library referencing page for more tools such as EndNote, referencing tutorials and referencing guides for printing.

<h3>Submission format</h3>
You should submit one PDF document with all answers together. <strong>&nbsp;</strong>

You must use Lucidchart to work on Part 1 of your assignment. You may use Word or any other word processor to compile your submission. Use section titles to indicate which question you are answering. At the end, convert it into PDF format. Do not submit Word files. If that option is not available on your system there are free pdf converters online you can utilise (e.g. http://convertonlinefree.com/). <strong>&nbsp;</strong>

Submit the PDF file by the due date to the Canvas.

<h3>Academic integrity and plagiarism</h3>
Academic integrity is about honest presentation of your academic work. It means acknowledging the work of others while developing your own insights, knowledge, and ideas.

You should take extreme care that you have:

<ul>
<li>Acknowledged words, data, diagrams, models, frameworks and/or ideas of others you have quoted (i.e., directly copied), summarised, paraphrased, discussed, or mentioned in your assessment through the appropriate referencing methods.</li>
<li>Provided a reference list of the publication details so your reader can locate the source if necessary. This includes material taken from Internet sites.</li>
</ul>
If you do not acknowledge the sources of your material, you may be accused of plagiarism because you have passed off the work and ideas of another person without appropriate referencing, as if they were your own.

RMIT University treats plagiarism as a very serious offence constituting misconduct.

Plagiarism covers a variety of inappropriate behaviours, including:

<ul>
<li>Failure to properly document a source</li>
<li>Copyright material from the internet or databases</li>
<li>Collusion between students</li>
</ul>
For further information on our policies and procedures, please refer to the <a href="https://www.rmit.edu.au/students/student-essentials/rights-and-responsibilities/academic-integrity">University website.</a>

<h3>Penalties for late submissions</h3>
Late submissions of assignments will be penalised as follows. For 1 to 5 days late, a penalty of 10% (i.e. 10% out of total marks, not 10% out of your marks) per day. For assignments more than 5 days late, 100% penalty applies.

<h3>Assessment declaration</h3>
When you submit work electronically, you agree to the <a href="https://www.rmit.edu.au/students/student-essentials/assessment-and-exams/assessment/assessment-declaration">assessment declaration.</a>
