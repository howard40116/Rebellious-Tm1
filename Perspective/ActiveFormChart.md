
#Bug

當ActiveForm沒有顯示任何一列資料時(拼接MDX)，OFFSET取資料範圍永遠只有第一列，
顯示的圖形也只會有一筆資料。

#解決方法

將TM1RPTROW隨意套一個Subset，重新建置Sheet將資料顯示出來，
TM1RPTROW套回MDX後重新上傳即可。


