***
Mục tiêu: kiểm tra Title tem, số lượng ký tự trong GTIN
Ý tưởng:
so sánh số lượng ký tự + maching template
***


1. Teaching để detect đc logo cognex
2. Đếm số lượng blob = số lượng ký tự đọc được


tham khảo các lệnh thao tác với chuỗi

Mid(Text, StartChar, NumChars)

Returns the Text starting from the indexed StartChar position in the alphanumeric string, for as many characters as specified by NumChars.

OpenMid Example

If cell A2 contains the alphanumeric string, "ABC123", then the function Mid(A2,2,2) returns the string "C1".

https://support.cognex.com/docs/is_574/web/EN/ise/Content/Reference/StringTextFunctions.htm?Highlight=Mid
