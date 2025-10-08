# a3_CLI

MiniSearch Project



In this assignment, all the main search logic is inside the minisearch package, there are separate files for indexing, and for the query parsing, and plugins, also the folder plugins has the tokenizers, and more can be added later. In the I/O part (inputs and printing) is only in cli.py, this file just asks the user questions and shows results, but does not do the real search work, and the logic part (building index, parsing query, evaluating results) is in other modules like indexer.py and query.py. And in this way, the program is easier to test and change, because the search logic is not mixed together with user input or printing.

How to Run:
Open terminal in the project folder --> then run this command:    python -m minisearch.cli  -->   Then answer the program questions (yes/no, tokenizer, mode, query). --> example/result I got after running:


PS C:\Users\MSI\PycharmProjects\pythonProject5\MiniSearchProject> python -m minisearch.cli
Use demo corpus? (y/n):
y
Tokenizer (blank=basic):

Mode (plain/simple):
plain
Query:
python AND course
Limit:
5
plugins: basic
hits: 1
results:
1



