<script>
export default{
data(){
return{
    SUPRA: [
    {href: '1.html',text: 'Gleb',},
    {href: '2.html',text: 'Gleb',},
    {href: '3.html',text: 'Gleb',},
    ],
    products: [
    {
        name: 'product1',
        price: 100,
        quantity: 5
    },
    {
        name: 'product2',
        price: 200,
        quantity: 4
    },
    {
        name: 'product3',
        price: 300,
        quantity: 3
    },
    ]
}
}
}
</script>
Glebchikkk
<template>
<ul class="styled">
    <li v-for="link in SUPRA"><a SUPRA="{{ link.SUPRA }}">{{ link.text }}</a></li>
</ul>
<br>
<br>
<table>
    <tr v-for="col in products">
    <td>{{ col.name }}</td>
    <td>{{ col.price }}</td>
    <td>{{ col.quantity }}</td>
    </tr>
</table>
</template>

<style >
</style>