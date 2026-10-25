# KHÓA LUẬN TỐT NGHIỆP 

#### **Đề tài:** Ứng dụng công nghệ in 3D trong hỗ trợ dạy học chủ đề thể tích vật thể

1. ### Giới thiệu tổng quan:

Trong chương trình Hình học không gian lớp 11, chủ đề **thể tích khối đa diện -** Đặc biệt là mối liên hệ giữa thể tích khối lăng trụ/ khối hộp và khối chóp là kiến thức trọng tâm, yêu cầu năng lực tư duy hình học không gian và tư duy tưởng tượng của học sinh.

##### 1.1: Thực trạng và mâu thuẫn dạy học

###### *Khó khăn của học sinh:*

* Học sinh thuộc lòng công thức $ V\_{\\text{chóp}} = \\frac{1}{3}S\_{\\text{đáy}} \\cdot h $ một cách máy móc mà không hiểu được bản chất của hệ số $\\frac{1}{3}$
* Học sinh khó hình dung trực quan lý do vì sao một khối lăng trụ/ khối hộp có thể tích đúng bằng 3 lần thể tích khối chóp.

###### *Hạn chế của phương pháp dạy học truyền thống:*

Việc thừa nhận công thức mang tính áp đặt, giảm tính tư duy khám phá của học sinh.

* Việc chứng minh công thức bằng nguyên lý Cavalieri hay theo lý thuyết tích phân yêu cầu nền tảng toán học cao cấp đều không phù hợp với mức độ tiếp thu của học sinh THPT.
* Các thiết bị dạy học phẳng (dạy học 2D) không mô phỏng đầy đủ tính chất không gian và thao tác lắp ráp.

##### 1.2 Giải pháp đề xuất

Ứng dụng công nghệ in 3D để chế tạo bộ thiết bị dạy học trực quan, có tính tương tác cao thông qua mô hình đong định lượng của nước/cát hoặc lắp ráp mô hình ghép 3 khối chóp thành 1 khối lăng trụ/khối hộp giúp học sinh tự thực nghiệm, quan sát và trực tiếp khám phá kiến tạo tri thức theo tinh thần đổi mới giáo dục STEM/STEAM Toán học để tìm ra bản chất của hệ số $\\frac{1}{3}$.

### 2\. Mục tiêu nghiên cứu và giả thuyết khoa học

##### 2.1 Mục tiêu nghiên cứu

*1 Mục tiêu lý luận:*

* Hệ thống hoá cơ sở lý luận về phương tiện dạy học trực quan và công nghệ in 3D trong giáo dục Toán(STEM/STEAM).
* Xây dựng quy trình 5 bước tích hợp công nghệ in 3D (Open SCAD/3D Printing/Tinker CAD/Geogebra 3D) vào thiết kế thiết bị dạy học Toán THPT.

*2 Mục tiêu thực tiễn:*

* Thiết kế bản vẽ 3D (CAD) và in thành công bộ mô hình trực quan so sánh thể tích giữa khối hộp/khối lăng trụ và khối chóp (có cùng $S\_{\\text{đáy}}$ và chiều cao $h$)
* Thiết kế mô hình đong định lượng rỗng đo thể tích giữa khối lăng trụ/ khối hộp và khối chóp cùng diện tích đáy và cùng chiều cao. Khối lăng trụ tam giác $ABC.A'B'C'$ thành 3 khối chóp $A.A'B'C'$, $A.BCC'B'$ và $C'.ABC$

*3 Mục tiêu sư phạm:*

* Xây dựng kế hoạch bài dạy (giáo án) ứng dụng bộ mô hình in 3D, thực nghiệm sư phạm tại trường THPT để kiểm chứng giả thuyết khoa học về hiệu quả hỗ trợ phát triển năng lực tư duy và tưởng tượng không gian của học sinh.

##### 2.2 Giả thuyết khoa học

Nếu thiết kế và tổ chức dạy học với bộ thiết bị in 3D theo hướng hoạt động hóa trải nghiệm thao tác, học sinh sẽ hiểu rõ bản chất hình học của hệ số 1/3, qua đó nâng cao năng lực tư duy - tưởng tượng không gian và hiệu quả ghi nhớ lâu dài công thức tính thể tích.

### 3\. Nội dung \& Giải pháp kỹ thuật chế tạo mô hình in 3D

Khoá luận tập trung vào 2 phương án mô hình trực quan:

