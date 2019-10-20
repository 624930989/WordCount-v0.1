# WordCount-v0.1
##introduce:<br>
这是一段关于提取文本后，对文本内字符、句子、单词、注释句、空行、代码行统计的代码<br>
##use:<br>
在Python IDLE上运行这段代码，输入相应命令得到不同统计功能：<br>
命令模式： wc.exe [参数] [文件名]<br>
例：wc.exe -c file.txt 统计字符数<br>
-c：字符数； -w：单词数 ；-sen：句子数 ；-e：注释行数 ；-n：空行数 ；-d行数：代码。<br>
##example
data.txt：<br>
Chinese President Xi Jinping on Wednesday met with former New Zealand Prime Minister John Key at the Great Hall of the People in Beijing.<br>
***123<br>
Noting that the situation in the world today has undergone profound and complicated changes, Xi said China has become even more willing to cooperate with other countries under the new situation.<br>
***456<br>
China sticks to the path of peaceful development, said Xi, adding that China's door "will be open even wider to the world."<br>
Do:<br>
请输入您要统计的文件命令：wc.exe -e data.txt<br>
文件data.txt总共有2行注释行<br>
>>> <br>
请输入您要统计的文件命令：wc.exe -d data.txt
文件data.txt总共有3行代码行<br>
