# Viterbi-Decoder

* Mô phỏng:
  - Bộ giải điều chế Viterbi được thiết kế để triển khai trên FPGA.
  - Cơ sở lý thuyết và Specification: Theory.pdf và Report.pdf.
  - Sau khi thiết kế, hệ thống sẽ được kiểm thử bằng file golden input và golden output: input - Viterbi.txt và output - Viterbi.txt.
  - Kết quả mô phỏng với direct test:
  
  ![image](https://github.com/user-attachments/assets/e12d44ea-89e4-4b1d-8a82-20a32c55ca02)
  
  - Kết quả mô phỏng với golden input:

  ![Screenshot 2025-01-29 122921](https://github.com/user-attachments/assets/20ae8705-4091-4d48-86b0-e7d3152180bb)

  - So sánh đầu ra và golden output:

  ![image](https://github.com/user-attachments/assets/8e31b691-418b-4c80-815d-b7eb3b3e5920)

  ==> 100% accuracy.

*  Kết quả thử nghiệm trên PYNQ-Z2 sử dụng kiến trúc ZYNQ:
  
  - Mô hình hệ thống:

  ![image](https://github.com/user-attachments/assets/8a4de453-3713-470f-8a2f-ec05817d4747)

  - Input và Output của PL do PS kiểm soát thông qua giao thức AXI.
  - Kết quả Synthesis và Implementation:

  ![image](https://github.com/user-attachments/assets/1f079f18-ad19-4da5-8f6f-d540b62ac560)

  ![image](https://github.com/user-attachments/assets/ed46aa2b-3fcc-4702-b147-0adc947a5de3)

  - Thử nghiệm direct test thông qua PS sử dụng Jupyter Notebook:

  ![image](https://github.com/user-attachments/assets/7da7c70c-901e-4f00-ade8-5b9c64041245)







    
