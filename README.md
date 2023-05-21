# dyplom
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Styles -->
    <link rel="stylesheet" href="styles/fancybox.css">
    <link rel="stylesheet" href="styles/tailwind.css">
    <link rel="stylesheet" href="styles/master.css">
    <!-- Styles -->
    <!-- Favicons -->
    <link type="image/x-icon" href="img/favicon.jpg" rel="shortcut icon">
    <link type="Image/x-icon" href="img/favicon.jpg" rel="icon">
    <!-- Favicons -->
    <title> Козаченко Л.В. Перевезення</title>
</head>

<body class="wrapper">
<!-- Float Elements -->

    <!-- Notifications block -->
    <div id="notification" class="
    fixed
    my-4
    w-full
    select-none
    flex
    justify-center
    items-center
    text-md
    text-white
    ">
    <div id="not-text" class="flex py-6 px-12 rounded-lg cursor-pointer bg-gray-800">
            Ошибка или успех
        </div>
    </div>

    <!-- To top Arrow -->
    <div id="to-top" class="
        select-none
        flex
        justify-center
        items-center
        cursor-pointer
        text-3xl
        text-white
        rounded-full
        fixed

        bottom-0
        right-0
        my-4
        mx-4

        sm:mx-14
        sm:my-14

        bg-pink-500
        h-12
        w-12
        transition-all
        opacity-50
        hover:opacity-100
        ">
    </div>


    <!-- Preloader -->
    <div id="preloader" class="flex fixed w-screen h-screen z-50 bg-white justify-center items-center">
        <span id="loading-value" class="font-theme text-lg absolute">0%</span>
        <div class="flex animate-spin circle h-20 w-20 border-t-2 border-purple-600 rounded-full">
        </div>
    </div>

