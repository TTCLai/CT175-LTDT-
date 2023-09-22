# CT175-LTDT-
Cho cấu trúc dữ liệu đồ thị được khai báo sử dụng ma trận đỉnh - cung như sau:

typedef struct {
    int A[100][500];
    int n, m;
} Graph;
Giả sử đồ thị vô hướng, không chứa khuyên.

Viết hàm add_edge(Graph* G, int e, int x, int y) để thêm cung e = (x, y) vào đồ thị G.

Hướng dẫn: 

Các bạn tạo file chương trình C mới trên Dev-C++, dùng chương trình mẫu sau:

#include <stdio.h>

typedef struct {
    //...
} Graph;

void init_graph(Graph* G, int n, int m) { //n là số đỉnh, m là số cung
    //các lệnh khởi tạo
}

//các bạn viết hàm của mình vào đây

int main() {
    Graph G;
    init_graph(&G, 4, 5);
    //thay dòng này bằng lệnh thêm cung cụ thể nào đó
    //thay dòng này bằng lệnh in ô nhớ của ma trận được dùng để lưu cung vừa nhập phía trên, để kiểm tra kết hoạt động của hàm thêm cung
    return 0;
}



