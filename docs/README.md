<div align="center">

# Nhật ký thay đổi</div>

<div align="center" style="font-size:xx-small">(✨: Tính năng, chức năng mới. 🐛: Chỉnh lỗi. ☑: Giải quyết công việc, issue) </div>

#

## [v.3.26.0903.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32609030-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32609030-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32609030-NasDHSolutions.json)</sup></sup></sub>
- ✨: Thực hiện theo mô tả [THAM_SO_HE_THONG
  /Hau-mota-them-thamso-cauhinh_phong_cls.md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/THAM_SO_HE_THONG/Hau-mota-them-thamso-cauhinh_phong_cls.md)
- ✨: Mở chức năng hiển thị hàng chờ Tivi Cận lâm sàng (optCLS) trên FrmMainV2 và FrmShow_OMon_CDHA, tự động khởi động FrmMainV2 khi bật tham số cauhinh_phong_cls = 1.
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/903
  https://i.dh-his.com/hdhiswork/YEUCAU/issues/886
- 📗: Đọc dữ liệu hàng chờ gọi bệnh nhân từ current.pscls_lcd, nạp danh sách phòng từ current.cauhinhmay và current.dmphong_cls.
- 📕: Chạy Monitor.exe trên PC kết nối Tivi phòng CLS (Extend screen), chọn Cận lâm sàng -> Chọn phòng CLS -> Bấm [Hiển thị] để chiếu danh sách gọi bệnh nhân và video truyền thông.
  ![](https://images-worker.tlt36.workers.dev/i/01a06633-b4e8-7682-91b3-1965c27c14fa)
  ![](https://images-worker.tlt26.workers.dev/i/01a06630-e46b-788d-95bf-daa43345ddc0)
  ![](https://images-worker.tlt34.workers.dev/i/01a06638-20a8-7a50-a75c-cf82caa80003)
  ![](https://images-worker.tlt43.workers.dev/i/01a0663e-51a3-7023-a271-d9540ce0e432)
  ![](https://images-worker.tlt41.workers.dev/i/01a0663d-9378-7656-ae22-bcaa5f265be7)
  ![](https://images-worker.tlt44.workers.dev/i/01a06641-5b79-7e58-94ce-8fb5a6055414)

## [v.3.26.0819.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32608190-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32608190-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32608190-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi Xét nghiệm chưa loại trừ ra CLS không thanh BHYT khi kiểm tra mã máy.
![](https://lh3.googleusercontent.com/pw/AP1GczNJNnUPPmalg2lQYgEjJYGXdrufiKzKy3A_sKwn5cjkwdAG2DHFmPA_jbF_Q5X5OEZjQmzwBVV9TJCV97xlaJosgeJ1jDdqkYP71Uq6i4btq-0-L2OE_qqBpEeeVoFAGW2hvQvSmOdlAw4OzyT-08hA=w1661-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/870#issuecomment-33162 (hdhiswork/YEUCAU#870)

## [v.3.26.0814.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32608140-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32608140-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32608140-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Register/Laboratory: Chưa hiển thị được CLS con với đối tượng người nước ngoài #966
![](https://i.vgy.me/vtEo7U.png)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/966

## [v.3.26.0813.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32608130-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32608130-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32608130-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bổ sung chức năng cảnh báo/chặn trùng mã máy thực hiện cận lâm sàng theo mô tả [THAM_SO_HE_THONG/Kiem-soat-trung-ma-may-thuc-hien.md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/THAM_SO_HE_THONG/Kiem-soat-trung-ma-may-thuc-hien.md).
![](https://lh3.googleusercontent.com/pw/AP1GczNr_n71RuIGsogh8_GvVbc_Fp9puVZLVfk4WyF0Nl8qpwNweAEsqyCYr742Y5SjAVFDa9mKopNYxR4IShC0qdO_eGqUdjP3LZa9y6-o8YUu4-KjRurDIAL8s9I77iQAlAuANED0vbLS8OTz1TG4kUG0=w1654-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/870#issuecomment-32585 (hdhiswork/YEUCAU#870)

## [v.3.26.0729.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32607290-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32607290-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32607290-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Laboratory: Không in được kết quả XN có chữ ký số (PK Minh Quang) #945
![](https://i.vgy.me/Pbh284.png)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/945

## [v.3.26.0727.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32607272-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32607272-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32607272-NasDHSolutions.json)</sup></sup></sub>
✨: Yêu cầu - Ẩn đi cột Tồn cuối tại form dự trù thuốc, VTYT #820
        - Laboratory:

		- Tham số: dutru.tonkho = 0

		Dự trù hóa chất:

		![](https://i.vgy.me/911jB3.png)

		Dự trù vật tư:

		![](https://i.vgy.me/5aY4p4.png)

		- Tham số: dutru.tonkho = 1

		Dự trù hóa chất:
		![](https://i.vgy.me/nuaTSu.png)

		Dự trù vật tư:
		![](https://i.vgy.me/pTlSio.png)


- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/820

## [v.3.26.0727.1]()
✨: Yêu cầu - Ẩn đi cột Tồn cuối tại form dự trù thuốc, VTYT #820
        - Laboratory:

		- Tham số: dutru.tonkho = 0

		Dự trù hóa chất:

		![](https://i.vgy.me/911jB3.png)

		Dự trù vật tư:

		![](https://i.vgy.me/5aY4p4.png)

		- Tham số: dutru.tonkho = 1

		Dự trù hóa chất:
		![](https://i.vgy.me/nuaTSu.png)

		Dự trù vật tư:
		![](https://i.vgy.me/pTlSio.png)


- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/820
<<<<<<< HEAD

## [v.3.26.0727.0]()
- ✨: Yêu cầu - Ẩn đi cột Tồn cuối tại form dự trù thuốc, VTYT #820
        - Laboratory:

		- Tham số: dutru.tonkho = 0

		Dự trù hóa chất:

		![](https://i.vgy.me/911jB3.png)

		Dự trù vật tư:

		![](https://i.vgy.me/5aY4p4.png)

		- Tham số: dutru.tonkho = 1

		Dự trù hóa chất:
		![](https://i.vgy.me/nuaTSu.png)

		Dự trù vật tư:
		![](https://i.vgy.me/pTlSio.png)


- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/820
=======

## [v.3.26.0723.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32607232-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32607232-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32607232-NasDHSolutions.json)</sup></sup></sub>
- ✨:  cầu - Cấp key HIS và Buiding các module triển khai cho Phòng khám đa khoa Thánh Tâm (TP. HCM (tỉnh Bình Dương cũ))- Yêu
- ✨:  ***Bổ sung key theo Hợp đồng: `74167`.***
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/851#issuecomment-31292

## [v.3.26.0723.1]()
- ✨:  cầu - Cấp key HIS và Buiding các module triển khai cho Phòng khám đa khoa Thánh Tâm (TP. HCM (tỉnh Bình Dương cũ))- Yêu
- ✨:  ***Bổ sung key theo Hợp đồng: `74167`.***
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/851#issuecomment-31292

## [v.3.26.0723.0]()
- ✨:  cầu - Cấp key HIS và Buiding các module triển khai cho Phòng khám đa khoa Thánh Tâm (TP. HCM (tỉnh Bình Dương cũ))- Yêu
- ✨:  ***Bổ sung key theo Hợp đồng: `74167`.***
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/851#issuecomment-31292

## [v.3.26.0714.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32607140-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32607140-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32607140-NasDHSolutions.json)</sup></sup></sub>

- ✨: Sử dụng UserControl `MaMayControl` cho phép chọn nhiều mã máy khi thực hiện xét nghiệm Sinh thiết/Tế bào tử cung/Đờm.
![](https://lh3.googleusercontent.com/pw/AP1GczMiqFvU956XSERYtSZKNeJtIvER8dVr7K84SiWdoCcnIUbbp4Eatuk3vSNKWokIultCHGGhBGvmIhl__o96QhOOx5ZRTJJXKwDwTLF4zVINqj4AO8iTyLxj_lLrrxPLiHqvBwMi6yQA86Lc06_ZJ24o=w1654-h879-s-no-gm?authuser=0)
![](https://lh3.googleusercontent.com/pw/AP1GczNLiMEDGBn_B8CuDTZNJ_NUycKIx_SdiTQtKB8L_om7Bhd-Oh_KnnqViz3KUswi5N51FFp-1LnSCiLaA5I30UC_5_A9g6Wfjo9LI2OvqKD-E3ddY1T9SPELgo1MOYfS8j_PUxJcOpERR0woKr5BFXzC=w1653-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/706#issuecomment-30270

## [v.3.26.0707.1]()
- ✨: Yêu cầu - Ẩn đi cột Tồn cuối tại form dự trù thuốc, VTYT #820
        - Laboratory:

		- Tham số: dutru.tonkho = 0

		Dự trù hóa chất:

		![](https://i.vgy.me/911jB3.png)

		Dự trù vật tư:

		![](https://i.vgy.me/5aY4p4.png)

		- Tham số: dutru.tonkho = 1

		Dự trù hóa chất:
		![](https://i.vgy.me/nuaTSu.png)

		Dự trù vật tư:
		![](https://i.vgy.me/pTlSio.png)


- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/820
<<<<<<< HEAD

## [v.3.26.0707.0]()
- ✨: Yêu cầu - Ẩn đi cột Tồn cuối tại form dự trù thuốc, VTYT #820
        - Laboratory:

		- Tham số: dutru.tonkho = 0

		Dự trù hóa chất:

		![](https://i.vgy.me/911jB3.png)

		Dự trù vật tư:

		![](https://i.vgy.me/5aY4p4.png)

		- Tham số: dutru.tonkho = 1

		Dự trù hóa chất:
		![](https://i.vgy.me/nuaTSu.png)

		Dự trù vật tư:
		![](https://i.vgy.me/pTlSio.png)


- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/820
=======

## [v.3.26.0624.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32606240-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32606240-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32606240-NasDHSolutions.json)</sup></sup></sub>

- ✨: Cải tiến hàm `current.fn_check_sudung()` theo mô tả [Quan-tri-Admin/Danh-muc-Ma-may.md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/Quan-tri-Admin/Danh-muc-Ma-may.md) áp dụng cho mã máy.
![](https://lh3.googleusercontent.com/pw/AP1GczPonavjg8MHiqTBuJKVFpdcv37LuYC-tIhgxvip1B2X1fUjN1epvmMvbz95xdtE2_JRG4-RtfWoR_Xm43XGGuFS5b4YY8x6JGcWs2Cov2cB3I6gFQ9uqgc_C-BQm7BPS2jszezHB68zSGHVxaMxc_v_=w1160-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/793#issuecomment-29998

## [v.3.26.0618.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32606181-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32606181-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32606181-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi load mã máy khi mở form nhập kết quả xét nghiệm
![](https://lh3.googleusercontent.com/pw/AP1GczNo-M1TflUO1oCOK6IAAAERTY4ll7aep3RWr3a5MLVQFLl70vf4aENB6AELFId4KZzzWNo5oBD3pTOjZ4v3iYMgWC6Wopcr_SuNwa91DfX-pGC825LlT3sBN-PtAuYryKqWp2fTJ6CsBt2zX1ZXesWP=w1654-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/893#issuecomment-29798
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/793#issuecomment-29357

## [v.3.26.0618.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32606180-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32606180-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32606180-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi không load được có xét nghiệm gửi nơi khác để trả kết quả khi tham số `xn.danhsachxn = 1`
![](https://lh3.googleusercontent.com/pw/AP1GczMB_jda8JOQViMyI60adMvKByDFXtUzYnX_PSFvLBU8aMv9ORedjtu1afpW1OeriD7GhtR67Rc5IGusKyclbnIz8JGvNsyjGOxZRiSshpSFABkqjedmz56Eg2Csv5bnsTGH8aEEl03hqZe25oO9KQwN=w1654-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/893#issuecomment-29641
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/555

## [v.3.26.0612.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32606120-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32606120-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32606120-NasDHSolutions.json)</sup></sup></sub>

- ✨: Lấy danh mục mã máy theo mô tả [Quan-tri-Admin/Danh-muc-Ma-may.md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/Quan-tri-Admin/Danh-muc-Ma-may.md).
![](https://lh3.googleusercontent.com/pw/AP1GczOEFl61_bKyTdExnLjmYq1-3fq3LVIhIEGm_vOQU3eATB6a-V50kkzX1OooT7U7VnVTbJZRisSNowJcttmICx8qSLH2vhOFl3K4cjiwDMxS3AupF0zqMxXuPQPEAm-pQVyeI7Ezki3VSO_-SbYzDPnZ=w1654-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/793#issuecomment-29357

## [v.3.26.0515.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32605150-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32605150-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32605150-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi:
	- Lỗi trả kết quả XN:
	![](https://lh3.googleusercontent.com/pw/AP1GczMMBRtUcpItym_96Mh9HGQoroxv2UVifcHQv5c_Z5luPnHgByZnNo-d0B59E-pkkj1yBkyAfNnXfLDQBzAxIJkCBq88W35StOwMSzxGNXpKgkzCTEoc0d2JTltg1k-zLwf2Ufa8VAvjITcXDFHs9UcR=w1654-h879-s-no-gm?authuser=0)
	- Các mẫu XN chuẩn riêng khi Tài khoản không có cấu hình ký số thì không hiện cảnh báo tài khoản nào không có cấu hình ký số và hiện trang in thường -> Có cảnh báo tài khoản nào mã+tên không có ký số, Hiện trang in ký số có chữ ký của những tài khoản có chữ ký số:
	![](https://lh3.googleusercontent.com/pw/AP1GczMEGrdwCP_tqodJIOtxJf32bNQjsn2SHZp7OTXkTTcHK6Pg0csOHPbbcws6Gth4lyzu0Fh-YQfn5_2ocvEhmaTyhXpdeGQkrF6IraKTmf6uP-IiQfUOJYAWw8Ck0pQn5-LHWvHcTAEbIx-j_sutqLwj=w1654-h879-s-no-gm?authuser=0)
	- Mẫu XN chung khi tài khoản không có chữ ký số thì có cảnh báo mã nhân viên không có chữ ký số và hiện trang in dang ký số -> Đề nghị thêm tên nhân viên sau mã nhân viên trên cảnh báo:
	![](https://lh3.googleusercontent.com/pw/AP1GczM0op5UdpUJbG2c_oIweHtZdHl-F1wFNJd70uibD6jBsIjm9frgl38YK4ua8SSDV8lCHF9g3PUXeK6wIs5uRiRYI7XDaGShYziYttX4Ow7qniRRfOrfV2MURU7N39SvC04NM-aZxjg6z1a7_nRIrBRK=w635-h150-s-no-gm?authuser=0)
	- Các Mẫu XN chuẩn riêng mất tiêu đề mẫu ở tất cả các mẫu:
	![](https://lh3.googleusercontent.com/pw/AP1GczOlIZi-nqdMImXf__FEzxUDiM8XMHfQbvpMNAXJEv6F8_4a-UHfu-Roxk1s94BA9Q0zsJfnDnPXY-pbcbxnLfumRbxVC6Z0zkOuhMpMkOUpBMQy54iG5H0W5h0Xzi7xOjD-8tNEaybUcROlq7xjM6vY=w1654-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/739#issuecomment-27888

## [v.3.26.0514.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32605140-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32605140-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32605140-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi thao tác Lưu kết quả xét nghiệm.
![](https://lh3.googleusercontent.com/pw/AP1GczPV0qICjYNrD0bSuaL0YD5S6vet4HdLeDsrz7MA8odCypPKt7WV6gvoj8lbMe6SPccsaiFrRFthq-9l4M7SuRu_6E7iTHweRLaMXsu2YOmlLq_VoavF2fZDN8gEev6ZCWiUoolrZs2zbfmQcJ5i6BYc=w1654-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/767#issuecomment-27874

## [v.3.26.0513.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32605131-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32605131-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32605131-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bổ sung chặn khi lưu kết quả nếu không nhập mã máy thực hiện theo mô tả [Quan-tri-Admin/BO_SUNG_THONG_TIN_NHAP_MA_MAY_PTTT.md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/Quan-tri-Admin/BO_SUNG_THONG_TIN_NHAP_MA_MAY_PTTT.md)
![](https://lh3.googleusercontent.com/pw/AP1GczP_F1EdXKbBq2slVjF83WArMbyfLodYOYiZR3YCM0DWJTdK4owUhjVCoHJmpm74GqYifhmaVbPk1qR4qZfN-i0h5TNr4cT8RldaRsB-CoE2GMpUXA-Ge7T3V1N2zRfJhqo_zhF8FsnQwE9gPvgBvSb3=w1654-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/767#issuecomment-27664

## [v.3.26.0513.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32605130-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32605130-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32605130-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi: 
	- Mẫu không chuẩn không in được chữ ký số bác sĩ đọc kết quả và Mẫu chuẩn tt32 không in được chữ ký số
	![](https://lh3.googleusercontent.com/pw/AP1GczPS-7VKIrBnOfBYCpAwpuljbvlgBGJNG_v_lB_G6xlG2-GCBxiLkc4goi6DYsToNzVacZykdtE6YDXnJi7duxsgXuiH2b6Rpm53ZNw7HrTatKQJvkZRp-RIXzQ_CUjIow9N2_okYNo5aAswGuFQBsVL=w1661-h879-s-no-gm?authuser=0)
	- Khi tài khoản chỉ định hoặc tài khoản đọc kết quả không có cấu hình chữ ký số thì phần mềm báo lỗi -> đề xuất hiện cảnh báo tài khoản chỉ đinh hoặc tài khoản đọc kết quả không có ký số và hiện trang in thiếu chữ ký số đó không hiện thông báo lỗi code:
	![](https://lh3.googleusercontent.com/pw/AP1GczNT1pHQjusRR_IHwm-PfQKuwLVS3Xto2-au2PvS90CEeA54vgLrBy9pvcY_9sY8gUvHaHj8YiHifZBkmohj6qsuhydWNxJKHoasWWKURyj0JqTu0SRnW859O8rbnkRRMrDHrymfRQFCfvfDZvlpnbCU=w1654-h879-s-no-gm?authuser=0)
	![](https://lh3.googleusercontent.com/pw/AP1GczOjlqNyrk0ODme-zQgkXPQbE3oswvbj73RzoTSFOjbzm6Cv406okPiv2_rC44KI_U_g6pNtQyrg4GCQGFumv2KIvfDQzAMGtypPzPpSE5YOWD6YrjyJj7tCP4Bixcse6Mg4us8i_LWVhdo8ZADGiF3g=w1668-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/739#issuecomment-27653

## [v.3.26.0508.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32605080-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32605080-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32605080-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bổ sung kết quả CLS có thêm chữ ký số bác sĩ chỉ định khi hiển thị phiếu kết quả có ký số. Cập nhật thêm chức năng upload file PDF kết quả xét nghiệm.
	- Cấu hình mã nhân viên tại vùng chữ ký số của bác sĩ chỉ định: đưa para manv_chidinh vào vùng `<<SIGN:{{[Parameters.manv_chidinh]}}>>` như hình:
	![](https://lh3.googleusercontent.com/pw/AP1GczOYMQQ8k-YJW8OMBmsqu0SEb3v5n8Lcc1Awv3d1Ejbd4xmkWUKWaBlJJpFV253PZEac4vz8WyWq2nsoYrJQMT7Jwe_yi-HPEJy8LldiL_tdx2u_aYducfeTTS1-YkY3XWOzvxUK9Arc0NC4JQvVUipL=w1270-h879-s-no-gm?authuser=0)
	- Kết quả:
	![](https://lh3.googleusercontent.com/pw/AP1GczP6xDuSP-sS8A3b4bBXX-GPKDTIvSKDuKsWXwnfKD92Dkf30YCNXm_5XS0yeJe6xVpREYtVB6NQxfRQ9I6fd6V0rkkLv99lkRBNXow8tJmsP6I4zsPXWhKaz_Pq4YjiGijqzGr4BDeVEFrCfuc6OuSr=w661-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/739#issuecomment-27369

## [v.3.26.0507.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32605070-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32605070-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32605070-NasDHSolutions.json)</sup></sup></sub>


- ✨: Bổ sung kết quả CLS có thêm chữ ký số bác sĩ chỉ định khi hiển thị phiếu kết quả có ký số.
	- Cấu hình mã nhân viên tại vùng chữ ký số của bác sĩ chỉ định: đưa para manv_chidinh vào vùng `<<SIGN:{{[Parameters.manv_chidinh]}}>>` như hình:
	![](https://lh3.googleusercontent.com/pw/AP1GczOYMQQ8k-YJW8OMBmsqu0SEb3v5n8Lcc1Awv3d1Ejbd4xmkWUKWaBlJJpFV253PZEac4vz8WyWq2nsoYrJQMT7Jwe_yi-HPEJy8LldiL_tdx2u_aYducfeTTS1-YkY3XWOzvxUK9Arc0NC4JQvVUipL=w1270-h879-s-no-gm?authuser=0)
	- Kết quả:
	![](https://lh3.googleusercontent.com/pw/AP1GczP6xDuSP-sS8A3b4bBXX-GPKDTIvSKDuKsWXwnfKD92Dkf30YCNXm_5XS0yeJe6xVpREYtVB6NQxfRQ9I6fd6V0rkkLv99lkRBNXow8tJmsP6I4zsPXWhKaz_Pq4YjiGijqzGr4BDeVEFrCfuc6OuSr=w661-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/739#issuecomment-27369

## [v.3.26.0505.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32605050-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32605050-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32605050-NasDHSolutions.json)</sup></sup></sub>
- 🐛:  Labolatory - Diagose: Up load file lên bucket không được- Lỗi
- 🐛:  ***Chỉnh lỗi  không upload được các file pdf lên hệ thống VPS của DH (https://pocketbasedh.dpdns.org).***
- ☑: Nguyên nhân Token hết hạn, bổ sung hàm lấy token mới khi hết hạn.
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/827

## [v.3.26.0424.6]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32604246-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32604246-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32604246-NasDHSolutions.json)</sup></sup></sub>
- 🐛:  Labolatory - Diagose: Up load file lên bucket không được- Lỗi
- 🐛:  ***Chỉnh lỗi  không upload được các file pdf (do Google yêu cầu phải billing bucket). Xử lý chuyển qua hệ thống VPS của DH (https://pocketbasedh.dpdns.org).***
- 🐛: Cài đặt `pocketbase` trên VPS, tạo tài khoản và tích hợp vào code để lưu trữ các pdf từ phía Khách hàng. Triển khai tạm các thông tin cố định và theo dõi hệ thống, khi ổn định sẽ tiến hành cập nhật các thông số cấu hình để thực hiện đa dạng Khách hàng.
![](https://images-worker.tlt43.workers.dev/i/019db94d-7de7-7da8-9d67-007098d1ec50)
![](https://images-worker.tlt24.workers.dev/i/019db94e-3a1b-7553-b212-0b5a420ba5a9)
- []: Cập nhật mô tả [MO_TA_XEM_KET_QUA_CLS_ONLINE_QRCODE.md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/KET%20QUA%20CLS%20ONLINE/MO_TA_XEM_KET_QUA_CLS_ONLINE_QRCODE.md)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/827

## [v.3.26.0424.5]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32604245-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32604245-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32604245-NasDHSolutions.json)</sup></sup></sub>
- 🐛:  Labolatory - Diagose: Up load file lên bucket không được- Lỗi
- 🐛:  ***Chỉnh lỗi  không upload được các file pdf (do Google yêu cầu phải billing bucket). Xử lý chuyển qua hệ thống VPS của DH (https://pocketbasedh.dpdns.org).***
- 🐛: Cài đặt `pocketbase` trên VPS, tạo tài khoản và tích hợp vào code để lưu trữ các pdf từ phía Khách hàng. Triển khai tạm các thông tin cố định và theo dõi hệ thống, khi ổn định sẽ tiến hành cập nhật các thông số cấu hình để thực hiện đa dạng Khách hàng.
![](https://images-worker.tlt43.workers.dev/i/019db94d-7de7-7da8-9d67-007098d1ec50)
![](https://images-worker.tlt24.workers.dev/i/019db94e-3a1b-7553-b212-0b5a420ba5a9)
- []: Cập nhật mô tả [MO_TA_XEM_KET_QUA_CLS_ONLINE_QRCODE.md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/KET%20QUA%20CLS%20ONLINE/MO_TA_XEM_KET_QUA_CLS_ONLINE_QRCODE.md)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/827

## [v.3.26.0424.4]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32604244-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32604244-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32604244-NasDHSolutions.json)</sup></sup></sub>
- 🐛:  Labolatory - Diagose: Up load file lên bucket không được- Lỗi
- 🐛:  ***Chỉnh lỗi  không upload được các file pdf (do Google yêu cầu phải billing bucket). Xử lý chuyển qua hệ thống VPS của DH (https://pocketbasedh.dpdns.org).***
- 🐛: Cài đặt `pocketbase` trên VPS, tạo tài khoản và tích hợp vào code để lưu trữ các pdf từ phía Khách hàng. Triển khai tạm các thông tin cố định và theo dõi hệ thống, khi ổn định sẽ tiến hành cập nhật các thông số cấu hình để thực hiện đa dạng Khách hàng.
![](https://images-worker.tlt43.workers.dev/i/019db94d-7de7-7da8-9d67-007098d1ec50)
![](https://images-worker.tlt24.workers.dev/i/019db94e-3a1b-7553-b212-0b5a420ba5a9)
- []: Cập nhật mô tả [MO_TA_XEM_KET_QUA_CLS_ONLINE_QRCODE.md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/KET%20QUA%20CLS%20ONLINE/MO_TA_XEM_KET_QUA_CLS_ONLINE_QRCODE.md)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/827

## [v.3.26.0424.3]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32604243-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32604243-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32604243-NasDHSolutions.json)</sup></sup></sub>
- 🐛:  Labolatory - Diagose: Up load file lên bucket không được- Lỗi
- 🐛:  ***Chỉnh lỗi  không upload được các file pdf (do Google yêu cầu phải billing bucket). Xử lý chuyển qua hệ thống VPS của DH (https://pocketbasedh.dpdns.org).***
- 🐛: Cài đặt `pocketbase` trên VPS, tạo tài khoản và tích hợp vào code để lưu trữ các pdf từ phía Khách hàng. Triển khai tạm các thông tin cố định và theo dõi hệ thống, khi ổn định sẽ tiến hành cập nhật các thông số cấu hình để thực hiện đa dạng Khách hàng.
![](https://images-worker.tlt43.workers.dev/i/019db94d-7de7-7da8-9d67-007098d1ec50)
![](https://images-worker.tlt24.workers.dev/i/019db94e-3a1b-7553-b212-0b5a420ba5a9)
- []: Cập nhật mô tả [MO_TA_XEM_KET_QUA_CLS_ONLINE_QRCODE.md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/KET%20QUA%20CLS%20ONLINE/MO_TA_XEM_KET_QUA_CLS_ONLINE_QRCODE.md)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/827

## [v.3.26.0424.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32604242-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32604242-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32604242-NasDHSolutions.json)</sup></sup></sub>
- 🐛:  Labolatory - Diagose: Up load file lên bucket không được- Lỗi
- 🐛:  ***Chỉnh lỗi  không upload được các file pdf (do Google yêu cầu phải billing bucket). Xử lý chuyển qua hệ thống VPS của DH (https://pocketbasedh.dpdns.org).***
- 🐛: Cài đặt `pocketbase` trên VPS, tạo tài khoản và tích hợp vào code để lưu trữ các pdf từ phía Khách hàng. Triển khai tạm các thông tin cố định và theo dõi hệ thống, khi ổn định sẽ tiến hành cập nhật các thông số cấu hình để thực hiện đa dạng Khách hàng.
![](https://images-worker.tlt43.workers.dev/i/019db94d-7de7-7da8-9d67-007098d1ec50)
![](https://images-worker.tlt24.workers.dev/i/019db94e-3a1b-7553-b212-0b5a420ba5a9)
- []: Cập nhật mô tả [MO_TA_XEM_KET_QUA_CLS_ONLINE_QRCODE.md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/KET%20QUA%20CLS%20ONLINE/MO_TA_XEM_KET_QUA_CLS_ONLINE_QRCODE.md)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/827

## [v.3.26.0424.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32604241-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32604241-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32604241-NasDHSolutions.json)</sup></sup></sub>
- 🐛:  Labolatory - Diagose: Up load file lên bucket không được- Lỗi
- 🐛:  ***Chỉnh lỗi  không upload được các file pdf (do Google yêu cầu phải billing bucket). Xử lý chuyển qua hệ thống VPS của DH (https://pocketbasedh.dpdns.org).***
- 🐛: Cài đặt `pocketbase` trên VPS, tạo tài khoản và tích hợp vào code để lưu trữ các pdf từ phía Khách hàng. Triển khai tạm các thông tin cố định và theo dõi hệ thống, khi ổn định sẽ tiến hành cập nhật các thông số cấu hình để thực hiện đa dạng Khách hàng.
![](https://images-worker.tlt43.workers.dev/i/019db94d-7de7-7da8-9d67-007098d1ec50)
![](https://images-worker.tlt24.workers.dev/i/019db94e-3a1b-7553-b212-0b5a420ba5a9)
- []: Cập nhật mô tả [MO_TA_XEM_KET_QUA_CLS_ONLINE_QRCODE.md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/KET%20QUA%20CLS%20ONLINE/MO_TA_XEM_KET_QUA_CLS_ONLINE_QRCODE.md)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/827

## [v.3.26.0424.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32604240-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32604240-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32604240-NasDHSolutions.json)</sup></sup></sub>
- 🐛:  Labolatory - Diagose: Up load file lên bucket không được- Lỗi
- 🐛:  ***Chỉnh lỗi  không upload được các file pdf (do Google yêu cầu phải billing bucket). Xử lý chuyển qua hệ thống VPS của DH (https://pocketbasedh.dpdns.org).***
- 🐛: Cài đặt `pocketbase` trên VPS, tạo tài khoản và tích hợp vào code để lưu trữ các pdf từ phía Khách hàng. Triển khai tạm các thông tin cố định và theo dõi hệ thống, khi ổn định sẽ tiến hành cập nhật các thông số cấu hình để thực hiện đa dạng Khách hàng.
![](https://images-worker.tlt43.workers.dev/i/019db94d-7de7-7da8-9d67-007098d1ec50)
![](https://images-worker.tlt24.workers.dev/i/019db94e-3a1b-7553-b212-0b5a420ba5a9)
- []: Cập nhật mô tả [MO_TA_XEM_KET_QUA_CLS_ONLINE_QRCODE.md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/KET%20QUA%20CLS%20ONLINE/MO_TA_XEM_KET_QUA_CLS_ONLINE_QRCODE.md)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/827

## [v.3.26.0423.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32604230-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32604230-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32604230-NasDHSolutions.json)</sup></sup></sub>
- 🐛:  Labolatory - Diagose: Up load file lên bucket không được- Lỗi
- 🐛:  ***Chỉnh lỗi  không upload được các file pdf (do Google yêu cầu phải billing bucket). Xử lý chuyển qua hệ thống VPS của DH (https://pocketbasedh.dpdns.org).***
- 🐛: Cài đặt `pocketbase` trên VPS, tạo tài khoản và tích hợp vào code để lưu trữ các pdf từ phía Khách hàng. Triển khai tạm các thông tin cố định và theo dõi hệ thống, khi ổn định sẽ tiến hành cập nhật các thông số cấu hình để thực hiện đa dạng Khách hàng.
![](https://images-worker.tlt43.workers.dev/i/019db94d-7de7-7da8-9d67-007098d1ec50)
![](https://images-worker.tlt24.workers.dev/i/019db94e-3a1b-7553-b212-0b5a420ba5a9)
- []: Cập nhật mô tả [MO_TA_XEM_KET_QUA_CLS_ONLINE_QRCODE.md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/KET%20QUA%20CLS%20ONLINE/MO_TA_XEM_KET_QUA_CLS_ONLINE_QRCODE.md)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/827

## [v.3.26.0409.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32604090-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32604090-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32604090-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Fix lỗi Form giao diện chính hiển thị các nút bị che khuất.
![](https://lh3.googleusercontent.com/pw/AP1GczN3ovizx_4a7oRnj6DiS92W5pfHjPKIVj82znNOrsYu4p76o8-xLX78GaMugsiPjIXwk9NrUaDhxcDIDqSOJ4ZPYzWWXdSKgqkAzI0sGdsO85KS45tiLeYEzsmbRy9VeMOT1XybVukQhbfjqgxzdUJA=w1654-h879-s-no-gm?authuser=0)
Ngoài ra có thể sử dụng phím tắt F6 để ẩn/hiện cụm điều khiển gọi số.
![](https://lh3.googleusercontent.com/pw/AP1GczOota4WMBzg2ToMGWIaB7FtPHTQ0AmVj5A9JunGme9woxrGOrZqr1IVdTqkeUqCDbUX0NjN3Vm3pb1DjNangHy9FOuTBCL3t1TSWH_HHctC0tpoHLbYvOBVsjpl9KCEfaNs3hlKwXRsRkA2uWRlNK0d=w1654-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/810#issuecomment-25970

## [v.3.26.0331.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32603310-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32603310-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32603310-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Laboratory Sổ xét nghiệm ghi nhận sai BS đọc kết quả và tài khoản chỉ định
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/804

![](https://files.catbox.moe/13pbla.png)

## [v.3.26.0302.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32603021-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32603021-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32603021-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Laboratory Thông tin tuổi và tên đối tượng bị mất khi chuyển CLS từ khám ngoại trú vào Bệnh án ngoại trú theo ngày
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/764

![](https://i.vgy.me/rZBpDN.png)

## [v.3.26.0302.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32603020-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32603020-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32603020-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Laboratory Thông tin tuổi và tên đối tượng bị mất khi chuyển CLS từ khám ngoại trú vào Bệnh án ngoại trú theo ngày
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/764

![](https://i.vgy.me/rZBpDN.png)

## [v.3.26.0210.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32602100-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32602100-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32602100-NasDHSolutions.json)</sup></sup></sub>
- ✨: Cải tiến tốc độ xuất báo cáo Sổ xét nghiệm
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/670

![](https://i.vgy.me/D6j7UH.gif)
![](https://i.vgy.me/tVBqyz.gif)

## [v.3.26.0207.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32602070-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32602070-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32602070-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi Không cảnh báo đóng tiền khi thực hiện cls không thanh bhyt.
![](https://lh3.googleusercontent.com/pw/AP1GczNfMal0vE0hITkFl4un3DVzsMPNhqk5Q2CQsd8joc6fnFhRskD615Gk8at1rsT3scAosuwbdi3HlqPuvv_r5hj2vbVJDfrYSVGLGPhc31pNsenGPQDGoT0Q1a39bM7XqNg2ftbIsS7vkaU0wMIdWKqM=w1654-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/738

## [v.3.26.0205.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32602050-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32602050-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32602050-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi mẫu phiếu kết quả tự thiết kế parameters dvtuoi, ngaysinh chưa load được nội dung.
![](https://lh3.googleusercontent.com/pw/AP1GczPw_8tNL23yAUeY4Wz2wIR0i7lrtn5Hjw5Y_JG913tsJK1SnFvE_MOBkKKwMJmueMs8DBuNXQYKX9X_Ga0QsoDNGKqplcwXciWfnOtNat0M7HQIrBBetP3jEpjTe7V7V_47c5vPetPov75rr1ZJ0JTK=w1654-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/732

## [v.3.26.0203.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32602030-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32602030-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32602030-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Laboratory Bổ sung cột lọc theo tài khoản chỉ định cận lâm sàng trên Sổ xét nghiệm
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/670
- 📕: Lấy thêm thông tin tài khoản chỉ định để thể hiện lên lưới cho Sổ xét nghiệm
- 📕: Bổ sung điều kiện cải thiện tốc độ xuất báo cáo Sổ xét nghiệm ĐKTP CT

![](https://files.catbox.moe/6wrjbk.png)

## [v.3.26.0202.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32602020-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32602020-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32602020-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Admin bổ sung chức năng Ngưng sủ dụng chữ ký số và thêm nút Xóa Chữ ký số
- Cập nhật lại chức năng ký số, khi kiểm tra chứng thư số, chỉ kiểm tra chứng thư số có `current.dmcts.xoa = 0`
[Mô tả](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/Thong-mo-ta-chuc-nang-ngung-su-dung-chu-ky-so.md)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/657

## [v.3.26.0114.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32601141-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32601141-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32601141-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi 
*. Cấu hình nước dịch: Nút đóng bị ẩn:
![](https://lh3.googleusercontent.com/pw/AP1GczOXUajh3Js-MZkErUcssa2gfTpqaoiRJojMCcutfCV6MF4wU0f1rFMToaXwIUJKzPy5Wd7ZU-xNxVQBJ1tIc2S0Y2ouFfUzu7l6WTDTDSXwBx7wzhcSZLNgVfJRPhIJ5fdzs1JJJv1yY2o49S9bOIN5=w1312-h872-s-no-gm?authuser=0)
*. Form thực hiện xét nghiệm sinh thiết: Khi lần đầu bấm vào form thực hiện sinh thiết thì có báo lỗi:
![](https://lh3.googleusercontent.com/pw/AP1GczOt3WK2RWX1iWv4qHf-MMgfEOYwQkV28Cv3tyyLmgewZXR8Ddurqj_ftD2oxaBWPWf8sf4MUpB6XDRkLeQJa-rFNMFQxKhedtQiQWUx5nnoix90c_fuvQLHad3G5Pax3zD2C2FwFN_alosm8_q3e8yX=w1231-h879-s-no-gm?authuser=0)
![](https://lh3.googleusercontent.com/pw/AP1GczMaVVWpmPOvl53bcQhY7g9kikiqyKlkXoM_gcnQJ1KuBsJklgiVHZs1EulyLcON20SKJyBiJ3ERLGqi6DAVWIgyLmfJaEOXTmn2G4VhmRoewUfmG2fXmYFUJMywENG7T7E8Nztfi_P8UnlqGfErRhmb=w679-h879-s-no-gm?authuser=0)
*. Xuất điều về: Khi click vào nút Xuất điều về có lỗi:
![](https://lh3.googleusercontent.com/pw/AP1GczNh7zsPvGpGRa0lJJDWj3em0rfC7UACv2-XCO8HGrBIStzcwhbFXZw3V9euHuMKRflS0oHvGw2G6qQZ6gEsv3mEPyn9sTTq6k3JGRd6RzaBJazow_GrPxdvlpjL5clnN50gr3HeXXC_78lb0Rf3RrbC=w1293-h872-s-no-gm?authuser=0)
*. Định nghĩa danh mục: Có dư một dấu cách trong chữ nghĩ a: đây là font `Microsoft Sans Serif`, font mặc định của Windows nó hiển thị chữ `ĩ` hơi giãn tí, chứ `không phải dư dấu cách`.
*. Báo cáo: Sổ XN tế bào ngoại vi: Không có dữ liệu:
Nguyên nhân: do cấu hình mã xét nghiệm không đúng/không có trong danh mục: Nên sổ không load được dữ liệu.
![](https://lh3.googleusercontent.com/pw/AP1GczPLwRYsMecg6MyDeKaERTa1DyOFIr6F3YNDhWSRCTKbMUCCYog1zRpak-fEsoZnOCWsXBcvJTWwO_DZXHiUj2tEvNBPKzz7k1_UOhHi-ySD0bFbFkAprbu9pIMyCiKprmlHKykP5WnG67lkpMVhwcPy=w1509-h879-s-no-gm?authuser=0)
*. Lỗi khi đăng nhập (dữ liệu emr_dktp):
![](https://lh3.googleusercontent.com/pw/AP1GczMpDCIpCtqfjx8a-vWmylV5LKVz7kAEcAqEQ5lLOwsAuji5FmnSNGAyYEHPKRqcauZBO2iADQtvxSJ6Iaj0nG3c96WMCclUb2P-JuaCVgJaFzoCpRVqWkefBS5nUDYtnfJ0rraoT9GMPnGTvY1Kg-Xv=w1206-h872-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/TOLAPTRINH/issues/101

## [v.3.26.0114.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32601140-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32601140-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32601140-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Laboratory : bệnh nhân đối tượng Thu phí đã đóng tiền nhưng khi bấm nút Lấy mẫu báo Bệnh nhân chưa đóng tiền
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/691
- 📕: Sai do cộng chi phí lại cho đối tượng thu phí hoặc KSK tại hàm FrmDanhSach.CheckLayMau

![](https://files.catbox.moe/bfp3bb.png)

## [v.3.26.0113.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32601130-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32601130-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32601130-NasDHSolutions.json)</sup></sup></sub>

- ✨: Chức năng cập nhật: `Không sử dụng SELECT *`
*. Các chức năng:
   + Các form Cấu hình xét nghiệm.
   + Form danh sách xét nghiệm: thực hiện, lấy mẫu, bỏ lấy mẫu.
   + Form thực hiện xét nghiệm.
   + Form thực hiện xét nghiệm sinh thiết.
   + Form thực hiện xét nghiệm tế bào tử cung.
   + Form thực hiện xét nghiệm Covid19.
   + Form thực hiện xét nghiệm đờm.
   + Các form tại menu quản lý kho xét nghiệm.

*. Báo cáo:
   + Sổ XN tế bào ngoại vi
   + Sổ XN Vi sinh
- ☑: https://i.dh-his.com/hdhiswork/TOLAPTRINH/issues/101

## [v.3.26.0106.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32601060-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32601060-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32601060-NasDHSolutions.json)</sup></sup></sub>
- ✨: DỰ ÁN XEM KẾT QUẢ CLS TRÊN WEB
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/28

- Sử dụng chức năng xem kết quả online và huỷ kết quả theo option bổ sung

![](https://i.vgy.me/rM52ld.png)

## [v.3.26.0103.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32601030-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32601030-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32601030-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Xuất Excel theo lưới bị ký tự lỗi của XML 
- ![](https://images-worker.tlt14.workers.dev/i/019b82f9-94fb-7cd7-8a81-ac47fcdc2e7a)
![](https://images-worker.tlt15.workers.dev/i/019b82f9-76eb-7aa6-a748-06a4bbb34173)

## [v.3.25.1218.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32512181-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32512181-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32512181-NasDHSolutions.json)</sup></sup></sub>
- ✨: DỰ ÁN XEM KẾT QUẢ CLS TRÊN WEB
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/28
- 📕: Gọi xoá pdf kết quả khi huỷ kết quả Xét nghiệm, bổ sung thông báo để xác nhận huỷ kết quả - Build lại lấy toàn bộ dll mới

![](https://i.vgy.me/WuphWy.png)

## [v.3.25.1218.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32512180-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32512180-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32512180-NasDHSolutions.json)</sup></sup></sub>
- ✨: DỰ ÁN XEM KẾT QUẢ CLS TRÊN WEB
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/28
- 📕: Gọi xoá pdf kết quả khi huỷ kết quả CDHA, bổ sung thông báo để xác nhận huỷ kết quả rebuild

![](https://i.vgy.me/WuphWy.png)

## [v.3.25.1210.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32512100-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32512100-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32512100-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Laboratory nhập kết quả đối với cls không check thực hiện (BV Cái Răng)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/555

- 📗: Cập nhật cấu trúc thêm tham số theo mô tả [DANH_SACH_XET_NGHIEM_THUC_HIEN.md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/XETNGHIEM/DANH_SACH_XET_NGHIEM_THUC_HIEN.md)
- 📕: Chỉnh lại điều kiện khi lấy danh sách xét nghiệm lên Form danh sách dựa vào tham số xn.danhsachxn

![](https://files.catbox.moe/52gxdg.png)

![](https://files.catbox.moe/o86xf7.png)

![](https://files.catbox.moe/4idad2.png)

## [v.3.25.1209.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32512090-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32512090-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32512090-NasDHSolutions.json)</sup></sup></sub>
- ✨: DỰ ÁN XEM KẾT QUẢ CLS TRÊN WEB
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/28
- 📕: Gọi xoá pdf kết quả khi huỷ kết quả CDHA, bổ sung thông báo để xác nhận huỷ kết quả

![](https://files.catbox.moe/nup1b1.png)

## [v.3.25.1203.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32512030-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32512030-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32512030-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Laboratory: BV Tam Nông: Không hủy được kết quả xét nghiệm
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/650

![](https://files.catbox.moe/mj6woh.gif)

## [v.3.25.1202.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32512020-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32512020-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32512020-NasDHSolutions.json)</sup></sup></sub>
- ✨: DỰ ÁN XEM KẾT QUẢ CLS TRÊN WEB
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/28
- 📕: Điều chỉnh sinh ra UUID bệnh nhân để gán vào QRCode xem kết quả CLS online không dựa vào ngaykcb

![](https://files.catbox.moe/5olho4.png)

## [v.3.25.1201.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32512012-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32512012-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32512012-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Không hiển thị tên BS đọc KQ trên phiếu kết quả XN
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/645

![](https://files.catbox.moe/7ejqlu.png)

## [v.3.25.1201.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32512011-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32512011-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32512011-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Không hiển thị tên BS đọc KQ trên phiếu kết quả XN
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/645

![](https://files.catbox.moe/7ejqlu.png)

## [v.3.25.1201.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32512010-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32512010-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32512010-NasDHSolutions.json)</sup></sup></sub>
- ✨: DỰ ÁN XEM KẾT QUẢ CLS TRÊN WEB
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/28
- 📕: Bổ sung QRCode xem kết quả CLS Online lên phiếu lấy mẫu

![](https://files.catbox.moe/l3s1uz.png)

---

- ✨: Yêu cầu - Laboratory Mẫu kết quả xét nghiệm tự thiết kế in theo tên chỉ số xét nghiệm (BV Thạnh Trị)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/584

- 📕: Bổ sung para tenchiso và tencls_uutien_tenchiso lên design mẫu kết quả Xét nghiệm

![](https://files.catbox.moe/qhqz9v.png)
![](https://files.catbox.moe/v0bbww.png)

## [v.3.25.1128.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511281-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511281-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511281-NasDHSolutions.json)</sup></sup></sub>
- ✨: DỰ ÁN XEM KẾT QUẢ CLS TRÊN WEB
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/28
- 📕: Build lại file cài đặt 

![](https://files.catbox.moe/yfljvo.png)


- 🐛: Lỗi - Laboratory: Form xét nghiệm chưa hiển thị nút BADT - Hủy ký số
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/643

![](https://files.catbox.moe/raynzs.png)

## [v.3.25.1128.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511280-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511280-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511280-NasDHSolutions.json)</sup></sup></sub>
- ✨: DỰ ÁN XEM KẾT QUẢ CLS TRÊN WEB
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/28
- 📕: Xử lý lại khi cấp QRCode xem kết quả online

![](https://files.catbox.moe/skvfg2.png)

## [v.3.25.1127.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511271-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511271-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511271-NasDHSolutions.json)</sup></sup></sub>
- ✨: DỰ ÁN XEM KẾT QUẢ CLS TRÊN WEB
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/28
- 📕: Thay đổi xử lý metadata cho file PDF

## [v.3.25.1127.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511270-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511270-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511270-NasDHSolutions.json)</sup></sup></sub>
- ✨: DỰ ÁN XEM KẾT QUẢ CLS TRÊN WEB
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/28
- 📕: Tạo QRCode để quét xem kết quả xét nghiệm WEB

![](https://files.catbox.moe/y3n5n1.gif)
![](https://files.catbox.moe/0liub8.png)
![](https://files.catbox.moe/wr8zm4.png)

## [v.3.25.1126.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511260-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511260-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511260-NasDHSolutions.json)</sup></sup></sub>
- ✨: DỰ ÁN XEM KẾT QUẢ CLS TRÊN WEB
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/28

- Thêm QRCode cho phiếu kết quả xét nghiệm để View kết quả web
- Lưu trữ file kết quả dạng pdf 

![](https://files.catbox.moe/b2p7jt.png)

## [v.3.25.1124.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511241-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511241-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511241-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Laboratory Bổ sung para đối với mẫu kết quả KSK Hợp đồng (BV Cái răng)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/577
- 📕: Bổ sung 4 para mới vào design phiếu kết quả Xét nghiệm

![](https://files.catbox.moe/3q0kei.png)

![](https://files.catbox.moe/vsg744.png)

## [v.3.25.1124.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511240-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511240-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511240-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Laboratory phục hồi lại một số chức năng cơ bản của thao tác như bản cũ trước đó (năm 2024)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/571

![](https://files.catbox.moe/f3kibe.png)

![](https://files.catbox.moe/sllhqt.gif)

## [v.3.25.1121.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511210-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511210-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511210-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Điều chỉnh cột bang3.ngay_kq theo mô tả XML4750.
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/627

## [v.3.25.1120.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511200-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511200-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511200-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi kết quả xét nghiệm không lấy được ngày kết quả.
![](https://lh3.googleusercontent.com/pw/AP1GczMpGk5h7sSS6hopicouPtsW-qI0-74sKuTuu2sXOXJUAoSVaAAzYDCJy6RWyYjSMrvM7CLFaFCURjNzaHA70xXwHiH5own_BRRUVocZ16PckosXD9Q_BnjbDRoOlGvpLDdQYmPliIwRnUF9h-rnPmXx=w1654-h879-s-no-gm?authuser=0)

- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/627

## [v.3.25.1119.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511190-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511190-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511190-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Fix phát sinh lỗi khi xem kết quả nếu tham số khác 8|9
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/626

![](https://files.catbox.moe/1rqxmq.png)

## [v.3.25.1114.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511140-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511140-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511140-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Fix không ký số được SoftDream
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/560

![](https://files.catbox.moe/cbz8p5.gif)

## [v.3.25.1113.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511130-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511130-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511130-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Tài khoản không cấu hình ký số SoftDream vào xem kết quả xét nghiệm bác sĩ khác không view được kết quả
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/560

![](https://files.catbox.moe/ze9j2z.png)

![](https://files.catbox.moe/35a6sv.png)

![](https://files.catbox.moe/uje9gu.png)

## [v.3.25.1112.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511122-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511122-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511122-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Fix không ký số được SoftDeam 
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/560

![](https://files.catbox.moe/vz6nhy.png)

- 🐛: Fix sai logic kiểm tra số phút tối thiểu gây ra lỗi vẫn lấy mẫu được khi tham số xn.canhbaovuotthoigian = 0
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/562

![](https://files.catbox.moe/pt9yr1.gif)

## [v.3.25.1112.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511121-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511121-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511121-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Laboratory: Thao tác Lấy mẫu bắt theo tham số xn.sophuttoithieu
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/562
- 📕: Bổ sung kiểm tra thêm số phút tối thiểu theo tham số bằng cách lấy ngày chỉ định lớn nhất của các xét nghiệm chọn lấy mẫu để kiểm tra với thời gian hiện tại của hệ thống.
- 📕: Khi không hợp lệ thì sẽ Chặn hoặc Cảnh báo theo tham số xn.canhbaovuotthoigian

![](https://files.catbox.moe/1ebewi.png)
![](https://files.catbox.moe/dr2wuv.png)

## [v.3.25.1112.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511120-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511120-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511120-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Không copy ID khi click Lấy mẫu như bản cũ
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/560

![](https://files.catbox.moe/a56zne.gif)

## [v.3.25.1111.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511110-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511110-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511110-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Laboratory: Hiển thị màu danh sách bệnh nhân xét nghiệm
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/559
- 📕: Bổ sung thêm thông tin dath để thay đổi trạng thái màu của danh sách bệnh nhân xét nghiệm trên Labor

![](https://files.catbox.moe/e31as0.png)

## [v.3.25.1107.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511071-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511071-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511071-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Laboratory: Giao diện hiển thị danh sách các chỉ định xét nghiệm
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/556

![](https://files.catbox.moe/fjqmth.png)

## [v.3.25.1107.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511070-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511070-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511070-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Laboratory: Giao diện hiển thị danh sách các chỉ định xét nghiệm
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/556
- 📕: Điều chỉnh giao diện danh sách xét nghiệm phù hợp với màn hình độ phân giải thấp

![](https://files.catbox.moe/54he1y.gif)

## [v.3.25.1105.2]()
- ✨: Rà soát cách kiểm soát hạn triển khai các phân hệ Diagnose, Laboratory

## [v.3.25.1105.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511051-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511051-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511051-NasDHSolutions.json)</sup></sup></sub>
- ✨: Cập nhật key theo private code: `leddia_release` `ledlabo_release` `dieuphoilabo_release`

## [v.3.25.1105.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511050-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511050-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32511050-NasDHSolutions.json)</sup></sup></sub>
- ✨: Cập nhật key theo private code
![](https://storage.googleapis.com/calf-sure-sawfly.appspot.com/2025/11/05/DESKTOP-2FLMTI6-sidekick-2025-11-05-09h11p52.568.png)
![](https://storage.googleapis.com/calf-sure-sawfly.appspot.com/2025/11/05/DESKTOP-2FLMTI6-sidekick-2025-11-05-09h11p45.051.png)
![](https://storage.googleapis.com/calf-sure-sawfly.appspot.com/2025/11/05/DESKTOP-2FLMTI6-explorer-2025-11-05-09h11p36.230.png)
![](https://storage.googleapis.com/calf-sure-sawfly.appspot.com/2025/11/05/DESKTOP-2FLMTI6-explorer-2025-11-05-09h06p52.685.png)
![](https://storage.googleapis.com/calf-sure-sawfly.appspot.com/2025/11/05/DESKTOP-2FLMTI6-explorer-2025-11-05-09h06p22.830.png)
![](https://storage.googleapis.com/calf-sure-sawfly.appspot.com/2025/11/05/DESKTOP-2FLMTI6-explorer-2025-11-05-08h09p43.535.png)

## [v.3.25.1031.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32510310-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32510310-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32510310-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Laboratory: tham số xn.sudungmauchuan=8 Hỗ trợ phiếu kết quả gom tất cả các Xét nghiệm trên cùng một phiếu và nhóm theo loại cls
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/463

- 📗: Bổ sung cấu trúc theo mô tả
- 📗: Mô tả : [CAU_HINH_PHIEUYC_PHIEUKQ_THEO_MA_LOAI_CLS.md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/Quan-tri-Admin/CAU_HINH_PHIEUYC_PHIEUKQ_THEO_MA_LOAI_CLS.md)

![](https://files.catbox.moe/w5wgu7.png)

![](https://files.catbox.moe/tbec6b.png)

## [v.3.25.1028.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32510280-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32510280-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32510280-NasDHSolutions.json)</sup></sup></sub>

- ✨: Điều chỉnh ngày kết quả trên các sổ kết quả khớp với ngày kết quả của xuất XML4750/XML3176.
![](https://lh3.googleusercontent.com/pw/AP1GczMvA6w08ZHlAvFlO55X9cCsnkEXgDVHe900SigD91zK0OgRGD8O3_u9eTtkQkHOckBmKhRD50XpXIWloYDM7uY-10t8vWBMlGGBA7gdE6wdMT0a8gYCTF6OvWUj6ciQaxkoHmiiO6OYyPWN01C1UZXc=w1573-h879-s-no-gm?authuser=0)
![](https://lh3.googleusercontent.com/pw/AP1GczPG3LsHpnCJWI4mZJYH2ep6kK9KL2L-zCxExNg1LW6vqI4RztuHcdh6MatjcD-Il-9emx-z3YQ6UCxRuC8YJfxLT56s-9w3upAQB4778BN2ppzF8cE9lAMigtoevcpIJDAg4DhjwBHbV8dsr2b7jjZc=w1584-h879-s-no-gm?authuser=0)

- ☑: https://i.dh-his.com/hdhiswork/TOLAPTRINH/issues/68

## [v.3.25.1023.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32510230-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32510230-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32510230-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Laboratory không ký số được phiếu Kết quả xét nghiệm
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/584

- Thể hiện ký số bằng Form Preview
![](https://files.catbox.moe/ae6f7r.png)

## [v.3.25.1022.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32510222-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32510222-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32510222-NasDHSolutions.json)</sup></sup></sub>
- 🐛:  Lỗi - Laboratory Bảng kê xét nghiệm không hiển thị macls - tên cận lâm sàng, tên cls phụ (Ghi chú) - LOI - dh-issue- #583
- 🐛:  ***Chỉnh lỗi không tenclsphu lúc chỉ định trong phần bảng kê cls.*** 
![](https://storage.googleapis.com/accurately-sharp-katydid.appspot.com/ShareX/2025/10/DESKTOP-2FLMTI6-explorer-2025-10-22-14h07p15.962.png)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/583#issuecomment-17391

## [v.3.25.1022.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32510221-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32510221-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32510221-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Fix không ký số khi Xem kết quả xét nghiệm theo tham số xn.sudungmauchuan = 8 
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/584

![](https://files.catbox.moe/ei6gjf.png)

## [v.3.25.1022.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32510220-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32510220-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32510220-NasDHSolutions.json)</sup></sup></sub>
- 🐛:  Lỗi - Laboratory Bảng kê xét nghiệm không hiển thị macls - tên cận lâm sàng, tên cls phụ (Ghi chú) - LOI - dh-issue- #583
- 🐛:  ***Chỉnh lỗi không in được bảng kê.*** 
![](https://storage.googleapis.com/accurately-sharp-katydid.appspot.com/ShareX/2025/10/DESKTOP-2FLMTI6-explorer-2025-10-22-11h09p40.466.png)
![](https://storage.googleapis.com/accurately-sharp-katydid.appspot.com/ShareX/2025/10/DESKTOP-2FLMTI6-explorer-2025-10-22-10h56p45.061.png)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/583#issuecomment-17391

## [v.3.25.1020.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32510200-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32510200-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32510200-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Fix không ký số mẫu kết quả miễn dịch
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/5

- Đã bổ sung ký số cho mã loại MD = OTH.Entity.Enum.LoaiPhieuKySoEnum.EMR_XN_MIENDICH
![](https://files.catbox.moe/fhabmp.png)

## [v.3.25.1016.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32510160-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32510160-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32510160-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Laboratory: Hiển thị sai tiêu đề loại xét nghiệm
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/578

- Lấy đúng tên theo mã loại cho phiếu kết quả Xét nghiệm chung

![](https://files.catbox.moe/ep3l6j.gif)

## [v.3.25.1003.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32510031-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32510031-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32510031-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Fix không cho xem trước phiếu kết quả Cồn
- 🐛: Fix chỉ in kết quả các Xét nghiệm đang chọn
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/60

![](https://i.vgy.me/OuPoVt.gif)

## [v.3.25.1003.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32510030-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32510030-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32510030-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi hiển thị sai giới tính tại form Chỉ số độ thanh thải cầu thận (GFR).
![](https://lh3.googleusercontent.com/pw/AP1GczOZNTneQomEWMM2OctQ9Z-STZGf5LvX7eceAjGpDWwP7VWxTaDJ4ggWzF6S57-65B50iGoCZarqOoE3duDu6-WAi6DAmES1UxATZ-r8s2GtK-o3Q4oQEu3ULVAqqqGJDe6z97g-fU52MJd6K0wlRFhG=w1654-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/540

## [v.3.25.0925.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509250-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509250-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509250-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Bổ sung chức năng ngưng sử dụng mã máy thực hiện cls (BV Thanh Bình)
- ✨: Khi load danh sách máy thực hiện CLS thêm điều kiện xoa = 0.
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/448

## [v.3.25.0924.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509241-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509241-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509241-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - BV Ô Môn: Báo cáo chi tiết lượt chỉ định theo XN báo CLS XN đờm chưa thực hiện không xem được kết quả #521
	- Cập nhật: fix còn hiển thị thông báo chưa có kết quả
		![](https://i.vgy.me/ZXogIw.gif)

- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/521
<<<<<<< HEAD

## [v.3.25.0924.0]()
- 🐛: Lỗi - BV Ô Môn: Báo cáo chi tiết lượt chỉ định theo XN báo CLS XN đờm chưa thực hiện không xem được kết quả #521
	- Cập nhật: fix còn hiển thị thông báo chưa có kết quả
		![](https://i.vgy.me/ZXogIw.gif)

- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/521

=======

## [v.3.25.0923.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509231-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509231-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509231-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Laboratory: Không load được kết quả XN từ LIS LabConn
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/531

![](https://i.vgy.me/siJtfm.gif)

## [v.3.25.0923.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509230-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509230-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509230-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - BV Ô Môn: Báo cáo chi tiết lượt chỉ định theo XN báo CLS XN đờm chưa thực hiện không xem được kết quả #521
	- Cập nhật:
		![](https://i.vgy.me/DeBifi.png)

	- 🐛: Lỗi - Laboratory: Không thực hiện được CLS miễn giảm 100% #515
	- Cập nhật:
		![](https://i.vgy.me/qfycfQ.gif)

- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/521
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/515

## [v.3.25.0919.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509192-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509192-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509192-NasDHSolutions.json)</sup></sup></sub>
- ✨: Bệnh án điện tử tích hợp với DHS #5
- ✨: Fix lỗi - khi in ký số EMR thì lable ##{S1}##,##{S2}## đổi sang màu trắng nhưng khi in thường thì vẫn là màu đen
![](https://i.vgy.me/DFRtqy.gif)
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/5

## [v.3.25.0919.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509191-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509191-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509191-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Fix truyền sai request.UserCode khi gọi ký số tại HOSO.BADTKyso.KySoEMR gây ra lỗi khi huỷ ký số
- ☑: https://i.dh-his.com/hdhiswork/TOLAPTRINH/issues/27

![](https://i.vgy.me/tSvtAO.png)

## [v.3.25.0919.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509190-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509190-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509190-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Fix lỗi không xem kết quả được với Xét nghiệm Vi sinh
- ☑: https://i.dh-his.com/hdhiswork/TOLAPTRINH/issues/27

![](https://i.vgy.me/S9GbXz.png)

## [v.3.25.0917.3]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509173-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509173-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509173-NasDHSolutions.json)</sup></sup></sub>
- ✨: Thử nghiệm ký số kết quả Xét nghiệm
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/5

![](https://i.vgy.me/qWfer2.png)

## [v.3.25.0917.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509172-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509172-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509172-NasDHSolutions.json)</sup></sup></sub>
- ✨: Bệnh án điện tử tích hợp với DHS #5
- ✨: Thêm thông báo khi không tìm thấy loại phiếu
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/5

## [v.3.25.0917.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509171-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509171-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509171-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Labolatory: Bổ sung lại check lọc những BN đã XN. #441
	- Cập nhật: 
		- Chọn tất cả
		![](https://i.vgy.me/W6tcyW.png)

		- Có ít nhất 1 XN đã lấy mẫu
		![](https://i.vgy.me/rRqZap.png)

		- Có ít nhất 1 XN chưa thực hiện
		![](https://i.vgy.me/tQOfWO.png)

		- Tất cả các XN đã thực hiện
		![](https://i.vgy.me/bUm5FB.png)

- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/441
<<<<<<< HEAD

## [v.3.25.0917.0]()
- ✨: Yêu cầu - Labolatory: Bổ sung lại check lọc những BN đã XN. #441
	- Cập nhật: 
		- Chọn tất cả
		![](https://i.vgy.me/W6tcyW.png)

		- Có ít nhất 1 XN đã lấy mẫu
		![](https://i.vgy.me/rRqZap.png)

		- Có ít nhất 1 XN chưa thực hiện
		![](https://i.vgy.me/tQOfWO.png)

		- Tất cả các XN đã thực hiện
		![](https://i.vgy.me/bUm5FB.png)

- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/441
=======

## [v.3.25.0916.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509160-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509160-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509160-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Fix sai điều kiện ký số EMR gây ra lỗi không Preview được kết quả Xét nghiệm
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/60

- Fix lỗi không Preview kết quả

![](https://i.vgy.me/TNJ0UT.png)

![](https://i.vgy.me/2URq7Z.png)

## [v.3.25.0915.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509152-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509152-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509152-NasDHSolutions.json)</sup></sup></sub>
- ✨: Bệnh án điện tử tích hợp với DHS #5
- 🐛: Fix lỗi khi in ký số EMR, phần lable đặt chữ ký chưa đổ sang màu trắng
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/5

## [v.3.25.0915.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509151-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509151-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509151-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Fix lỗi sai điều kiện manv khi chỉ định CLS tự do gây ra lỗi không lấy mẫu được
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/60

![](https://i.vgy.me/I6sJzQ.png)

## [v.3.25.0915.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509150-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509150-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509150-NasDHSolutions.json)</sup></sup></sub>
- ✨: Bệnh án điện tử tích hợp với DHS #5
- 🐛: Fix lỗi ký số EMR - phát sinh lỗi khi update lại xmlreport
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/5

## [v.3.25.0913.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509131-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509131-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509131-NasDHSolutions.json)</sup></sup></sub>
- ✨: Bệnh án điện tử tích hợp với DHS.
- ✨: Kiểm tra khi ký số EMR, nếu chưa có lable hiển thị chữ ký thì tự động thêm vào.
[Mô tả thực hiện](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/Thong-mo-ta-cap-nhat-chuc-nang-ky-so-BADT-EMR.md)
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/5

## [v.3.25.0913.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509130-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509130-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509130-NasDHSolutions.json)</sup></sup></sub>
- ✨: Tích hợp ký số EMR đối với các phiếu Xét nghiệm
![](https://i.vgy.me/v4JJ0V.png)
![](https://i.vgy.me/IX77SI.png)
![](https://i.vgy.me/CdKiXE.png)
![](https://i.vgy.me/pvEtus.png)
![](https://i.vgy.me/Q86nsA.png)	
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/5

## [v.3.25.0912.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509121-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509121-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509121-NasDHSolutions.json)</sup></sup></sub>
-- 🐛: Bấm làm mới dữ liệu, sau đó tìm Tên BN -> bấm enter thì lọc được tên BN nhưng không load được CLS đã được chỉ định, nếu trong ds tìm được có nhiều tên BN, thì chọn qua chọn lại thì mới thấy được CLS
	- Cập nhật:
		![](https://i.vgy.me/uFTvTG.png)
		![](https://i.vgy.me/xl6onZ.png)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/484
<<<<<<< HEAD

## [v.3.25.0912.0]()
- 🐛: Bấm làm mới dữ liệu, sau đó tìm Tên BN -> bấm enter thì lọc được tên BN nhưng không load được CLS đã được chỉ định, nếu trong ds tìm được có nhiều tên BN, thì chọn qua chọn lại thì mới thấy được CLS
	- Cập nhật:
		![](https://i.vgy.me/uFTvTG.png)
		![](https://i.vgy.me/xl6onZ.png)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/484
=======

## [v.3.25.0910.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509102-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509102-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509102-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Yêu cầu - BV Nghĩa Hành: Đổi mẫu xét nghiệm qua mẫu XN theo thông tư 32
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/60

- Fix không show preview mẫu chung

![](https://i.vgy.me/QVGWiL.png)

- Các phiếu được tách ra theo thống nhất qui trình và mô tả

![](https://i.vgy.me/P49oUr.png)

- Test lại lấy mẫu các CLS được chỉ định thêm sau

![](https://i.vgy.me/OQfILS.gif)

## [v.3.25.0910.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509101-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509101-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509101-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Labolatory: Không cập nhật được trang thái lấy mẫu sau khi hủy lấy mẫu #484
	- Cập nhật:
		- Bỏ và lấy mẫu:
		![](https://i.vgy.me/gbsved.png)
		![](https://i.vgy.me/LTIBNq.png)

		- Chọn lại ngày thực hiện:
		![](https://i.vgy.me/o9C9lF.png)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/484
<<<<<<< HEAD

## [v.3.25.0910.0]()
- 🐛: Lỗi - Labolatory: Không cập nhật được trang thái lấy mẫu sau khi hủy lấy mẫu #484
	- Cập nhật:
		- Bỏ và lấy mẫu:
		![](https://i.vgy.me/gbsved.png)
		![](https://i.vgy.me/LTIBNq.png)

		- Chọn lại ngày thực hiện:
		![](https://i.vgy.me/o9C9lF.png)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/484
=======

## [v.3.25.0909.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509091-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509091-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509091-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - BV Nghĩa Hành: Đổi mẫu xét nghiệm qua mẫu XN theo thông tư 32
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/60

- Chỉnh lại design mẫu Nước dịch

![](https://i.vgy.me/9Gnf8K.png)

![](https://i.vgy.me/yos8qA.png)

## [v.3.25.0909.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509090-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509090-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509090-NasDHSolutions.json)</sup></sup></sub>
- ✨:  Kiểm lỗi không thực hiện được xét nghiệm đối với trường hợp Nội trú - cấp cứu nhưng vẫn cảnh báo đóng tiền. - TOLAPTRINH - dh-issue- #12
- ✨:  ***Chỉnh lỗi Xét nghiệm không cảnh báo chưa đóng tiền đối với Bệnh nhân ngoại trú BHYT có chỉ định BHYT không thanh và tham số `bhytthuchenhlech=1`.*** ![](https://live.staticflickr.com/65535/54775133431_8937d8a296_b.jpg)
- ☑: https://i.dh-his.com/hdhiswork/TOLAPTRINH/issues/12

## [v.3.25.0908.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509081-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509081-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509081-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Các module liên quan hoàn thiện Chữ ký số theo cách mới
![](https://i.vgy.me/rpwi3W.png)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/436

## [v.3.25.0908.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509080-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509080-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32509080-NasDHSolutions.json)</sup></sup></sub>
- ✨:  Kiểm lỗi không thực hiện được xét nghiệm đối với trường hợp Nội trú - cấp cứu nhưng vẫn cảnh báo đóng tiền. - TOLAPTRINH - dh-issue- #12
- ✨:  ***Chỉnh lỗi khi lấy mẫu lại bắt kiểm tra tiền CLS đối với trường hợp cấp cứu..*** ![](https://live.staticflickr.com/65535/54772522936_4e3621b842_b.jpg) ![](https://live.staticflickr.com/65535/54773257414_2e6a5f3c49_b.jpg)
- ☑: https://i.dh-his.com/hdhiswork/TOLAPTRINH/issues/12

## [v.3.25.0829.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32508290-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32508290-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32508290-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - BV Nghĩa Hành: Đổi mẫu xét nghiệm qua mẫu XN theo thông tư 32 rebuild
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/60

- Sửa thiết kế kết quả XN thông tư 32

![](https://i.vgy.me/v94AFu.png)

![](https://i.vgy.me/10Varw.png)

![](https://i.vgy.me/pKrqOe.png)

![](https://i.vgy.me/9C1w2t.png)

![](https://i.vgy.me/aoMDZj.png)

![](https://i.vgy.me/FofCm5.png)

## [v.3.25.0828.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32508280-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32508280-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32508280-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - BV Nghĩa Hành: Đổi mẫu xét nghiệm qua mẫu XN theo thông tư 32
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/60

- Sửa thiết kế kết quả XN thông tư 32

![](https://i.vgy.me/v94AFu.png)
![](https://i.vgy.me/10Varw.png)
![](https://i.vgy.me/pKrqOe.png)
![](https://i.vgy.me/9C1w2t.png)
![](https://i.vgy.me/aoMDZj.png)
![](https://i.vgy.me/FofCm5.png)

## [v.3.25.0826.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32508260-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32508260-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32508260-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - BV Nghĩa Hành: Đổi mẫu xét nghiệm qua mẫu XN theo thông tư 32
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/60

-  Điều chỉnh hoàn thiện các trang in kết quả Xét nghiệm TT32

- Huyết học 

![](https://i.vgy.me/vRiv5l.png)

- Đông cầm máu

![](https://i.vgy.me/Q5YURt.png)

- Nước dịch

![](https://i.vgy.me/FpmyBK.png)

- Hoá sinh máu

![](https://i.vgy.me/t5a0ZH.png)

- Nước tiểu

![](https://i.vgy.me/Fiucft.png)

- Vi sinh

![](https://i.vgy.me/3W8kFS.png)

![](https://i.vgy.me/GtL9ay.png)

## [v.3.25.0825.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32508250-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32508250-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32508250-NasDHSolutions.json)</sup></sup></sub>
- 🐛: LỖI - LABORATORY - Mẫu trả kết quả Xét nghiệm Tiêu đề tên cơ quan chủ quản, Tên BV, SĐT không lấy theo Key #467
	
	- Cập nhật: fix lỗi phiếu xn
	![](https://i.vgy.me/XYYLkk.png)
	![](https://i.vgy.me/iLQ5tv.png)

- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/467

## [v.3.25.0822.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32508220-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32508220-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32508220-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - BV Nghĩa Hành: Đổi mẫu xét nghiệm qua mẫu XN theo thông tư 32
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/60

- Fix thông báo sai giờ lấy mẫu
- Fix không hiển thị tên cán bộ XN và người thực hiện
- Trả kết quả nhiều loại CLS khi chỉnh kết quả thì các loại khác mất người thực hiện và người đọc kết quả => do 2 lý do trên
- Fix key còn hạn vẫn báo PHIÊN BẢN KHÔNG HỖ TRỢ
- Fix không in đậm khi kết quả có check bất thường
- Fix lấy sai ngày kết quả
- Fix gán giá trị sai tên người ký

![](https://i.vgy.me/3xPhms.png)

![](https://i.vgy.me/K7KvwE.png)

![](https://i.vgy.me/qPhyEp.png)

![](https://i.vgy.me/GiDj1Q.png)

![](https://i.vgy.me/H8QzC2.png)

![](https://i.vgy.me/rcToAw.png)

## [v.3.25.0731.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32507310-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32507310-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32507310-NasDHSolutions.json)</sup></sup></sub>
- ✨: Bổ sung Phiếu chỉ định và phiếu kết quả Sinh thiết, Tế bào tử cung tự thiết kế
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/5
- 📕: Bắt theo tham số tại Form kết quả Sinh thiết, Tế bào tử cung chuyển sang mẫu tự thiết kế

[Clip Test](https://gofile.me/78TQg/n41bi6d1L)

## [v.3.25.0724.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32507240-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32507240-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32507240-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - BV Nghĩa Hành: Đổi mẫu xét nghiệm qua mẫu XN theo thông tư 32
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/60

- Cập nhật script thêm cột dmcls.inhieuchuan, dmcls.stthieuchuan, update tham số xn.sudungmauchuan theo Mô tả [Mau-Xet-Nghiem.md](https://i.dh-his.com/hdhiswork/YEUCAU/issues/60)
- Chuyển sang sử dụng HOSO.KqXetNghiem khi in phiếu kết quả Xét nghiệm cho các mẫu cũ và mẫu mới theo TT32

![](https://i.vgy.me/2vbZJB.png)
![](https://i.vgy.me/F9PEah.png)
![](https://i.vgy.me/9dFrDl.png)
![](https://i.vgy.me/jbx18f.png)

## [v.3.25.0721.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32507210-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32507210-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32507210-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Labor xem kết quả xét nghiệm BV Hồng Dân #412
	+ Nguyên nhân: tham số cks.url chưa cấu hình
	+ Fix lỗi tham số cks.url chưa cấu hình
	
	![](https://i.vgy.me/GOwz7c.png)

- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/412

## [v.3.25.0714.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32507140-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32507140-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32507140-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Fix lỗi bị double nhiều dòng khi load danh sách XN lên Form
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/178

![](https://live.staticflickr.com/65535/54652243112_63118fac56_b.jpg)

## [v.3.25.0630.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32506300-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32506300-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32506300-NasDHSolutions.json)</sup></sup></sub>

- ✨: Kết nối API với phần mềm xét nghiệm LIS-TPH, hiển thị phiếu kết quả từ phần mềm LIS lên phần mềm DHG.Hospital.
![](https://lh3.googleusercontent.com/pw/AP1GczOJl14tGuZqERcW9V8xfHvFMWoaoLej3a6rzS83t8rFOoxvVPRCbn5_DUzEQhCu1HNy1TBQyLLGkJHrAyYABaRQnnrCQqXyEhidZ9r9eQ-TKuATEUYikhqWonKQtqnrCBnLnGddCEzDg_bxTaSx7j0s=w1653-h879-s-no-gm?authuser=0)
![](https://lh3.googleusercontent.com/pw/AP1GczOoQj39PYbX83rVUtDjEvzMtLONSG7sHArS0G1CJIz8nls6B_EAlSEIAY0pKOZpH1S2AU3ZvV0OrPR9nlGl1r7GRRuKIM4iDlTSaCcPYdAeqUbY07q0d5S6zEmgUIeXFgczkqDBD6H6vZGRKrLLN0Uv=w576-h822-s-no-gm?authuser=0)
![](https://lh3.googleusercontent.com/pw/AP1GczOdhbe4zjjX5cr00AUmZXp03OERj3LletitMlsL7g6mM1x7gflmG3Jlek-LMrFORDgfD5rCrR1r59ultncWVYASyiCgheDRSijyy94JEmtu9f62mSI910i9IQuBlbKkM44ZWWEuwLetP41esjWtKkHl=w565-h814-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/332

## [v.3.25.0626.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32506260-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32506260-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32506260-NasDHSolutions.json)</sup></sup></sub>

- ✨: Yêu cầu - Kết nối API với phần mềm xét nghiệm LIS, hiển thị phiếu kết quả từ phần mềm LIS lên phần mềm DHG.Hospital.
![](https://lh3.googleusercontent.com/pw/AP1GczOJl14tGuZqERcW9V8xfHvFMWoaoLej3a6rzS83t8rFOoxvVPRCbn5_DUzEQhCu1HNy1TBQyLLGkJHrAyYABaRQnnrCQqXyEhidZ9r9eQ-TKuATEUYikhqWonKQtqnrCBnLnGddCEzDg_bxTaSx7j0s=w1653-h879-s-no-gm?authuser=0)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/332

## [v.3.25.0613.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32506131-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32506131-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32506131-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bổ sung cột Triệu chứng sổ xét nghiệm PK Phương Nam.

## [v.3.25.0613.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32506130-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32506130-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32506130-NasDHSolutions.json)</sup></sup></sub>

- ✨: Sổ XN PK Phương Nam

## [v.3.25.0612.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32506120-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32506120-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32506120-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bổ sung tham số: cks.ketquacls: Sử dụng phiếu kết quả có chữ ký số bác sĩ (0: không sử dụng; 1: sử dụng).
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/66

## [v.3.25.0610.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32506100-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32506100-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32506100-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bổ sung kiểm tra thời gian thực hiện y lệnh và thời gian trả kết quả xét nghiệm đờm khi thực hiện.
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/302

## [v.3.25.0609.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32506090-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32506090-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32506090-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bổ sung thêm trường Ngày thực hiện YL tại form nhập thông tin Xét nghiệm đờm.
![image](https://img.upanh.tv/2025/06/09/imagebdef0f82ec9117ff.png)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/302

## [v.3.25.0603.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32506030-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32506030-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32506030-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Cập nhật thời gian chỉ định CLS chưa thực hiện
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/178

- Fix sai giá trị khi chỉnh giờ kết quả trên lưới
- Tách bảng màu cho danh sách xét nghiệm
![](https://live.staticflickr.com/65535/54564652476_e10016c0ee_b.jpg)

- Bổ sung DH-LIS

![](https://live.staticflickr.com/65535/54564994275_246abe6798_b.jpg)

## [v.3.25.0525.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32505250-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32505250-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32505250-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Cập nhật thời gian chỉ định CLS chưa thực hiện
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/178

![](https://i.ibb.co/vbsJ7hK/t-Tm1y-Cp-N0l.png)

## [v.3.25.0424.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32504240-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32504240-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32504240-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi `Phiếu Xét nghiệm nồng độ cồn trong máu` chưa ký số được.
![](https://i.imgur.com/o7nrbXa.png)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/66

## [v.3.25.0418.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32504180-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32504180-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32504180-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bổ sung chức năng ký số phiếu kết quả xét nghiệm.
![](https://i.imgur.com/J896tU6.png)
![](https://i.imgur.com/WjSJAS5.png)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/66

## [v.3.25.0417.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32504170-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32504170-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32504170-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bổ sung chức năng ký số phiếu kết quả xét nghiệm.
![](https://i.imgur.com/J896tU6.png)
![](https://i.imgur.com/WjSJAS5.png)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/66

## [v.3.25.0401.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32504010-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32504010-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32504010-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu: Laboratory bổ sung chỉ số chiều cao, cân nặng trên form nhập kết quả
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/101

![](https://i.imgur.com/DIewB5h.png)

## [v.3.25.0331.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32503310-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32503310-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32503310-NasDHSolutions.json)</sup></sup></sub>
- 🐛: Lỗi - Laboratory: Lỗi trùng giờ lấy mẫu cho 2 cận lâm sàng của 2 chỉ định khác nhau, (BV Phổi Đồng Tháp)
- ☑: https://i.dh-his.com/hdhiswork/LOI/issues/180

![](https://i.imgur.com/nz7aeWh.gif)

## [v.3.25.0318.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32503180-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32503180-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32503180-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi lưu kết quả `Sinh thiết`.
![](https://i.imgur.com/UrsKTrI.png)
![](https://i.imgur.com/AIjeGn1.png)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/97

## [v.3.25.0311.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32503111-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32503111-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32503111-NasDHSolutions.json)</sup></sup></sub>

- ✨: Chức năng ghi nhận dữ liệu phân luồng kết quả theo tham số `phanluong.ketqua`.
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/109

## [v.3.25.0311.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32503110-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32503110-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32503110-NasDHSolutions.json)</sup></sup></sub>

- ✨: Form [Giải phẫu bệnh Sinh thiết]: Bổ sung `ngày thực hiện` và `ngày kết quả`. Theo mô tả: [XETNGHIEM/Xet-nghiem-Giai-phau-benh-Sinh-Thiet.md](https://github.com/dhhiswork/Mo-ta-he-thong/blob/main/XETNGHIEM/Xet-nghiem-Giai-phau-benh-Sinh-Thiet.md).
![](https://i.imgur.com/5aj22HW.png)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/97

## [v.3.25.0304.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32503040-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32503040-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32503040-NasDHSolutions.json)</sup></sup></sub>
- ✨: Hiển thị thêm thông tin tên CLS phụ vào danh sách xét nghiệm chỉ định tại form danh sách bệnh nhân thực hiện xét nghiệm.
![](https://i.imgur.com/GGGvBf5.png)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/68

## [v.3.25.0113.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32501130-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32501130-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32501130-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Thực hiện - Tích hợp vào hệ thống cấp key của HĐĐT - (dh-issue/YEUCAU/#18)
- ☑: https://i.dh-his.com/hdhiswork/YEUCAU/issues/18

## [v.3.25.0110.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32501100-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32501100-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32501100-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Form `[Phân luồng]`: Sửa lỗi chưa ưu tiên phân vào phòng cấu hình cls có số BN ít nhất.
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/1

## [v.3.25.0109.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32501090-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32501090-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32501090-NasDHSolutions.json)</sup></sup></sub>

- ✨: Thay đổi cách xác định phòng sau khi quét mã vạch tại form `[Phân luồng]`.
![](https://i.imgur.com/jodURPL.png)
![](https://i.imgur.com/FCYRv1P.png)
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/1

## [v.3.25.0104.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32501040-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32501040-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32501040-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bổ sung chức năng cấu hình khu vực.
![](https://i.imgur.com/ajepLWe.png)
- ☑: https://i.dh-his.com/hdhiswork/DUAN/issues/1

## [v.3.24.1230.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32412300-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32412300-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32412300-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi xem kết quả XN bệnh nhân tháng cũ.
![](https://i.imgur.com/lGhAgCv.png)
![](https://i.imgur.com/HFqi717.png)
- ☑: https://i.dh-his.com/test/LOI/issues/9

## [v.3.24.1228.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32412281-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32412281-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32412281-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bổ sung chức năng `[Phân luồng]` và `[Gọi bệnh]`.
![image](https://github.com/user-attachments/assets/e5712842-60b6-484d-92c4-b6330ad168a7)
![image](https://github.com/user-attachments/assets/0574c7f0-fd8d-4d8c-bf45-299989136d3c)
- ☑: https://github.com/dhhiswork/DuAn/issues/7
<<<<<<< HEAD

## [v.3.24.1228.0]()

- ✨: Bổ sung chức năng `[Phân luồng]` và `[Gọi bệnh]`.
![image](https://github.com/user-attachments/assets/e5712842-60b6-484d-92c4-b6330ad168a7)
![image](https://github.com/user-attachments/assets/0574c7f0-fd8d-4d8c-bf45-299989136d3c)
- ☑: https://github.com/dhhiswork/DuAn/issues/7
=======

## [v.3.24.1227.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32412271-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32412271-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32412271-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Các module add mã chính thức 96176 Phòng khám đa khoa Y Đức Sài Gòn - YEUCAU
- ☑: https://i.dh-his.com/test/YEUCAU/issues/4

## [v.3.24.1227.0]()
- ✨: Yêu cầu - Các module add mã chính thức 96176 Phòng khám đa khoa Y Đức Sài Gòn - YEUCAU
- ☑: https://i.dh-his.com/test/YEUCAU/issues/4

## [v.3.24.1224.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32412241-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32412241-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32412241-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi chỉnh giờ lấy mẫu không được.
- ☑: https://github.com/dhhiswork/Loi/issues/108

## [v.3.24.1224.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32412240-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32412240-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32412240-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi in `Bảng kê xét nghiệm` khi dữ liệu chưa lấy mẫu.
![image](https://github.com/user-attachments/assets/08abcf3c-1896-4682-9984-1ab1f3d88364)
- ☑: https://github.com/dhhiswork/Loi/issues/109

## [v.3.24.1220.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32412201-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32412201-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32412201-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Các module add mã tạm 96151 Phòng khám đa khoa Sài Gòn Y Đức ·
- ☑: https://github.com/dhhiswork/YeuCau/issues/60

## [v.3.24.1220.0]()
- ✨: Yêu cầu - Các module add mã tạm 96151 Phòng khám đa khoa Sài Gòn Y Đức ·
- ☑: https://github.com/dhhiswork/YeuCau/issues/60

## [v.3.24.1205.2]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32412052-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32412052-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32412052-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - Prescription chỉnh sửa thông tin hồ sơ thanh toán BHYT đã in phiếu thanh toán và đã mở khóa ![](https://i.imgur.com/L5X1fbw.png) ![](https://i.imgur.com/Ctf36m3.png)
- ☑: https://github.com/dhhiswork/To_lap_trinh/issues/4

## [v.3.24.1205.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32412051-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32412051-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32412051-NasDHSolutions.json)</sup></sup></sub>
- ✨: Yêu cầu - mở khoá không xoá giờ kết thúc khám không cho thêm chi phí mới
- ☑: https://github.com/dhhiswork/To_lap_trinh/issues/4

- không hợp lệ > chặn
![](https://i.imgur.com/L5X1fbw.png)
- hợp lệ cho phép lưu
![](https://i.imgur.com/Ctf36m3.png)

## [v.3.24.1205.0]()
- ✨: Yêu cầu - mở khoá không xoá giờ kết thúc khám không cho thêm chi phí mới
- ☑: https://github.com/dhhiswork/To_lap_trinh/issues/4

![](https://i.imgur.com/5SmILCZ.png)

- Cho phép lưu khi thời gian trả kết quả không lớn hơn thời gian kết thúc khám
![](https://i.imgur.com/v5Ctg87.png)

## [v.3.24.1204.1]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32412041-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32412041-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32412041-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi: Mẫu mặc định `Bảng kê xét nghiệm` chưa nhóm được CLS theo loại CLS.
![image](https://github.com/user-attachments/assets/05af59f1-5b29-4c89-b8e3-167ce836dc8b)
- ☑: https://github.com/dhhiswork/YeuCau/issues/24

## [v.3.24.1204.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32412040-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32412040-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32412040-NasDHSolutions.json)</sup></sup></sub>

- ✨: Thiết kế lại `Bảng kê xét nghiệm` giống mẫu cũ. Thay đổi `ngaylaymau` lấy từ `chidinhcls.giolaymau`.
![image](https://github.com/user-attachments/assets/6b4e4d3e-45f5-43b8-bad9-6eafbc53445b)
- ☑: https://github.com/dhhiswork/YeuCau/issues/24

## [v.3.24.1203.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32412030-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32412030-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32412030-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi xóa định mức hóa chất.
- ☑: https://github.com/dhhiswork/Loi/issues/61

## [v.3.24.1201.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32412010-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32412010-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32412010-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi không lưu được kết quả xét nghiệm khi sử dụng tham số `xn.sophuttoithieu` và `xn.sophuttraketqua`.
- ☑: https://github.com/dhhiswork/Loi/issues/51

## [v.3.24.1130.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32411300-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32411300-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32411300-NasDHSolutions.json)</sup></sup></sub>

- ✨: Chuyển bảng kê xét nghiệm sang mẫu tự thiết kế. Lưu ý: tài khoản đăng nhập có quyền Admin phân hệ sẽ có thêm chức năng `Thiết kế trang in`.
![image](https://github.com/user-attachments/assets/0e7a0877-b925-49e3-91d9-744983d7ce6b)
![image](https://github.com/user-attachments/assets/9c6e0bb9-246b-42cf-a246-e5ac4475ff55)
- ☑: https://github.com/dhhiswork/YeuCau/issues/24

## [v.3.24.1127.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32411270-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32411270-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32411270-NasDHSolutions.json)</sup></sup></sub>

- ✨: Form `Hủy kết quả`: Bổ sung chức năng chặn/cảnh báo khi người bệnh đã kết thúc hồ sơ theo tham số `thuchiencls_phieu01`.
![image](https://github.com/user-attachments/assets/5ca52512-e517-4eac-8e77-e3bdcde5fc58)
- ☑: https://github.com/dhhiswork/Loi/issues/45

## [v.3.24.1121.0]() <sub><sup><sup>[⬇️OneDrive](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32411210-OneDrive.json) [⬇️GoogleStorage](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32411210-GoogleStorage.json) [⬇️NasDHSolutions](https://code-dh-hospital.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32411210-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi: Danh sách xét nghiệm bị double bệnh nhân (BV Cái răng).
![image](https://github.com/user-attachments/assets/c5aaea34-a920-4784-a0c6-b7f06b0ea893)
- ☑: https://github.com/dhhiswork/Loi/issues/22

## [v.3.24.1030.1]() <sub><sup><sup>[⬇️OneDrive](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32410301-OneDrive.json) [⬇️GoogleStorage](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32410301-GoogleStorage.json) [⬇️NasDHSolutions](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32410301-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi khi xem kết quả xét nghiệm hiển thị nhiều lần (BV Phụ Sản). Nguyên nhân: TPH đổ kết quả với thời gian khác nhau của mỗi xét nghiệm (của cùng 1 lần chỉ định).
![image](https://github.com/user-attachments/assets/224bd01f-dfc2-415c-a18e-7b6ffa54f32b)
![image](https://github.com/user-attachments/assets/cc0eef73-7955-4650-b4eb-b61a3bb80b15)
![image](https://github.com/user-attachments/assets/a3fb413a-6c04-418a-b8f2-70892a18084f)
- ☑: https://github.com/dh-his/Ghi_Nhan_Loi/issues/20

## [v.3.24.1030.0]() <sub><sup><sup>[⬇️OneDrive](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32410300-OneDrive.json) [⬇️GoogleStorage](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32410300-GoogleStorage.json) [⬇️NasDHSolutions](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32410300-NasDHSolutions.json)</sup></sup></sub>

- 🐛: Sửa lỗi khi xem kết quả xét nghiệm hiển thị nhiều lần (BV Phụ Sản). Nguyên nhân: TPH đổ kết quả với thời gian khác nhau của mỗi xét nghiệm (của cùng 1 lần chỉ định).
![image](https://github.com/user-attachments/assets/224bd01f-dfc2-415c-a18e-7b6ffa54f32b)
![image](https://github.com/user-attachments/assets/cc0eef73-7955-4650-b4eb-b61a3bb80b15)
![image](https://github.com/user-attachments/assets/a3fb413a-6c04-418a-b8f2-70892a18084f)
- ☑: https://github.com/dh-his/Ghi_Nhan_Loi/issues/20

## [v.3.24.1028.0]() <sub><sup><sup>[⬇️OneDrive](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32410280-OneDrive.json) [⬇️GoogleStorage](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32410280-GoogleStorage.json) [⬇️NasDHSolutions](https://tolaptrinh.github.io/directTo/?&redirect_url=https%3A%2F%2Fo-dh-007-default-rtdb.asia-southeast1.firebasedatabase.app%2FdirectTo%2FDHLaboratoryexe%2F32410280-NasDHSolutions.json)</sup></sup></sub>

- ✨: Bổ sung tham số bắt lại thời gian lấy mẫu đến có kết quả của XN. Chi tiết: [Mô tả Kiểm tra thời gian kết quả xét nghiệm](https://github.com/dh-hos/Mo-ta-he-thong/blob/main/M%C3%B4%20t%E1%BA%A3%20Ki%E1%BB%83m%20tra%20th%E1%BB%9Di%20gian%20k%E1%BA%BFt%20qu%E1%BA%A3%20x%C3%A9t%20nghi%E1%BB%87m.md)
- ☑: https://github.com/dh-his/Phieu_Yeu_Cau/issues/3

## [v.3.24.1022.0]()

- 🐛: Sửa lỗi: Không chỉnh được ngày giờ lấy mẫu khi chỉnh kết quả XN đã trả kết quả.
![image](https://github.com/user-attachments/assets/33874aed-e132-47ad-b231-c2e978c2c626)
- ☑: https://github.com/dh-hos/dhg.hospitallaboratory/issues/64

## [v.3.24.0915.0]()

- 🐛: Sửa lỗi: ràng buộc thời gian chỉ định xét nghiệm luôn nhỏ hơn thời gian lấy mẫu.
- 🐛: Sửa lỗi: không điều chỉnh được thời gian lấy mẫu đối với các ca xét nghiệm điều chỉnh.
- ☑: https://github.com/dh-hos/dhg.hospitallaboratory/issues/63

## [v.3.24.0906.0]()

- ✨: Kiểm tra [thời gian đọc kết quả xét nghiệm] >= [thời gian lấy mẫu].
- ✨: Cho phép điều chỉnh [thời gian lấy mẫu] tại form thực hiện xét nghiệm.
- ☑: https://github.com/dh-hos/THEO-DOI-THUC-HIEN/issues/117

## [v.3.24.0729.0]()

- ✨: Bổ sung chức năng cấu hình người thực hiện. ![image](https://github.com/user-attachments/assets/5d26e4b7-6c1f-4b8f-b0c6-01e39b81f98a). 
- ✨: Bổ sung chức năng chọn người thực hiện tại các form trả kết quả. ![image](https://github.com/user-attachments/assets/42544f9f-dad6-47d8-b702-bf93e32b3967)
- ☑: https://github.com/dh-hos/To_Lap_Trinh/issues/540

## [v.3.24.0710.0]()

- 🐛: Sửa lỗi phiếu kết quả xét nghiệm in sai ngày thực hiện.
- ☑: https://github.com/dh-hos/dhg.hospitallaboratory/issues/61

## [v.3.24.0607.0]()

- ✨: Bổ sung chức năng Quầy điều phối lấy mẫu bệnh nhân cho Bệnh viện Nhi Đồng Cần Thơ (92003).
- ☑: https://github.com/dh-hos/Yeu_cau_ho_tro/issues/58

## [v.3.24.0606.0]()

- ✨: Fix lỗi mất logo
- ☑: https://github.com/dh-hos/dhg.hospitalregister/issues/68

## [v.3.24.0516.2]()

- ✨: Test lần thứ 3