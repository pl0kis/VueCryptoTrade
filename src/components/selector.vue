<script>
export default{

}
</script>

<template>
    <ul>
        <li>
            Bitcoin
        </li>
        <li>
            ETH
        </li>
        <li>
            USDT
        </li>
    </ul>

</template>

<style scoped>
ul{
    list-style: none;
    width: 200px;
    padding: 0;
    border-radius: 3px;
    border: 3px solid #000;
}
li{
    display: block;
    background:#1A032D;
    color: white;
    padding: 20px 0;
}
li:hover, li.active{
background: #24043e;
cursor: pointer;
}
</style>
