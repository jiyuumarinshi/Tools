## Cài đặt sẵn những thứ trước khi cài NeoVim

1. Cài đặt [Node Js](https://nodejs.org/en/)
2. Cài đặt ```python npm install neovim -g ```
3. Cài đặt ```python pip install pynvim ```
4. Tải NeoVim tại [đây](https://github.com/neovim/neovim/releases/tag/stable)

![image](https://user-images.githubusercontent.com/93731698/207932574-8eeb440b-46a1-4987-86cc-d4492f7df27a.png)

## Bắt đầu cài đặt Neovim

- Sau khi giản nén mở file ``` nvim-qt.exe ```, ta check xem có thiếu file ``` init.vim ``` không (sử dụng câu lệnh ```:checkhealth```), nếu chưa có thử ta sẽ tạo 1 thư mục ``` nvim ```
rồi tạo file ``` init.vim ``` (như trong hình bên dưới).

![image](https://user-images.githubusercontent.com/93731698/207933786-711e2a3f-937f-403e-b236-fb2a1d44866e.png)

- Trong file ``` init.vim ``` copy hết các file trong đường link dưới [đây](https://github.com/VuNguyenCoder/VimConfig/blob/main/init.vim).

- Sau đó mở terminal hoặc là cmd trên máy tính rồi copy câu lệnh ở [đây](https://github.com/junegunn/vim-plug)              

![image](https://user-images.githubusercontent.com/93731698/207935513-32a05038-e295-4ab0-b1ee-315b9886f8bf.png)

tiếp đó mở ``` nvim-qt.exe ``` rồi dùng câu lệnh ```:PlugInstall``` để cài đặt.

- Trong quá trình cài đặt, mỗi một lần chính ta cài thêm plugin hay chỉnh sửa config gì đó nên tắt NeoVim đi dùng mở lại. 

=> Mở NeoVim như dưới đây là cài đặt thành công

![image](https://user-images.githubusercontent.com/93731698/207936404-9b421269-35b0-4ce6-84ef-89e1fb1520d3.png)

### `Chú ý`
- Cách làm trên được thực hiện theo video của anh [Vũ Nguyễn Coder](https://www.youtube.com/watch?v=Tp8i1EHsQ1Q) 
- Nếu muốn cài các plugin đẹp hơn, nhiều tính năng hơn, thì có thể search google `How to use Python in NeoVim?`
[Example](https://ramezanpour.net/post/2021/04/24/My-ultimate-Neovim-configuration-for-Python-development?fbclid=IwAR1Hl_2jc-Oz5SMrkWTWIAfnD3YAC5QR6KIU0xug2I1ILd_32vavuEmRzfo)
- Dùng theo Vu Nguyen Coder [theo settings này](https://github.com/VuNguyenCoder/VimConfig)
![image](https://user-images.githubusercontent.com/93731698/207937139-d8552569-c775-4c2a-88db-b48e61f0ef8e.png)
