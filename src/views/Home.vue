<template>
    <div class="shop-page">
        <h1>Товары для шугаринга</h1>
        <div class="breadcrumbs"></div>
        <div class="items-wrapper">
            <aside class="items-filter">
                <ul>
                    <li><a href="#">Наборы для депиляции</a>
                    <ul>
                        <li value="nabor-shugaring"><a href="#">Наборы для шугаринга</a></li>
                        <li value="nabor-vosk"><a href="#">Наборы для восковой депиляции</a></li>
                    </ul>
                    </li>
                </ul>
                <ul>
                    <li><a href="#">Дополнительные продукты</a>
                    <ul>
                        <li value="add-shine"><a href="#">Блестки</a></li>
                        <li value="add-shine"><a href="#">Перчатки</a></li>
                    </ul>
                    </li>
                </ul>
                <ul>
                    <li><a href="#">Мебель для кабинета</a>
                    <ul>
                        <li value="pufy"><a href="#">Пуфы</a></li>
                        <li value="pufy"><a href="#">Диваны</a></li>
                        <li value="pufy"><a href="#">Кешетки</a></li>
                    </ul>
                    </li>
                </ul>
            </aside>
            <main class="all-items">
                <div class="product-item">
                    <img src="http://placehold.it/250x150 " alt=" ">
                    <div class="item-content">
                        <div class="item-name">Паста для депиляции</div>
                        <div class="item-price">250 грн</div>
                    </div>
                </div>
                <div class="product-item">
                    <img src="http://placehold.it/250x150 " alt=" ">
                    <div class="item-content">
                        <div class="item-name">Паста для депиляции</div>
                        <div class="item-price">250 грн</div>
                    </div>
                </div>
                <div class="product-item">
                    <img src="http://placehold.it/250x150 " alt=" ">
                    <div class="item-content">
                        <div class="item-name">Паста для депиляции</div>
                        <div class="item-price">250 грн</div>
                    </div>
                </div>
                <div class="product-item">
                    <img src="http://placehold.it/250x150 " alt=" ">
                    <div class="item-content">
                        <div class="item-name">Паста для депиляции</div>
                        <div class="item-price">250 грн</div>
                    </div>
                </div>
            </main>
        </div>
    </div>
</template>

<script>
    export default {
        name: "Home"
    }
</script>

<style scoped>
.items-wrapper{
    display: flex;
}
.items-filter{
    width: 255px;
    display: block;
}
.items-filter > ul li a{
    display: block;
    background: #ececed;
    padding: 15px 30px 15px 40px;
    font-size: 14px;
    color: #000524;
    text-decoration: none;
    text-transform:uppercase;
    margin-right: 10px;
    margin-bottom: 5px;
    transition: all 0.3s ease;
}
.items-filter li a:hover{
    background: rgba(12,7,36,0.67);
    color: #ffffff;
    box-shadow: 1px 5px 10px -5px black;
    transition: all 0.3s ease;
}
</style>