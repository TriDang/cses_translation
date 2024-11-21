[Point Location Test](https://cses.fi/problemset/task/2189)  
  
  
Translation  

Có một đường thẳng đi qua hai điểm p1=(x1, y1) và p2=(x2, y2). Ngoài ra, còn có một điểm p3=(x3, y3).
Nhiệm vụ của bạn là xác định xem p3 nằm ở bên trái hay bên phải đường thẳng, hoặc nếu nó nằm trên đường thẳng khi nhìn từ p1 đến p2.

Đầu vào
Dòng đầu tiên chứa một số nguyên t: số lượng bài kiểm tra.
Sau đó, có t dòng, mỗi dòng mô tả một bài kiểm tra bằng sáu số nguyên: x1, y1, x2, y2, x3, y3.

Đầu ra
Với mỗi bài kiểm tra, in ra:

"LEFT" nếu p3 nằm bên trái đường thẳng.
"RIGHT" nếu p3 nằm bên phải đường thẳng.
"TOUCH" nếu p3 nằm trên đường thẳng.

Ràng buộc
1 <= t <= 10^5
-10^9 <= x1, y1, x2, y2, x3, y3 <= 10^9
x1 != x2 hoặc y1 != y2

Ví dụ
Đầu vào:
3
1 1 5 3 2 3
1 1 5 3 4 1
1 1 5 3 3 2

Đầu ra:
LEFT
RIGHT
TOUCH
  
