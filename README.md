let urun1 = {

    isim : "Monster Tulpar T7 ",
    fiyat : "16.000 TL"  , 
    tip : "Laptop"
}
let urun2 = {

    isim : "Monster Huma H4",
    fiyat : "12.000 TL"  , 
    tip : "Laptop"
}
let urun3 = {

    isim : "Casper Excalibur G870",
    fiyat : "18.000 TL" , 
    tip : "Laptop"
}
let urun4 = {

    isim : "Casper Nirvana X650",
    fiyat : "20.000 TL"  , 
    tip : "Laptop"
}
let urun5 = {

    isim : "Huawei MateBook 14",
    fiyat : "19.000 TL" , 
    tip : "Laptop"
}
let urun6 = {

    isim : "Huawei MateBook D14",
    fiyat : "11.000 TL"  , 
    tip : "Laptop"
}
let urun7 = {

    isim : "Lenovo Ideapad 1",
    fiyat : "14.000 TL"  , 
    tip : "Laptop"
}
let urun8 = {

    isim : "Lenovo Yoga 7",
    fiyat : "26.000 TL"  , 
    tip : "Laptop"
}
let urun9 = {

    isim : "Lenovo Ideapad Slim 3",
    fiyat : "21.000 TL"  , 
    tip : "Laptop"
}
let urun10 = {

    isim : "Acer Aspire 3",
    fiyat : "41.000 TL" , 
    tip : "Laptop"
}

let Searching = prompt("Lütfen istediğiniz markanın adını giriniz");
let FoundsProduct = [];
let urunler = [urun1,urun2,urun3,urun4,urun5,urun6,urun7,urun8,urun9,urun10];


ekle(urunler);
yaz(FoundsProduct);

function ekle(urunler) {
urunler.forEach(function(urun){
    if(urun.isim.toLowerCase().includes(Searching.toLowerCase(),0)){
FoundsProduct.push(urun);}})}

function yaz(urunler) { 
    urunler.forEach(function(urun){
console.log("|" + urun.isim + "|" + urun.fiyat + "|" + urun.tip + "|");
console.log("------------------------------------------------------");
})}

//fiyatlar farazidir
