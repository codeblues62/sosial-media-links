# sosial-media-links

![Video Demo Sosial Media Links]()

## en_EN
What is social media links? Social media links are external links on your website that lead to your social media pages.

## id_ID
Tautan media sosial adalah tautan eksternal di situs web Anda yang mengarah ke halaman media sosial Anda.

### HTML Tags
```html
     <div class="box">
        <a href="#" target="_blank" class="box-icons fb">
            <p>Facebook</p>
            <i class="bi bi-facebook"></i>
        </a>
        <a href="#" target="_blank" class="box-icons twit">
            <p>Twitter</p>
            <i class="bi bi-twitter"></i>
        </a>
        <a href="#" target="_blank" class="box-icons ig">
            <p>Insta</p>
            <i class="bi bi-instagram"></i>
        </a>
        <a href="#" target="_blank" class="box-icons in">
            <p>Linked In</p>
            <i class="bi bi-linkedin"></i>
        </a>
    </div>
```

### CSS Tags
```css
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700;800&display=swap');
        @import url("https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.3/font/bootstrap-icons.css");
        *
        {margin: 0;padding: 0;font-family: 'Poppins', sans-serif;box-sizing: border-box;}

        .box
        {
            display: flex;
            flex-direction: column;
            position: fixed;
            top: 25%;
        }
        .box-icons
        {
            width: 165px;
            padding: 10px 20px;
            color: whitesmoke;
            display: inline-flex;
            justify-content: space-between;
            text-decoration: none;
            font-size: 18px;
            border-radius: 8px;
            transition: all 0.25s;
            transform: translateX(-115px);
        }
        .box-icons:hover
        {
            transform: translateX(-5px);
        }
        p
        {margin-right: 20px;}
        .fb
        {
            background-color: #3b5998;
        }
        .twit
        {
            background-color: #0e76a8;
        }
        .ig
        {
            background-color: #8a3ab9;
        }
        .in
        {
            background-color: #0e76a8;
        }
```
