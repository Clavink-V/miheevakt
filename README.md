<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ресторан здоровой еды</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Custom CSS -->
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header Section -->
    <header class="header">
        <nav class="navbar navbar-expand-lg navbar-dark">
            <div class="container">
                <a class="navbar-brand" href="#">Здоровая еда</a>
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav ms-auto">
                        <li class="nav-item"><a class="nav-link active" href="#">Home</a></li>
                        <li class="nav-item"><a class="nav-link" href="#">About</a></li>
                        <li class="nav-item"><a class="nav-link" href="#">Menu</a></li>
                        <li class="nav-item"><a class="nav-link" href="#">Gallery</a></li>
                        <li class="nav-item"><a class="nav-link" href="#">Contact</a></li>
                    </ul>
                </div>
            </div>
        </nav>

        <div class="hero-text text-center">
            <h1>Ресторан здоровой еды</h1>
            <p class="lead">Вкусно, полезно, здорово!</p>
        </div>
    </header>

    <!-- About Section -->
    <section class="about-section py-5">
        <div class="container">
            <div class="row align-items-center">
                <div class="col-lg-6 mb-4 mb-lg-0">
                    <img src="https://images.unsplash.com/photo-1546069901-ba9599a7e63c?ixlib=rb-1.2.1&auto=format&fit=crop&w=800&q=80" alt="Healthy Food" class="img-fluid rounded">
                </div>
                <div class="col-lg-6">
                    <h2 class="section-title">О нас</h2>
                    <p>Наша еда славится всем чем только можно. Мы являемся одними из самых восстребованных на этом рынке. Покупайте у нас.</p>
                    <p>Бла бла бла бла бла бла бла бла бла бла бла бла бла бла бла бла бла бла бла бла бла </p>
                    <a href="#" class="btn btn-primary mt-3">Читать дальше</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Special Dishes Section -->
    <section class="special-dishes py-5 bg-light">
        <div class="container">
            <div class="section-header text-center mb-5">
                <h2 class="section-title">Особые блюда</h2>
                <p class="section-subtitle">Свежо и вкусно каждый день</p>
            </div>
            
            <div class="row">
                <div class="col-md-4 mb-4">
                    <div class="dish-card text-center p-4">
                        <div class="dish-icon mb-3">
                            <i class="fas fa-utensils"></i>
                        </div>
                        <h3>Органическая еда</h3>
                        <p>Все ингридиенты собранны в экологически чистых промышленных районах и славятся своей радиацией от которой ваша кожа будет светиться(буквально). </p>
                    </div>
                </div>
                
                <div class="col-md-4 mb-4">
                    <div class="dish-card text-center p-4">
                        <div class="dish-icon mb-3">
                            <i class="fas fa-leaf"></i>
                        </div>
                        <h3>Веганское меню</h3>
                        <p>Мы также не ущемляем братьев наших меньших. А именно у нас есть куча натуральных древесных опилок на любой цвет и вкус, и зуб.</p>
                    </div>
                </div>
                
                <div class="col-md-4 mb-4">
                    <div class="dish-card text-center p-4">
                        <div class="dish-icon mb-3">
                            <i class="fas fa-fish"></i>
                        </div>
                        <h3>Свежая рыба</h3>
                        <p>Что может быть лучше чем попробовать нашу морскую тарелку. Там собранно всё, что по какой-то причине не вписалось в естественный отбор и было выбрашенно на берег</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Menu Section -->
    <section class="menu-section py-5">
        <div class="container">
            <div class="section-header text-center mb-5">
                <h2 class="section-title">Меню</h2>
                <p class="section-subtitle">Свежие ингридиенты, вкусная еда</p>
            </div>
            
            <div class="row">
                <div class="col-lg-6">
                    <div class="menu-item mb-4">
                        <div class="d-flex justify-content-between">
                            <h4>Салат</h4>
                            <span class="price">$25.79</span>
                        </div>
                        <p>Свежие фрукты с машинным маслом</p>
                    </div>
                    
                    <div class="menu-item mb-4">
                        <div class="d-flex justify-content-between">
                            <h4>Боул с чечевицей</h4>
                            <span class="price">$0.19</span>
                        </div>
                        <p>Отобранные у голубей крошки с жмыхом из соковыжемалки</p>
                    </div>
                    
                    <div class="menu-item mb-4">
                        <div class="d-flex justify-content-between">
                            <h4>Запечёный лосось</h4>
                            <span class="price">$50.29</span>
                        </div>
                        <p>СВежий лосось с тимьяном</p>
                    </div>
                </div>
                
                <div class="col-lg-6">
                    <div class="menu-item mb-4">
                        <div class="d-flex justify-content-between">
                            <h4>Бутер с овощами</h4>
                            <span class="price">$4.39</span>
                        </div>
                        <p>Как у бабушки в деревне</p>
                    </div>
                    
                    <div class="menu-item mb-4">
                        <div class="d-flex justify-content-between">
                            <h4>Шаурма</h4>
                            <span class="price">$13.33</span>
                        </div>
                        <p>Хит от иностранного шефа</p>
                    </div>
                    
                    <div class="menu-item mb-4">
                        <div class="d-flex justify-content-between">
                            <h4>Синабон</h4>
                            <span class="price">$8.99</span>
                        </div>
                        <p>Тысяча калорий в каждом укусе</p>
                    </div>
                </div>
            </div>
            
            <div class="text-center mt-4">
                <a href="#" class="btn btn-outline-primary">Полное меню</a>
            </div>
        </div>
    </section>

    <!-- Gallery Section -->
    <section class="gallery-section py-5 bg-light">
        <div class="container">
            <div class="section-header text-center mb-5">
                <h2 class="section-title">Фотографии еды</h2>
                <p class="section-subtitle">Посмотрите что мы готовим</p>
            </div>
            
            <div class="row g-3">
                <div class="col-md-4 col-6">
                    <img src="https://images.unsplash.com/photo-1546069901-ba9599a7e63c?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="Food" class="img-fluid rounded gallery-img">
                </div>
                <div class="col-md-4 col-6">
                    <img src="https://images.unsplash.com/photo-1512621776951-a57141f2eefd?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="Food" class="img-fluid rounded gallery-img">
                </div>
                <div class="col-md-4 col-6">
                    <img src="https://images.unsplash.com/photo-1490645935967-10de6ba17061?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="Food" class="img-fluid rounded gallery-img">
                </div>
                <div class="col-md-4 col-6">
                    <img src="https://images.unsplash.com/photo-1505576399279-565b52d4ac71?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="Food" class="img-fluid rounded gallery-img">
                </div>
                <div class="col-md-4 col-6">
                    <img src="https://images.unsplash.com/photo-1490645935967-10de6ba17061?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="Food" class="img-fluid rounded gallery-img">
                </div>
                <div class="col-md-4 col-6">
                    <img src="https://images.unsplash.com/photo-1544025162-d76694265947?ixlib=rb-1.2.1&auto=format&fit=crop&w=500&q=60" alt="Food" class="img-fluid rounded gallery-img">
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section class="testimonials-section py-5">
        <div class="container">
            <div class="section-header text-center mb-5">
                <h2 class="section-title">Что говорят о нас наши гости</h2>
                <p class="section-subtitle">Отзывы</p>
            </div>
            
            <div class="row">
                <div class="col-lg-4 mb-4">
                    <div class="testimonial-card p-4">
                        <div class="rating mb-3">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                        </div>
                        <p class="mb-4">"Еда была прекрасной, спасибо за незабываемый отдых"</p>
                        <div class="customer">
                            <h5 class="mb-0">Вася пупкин</h5>
                            <small>Постоянный клиент</small>
                        </div>
                    </div>
                </div>
                
                <div class="col-lg-4 mb-4">
                    <div class="testimonial-card p-4">
                        <div class="rating mb-3">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star-half-alt"></i>
                        </div>
                        <p class="mb-4">"Всё супер! Больше не придём"</p>
                        <div class="customer">
                            <h5 class="mb-0">Окак Окакович</h5>
                            <small>Иноагент</small>
                        </div>
                    </div>
                </div>
                
                <div class="col-lg-4 mb-4">
                    <div class="testimonial-card p-4">
                        <div class="rating mb-3">
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                            <i class="fas fa-star"></i>
                        </div>
                        <p class="mb-4">"Моя собака была на седьмом небе от счастья"</p>
                        <div class="customer">
                            <h5 class="mb-0">Слава КПСС</h5>
                            <small>Реп минималист</small>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="contact-section py-5 bg-light">
        <div class="container">
            <div class="row">
                <div class="col-lg-6 mb-4 mb-lg-0">
                    <h2 class="section-title mb-4">Свяжитесь с нами</h2>
                    <p>Хотите забронировать столик? Скидка на ритуальные услуги 50%</p>
                    
                    <div class="contact-info mt-4">
                        <div class="info-item mb-3">
                            <i class="fas fa-map-marker-alt me-3"></i>
                            <span>Москва улица Шереметьего дом 3</span>
                        </div>
                        <div class="info-item mb-3">
                            <i class="fas fa-phone me-3"></i>
                            <span>88005553535</span>
                        </div>
                        <div class="info-item mb-3">
                            <i class="fas fa-envelope me-3"></i>
                            <span>hcdjcksdskncjkjdsjcn@cjsljcl</span>
                        </div>
                    </div>
                    
                    <div class="social-links mt-4">
                        <a href="#" class="me-3"><i class="fab fa-facebook-f"></i></a>
                        <a href="#" class="me-3"><i class="fab fa-instagram"></i></a>
                        <a href="#" class="me-3"><i class="fab fa-twitter"></i></a>
                        <a href="#"><i class="fab fa-yelp"></i></a>
                    </div>
                </div>
                
                <div class="col-lg-6">
                    <form class="contact-form">
                        <div class="mb-3">
                            <input type="text" class="form-control" placeholder="Имя">
                        </div>
                        <div class="mb-3">
                            <input type="email" class="form-control" placeholder="Номер телефона">
                        </div>
                        <div class="mb-3">
                            <input type="text" class="form-control" placeholder="Тема">
                        </div>
                        <div class="mb-3">
                            <textarea class="form-control" rows="5" placeholder="Ваше сообщение"></textarea>
                        </div>
                        <button type="Продолжить" class="btn btn-primary">Отправить</button>
                    </form>
                </div>
            </div>
        </div>
    </section>