**Mô hình 1: Thực nghiêm đong cát/nước định lượng thể tích**

* *Cấu trúc kỹ thuật:*
Khối lăng trụ đứng/ khối hộp rỗng: Đáy là tam giác đều hoặc hình vuông không nắp.
Khối chóp rỗng: Có diện tích đáy và chiều cao bằng khối lăng trụ.
* *Vật liệu và xử lý bề mặt:*
Nhựa trong suốt được có thể chịu được nước/cát bên trong.
* *Quy trình tương tác dạy học:*
1. Học sinh đong nước/cát vào khối chóp rỗng.
2. Rót toàn bộ vật liệu từ khối chóp sang khối lăng trụ/ khối hộp.
3. Lặp lại thao tác cho đến khi đầy khối lăng trụ/ khối hộp. Xác nhận thực nghiệm bằng 3 lần rót.
Kết luận:  $V\_{\\text{lăng trụ}} = 3 \\cdot V\_{\\text{chóp}} \\implies V\_{\\text{chóp}} = \\frac{1}{3} S\_{\\text{đáy}} \\cdot h$.
**Mô hình 2: Mô hình ghép khối :**
* *Cấu trúc kỹ thuật:*
Mỗi khối chóp được thiết kế các khớp để khi ghép khối lại tạo mô hình khối lang trụ tam giác hoàn chỉnh.
* *Quy trình tương tác dạy học:*
1. Tách khối lăng trụ tam giác $ABC.A'B'C'$ thành 3 khối chóp:
Khối chóp 1: A.A'B'C' (chóp tam giác có đỉnh A, đáy A'B'C').
2. Khối chóp 2: A.BCC'B'  chia tiếp thành 2 khối chóp tam giác bằng mặt phẳng (AB'C') thu được A.A'B'C' và C'.ABC.
3. Lập luận chứng minh thể tích 3 khối bằng nhau:
$V\_{A.A'B'C'}=V\_{C'.A'B'C'} $(cùng chiều cao và đáy).
$V\_{C'.ABC}=V\_{C'.A'B'C'}$ (do $ABC$=$A'B'C'$ và cùng chiều cao).
$V\_{A.BCC'B'}$=2$V\_{C'.ABC.}$

### 4\. Quy trình thiết kế và chế tạo kỹ thuật



**\[GeoGebra 3D / MathCAD] ──> \[Autodesk Fusion 360] ──> \[UltiMaker Cura] ──> \[FDM 3D Printer]**

&#x20;  (Tính toán tham số)  ──>      (Dựng mô hình CAD 3D)  ──>   (Mã hóa G-code)   ──>     (In PLA/PETG)

*Bước 1: Tính toán tham số*
Đặt biến tham số: Cạnh đáy $a=80mm$ chiều cao $h=120mm$ độ hở lắp ghép 0,2mm
*Bước 2: Chuẩn hoá xuất tệp*
Xuất tệp định dạng chất lượng cao.
*Bước 3: Lập trình cắt lát*
Infill density: 15% ( dạng Tri-hexagon để tối ưu độ chịu lực và trọng lượng nhẹ
Layer height: 0.2mm để tạo độ mịn bề mặt và thời gian ưu tối ưu.
Wall thickness: 1.6mm
Supports:  Tree support cho các vách nghiêng khối chóp >45
*Bước 4: In 3D \& Hậu kỳ*
In trên máy in FDM và chỉnh sửa.

### 5\. Tiến trình dạy học \& Thiết kế bài dạy

|**Giai đoạn**|**Hoạt động của GV và HS với bộ in 3D**|**Mục tiêu dạy học**|
|-|-|-|
|1. Gắn kết|GV đặt vấn đề: Dự đoán mối liên hệ thể tích giữa khối chóp và khối lăng trụ có cùng đáy và chiều cao.|Kích thích sự tò mò và dự đoán ban đầu.|
|2. Khám phá|HS chia nhóm thao tác với Bộ mô hình đong 3D (Phương án 1). Tiến hành đong chất lưu và ghi chép số liệu thu được vào phiếu học tập|Tự phát hiện tỉ lệ thể tích 1:3 thông qua thực nghiệm|
|3. Giải thích|HS sử dụng Bộ mô hình phân rã 3D (Phương án 2), tháo rời lăng trụ thành 3 khối chóp, so sánh diện tích đáy và chiều cao các khối con để chứng minh V1=V2=V3.|Chuyển từ trực quan thực nghiệm sang logic chứng minh hình học|
|4. Củng cố|HS áp dụng công thức $V = \\frac{1}{3} S\_{\\text{đáy}} \\cdot h$ giải quyết các bài toán thể tích khối chóp phức tạp (chóp tứ giác, chóp đều, chóp có cạnh bên vuông góc đáy).|Khái quát hóa và vận dụng tri thức vào giải bài tập.|
|5. Đánh giá|HS hoàn thành bài kiểm tra ngắn đánh giá khả năng tưởng tượng không gian và lập luận công thức thể tích.|Đo lường mức độ đạt chuẩn đầu ra của bài học.|

|

### 6\. Phương pháp đánh giá \& Thiết kế thực nghiệm sư phạm

##### 6.1: Mẫu thực nghiệm \& Đối chứng

Lớp thực nghiệm: Học tập với kế hoạch bài dạy tích hợp thiết bị in 3D và tiến trình dạy học 5 bước
Lớp đối chứng: Học theo phương pháp truyền thống( thừa nhận công thức hoặc vẽ hình 2D)
Lưu ý: Các lớp có trình độ học tập tương đương và năng lực toán học tương đương.

##### 6.2: Tiêu chí và công cụ đánh giá

1. Năng lực tư duy không gian : Thang đo trắc nghiệm tư duy không gian
2. Khả năng ghi nhớ và bản chất kiến thức được học
3. Độ tích cực trong hoạt động học tập của học sinh: Khảo sát qua bảng khảo sát về mức độ hứng thú với mức độ hỗ trợ của mô hình 3D.

### 7.Bố cục của bài Khoá luận

###### **Phần mở đầu:**

* Lý do chọn đề tài
* Mục đích và nhiệm vụ nghiên cứu
* Đối tượng và phạm vi nghiên cứu
* Giả thuyết khoa học
* Phương pháp nghiên cứu: nghiên cứu lý luận, thiết kế kỹ thuật, thực nghiệm sư phạm và thống kế kết quả toán học

###### **Chương 1:** Cơ sở lý luận và thực tiễn về ứng dụng cong nghệ in 3D trong dạy học hình học không gian THPT

* 1.1: Tổng quan nghiên cứu ứng dụng công nghệ in 3D/ STEM trong dạy học toán.
* 1.2: Lý thuyết phát triển nhận thức và dạy học trực quan .
* 1.3: Nội dung thể tích khối đa diện trong chương trình toán 11.
* 1.4: Thực trạng dạy học và nội dung thể tích tại trường THPT.

###### **Chương 2:** Quy trình thiết kế \& chế tạo thiết bị dạy học in 3D về thể tích khối đa diện.

* 2.1: Quy trình dạy học 5 bước thiết kế và chế tạo thiết bị dạy học bằng công nghệ in 3D.
* 2.2: Thiết kế và in 3D bộ mô hình đong định lượng thể tích.
* 2.3: Thiết kế và in 3D bộ mô hình phân rã lăng trụ thành 3 khối chóp.

###### **Chương 3:** Thiết kế tiến trình dạy học và Kế hoạch bài dạy

* 3.1: Nguyên tắc tổ chức dạy học khám phá với mô hình in 3D.
* 3.2: Tiến trình dạy học 5E chủ đề Thể tích (Toán 11 tập 2 ).
* 3.3: Kế hoạch bài dạy và phiếu học tập.

###### **Chương 4:** Thực nghiệm sư phạm và đánh giá kết quả

* 4.1: Kế hoạch và mẫu thực nghiệm sư phạm.
* 4.2: Tiến hành thực nghiệm và thu thập dữ liệu.
* 4.3: Phân tích kết quả thực nghiệm.

###### **Kết luận \& Khuyến nghị**

* Kết luận về mục tiêu nghiên cứu.
* Khuyến nghị về việc ứng dụng in 3D trong làm đồ dùng dạy học Toán.

###### **Tài liệu tham khảo**

###### **Phụ lục**

### 8\. Yêu cầu kỹ thuật, phần mềm \& vật liệu

* Phần mềm thiết kế \& mô phỏng: Geogebra/Math CAD/ Tinker CAD
* Phần mềm cắt lát
* Máy in 3D
* Phần mềm xử lý thống kê kết quả thực nghiệm: Excel

