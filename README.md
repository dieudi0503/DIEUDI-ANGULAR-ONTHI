# DIEUDI-ANGULAR-ONTHI
ONTHI
 + Bắt đầu ôn thi thôi 
  +>>>>>
  - Mở new terminal 
  - cài đặt angular CLI
  => npm install -g @angular/cli 

  + Tạo project Angular
  => ng new onThi --defaults
  
  + Thực Thi Ứng Dụng
  => ng serve --open
  
  + Sử dụng framework css như bootstrap ta thực hiện 2 bước
   => npm install --save bootstrap@4
  
  + Cấu trúc file và folder trong project Angular
  => node_modules: chứa các modules của Angular
  src: chứa source code project
  angular.json : nơi cấu hình Angular CLI
  package.json: chứa thông tin các thư viện cần trong project
  src/app : chứa code chính của project.
  app/app.component.html: file view chứa code html và dữ liệu show cho người dùng.
  app/app.component.ts: file component chính, chứa các hàm và các biến của bạn
  app/app.component.css: chứa định dạng css cho app.component.html
  app/app.routes.ts : nơi khai báo các route trong project.
  app/routes.ts : nơi khai báo route cho các chức năng trong project của bạn.
  app/app.config.ts: Nơi bạn khai báo các cấu hình của ứng dụng
  
   + sự dụng bootrap5
  <!--src/index.html-->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"> </script>
  