<template>
    <div class="product-card">
        <picture><img src="./images/image-product-desktop.jpg" alt="Perfume bottle" width="200px"></picture>
        <div class="side">
            <div class="description">
                <span class="category">PERFUME</span>
                <h2>Gabrielle Essence Eau De Parfum</h2>
                <p>A floral, solar and voluptuous interpretation composed by Olivier Polge, 
                    Perfumer-Creator for the House of CHANEL.
                </p>
            </div>
            <div class="price">$149.99 <span class="mrp">$169.99</span></div>
            <div class="add-to-cart">
                <!-- <KpsIcons name='ic'/> -->
                <img class="svg" src="./images/icon-cart.svg"/>
                <label class="cart-button">Add to Cart</label>
            </div>
        </div>
    </div>
</template>

<style >
@import url('https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght@9..144,700&family=Montserrat:wght@500;700&display=swap');
    p {
        font-size: 14px;
    }
    .svg{
        padding: 5px;
    }
    .product-card {
        background-color: white;
        display: flex;
        width: 450px;
        height: auto;
        align-items: center;
    }
    .side {
        font-family: 'Montserrat';
        font-weight: 500;
        display: flex;
        flex-direction: column;
        height: 300px;
        justify-content: space-around;
        margin-left: 20px;
    }
    h2 {
        font-family: 'Fraunces';
        font-weight: 700;
    }
    .category {
        align-self: flex-end;
        font-weight: 500;
        letter-spacing: 5px;
    }
    .add-to-cart {
        background-color: aquamarine;
        font-size: large;
        font-weight: 600;
        width: 150px;
        padding: 5px;
        border-radius: 5px;
        align-self: center;
        display: flex;
    }
    .cart-button {
        margin-left: 5px;
    }
    .add-to-cart:hover{
        scale: 1.1;
        transition: scale 0.5s ease;
        cursor: pointer;
    }
    .price {
        font-size: x-large;
        font-family: 'Fraunces';
        display: flex;
        align-items: center;
    }
    .mrp {
        font-family: 'Montserrat';
        margin-left: 20px;
        font-size: small;
        text-decoration: line-through;
    }
</style>

<script>
import KpsIcons from './icons/KpsIcons.vue'
export default {
    data(){
        return{
            perfume: 'image-product-desktop.jpg',
        }
    },
    components: {
        KpsIcons
    }
}
</script>