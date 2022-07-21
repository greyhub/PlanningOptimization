# Project 15. Xếp thời khóa biểu

- Có N lớp 1,2,...N cần được xếp thời khóa biểu. Mỗi lớp i có 
	t(i) 	: số tiết, 
	g(i) 	: giáo viên đã được phân công dạy lớp đó, 
	s(i) 	: số sinh viên của lớp
- Có M phòng học 1,2,...M, trong đó 
	c(i) 	: số chỗ ngồi của phòng i
- Trong tuần có 5 ngày (từ thứ 2 đến thứ 5),
mỗi ngày chia thành 12 tiết (6 tiết sáng và 6 tiết chiều)
- Hãy lập thời khóa biểu (xác định ngày, tiết và phòng gán cho mỗi lớp)
	- Hai lớp có chung giáo viên thì phải xếp thời khóa biểu tách rời nhau
	- Số sinh viên trong mỗi lớp phải nhỏ hơn hoặc bằng số chỗ ngồi của phòng học
	s(i) <= c(i)

- Input
	- Dòng 1		: ghi N và M
	- Dòng i+1 (i = 1..N)	: ghi t(i), g(i) và s(i)
	- Dòng N+2		: ghi c(1), c(2), ... c(M)

