<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nguyễn Trần Kiều Anh</title>
    <style>
        /* Thiết lập cơ bản cho thanh điều hướng */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        .navbar {
            background-color: #555;
            display: flex;
            position: fixed; /* Cố định thanh điều hướng */
            justify-content: center; /* Căn giữa các mục */
            align-items: center;
            height: 50px;
            width: 100%; /* Chiếm toàn bộ chiều rộng màn hình */
        }

        .navbar a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
        }

        .navbar a:hover {
            background-color: #f44336;
            color: white;
        }

        .dropdown {
            float: left;
            overflow: hidden;
        }

        .dropdown .dropbtn {
            cursor: pointer;
            font-size: 16px;  
            border: none;
            outline: none;
            color: white;
            padding: 14px 20px;
            background-color: inherit;
            margin: 0;
        }

        .navbar a:hover, .dropdown:hover .dropbtn {
            background-color: palevioletred;
        }

        .dropdown-content {
            display: none;
            position: absolute;
            background-color: #f9f9f9;
            min-width: 160px;
            box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
            z-index: 1;
        }

        .dropdown-content a {
            float: none;
            color: black;
            padding: 12px 16px;
            text-decoration: none;
            display: block;
            text-align: left;
        }

        .dropdown-content a:hover {
            background-color: #ddd;
        }

        .dropdown:hover .dropdown-content {
            display: block;
        }

        .content {
            padding: 16px;
            font-size: 1cm;
        }
    </style>
</head>
<body>
    <div class="navbar">
        <div class="dropdown">
            <button class="dropbtn">Sản phẩm 
                <i class="fa fa-caret-down"></i>
            </button>
            <div class="dropdown-content">
                <a href="#aokhoac">Áo khoác</a>
                <a href="#tuixach">Túi xách</a>
                <a href="#damcongso">Đầm công sở</a>
            </div>
        </div> 
        <a href="#bosuutap">Bộ sưu tập</a>
        <a href="#showroom">Showroom</a>
        <a href="#docquyenthang10">Độc quyền tháng 10</a>
    </div>

    <div class="content">
        <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut laoreet diam at rutrum dictum. Phasellus ex tortor, lacinia non dapibus lacinia, elementum id velit. Aliquam vitae sapien a est consectetur euismod eget nec tellus. Morbi sodales consectetur mi ac rhoncus. Class aptent taciti sociosqu ad litora torquent per conubia nostra, per inceptos himenaeos. Cras id interdum nulla. Sed faucibus arcu id quam bibendum, eu mollis sapien vehicula. Ut ullamcorper ipsum id magna dapibus, quis semper lectus pulvinar. Donec et nulla mi. Morbi placerat, diam ac consectetur venenatis, lacus orci consectetur metus, eget aliquam est dui a tellus.

            Vestibulum vel lectus vel sem varius imperdiet dignissim eu ante. Interdum et malesuada fames ac ante ipsum primis in faucibus. Mauris finibus nulla facilisis mollis ornare. Suspendisse rutrum justo non magna consectetur finibus. In quis tellus et erat sagittis tempus at eget dolor. Curabitur elit quam, bibendum non interdum a, scelerisque at nisi. Nulla bibendum lacinia ligula, vitae scelerisque purus egestas vitae. Nulla ornare mi id felis rutrum dignissim. Proin imperdiet nunc nulla, eget tempor diam porttitor ut. Nulla mi augue, fringilla ut ex vitae, mattis commodo purus. Sed porta eu ex porttitor malesuada. Curabitur finibus dolor quis eros tempus ullamcorper.
            
            Fusce sit amet sem orci. Aenean finibus pellentesque dolor a mattis. Proin posuere magna ut euismod consequat. In fringilla, erat et lacinia molestie, massa nunc viverra justo, in accumsan lorem ex ut massa. Sed dignissim nisl quam, non suscipit ipsum fermentum ac. Nullam eget libero in nunc volutpat sollicitudin. Nulla facilisi. Nam vel tellus sed odio tincidunt molestie quis a mi. Quisque tincidunt, mi a luctus ultrices, felis diam ultrices lacus, vel semper lacus felis quis purus. Praesent eros dui, placerat commodo molestie eget, pulvinar quis magna.
            
            Aliquam neque dui, venenatis tristique dignissim molestie, tincidunt ac ex. Vivamus finibus justo viverra orci condimentum congue. Etiam fringilla efficitur dolor nec lobortis. Ut eu enim ex. Praesent non lacinia quam, molestie blandit ipsum. Maecenas sagittis gravida odio, in interdum tortor viverra vitae. Duis quis consectetur augue. Nam tempus vestibulum ipsum, nec convallis lacus semper a. Suspendisse sed dolor ex.
            
            Vivamus at vulputate ex. Cras turpis eros, consequat eget dapibus non, consectetur vitae diam. Phasellus fermentum tristique tortor eu porta. Sed scelerisque accumsan enim eu dapibus. Mauris ac facilisis enim, eget pharetra quam. Mauris a lobortis leo, quis molestie sem. Donec pellentesque, massa in gravida consequat, justo nisi sollicitudin mauris, efficitur pulvinar quam dui pulvinar nisi. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam dictum augue vel enim pellentesque facilisis. Proin vel justo risus. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla pulvinar auctor justo ac tristique. In hac habitasse platea dictumst. Nunc varius lectus eget laoreet eleifend. Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
    </div>

</body>
</html>
