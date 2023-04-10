# @font-face {
    font-family: 'SuncheonB';
    src: url('https://cdn.jsdelivr.net/gh/projectnoonnu/noonfonts_2202-2@1.0/SuncheonB.woff') format('woff');
    font-weight: normal;
    font-style: normal;
}

html {
    scroll-behavior: smooth;
}
@media (prefers-reduced-motion: reduce) {
    html {
        scroll-behavior: auto;
    }
}


/* body */
body {
    color: #fff;
    background-color: rgb(11, 21, 53);
    -ms-user-select: none; 
    -moz-user-select: -moz-none; 
    -webkit-user-select: none; 
    -khtml-user-select: none; 
    user-select:none;
}

/* header */
.headers {
    color: #fff;
    background-color: rgba(24, 59, 136, 0.548);
    height: 75px;
    padding: 1rem;
    font-weight: bold;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.headers > .headers_log > h2 {
    font-size: 30px; 
    padding: 5px 1px 2px 10px; 
    display:inline-block; 
    vertical-align:top;
}
.nav_shortcuts {
    word-spacing: 1em
}
.headers_box {
    width: 80px;
    height: 80px; 
    border-radius: 100%;
    overflow: hidden;
}
.headers_img {
    position: relative;
    width: 100%;
    height: 100%;
}
.shortcuts {
    font-size: 19px;
    text-decoration-line: none;
    color: #fff;

}

/* main */
.main {

}
.text_center {
    text-align: center;
}
div.Description {
    display: none;
}
.Description > .img_box {
    display : block;
    margin : auto;
    width: 160px;
    height: 160px; 
    border-radius: 100%;
    overflow: hidden;
}
.Description > .img_box > img {
    width: 100%;
    height: 100%;
}
.rounded_description {
    display: inline-block;
    margin : auto;
    background: rgb(23, 31, 77);
    font-size: 20px;
    padding: auto;
    height: auto; 
    width: 450px;
    border-radius: 15px;
}

/*price tag*/
.price {
    padding: 100px;
    margin : auto;
}
table {
    width: 100%;
    border-top: 1px solid #444444;
    border-collapse: collapse;
  }
  th, td {
    border-bottom: 1px solid #444444;
    border-left: 1px solid #444444;
    padding: 10px;
  }
  th:first-child, td:first-child {
    border-left: none;
  }
