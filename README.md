# my_validation

The My_validation replication kit was developed out of the necessity to validate the ATDCodeAnalyzer (https://github.com/mining-software-repositories/cassandra). The concept behind it is to employ SATD (Self-Admitted Technical Debt) instances recorded in commits and issues to verify if Critical Files (identified by the ATDCodeAnalyzer) are present in issues associated with SATD, and whether these issues indicate architectural issues and technical debt.

Here, you will find the following files:

**My_Commits_and_my_Issues_from_Cassandra.ipynb** - A Google Colab notebook that contains all Python scripts, methods, and datasets required to validate the ATDCodeAnalyzer method.

**commits_com_muitos_arquivos_moficiados.xlsx** - A spreadsheet containing remarkable commits with many modified files and many lines modified per commit. 

**issues_in_commits_detailed_muitos_arquivos.xlsx** - A spreadsheet containing the issues that appear in remarkable commits.

**inspection_process.md** - A markdown file that provides an explanation of the inspection process assisted by ChatGPT using prompt engineering method.

**my_issues.zip** - A zip file containing all issues to be inspected.

**my_inspection.zip** - A zip file that holds the results of the inspection for checking architectural issues and technical debt.

**inspecao_manual.xlsx** - A spreadsheet containing the results of manual inspections.

**inspecao_by_chatgpt.xlsx** - A spreadsheet containing the results of manual inspections.

**inspecao_completa.xlsx** - A spreadsheet containing the results of inspections (merge of inspecao_manual and inspecao_by_chatgpt).
