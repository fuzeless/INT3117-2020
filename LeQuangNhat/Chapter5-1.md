# Suppose that coverage criterion C1 subsumes coverage criterion C2. Further suppose that test set T1 satisfies C1 on program P, and test set T2 satisfies C2, also on P.

### (a) Does T1 necessarily satisfy C2? Explain.

Có. Theo định nghĩa của tính bao hàm: C1 bao hàm C2 khi và chỉ khi tất cả các bộ kiểm thử T1 thoả mãn C1 cũng đều thoả mãn C2. Trong trường hợp này, T1 và T2 đã thoả mãn lần lượt C1 và C2, mà C1 bao hàm C2 nên T1 phải thoả mãn C2. Ngoài ra, định nghĩa tính bao hàm <strong>luôn đúng với tất cả các bộ kiểm thử</strong>.

### (b) Does T2 necessarily satisfy C1? Explain.
Không, T2 không nhất thiết phải thoả mãn C1 vì không có yêu cầu nào ép các bộ kiểm thử từ C2 phải tuân theo tiêu chuẩn C1.

### (c) If P contains a fault, and T2 reveals the fault, T1 does not necessarily also reveal the fault. Explain.
Ý kiến trên sai, vì T2 không nhất thiết là bộ kiểm thử nằm trong T1 (hay nói cách khác: T1 bao hàm T2). Nên có thể rằng T2 có ca kiểm thử mà phát hiện được lỗi của P, mà T1 không có, vì T1 không bao hàm T2.
