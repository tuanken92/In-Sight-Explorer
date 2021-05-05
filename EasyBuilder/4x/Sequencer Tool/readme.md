***
Mục tiêu: đọc đc các ký tự vaf QR code và matching output với nhau
Ý tưởng:
+ OCR MAx 
+ Reader
***


1. Dùng reader để đọc QR code
2. Đọc OCR trong vùng chữ
3. Dùng Exact(IDCode_1.String,Text_1.Result) để so sánh 2 text với nhau


https://support.cognex.com/docs/is_574/web/EN/ise/Content/Reference/StringTextFunctions.htm?Highlight=Exact


Returns 1 if Text1 and Text2 are identical, else 0.

Note: Exact is case-sensitive.
OpenExact Examples

If cell A2 contains the string, "ABC123", and cell A3 contains the string, "ABC1234", then Exact(A2,A3) returns 0.000.
If cell A2 contains the string, "VISION", and cell A3 contains the string, "VISION", then Exact(A2,A3) returns 1.000.