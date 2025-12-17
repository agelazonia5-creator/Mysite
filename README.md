!DOCTYPE html>
<html lang="ru">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Мой сайт</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <header>
      <nav>
        <a class="menu-item" href="#main">Главная</a>
        <a class="menu-item" href="#about">Обо мне</a>
        <a class="menu-item" href="#achivments">Мои домтижения</a>
        <a class="menu-item" href="#contact">Контакты</a>
      </nav>
      <div class="mobile-block">
        <h1>Навигация</h1>
    </header>

    <main>
      <div id="side-bar">
        <img
          class="menu-close"
          src="images/close.svg"
          alt="Menu Close"
          onclick="closeSideBar()"
        />
        <div class="menu-items">
          <a class="menu-item" href="#main">Главная</a>
          <a class="menu-item" href="#about">О банке</a>
          <a class="menu-item" href="#achivments">Достижения банки</a>
          <a class="menu-item" href="#contact">Контакты</a>
        </div>
      </div>

      <section id="main">
        <div class="main-text">
          <h1 class="header">портфолио</h1>
          <p class="text">
            привееет! Меня зовут Саша и я сделал свой первый сайт!!
          </p>
          <div class="skills-tags">
            <span class="tag">я надежный</span>
            <span class="tag">я крутоой</span>
            <span class="tag">Я красавчик</span>
          </div>
        </div>
        <img
          class="avatar"
          src= https://avatars.mds.yandex.net/i?id=55041a09f5afcd8db8191d98c71be53f383bd903-5246097-images-thumbs&n=13
          alt="обо мнее"
        />
      </section>

      <section id="about" style="position: relative">
        <div class="about-content">
          <h1>Обо мне</h1>
          <div class="about-wrapper">
            <img
              class="avatar about-avatar"
              src=data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD/2wCEAAkGBxAPEBUQDxMVFhUVFhoWGBgYFhEXFRgVFhcYHhkYGRgfHiggGBomGxUXITIlJSkuLi4uFx8zODgsNygtLisBCgoKBQUFDgUFDisZExkrKysrKysrKysrKysrKysrKysrKysrKysrKysrKysrKysrKysrKysrKysrKysrKysrK//AABEIAOEA4QMBIgACEQEDEQH/xAAcAAEAAgMBAQEAAAAAAAAAAAAABgcBBQgEAwL/xABKEAABAwIEAgcDBgkKBwEAAAABAAIDBBEFBhIhBzETIkFRYXGBCJGhFDJScnSyIzVCYoKxs8HRJCUzNlRzkpPD0hUmNENEU/AX/8QAFAEBAAAAAAAAAAAAAAAAAAAAAP/EABQRAQAAAAAAAAAAAAAAAAAAAAD/2gAMAwEAAhEDEQA/AKNREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEW3y1lypxKYwUjNbw0uILmtAaOZufNffNGUqzC3MZWsDDI0ubZ7HXAIB5HbmEGhRTLBuGOLVkDKiCAGN4u0ukjaXD6QBN7FRrF8MkpJn08wAkjdpcA5rgDbvGxQeJFv8sZPrsTNqOFzwDZzzZsbfNx2v4C5Uuk4H4uG6gacn6Ildf3ltr+qCskW0x/AKqgk6KridE7mL8nDva4bOHkvhhGGy1czKeBuqSR2louBc+Z2CDxIp+eDmN/2dn+dD/uUezBk+vw4A1lO+Np2Duq5hPdqaSLoNCiypNlbIeI4mNdLCTHy6RxDI7juJ+d6AoIwisup4I4uxupvQPP0WyEH01NAUBxbCp6SUw1Mbo5G82uFjY9o7CPEIPEilOWeH+I4lCZ6SIOYHFtzJG3rDmACb9oW2//AB3G/wCzt/zoP9yCAIpVW8P8Rgq4aKSICecExt6SMght73dew+aV8s0ZGr8LYySsiDGvdpaQ+N3Wte2x22BQRpFKst8PsSxGHp6SEOjuW6i+NlyOdrkXstXmPL1Rh0/yeraGyaQ6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
              alt="обо мнее"
            />
            <div class="about-text">
              <p class="about-paragraph">
                Я родился в Америке в 1899 году. Переехал в Россию  и начал учиться в школе. В школе было сожно привыкнуть, другие люди, нет никаких знакомых, друзей, но я смог найи общий язык с людьми. Что мне
                не понравилось, так это то, что в РОссии не очень популярен вид спорта, который ппулярен у меня на родине - баскетбол. А так все по кайфу
              </p>
              <p class="about-paragraph">
                Очен рад, что перехал сюда. Здесь оень класснооо!!
              </p>
            </div>
          </div>
        </div>
      </section>

      <section id="achivments">
        <h1>Мои достижения</h1>
        <div class="achivments-container">
          <div class="achivment-card">
            <div class="achivment-icon">&#127891</div>
            <h3>обучение</h3>
            <p>
              Я учусь в школе 1363, там очень интересно. Еще я хожу на дополнительное обучение в университет МИСИС по
               изучению создание сайт с помощью разных языков программирования
            </p>
          </div>
          <div class="achivment-card">
            <div class="achivment-icon">&#127936</div>
            <h3>Спорт</h3>
            <p>
              Выигрыввл разные соревнования от школы по баскетболу, один из которых стал КЭС баскет.
              Противнки были очень сильные, но мы не сдалиь и забрали первое место
            </p>
          </div>
          <div class="achivment-card">
            <div class="achivment-icon">&#9889</div>
            <h3>Совершенствование</h3>
            <p>
              Постоянно совершенствуюсь в спорте и в учебе. Изучаю новые навыки и просто пытаюсь
              стать лучше
            </p>
          </div>
          <div class="achivment-card">
            <div class="achivment-icon">&#128293</div>
            <h3>Мои разработки</h3>
            <p>
              Сделал первый сайт и бумажный самолетик 
              на уроке технологии в 1 классе
            </p>
          </div>
        </div>
      </section>

      <section id="contact">
        <h1>Свяжитесь со мной</h1>
        <p class="contact-description">
          Хотите задать впорос или больше узнать обо мне?  
          Заполните тут ваши данные и я сяжусь с вами!❤️
        </p>
        <form>
          <label for="name">Ваше имя</label>
          <input
            id="name"
            class="input"
            name="name"
            type="text"
            placeholder="Введите ваше имя"
          />

          <label for="age">Ваш возраст</label>
          <input
            id="age"
            name="age"
            type="number"
            placeholder="Введите количество для заказа"
          />

          <label for="email">Ваш e-mail</label>
          <input
            id="email"
            name="email"
            type="email"
            placeholder="example@mail.ru"
          />

          <label for="message">Ваше сообщение</label>
          <textarea
            id="message"
            name="message"
            placeholder="Опишите свой заказ или задайте вопрос"
          ></textarea>
        </form>
        <button id="button" class="form-btn" onclick="sendForm()">
          Отправить
        </button>
      </section>
    </main>
    <footer>
      <div class="footer-content">
        <div class="footer-links">
          <a href="tel:+79775069580">📞 +7 (985) 950 57 85</a>
          <a href="mailto:flionlin@ya.ru">✉️ agelazoniya@gmail.com</a>
        </div>
      </div>
    </footer>
  </body>

  <script src="script.js"></script>
</html>
