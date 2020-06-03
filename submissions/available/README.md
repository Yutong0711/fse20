# Available

Placed on a publicly accessible archival repository. A DOI with a unique identifier for the object is provided. 

# ReadMe

This artifact consists of three files:

1) Heuristic Linguistic Pattern Set.csv: 
On tab "Saturated HLP Set", we listed the 80 HLP we derived from dataset 1.  Column "Category"  lists the type of each pattern. Namely, LEX represents lexical pattern, STR represents structural pattern, SEM represents semantic pattern, and PRF represents profiling pattern.  Column "Name" is a descriptive name we give to each pattern. Column "Definition" defines the detailed content in each pattern.
The following tabs recorded the intermediate results of pattern derivation iterations, numbered from Iter. 1 to Iter. 13. It shows how each pattern is derived from dataset 1.

2) Sentence-Level Manual Tagging.csv:
This is the sentence-level  manual tagging result of Dataset-1 (for HLP derivation), Dataset-2 (for homologous evaluation), and Dataset-3 (for heterologous evaluation). 
The first column, "Key", shows the ID of  a Jira issue report.  The second column, "Number", is the order of the sentences in each issue report. The third column shows the content in the sentence.  The fourth column, "PerfTag" is the manual tagging decision---"no" means not related to performance, and "yes" means related to performance. The fifth column  ” Reason“ records the determining information for a sentence to be tagged as "yes".

3) Issue-Level Manual Tagging.csv:
These two spreadsheets record the issue-level manual tagging of Dataset-2 (for homologous evaluation) and Dataset-3 (for heterologous evaluation). Note that Dataset-1 are all performance issues, tagged by the developers. On each tab, the first column, "Key", records the ID of  an issue in Jira tracking system.  The second column records the text of the issue description report. The third column records  manual tag of the issue is performance-related, or not. The fourth column records the comments that explain why the issue should be tagged as performance-related. 


