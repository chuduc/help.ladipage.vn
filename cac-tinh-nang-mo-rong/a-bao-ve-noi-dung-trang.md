# 12. Mã bảo vệ nội dung trang

Để có thể bảo mật các thông tin trên Landing Page, ngăn chặn việc lấy cắp hình ảnh và thông tin trên trang, bạn nên copy đoạn code sau và dán vào thẻ Header.\
Code này sẽ có tác dụng ngăn chặn việc copy chữ và xem source code lấy link ảnh.

\<script>window.oncontextmenu=function (){return false;};document.onkeydown=function(e){if((event.ctrlKey || event.metaKey) && event.which==85){event.preventDefault(); return false;\}};\</script>\<style>body{-webkit-user-select: none; -moz-user-select: none; -ms-user-select: none; user-select: none;}\</style>

![](<../.gitbook/assets/image (1026).png>)
