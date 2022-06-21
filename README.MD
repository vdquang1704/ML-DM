Trong project lần này, chúng em sử dụng Jupyter NoteBook trên Visual Studio Code để chạy chương trình nên khuyến khích mọi người sử dụng.
********************************************************
Các bước để chạy chương trình:
1. Cài Visual Studio Code (https://code.visualstudio.com/download)
2. Cài Python extension cho VSCode (https://marketplace.visualstudio.com/items?itemName=ms-python.python)
3. Cài Python 3. trở lên (phiên bản mà chúng em sử dụng là 3.9.7) (https://www.python.org/downloads/)
4. Cài các thư viện cần thiết
Ở đây chúng em sử dụng pip để cài đặt các thư viện
4.1. Kiếm tra phiên bản python (khuyến nghị sử dụng phiên bản python 3.9.7)
py --version
4.2. Kiếm tra đã có pip hay chưa
py -m pip --version
Nếu chưa có pip thì cài đặt pip bằng dòng lệnh sau
py -m ensurepip --default-pip
4.3. Cài đặt các thư viện 
pip install pandas
pip install numpy
pip install matplotlib
pip install seaborn
pip install graphviz
pip install pydotplus
pip install -U scikit-learn
*LƯU Ý: Riêng thư viện graphviz dùng để mô hình hóa cây quyết định, ta phải tải và cài đặt bằng phần mềm ngoài để tạo ra folder chứa ảnh chứ không tải bằng pip được. Ta tải file từ đường dẫn: https://graphviz.org/download/ sau đó cài đặt. Trong bước cài đặt ta nhớ phải add Graphviz vào PATH để sử dụng được thư viện này.