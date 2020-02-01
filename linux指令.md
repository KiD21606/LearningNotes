# 參考資料：[莫煩](https://www.youtube.com/playlist?list=PLXO45tsB95cIiLTNZu-v3Y-xotBAjtH2x)
指令 | 功能 | 範例 | 效果
---  | --- |  --- | --- 




# 指令
指令 | 功能 
---  | --- 
cd | 資料夾間移動
ls | 列出當前目錄下的文件
touch | 創建文件
cp | 複製
clear | 清空螢幕內容
mv | 移動
mkdir | 建立資料夾
rmdir | 移除資料夾
rm | 移除檔案/資料夾


# 範例


指令 | 功能 | 範例 | 效果
---  | --- |  --- | --- 
__cd__  | __資料夾間移動__ 
| | | cd Folder1 | 移動到當前目錄下的Folder1
| | | cd 絕對位置 | 移動到絕對路徑
| | | cd .. | 移動到上一層目錄
| | | cd -  | 返回上一個所在目錄
__ls__  | __列出當前目錄下的文件__ 
| | | ls | 列出當前目錄下的文件
| | | ls -l | 列出文件的詳細訊息(l=long)
| | | ls -a | 連隱藏的東西也顯示出來(a=all)
| | | ls -lh | 列出文件的詳細訊息(用人比較容易看懂的寫法(檔案大小)) (h=human)
__touch__ | __創建文件__
| | | touch file1 |創建叫做file1的文件
| | | touch file2 file3 file4 | 一次創建多個文件
__cp__ | __複製__
| | | cp OldFile NewFile | 將OldFile複製到NewFile (若NewFile已存在，會被覆蓋!!)
| | | cp -i OldFile NewFile| 將OldFile複製到NewFile (會確認新文件是否已存在) 
| | | cp -R Folder1/ Folder2/ | 將Folder1整個複製到Folder2裡面 (在linux中，要對資料夾操作都需要加上-R)
| | | cp File* Folder2/ | 將所有以File開頭的文件都複製到Folder2裡面
| | | cp *4 Folder2/ | 將所有以4結尾的文件都複製到Folder2裡面
| | | cp File1 File2 Folder1/ | 將多個文件複製到Folder1(最後一項)裡面
__clear__ | __清空螢幕內容__
__mv__ | __移動__
| | | mv File1 Folder1/ | 將File1移動到Folder1裡面
| | | mv File1 File1Rename | (可用mv做到重新命名)
__mkdir__ | __建立資料夾__
| | | mkdir Folder1 | 建立Folder1
__rmdir__ | __移除資料夾__
| | | rmdir Folder1 | 移除Folder1 (只能移除空資料夾!)
__rm__ | __移除檔案/資料夾__
| | | rm File1 | 移除File1
| | | rm -r Folder1 | 移除Folder1
| | | rm * | 刪除目錄下所有東西
| | | rm -i File1 File2 File3 | 刪除多個檔案 (-i:會確認)
| | | rm -I * | (-I: 刪除超過3個檔案時會確認)





### 如果想瞭解更詳細的功能，可以用「指令 --help」查詢