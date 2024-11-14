[Weird Algorithm](https://cses.fi/problemset/task/1068)  
  
  
Translation  
  
Một thuật toán nhận vào một số nguyên dương n. Nếu n chẵn, giá trị n bị chia cho 2, còn nếu n lẻ, giá trị n nhân với 3 và cộng 1. Thuật toán lặp lại các bước này cho đến khi nào n là 1. Giả sử n=3 thì chuỗi số sau là kết quả của thuật toán trên:  

3 -> 10 -> 5 -> 16 -> 8 -> 4 -> 2 -> 1  

Viết chương trình mô phỏng hoạt động của thuật toán trên dựa theo giá trị đầu vào n.  

Đầu vào  
Đầu vào chứa một số nguyên dương n.  

Đầu ra  
In ra một dòng chứa toàn bộ các giá trị của n trong quá trình thuật toán hoạt động  

Ràng buộc  
1 <= n <= 10^6  

Ví dụ  
Đầu vào:  
3  

Đầu ra:  
3 10 5 16 8 4 2 1  
