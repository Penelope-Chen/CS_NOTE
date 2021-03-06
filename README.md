# CS_NOTE

Git是從Unix發展

## Git指令


cd 	變換目錄


pwd	顯示目前的目錄


mkdir 建立一個新目錄(資料夾)


rmdir 刪除一個裡面是空的空目錄


cp 複製


mv 移動


ls 顯示目錄下的所有內容


cat 查看檔案內容



## nano


Ctrl C：顯示游標所在


Ctrl W：查詢命令




## vi/vim


vi/vim(vim相當於vi的升級版)


i鍵編輯模式




Esc鍵退出編輯模式



### vi指令
!是強制的意思
:w  寫入
:q  離開
:wq 儲存後離開


## 
電腦系統用bytes，最小的計量單位是 bits (1 byte = 8 bits)

## 壓縮解壓縮
### gzip
壓縮：gzip FileName
解壓縮：gunzip FileName.gz 或 gzip -d FileName.gz
### xz
壓縮：xz -z FileName
解壓縮：xz -d FileName.xz
### tar.gz
壓縮：tar -zcvf FileName.tar.gz DirName
解壓縮：tar -zxvf FileName.tar.gz

## 正規表達法
![image](https://user-images.githubusercontent.com/91451706/147905899-2e0af9ed-d0fa-4e9f-b80f-4d377d8c514a.png)

![image](https://user-images.githubusercontent.com/91451706/147905935-bad9b6ba-4a71-4429-b6c7-84fdf674f6a0.png)

![image](https://user-images.githubusercontent.com/91451706/147905969-08e76c8f-ed5b-4c4a-a62d-559da107ce41.png)

## 文字處理
### join
join [option] filename1 filename2 → 將兩個文件中，指定欄位內容相同的行連接起來

-1 → 連接filename1指定的欄位

-2 → 連接filename2指定的欄位

-t → 使用欄位的分隔符號

-i → 忽略大小寫

-o → 按指定的格式顯示結果

-a → 除顯示結果，原檔案的其他行也顯示

### tr
tr [option] set1 set2 → 替換或刪除操作的字串轉換
### uniq
uniq [option] filename → 將重複文字刪除
### sort
sort [option] filename → 處理各種文字資料的排序問題
### diff
diff [option] filename1 filename2 → 比較文件的內容，特別是兩版本不同的同份文件