<!-- Float Elements -->


    <!-- DESKTOP HEADER -->
    <header class="section sm:bg-white justify-center desktop-header">
        <div class="container">

            <div class="flex flex-col md:flex-row w-full flex-wrap md:justify-between items-stretch">

                <a href="#" class="flex logo sm:mr-5 pb-5 md:pb-0 sm:justify-center items-center flex-1">
                    <img src="img/logo.svg" class="object-left sm:object-center object-contain" alt="LOGO">
                </a>

                <div class="flex sm:mr-5 pb-5 md:pb-0 items-center sm:justify-center flex-1 w-full">
                    <a href="#gallery" class="header-search">Транспорт</a>
                </div>

                <div class="flex sm:mr-5 pb-5 md:pb-0 items-center sm:justify-center flex-1 w-full">
                    <a class="text-sm text-center w-full sm:w-auto sm:text-md lg:text-lg" href="tel: +38 097 7217 249">+38 050 5638 438</a>
                </div>

                <div class="flex items-center sm:justify-center flex-1">
                    <a href="#conditions" class="w-full text-center text-sm sm:text-md rounded-full pink-border px-2 py-2 transition-all hover:bg-pink-500 hover:text-white">Зворотний звінок</a>
                </div>
            </div>

        </div>
    </header>
    <!-- DESKTOP HEADER -->

    <!-- MOBILE HEADER -->
    <header class="section mobile-header pb-0 pt-2">
        <div class="container pb-2">
            <div class="flex px-2 w-full items-center justify-between">
                <a href="#" class="flex logo w-48">
                    <img src="img/logo.svg" class="sm:object-center object-contain" alt="LOGO">
                </a>
                <a href="tel: +38 097 7217 249" class="flex cursor-pointer">
                    &#128222;
                </a>
            </div>
        </div>
        <nav class="flex self-stretch w-full items-center text-sm">
            <a href="#price" class="flex flex-1 justify-center items-center bg-pink-700 text-white">Ціна</a>
            <a href="#conditions" class="flex flex-1 justify-center items-center bg-purple-700 text-white">Умови</a>
            <a href="#times" class="flex flex-1 justify-center items-center bg-blue-500 text-white">Час поїздки</a>
        </nav>
        <nav class="flex self-stretch w-full items-center text-sm">
            <a href="#gallery" class="flex flex-1 justify-center items-center bg-blue-600 text-white">Транспорт</a>
        </nav>
    </header>
    <!-- MOBILE HEADER -->

    <!-- MAIN SECTIONS STACK -->
    <main>

        <div class="section desktop-header">
            <div class="container container-small">
                <nav class="flex flex-col sm:flex-row w-full flex-wrap justify-between">
                    <a href="#price" class="flex flex-1 items-center sm:justify-center">Ціна</a>
                    <a href="#conditions" class="flex flex-1 items-center sm:justify-center">Умови</a>
                    <a href="#times" class="flex flex-1 items-center sm:justify-center">Час поїздки</a>
                </nav>
            </div>
        </div>

        <!-- FIRST SCREEN -->
        <section class="section main-screen">
            <div class="container flex-col py-16">
                <div class="flex flex-col sm:flex-row w-full items-center justify-around">

                    <div class="flex flex-col items-center sm:items-start">
                        <h1 class="flex text-center text-3xl text-white mb-8 sm:text-left sm:mb-4 1xl:text-4xl">Козаченко Л.В. Перевезення</h1>
                        <span class="flex text-sm text-white mb-8">Регулярні перевезення товарної продукції по Україні</span>
                        <span class="flex text-md text-white mb-8">
                            <a href="#benefits" class="transition-all text-center hover:bg-white hover:text-black text-sm sm:text-md rounded-full border-2 border-white px-6 py-2 ">Чому варто обирати нас</a>
                        </span>
                    </div>

                    <div class="flex overflow-hidden flex-shrink-0 md:ml-10">
                        <div class="flex overflow-hidden border-8 border-pink-800 rounded-full">
                            <img class="w-48 h-48 sm:w-64 sm:h-64 md:w-80 md:h-80 object-cover rounded-full border-4 border-pink-200" src="img/3.jpg" alt="MainImage">
                        </div>
                    </div>

                </div>
            </div>
        </section>

        <!-- SECOND SCREEN  -->
        <section class="section">
            <div class="container mt-10">

                <div class="flex flex-col w-full md:flex-row md:justify-between">

                    <div class="w-full rounded-md flex flex-col sm:flex-row justify-center sm:justify-around items-center bg-main flex-grow mb-5 md:mb-0 p-4 mr-0 md:mr-4">

                        <form type="post" class="flex flex-col justify-center items-center md:mr-4">

                            <div class="mb-4 flex flex-grow text-white self-center sm:self-start text-lg font-theme md:text-md lg:text-lg">Зв'язатись з нами</div>

                            <div class="mb-4 flex flex-grow text-white self-center sm:self-start text-sm font-theme md:text-md lg:text-lg">
                                <input type="tel" name="phone" minlength="13" maxlength="13" required id="phone" class="send-input text-black text-sm font-theme" value="+380" placeholder="+380*********">
                            </div>

                            <div class="mb-4 flex flex-grow text-white self-center sm:self-start text-sm font-theme md:text-md lg:text-lg">
                                <button type="submit" class="transition-all hover:bg-white hover:text-black text-sm sm:text-md rounded-full border-2 border-white px-5 py-1 ">Відправити</button>
                            </div>

                        </form>

                        <div class="flex overflow-hidden w-full shadow-md h-0 w-0 sm:w-36 sm:h-36 lg:w-48">
                            <img src="img/ua.jpg" class="hidden rounded-lg shadow sm:w-full sm:h-full sm:flex w-full h-full object-cover" alt="UA">
                        </div>

                    </div>

                    <div id="conditions" class="w-full rounded-md flex flex-col sm:flex-row justify-center sm:justify-around items-center bg-main flex-grow mb-5 md:mb-0 p-4">
                        <div class="flex flex-col justify-center self-start sm:self-start items-start md:mr-4">
                            <div class="flex info-head font-theme text-lg">Чому ми:</div>
                            <ul class="flex flex-col info-list  mb-4 sm:mb-0">
                                <li>🔥 --- Автономне опа</li>
                                <li>💧 --- Возимо в будь-яку погоду</li>
                                <li>📶 --- Завжди на зв''</li>
                                <li>😊 --- Задоволені клієнти</li>
                            </ul>
                        </div>

                        <div class="flex overflow-hidden hidden lg:flex shadow-md w-full h-0 w-0 lg:w-36 lg:h-36 lg:w-48">
                            <img src="img/dh.png" class="hidden rounded-lg md:w-full lg:h-full lg:flex object-cover" alt="DE">
                        </div>
                    </div>

                </div>
            </div>
        </section>

        <!-- INFO -->
        <section class="section">
            <div class="container">
                <div id="price" class="
                    flex
                    items-center
                    justify-center
                    w-full
                    shadow-lg
                    p-4
                    rounded-md
                    cursor-pointer
                    md:mt-4
                    bg-pink-500
                    text-white
                    ">
                    <img src="img/price.svg"
                        class="w-8 h-8 sm:w-10 sm:h-10 object-contain"
                    >
                    <span class="ml-4">Ціна перевезення прямо залежить напряму від габаратиів і ваги</span>
                </div>
            </div>
        </section>
        <!-- INFO -->


        <!-- THIRD SCREEN -->
        <section id="benefits" class="section mt-4 md:mt-8">
            <div class="container">
                <div class="flex flex-col w-full items-stretch cursor-pointer select-none">

                    <div class="flex flex-row items-center shadow p-4 border-b border-gray-300 mb-4 transition-all hover:main">
                        <div class="flex sm:w-10/12 justify-between sm:justify-start w-full items-center">
                            <div class="flex ben-item items-center text-3xl mr-4 sm:mr-0">&#9850;</div>
                            <div class="flex text-sm sm:text-lg text-right sm:text-left">У нас регулярні виїзди щоденно</div>
                        </div>
                    </div>


                    <div class="flex w-full items-center shadow p-4 border-b border-gray-300 mb-4 transition-all hover:main">
                        <div class="flex sm:w-10/12 justify-between sm:justify-start w-full items-center">
                            <div class="flex ben-item items-center text-xl mr-4 sm:mr-0">&#22291;</div>
                            <div class="flex text-sm sm:text-lg text-right sm:text-left">Ми виготовляєм пакет документів для виїзду</div>
                        </div>
                    </div>

                    <div class="flex w-full items-center shadow p-4 border-b border-gray-300 mb-4 transition-all hover:main">
                        <div class="flex sm:w-10/12 justify-between sm:justify-start w-full items-center">
                            <div class="flex ben-item items-center text-3xl mr-4 sm:mr-0">&#9873;</div>
                            <div class="flex text-sm sm:text-lg text-right sm:text-left">Веземо до місця призначення</div>
                        </div>
                    </div>

                    <div class="flex w-full items-center shadow p-4 border-b border-gray-300 mb-4 transition-all hover:main">
                        <div class="flex sm:w-10/12 justify-between sm:justify-start w-full items-center">
                            <div class="flex ben-item items-center text-3xl mr-4 sm:mr-0">&#128386;</div>
                            <div class="flex text-sm sm:text-lg text-right sm:text-left">Листи перевозим за окремим тарифом</div>
                        </div>
                    </div>

                    <div class="flex w-full items-center shadow p-4 border-b border-gray-300 mb-4 transition-all hover:main">
                        <div class="flex sm:w-10/12 justify-between sm:justify-start w-full items-center">
                            <div class="flex ben-item items-center text-2xl mr-4 sm:mr-0">&#10105;</div>
                            <div class="flex text-sm sm:text-lg text-right sm:text-left">Працюєм в цій сфері більше 4 років</div>
                        </div>
                    </div>
                </div>
            </div>
        </section>


        <!-- INFO 2 -->
        <section class="section my-4">
            <div class="container flex-col">
                <h1 class="text-lg w-full text-center mb-4 md:text-xl md:text-left md:mb-6">Головна інформація</h1>
                <div class="grid grid w-full cursor-pointer justify-items-stretch gap-3 grid-cols-1 sm:grid-cols-2 md:grid-cols-2">

                    <div id="times" class="flex flex-col shadow p-4 transition-all border-t-4 border-pink-600 border-opacity-50 hover:border-opacity-100">
                        <span class="text-lg pb-2 font-bold border-b border-pink-600">
                            Інформація
                        </span>
                        <p class="mt-2 text-sm">
                            <ul class="list-inside">
                                <li><span class="text-pink-600"></span> Беремо до відправки:</li>
                                <ul class="ml-4 my-2 list-inside list-disc">
                                    <li>Палети</li>
                                    <li>Листи</li>
                                    <li>Особисті речі</li>
                                </ul>
                                <li><span class="text-pink-600"></span> Не перевозимо:</li>
                                <ul class="ml-4 my-2 list-inside list-disc">
                                    <li>Зброю та вибухівку(або легкозаймисті речовини)</li>
                                    <li>Людей, тварин та їх частини</li>
                                    <li>Лікарські та наркотичні засоби</li>
                                    <li>Та інше</li>
                                </ul>
                            </ul>
                        </p>
                    </div>

                    <div class="flex flex-col shadow p-4 transition-all border-t-4 border-pink-600 border-opacity-50 hover:border-opacity-100">
                        <span class="text-lg pb-2 font-bold border-b border-pink-600">
                            Ми знаходимось:
                        </span>
                        <p class="mt-2 text-sm">
                            <ul class="ml-4 my-2">
                                <li class="border-l-2 transition-all mb-2 p-2 border-pink-600 hover:shadow"><b>-</b>&nbsp;&nbsp;смт. Смига</li>
                            </ul>
                        </p>
                    </div>


                </div>
            </div>
        </section>
        <!-- INFO 2 -->

        <!-- GALLERY IMAGES (Fancy box) -->
        <div id="gallery" class="section mt-4 md:mt-8">
            <div class="container">
                <div id="gallery" class="grid w-full cursor-pointer justify-items-stretch gap-1 grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4">
                    <a href="img/1.jpg" class="flex w-full h-48"><img class="object-cover h-full w-full" src="img/1.jpg" alt="Gallery Image"></a>
                    <!-- IMAGE -->
                    <a href="img/2.jpg" class="flex w-full h-48"><img class="object-cover h-full w-full" src="img/2.jpg" alt="Gallery Image"></a>
                    <a href="img/gallery/3.jpg" class="flex w-full h-48"><img class="object-cover h-full w-full" src="img/gallery/3.jpg" alt="Gallery Image"></a>
                    <a href="img/gallery/4.jpg" class="flex w-full h-48"><img class="object-cover h-full w-full" src="img/gallery/4.jpg" alt="Gallery Image"></a>
                    <a href="img/gallery/5.jpg" class="flex w-full h-48"><img class="object-cover h-full w-full" src="img/gallery/5.jpg" alt="Gallery Image"></a>
                    <a href="img/gallery/6.jpeg" class="flex w-full h-48"><img class="object-cover h-full w-full" src="img/gallery/6.jpeg" alt="Gallery Image"></a>
                    <a href="img/gallery/7.jpg" class="flex w-full h-48"><img class="object-cover h-full w-full" src="img/gallery/7.jpg" alt="Gallery Image"></a>
                    <a href="img/gallery/9.jpg" class="flex w-full h-48"><img class="object-cover h-full w-full" src="img/gallery/9.jpg" alt="Gallery Image"></a>
                </div>
            </div>
        </div>
        <!-- GALLERY IMAGES -->

    </main>
    <!-- MAIN SECTIONS STACK -->

    <!-- FOOTER -->
    <footer class="section">
        <div class="container">
            <div class="flex flex-col-reverse items-center w-full flex-wrap md:flex-row md:justify-between md:items-center">

                <div class="flex mx-2 mb-4 md:mb-0">
                    <a target="_blank" href="https://www.instagram.com/mamchur_victor/" class="flex mr-4 w-9 h-9"><img src="img/ig.svg" alt="Instagram"></a>
                    <a target="_blank" href="https://www.facebook.com/profile.php?id=100022909552829" class="flex mr-4 w-9 h-9"><img src="img/fb.svg" alt="Facebook"></a>
                </div>

                <div class="flex mx-2 sm:mr-5 pb-5 md:pb-0 items-center sm:justify-center">
                    <a class="text-sm sm:text-md lg:text-lg" href="tel: +38 050 5638 438">+38 050 5638 438</a>
                </div>

                <div class="flex mx-2 mb-4 md:mb-0 text-sm">
                  Можливе перевезення день у день
                </div>

                <div class="flex mx-2 mb-4 items-center md:mb-0 sm:justify-center">
                    <a href="#conditions" class="text-sm text-center sm:text-md rounded-full pink-border px-4 py-2 transition-all hover:bg-pink-500 hover:text-white">Зворотний звінок</a>
                </div>

            </div>
        </div>
    </footer>
    <!-- FOOTER -->

    <!-- BOTTOM FOOTER -->
    <section class="section sub-footer">
        <div class="container">
            <div class="flex flex-col-reverse items-center w-full flex-wrap md:flex-row md:justify-between md:items-center">
                <address class="flex w-full items-center justify-center text-sm p-4 not-italic">(c) All right reserved 2023</address>
            </div>
        </div>
    </section>
    <!-- BOTTOM FOOTER -->


    <!-- SCRIPTS -->
    <script src="script/fancybox.js"></script>
    <script src="script/master.js"></script>
</body>

</html>
