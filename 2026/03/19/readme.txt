1. In ra các số từ 1 đến n và từ n về 0

>> CODE
#include<stdio.h>

int main() {
	int n;
	printf("Nhap n: ");
	scanf("%d", &n);
	for (int i = 1; i <= n; i++){
		printf("%d", i);
	}
	printf("\n");
	for (int i = n; i >= 0; i--){
		printf("%d", i);
	}
	printf("\n");
	return 0;
}
>>

2. Tính N giai thừa ( N! = 1, 2.3 ,...,N): Viết chương trình nhập vào một số nguyên dương N từ bàn phím. Tính và in ra giá trị của N! (N giai thừa).

>> CODE
#include<stdio.h>
#include<math.h>

int main() {
	int n;
	printf("Nhap n: ");
	scanf("%d", &n);
	double giaithua = tgamma(n + 1); 
	printf("%d! = %.0f", n, giaithua);
	return 0;
}
>>

3. Tính tổng và in ra bội số của 3 trong đoạn [a, b]
4. Tìm số đầu tiên chia hết cho 7
Yêu cầu: Viết chương trình duyệt các số nguyên từ 100 trở xuống. Khi tìm thấy số đầu tiên chia hết cho 7, hãy in ra số đó và dừng ngay vòng lặp.
Gợi ý: Sử dụng vòng lập for (hoặc while) và lệnh break.
5. In ra các số không chia hết cho 5
Yêu cầu: Viết chương trình in ra tất cả các số nguyên từ 1 đến n (Số
nguyên dương nhập từ bàn phím), nhưng bỏ qua những số mà chia hết cho 5.
Gợi ý: Sử dụng vòng lặp for và lệnh continue.
