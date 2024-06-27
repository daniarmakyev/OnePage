# Landing
Одностраничник адаптируемый на разные разрешения экрана был преимущественно использован boostrap.
## Технологии
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white)
## Bootstrap
В header был использован bootstrap, при уменьшении разрешения до 992px на экране выходит кнопка с навигацией. 
``` html
    <header class="header">
        <div class="container">
            <nav class="navbar navbar-expand-lg">
                <button class="navbar-toggler position-absolute" type="button" data-bs-toggle="collapse"
                    data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false"
                    aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse " id="navbarNavAltMarkup">
                    <div class="navbar-nav  d-flex flex  w-100">
                        <a class="nav-link me-lg-4 " href="#">Home</a>
                        <a class="nav-link me-lg-4 " href="#">About</a>
                        <a class="nav-link " href="#">Contact</a>
                        <a class="navbar-brand text-decoration-none fw-semibold ms-auto me-auto" href="#">Landing</a>
                        <button type="button" class="header-btn  text-nowrap border-0 text-white ">Buy
                            Now</button>
                    </div>
                </div>
                <a class="navbar-brand text-decoration-none fw-semibold ms-auto me-auto navbar-brand2"
                    href="#">Landing</a>
            </nav>
        </div>
    </header>


```
![logo](img/readme-pic.png)


[Figma](https://www.figma.com/file/yEgxlUIyQTkZhvjEuxQ2yI/Figma-Website-Template---Landing-Page-(Free)-(Community)?type=design&node-id=108-1324&mode=design&t=0caGRVc5b7qANqjO-0)
