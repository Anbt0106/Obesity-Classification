# Obesity-Classification

### Thông tin Tập dữ liệu

Tập dữ liệu này bao gồm thông tin để ước lượng các mức độ béo phì của các cá nhân ở Mexico, Peru và Colombia, dựa trên thói quen ăn uống và tình trạng thể chất. Tập dữ liệu bao gồm 17 thuộc tính và 2111 bản ghi. Các bản ghi được gán nhãn với biến lớp **NObesity** (mức độ béo phì), cho phép phân loại các dữ liệu theo các mức: Thiếu cân, Cân nặng bình thường, Thừa cân Độ I, Thừa cân Độ II, Béo phì Độ I, Béo phì Độ II, và Béo phì Độ III.

77% dữ liệu được tạo tổng hợp bằng công cụ Weka và bộ lọc SMOTE; 23% còn lại được thu thập trực tiếp từ người dùng qua một nền tảng web.

#### Các thuộc tính:

- **Giới tính (Gender):** Categorical, "Giới tính"
- **Tuổi (Age):** Continuous, "Tuổi"
- **Chiều cao (Height):** Continuous, "Chiều cao"
- **Cân nặng (Weight):** Continuous, "Cân nặng"
- **Tiền sử gia đình với béo phì (family_history_with_overweight):** Binary, "Gia đình có người từng béo phì hay không?"
- **Thường xuyên ăn thực phẩm nhiều calo (FAVC):** Binary, "Bạn có thường ăn thực phẩm nhiều calo không?"
- **Ăn rau trong bữa (FCVC):** Integer, "Bạn có thường ăn rau trong bữa không?"
- **Số bữa chính hàng ngày (NCP):** Categorical, "Số bữa chính mà bạn ăn hàng ngày?"
- **Ăn vặt giữa các bữa (CAEC):** Categorical, "Bạn có ăn vặt giữa các bữa không?"
- **Hút thuốc (SMOKE):** Binary, "Bạn có hút thuốc không?"
- **Lượng nước uống hàng ngày (CH2O):** Categorical, "Bạn uống bao nhiêu nước mỗi ngày?"
- **Kiểm soát lượng calo (SCC):** Binary, "Bạn có theo dõi lượng calo tiêu thụ hàng ngày không?"
- **Tần suất hoạt động thể chất (FAF):** Categorical, "Bạn thường hoạt động thể chất bao nhiêu lần mỗi tuần?"
- **Thời gian sử dụng thiết bị công nghệ (TUE):** Integer, "Bạn sử dụng các thiết bị công nghệ bao lâu mỗi ngày (như điện thoại, TV, máy tính)?"
- **Tần suất uống rượu bia (CALC):** Categorical, "Bạn thường uống rượu bia bao nhiêu lần?"
- **Phương tiện di chuyển (MTRANS):** Categorical, "Bạn thường sử dụng phương tiện di chuyển nào?"

#### Biến mục tiêu (Target variable):
- **NObeyesdad:** Categorical, "Mức độ béo phì"

