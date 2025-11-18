<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Возврат навязанной страховки в Самарской области | ВозвратСтраховокРФ</title>
    <meta name="description" content="Вернем деньги за навязанные услуги в автосалоне. Юридическая помощь по возврату КАСКО, страхования жизни в Самарской области. Бесплатная консультация.">
    <meta name="keywords" content="возврат страховки, навязанная страховка, автосалон, Самарская область, юридическая помощь, возврат КАСКО, страхование жизни, автострахование">
    <style>
        /* Общие стили */
        :root {
            --primary-color: #0d3b66;
            --accent-color: #8b0000;
            --dark-gray: #333;
            --light-gray: #f5f5f5;
            --white: #fff;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: var(--dark-gray);
            background-color: var(--white);
        }
        
        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
        }
        
        h1, h2, h3, h4 {
            margin-bottom: 1rem;
            color: var(--primary-color);
        }
        
        h1 {
            font-size: 2.5rem;
        }
        
        h2 {
            font-size: 2rem;
            text-align: center;
            margin-bottom: 2rem;
        }
        
        p {
            margin-bottom: 1rem;
        }
        
        section {
            padding: 5rem 0;
        }
        
        .section-bg {
            background-color: var(--light-gray);
        }
        
        .btn {
            display: inline-block;
            background-color: var(--accent-color);
            color: var(--white);
            padding: 0.8rem 1.5rem;
            border: none;
            border-radius: 4px;
            text-decoration: none;
            font-weight: bold;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        
        .btn:hover {
            background-color: #a00000;
        }
        
        /* Шапка */
        header {
            background-color: var(--white);
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
        }
        
        .header-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1rem 0;
        }
        
        .logo {
            font-size: 1.5rem;
            font-weight: bold;
            color: var(--primary-color);
            text-decoration: none;
        }
        
        .nav-menu {
            display: flex;
            list-style: none;
        }
        
        .nav-menu li {
            margin-left: 1.5rem;
        }
        
        .nav-menu a {
            text-decoration: none;
            color: var(--dark-gray);
            font-weight: 500;
            transition: color 0.3s;
        }
        
        .nav-menu a:hover {
            color: var(--primary-color);
        }
        
        .contact-info {
            display: flex;
            align-items: center;
        }
        
        .phone {
            font-weight: bold;
            color: var(--primary-color);
            margin-right: 1rem;
        }
        
        .mobile-menu-btn {
            display: none;
            background: none;
            border: none;
            font-size: 1.5rem;
            cursor: pointer;
            color: var(--primary-color);
        }
        
        /* Главный экран */
        .hero {
            background: linear-gradient(rgba(13, 59, 102, 0.8), rgba(13, 59, 102, 0.8)), url('https://img.freepik.com/free-photo/side-view-woman-receiving-car-keys_23-2150344559.jpg');
            background-size: cover;
            background-position: center;
            color: var(--white);
            text-align: center;
            padding: 10rem 0;
            margin-top: 70px;
        }
        
        .hero h1 {
            color: var(--white);
            font-size: 3rem;
            margin-bottom: 1.5rem;
        }
        
        .hero p {
            font-size: 1.2rem;
            margin-bottom: 2rem;
            max-width: 800px;
            margin-left: auto;
            margin-right: auto;
        }
        
        .hero .btn {
            font-size: 1.1rem;
            padding: 1rem 2rem;
        }
        
        /* Блок с преимуществами */
        .benefits {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
        }
        
        .benefit-item {
            text-align: center;
            padding: 2rem;
            background-color: var(--white);
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        
        .benefit-icon {
            font-size: 3rem;
            margin-bottom: 1rem;
            color: var(--primary-color);
        }
        
        /* Услуги */
        .services-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }
        
        .service-item {
            background-color: var(--white);
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        
        .service-item h3 {
            color: var(--primary-color);
            margin-bottom: 1rem;
        }
        
        /* Как мы работаем */
        .steps {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            counter-reset: step-counter;
        }
        
        .step {
            flex-basis: calc(20% - 1rem);
            text-align: center;
            position: relative;
            margin-bottom: 2rem;
        }
        
        .step:not(:last-child)::after {
            content: '';
            position: absolute;
            top: 30px;
            right: -50%;
            width: 100%;
            height: 2px;
            background-color: var(--primary-color);
            z-index: -1;
        }
        
        .step-number {
            width: 60px;
            height: 60px;
            background-color: var(--primary-color);
            color: var(--white);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto 1rem;
            font-size: 1.5rem;
            font-weight: bold;
        }
        
        /* Статьи */
        .articles-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }
        
        .article {
            background-color: var(--white);
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        
        .article-img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        
        .article-content {
            padding: 1.5rem;
        }
        
        .article h3 {
            margin-bottom: 1rem;
        }
        
        /* FAQ */
        .faq-container {
            max-width: 800px;
            margin: 0 auto;
        }
        
        .faq-item {
            margin-bottom: 1rem;
            border: 1px solid #ddd;
            border-radius: 4px;
            overflow: hidden;
        }
        
        .faq-question {
            background-color: var(--light-gray);
            padding: 1rem;
            cursor: pointer;
            display: flex;
            justify-content: space-between;
            align-items: center;
            font-weight: bold;
        }
        
        .faq-answer {
            padding: 0 1rem;
            max-height: 0;
            overflow: hidden;
            transition: max-height 0.3s, padding 0.3s;
        }
        
        .faq-answer.active {
            padding: 1rem;
            max-height: 500px;
        }
        
        /* Контакты */
        .contact-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }
        
        .contact-info-block {
            background-color: var(--white);
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        
        .contact-info-block h3 {
            margin-bottom: 1.5rem;
            color: var(--primary-color);
        }
        
        .contact-details {
            margin-bottom: 1.5rem;
        }
        
        .contact-details p {
            margin-bottom: 0.5rem;
        }
        
        .map-container {
            height: 300px;
            background-color: #eee;
            border-radius: 8px;
            overflow: hidden;
        }
        
        .map-image {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
        
        /* Форма обратной связи */
        .contact-form {
            background-color: var(--white);
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        
        .form-group {
            margin-bottom: 1.5rem;
        }
        
        .form-group label {
            display: block;
            margin-bottom: 0.5rem;
            font-weight: bold;
        }
        
        .form-group input,
        .form-group textarea {
            width: 100%;
            padding: 0.8rem;
            border: 1px solid #ddd;
            border-radius: 4px;
            font-family: inherit;
        }
        
        .form-group textarea {
            height: 150px;
            resize: vertical;
        }
        
        /* Футер */
        footer {
            background-color: var(--primary-color);
            color: var(--white);
            padding: 3rem 0;
        }
        
        .footer-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 2rem;
        }
        
        .footer-logo {
            font-size: 1.5rem;
            font-weight: bold;
            margin-bottom: 1rem;
        }
        
        .footer-nav {
            list-style: none;
        }
        
        .footer-nav li {
            margin-bottom: 0.5rem;
        }
        
        .footer-nav a {
            color: var(--white);
            text-decoration: none;
        }
        
        .footer-nav a:hover {
            text-decoration: underline;
        }
        
        .footer-contact p {
            margin-bottom: 0.5rem;
        }
        
        .copyright {
            text-align: center;
            margin-top: 2rem;
            padding-top: 2rem;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        /* Адаптивность */
        @media (max-width: 992px) {
            h1 {
                font-size: 2rem;
            }
            
            h2 {
                font-size: 1.8rem;
            }
            
            .hero h1 {
                font-size: 2.5rem;
            }
            
            .step {
                flex-basis: calc(50% - 1rem);
                margin-bottom: 3rem;
            }
            
            .step:not(:last-child)::after {
                display: none;
            }
        }
        
        @media (max-width: 768px) {
            .header-container {
                flex-wrap: wrap;
            }
            
            .nav-menu {
                display: none;
                width: 100%;
                flex-direction: column;
                margin-top: 1rem;
            }
            
            .nav-menu.active {
                display: flex;
            }
            
            .nav-menu li {
                margin: 0.5rem 0;
            }
            
            .mobile-menu-btn {
                display: block;
            }
            
            .contact-info {
                margin-top: 1rem;
                width: 100%;
                justify-content: center;
            }
            
            .hero {
                padding: 7rem 0;
            }
            
            .hero h1 {
                font-size: 2rem;
            }
            
            .hero p {
                font-size: 1rem;
            }
        }
        
        @media (max-width: 576px) {
            section {
                padding: 3rem 0;
            }
            
            .hero {
                padding: 5rem 0;
            }
            
            .hero h1 {
                font-size: 1.8rem;
            }
            
            h2 {
                font-size: 1.5rem;
            }
            
            .step {
                flex-basis: 100%;
            }
        }
    </style>
</head>
<body>
    <!-- Шапка -->
    <header>
        <div class="container header-container">
            <a href="#home" class="logo">ВозвратСтраховокРФ</a>
            
            <button class="mobile-menu-btn">☰</button>
            
            <ul class="nav-menu">
                <li><a href="#services">Услуги</a></li>
                <li><a href="#about">О нас</a></li>
                <li><a href="#articles">Статьи</a></li>
                <li><a href="#contacts">Контакты</a></li>
            </ul>
            
            <div class="contact-info">
                <a href="tel:+79198180835" class="phone">+7 (919) 818-08-35</a>
                <a href="#contacts" class="btn">Бесплатная консультация</a>
            </div>
        </div>
    </header>

    <!-- Главный экран -->
    <section class="hero" id="home">
        <div class="container">
            <h1>Вернем ваши деньги за навязанную страховку при покупке авто!</h1>
            <p>Профессиональная юридическая помощь по возврату навязанных страховых и дополнительных услуг при покупке автомобиля в Самарской области</p>
            <a href="#contacts" class="btn">Бесплатная консультация</a>
        </div>
    </section>

    <!-- О нас / Преимущества -->
    <section id="about">
        <div class="container">
            <h2>О нашей компании</h2>
            <p>Юридическая фирма «ВозвратСтраховокРФ» специализируется на защите прав потребителей при покупке автомобилей в автосалонах Самарской области. Мы помогаем вернуть деньги за навязанные страховые услуги, используя законные методы и многолетний опыт.</p>
            
            <div class="benefits">
                <div class="benefit-item">
                    <div class="benefit-icon">⚖️</div>
                    <h3>Юридическая экспертиза</h3>
                    <p>Наша команда состоит из опытных юристов, специализирующихся на защите прав потребителей в сфере автострахования.</p>
                </div>
                <div class="benefit-item">
                    <div class="benefit-icon">📈</div>
                    <h3>Высокий процент успеха</h3>
                    <p>Более 90% наших клиентов успешно возвращают средства за навязанные страховки и дополнительные услуги.</p>
                </div>
                <div class="benefit-item">
                    <div class="benefit-icon">📍</div>
                    <h3>Работаем по Самарской области</h3>
                    <p>Мы знаем специфику автосалонов и судебную практику именно в Самарской области, что повышает эффективность нашей работы.</p>
                </div>
                <div class="benefit-item">
                    <div class="benefit-icon">💰</div>
                    <h3>Оплата за результат</h3>
                    <p>Мы работаем по принципу "успех-ориентированной" оплаты: вы платите только после получения положительного результата.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Услуги -->
    <section class="section-bg" id="services">
        <div class="container">
            <h2>Наши услуги</h2>
            <div class="services-container">
                <div class="service-item">
                    <h3>Возврат КАСКО</h3>
                    <p>Помогаем вернуть деньги за навязанное КАСКО, которое часто включают в кредитный договор без согласия покупателя.</p>
                </div>
                <div class="service-item">
                    <h3>Возврат страхования жизни</h3>
                    <p>Возвращаем средства за ненужную страховку жизни, которую часто навязывают при оформлении автокредита.</p>
                </div>
                <div class="service-item">
                    <h3>Возврат ГПО</h3>
                    <p>Юридическая помощь в возврате средств за гарантийное продление обслуживания, которое часто навязывают при покупке авто.</p>
                </div>
                <div class="service-item">
                    <h3>Возврат за доп. оборудование</h3>
                    <p>Помогаем вернуть деньги за дополнительное оборудование, установленное без согласия покупателя.</p>
                </div>
                <div class="service-item">
                    <h3>Досудебное урегулирование</h3>
                    <p>Составляем претензии и ведем переговоры с автосалонами для досудебного решения вопроса.</p>
                </div>
                <div class="service-item">
                    <h3>Судебная защита</h3>
                    <p>Представляем интересы клиента в суде при необходимости принудительного взыскания средств.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Как мы работаем -->
    <section id="process">
        <div class="container">
            <h2>Как мы работаем</h2>
            <div class="steps">
                <div class="step">
                    <div class="step-number">1</div>
                    <h3>Консультация</h3>
                    <p>Бесплатная консультация и анализ вашей ситуации</p>
                </div>
                <div class="step">
                    <div class="step-number">2</div>
                    <h3>Анализ документов</h3>
                    <p>Изучаем договоры и выявляем нарушения</p>
                </div>
                <div class="step">
                    <div class="step-number">3</div>
                    <h3>Претензия</h3>
                    <p>Составляем и направляем претензию автосалону</p>
                </div>
                <div class="step">
                    <div class="step-number">4</div>
                    <h3>Переговоры</h3>
                    <p>Ведем переговоры и добиваемся возврата средств</p>
                </div>
                <div class="step">
                    <div class="step-number">5</div>
                    <h3>Возврат денег</h3>
                    <p>Вы получаете деньги за навязанные услуги</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Статьи -->
    <section class="section-bg" id="articles">
        <div class="container">
            <h2>Полезные статьи</h2>
            <div class="articles-container">
                <article class="article">
                    <img src="https://img.freepik.com/free-photo/close-up-owners-new-car_23-2150166183.jpg" alt="Навязанная страховка" class="article-img">
                    <div class="article-content">
                        <h3>Что делать, если в автосалоне навязали КАСКО? Пошаговая инструкция 2024</h3>
                        <p>Многие автосалоны навязывают дополнительные услуги, в том числе КАСКО, при покупке автомобиля. В этой статье мы расскажем, как законно отказаться от навязанной страховки и вернуть свои деньги...</p>
                        <a href="#" class="btn">Читать далее</a>
                    </div>
                </article>
                
                <article class="article">
                    <img src="https://img.freepik.com/free-photo/still-life-with-scales-justice_23-2151533256.jpg" alt="Закон о навязанной страховке" class="article-img">
                    <div class="article-content">
                        <h3>Закон о навязанной страховке: как вернуть деньги за полис по Закону о защите прав потребителей</h3>
                        <p>Законодательство РФ защищает потребителей от навязанных услуг. Узнайте, какие статьи закона помогут вам вернуть деньги за навязанную страховку и как правильно составить претензию...</p>
                        <a href="#" class="btn">Читать далее</a>
                    </div>
                </article>
                
                <article class="article">
                    <img src="https://img.freepik.com/free-photo/businessman-signing-important-contract-papers_23-2151153187.jpg" alt="Возврат страховки после покупки" class="article-img">
                    <div class="article-content">
                        <h3>Возврат страховки после покупки автомобиля: сроки, процедура, судебная практика в Самарской области</h3>
                        <p>Даже если вы уже оплатили страховку, у вас есть возможность вернуть средства. В статье рассмотрены сроки возврата, процедура оформления и особенности судебной практики в Самарской области...</p>
                        <a href="#" class="btn">Читать далее</a>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- FAQ -->
    <section id="faq">
        <div class="container">
            <h2>Часто задаваемые вопросы</h2>
            <div class="faq-container">
                <div class="faq-item">
                    <div class="faq-question">
                        <span>Можно ли вернуть деньги за навязанную страховку?</span>
                        <span>+</span>
                    </div>
                    <div class="faq-answer">
                        <p>Да, согласно Закону "О защите прав потребителей", навязанная услуга является нарушением ваших прав. Вы имеете полное право требовать возврата уплаченных средств за страховку, которую вам навязали при покупке автомобиля.</p>
                    </div>
                </div>
                
                <div class="faq-item">
                    <div class="faq-question">
                        <span>Какие документы нужны для возврата страховки?</span>
                        <span>+</span>
                    </div>
                    <div class="faq-answer">
                        <p>Для начала процедуры возврата вам понадобятся: договор купли-продажи автомобиля, кредитный договор (если есть), страховой полис, чеки об оплате, паспорт. Наши юристы помогут подготовить все необходимые документы для претензии.</p>
                    </div>
                </div>
                
                <div class="faq-item">
                    <div class="faq-question">
                        <span>Сколько времени занимает возврат страховки?</span>
                        <span>+</span>
                    </div>
                    <div class="faq-answer">
                        <p>Срок возврата зависит от конкретной ситуации. В среднем, досудебное урегулирование занимает от 2 до 4 недель. Если дело доходит до суда, процесс может занять от 2 до 6 месяцев.</p>
                    </div>
                </div>
                
                <div class="faq-item">
                    <div class="faq-question">
                        <span>Как доказать, что страховка была навязана?</span>
                        <span>+</span>
                    </div>
                    <div class="faq-answer">
                        <p>Доказательствами навязанной услуги могут служить: условия договора, где страховка является обязательной для получения скидки или одобрения кредита; отсутствие информации о добровольном характере услуги; свидетельские показания; аудио- и видеозаписи переговоров.</p>
                    </div>
                </div>
                
                <div class="faq-item">
                    <div class="faq-question">
                        <span>Каков процент успеха в возврате страховок?</span>
                        <span>+</span>
                    </div>
                    <div class="faq-answer">
                        <p>По нашей статистике, более 90% дел заканчиваются успешным возвратом средств. В большинстве случаев вопрос решается на досудебной стадии после грамотно составленной претензии.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Контакты -->
    <section class="section-bg" id="contacts">
        <div class="container">
            <h2>Контакты</h2>
            <div class="contact-container">
                <div class="contact-info-block">
                    <h3>Свяжитесь с нами</h3>
                    <div class="contact-details">
                        <p><strong>Телефон:</strong> <a href="tel:+79198180835">+7 (919) 818-08-35</a></p>
                        <p><strong>WhatsApp/Telegram:</strong> <a href="https://wa.me/79198180835">+7 (919) 818-08-35</a></p>
                        <p><strong>Email:</strong> <a href="mailto:mail@arsconsulting.su">mail@arsconsulting.su</a></p>
                        <p><strong>Регион работы:</strong> Самарская область</p>
                    </div>
                    <a href="tel:+79198180835" class="btn">Позвонить сейчас</a>
                </div>
                
                <div class="contact-form">
                    <h3>Заявка на консультацию</h3>
                    <form id="consultation-form">
                        <div class="form-group">
                            <label for="name">Ваше имя</label>
                            <input type="text" id="name" name="name" required>
                        </div>
                        <div class="form-group">
                            <label for="phone">Телефон</label>
                            <input type="tel" id="phone" name="phone" required>
                        </div>
                        <div class="form-group">
                            <label for="message">Ваш вопрос</label>
                            <textarea id="message" name="message" required></textarea>
                        </div>
                        <button type="submit" class="btn">Отправить заявку</button>
                    </form>
                </div>
            </div>
            
            <div class="map-container">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/6f/Samara_Oblast.svg/1200px-Samara_Oblast.svg.png" alt="Карта Самарской области" class="map-image">
            </div>
        </div>
    </section>

    <!-- Футер -->
    <footer>
        <div class="container">
            <div class="footer-container">
                <div>
                    <div class="footer-logo">ВозвратСтраховокРФ</div>
                    <p>Юридическая помощь по возврату навязанных страховок в Самарской области</p>
                </div>
                
                <div>
                    <h3>Навигация</h3>
                    <ul class="footer-nav">
                        <li><a href="#services">Услуги</a></li>
                        <li><a href="#about">О нас</a></li>
                        <li><a href="#articles">Статьи</a></li>
                        <li><a href="#contacts">Контакты</a></li>
                    </ul>
                </div>
                
                <div class="footer-contact">
                    <h3>Контакты</h3>
                    <p>Телефон: +7 (919) 818-08-35</p>
                    <p>Email: mail@arsconsulting.su</p>
                    <p>Регион: Самарская область</p>
                </div>
            </div>
            
            <div class="copyright">
                <p>&copy; 2024 ВозвратСтраховокРФ. Все права защищены.</p>
            </div>
        </div>
    </footer>

    <script>
        // Плавная прокрутка к якорям
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                
                const targetId = this.getAttribute('href');
                if (targetId === '#') return;
                
                const targetElement = document.querySelector(targetId);
                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop - 80,
                        behavior: 'smooth'
                    });
                }
            });
        });
        
        // Аккордеон для FAQ
        document.querySelectorAll('.faq-question').forEach(question => {
            question.addEventListener('click', () => {
                const answer = question.nextElementSibling;
                const isActive = answer.classList.contains('active');
                
                // Закрываем все ответы
                document.querySelectorAll('.faq-answer').forEach(item => {
                    item.classList.remove('active');
                });
                
                document.querySelectorAll('.faq-question span:last-child').forEach(icon => {
                    icon.textContent = '+';
                });
                
                // Открываем текущий ответ, если он был закрыт
                if (!isActive) {
                    answer.classList.add('active');
                    question.querySelector('span:last-child').textContent = '−';
                }
            });
        });
        
        // Мобильное меню
        const mobileMenuBtn = document.querySelector('.mobile-menu-btn');
        const navMenu = document.querySelector('.nav-menu');
        
        mobileMenuBtn.addEventListener('click', () => {
            navMenu.classList.toggle('active');
        });
        
        // Обработка формы
        const contactForm = document.getElementById('consultation-form');
        
        contactForm.addEventListener('submit', function(e) {
            e.preventDefault();
            
            // Простая валидация
            const name = document.getElementById('name').value.trim();
            const phone = document.getElementById('phone').value.trim();
            const message = document.getElementById('message').value.trim();
            
            if (!name || !phone || !message) {
                alert('Пожалуйста, заполните все поля');
                return;
            }
            
            // В реальном проекте здесь был бы код для отправки данных на сервер
            alert('Спасибо! Ваша заявка отправлена. Мы свяжемся с вами в ближайшее время.');
            contactForm.reset();
        });
        
        // Закрытие мобильного меню при клике на ссылку
        document.querySelectorAll('.nav-menu a').forEach(link => {
            link.addEventListener('click', () => {
                navMenu.classList.remove('active');
            });
        });
    </script>
</body>
</html>
