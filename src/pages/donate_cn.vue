<script setup lang="ts">
    import { useHead } from '@vueuse/head';

    useHead({ title: 'donat' });
</script>

<template>
    <h1>欢迎捐赠</h1>
    <p>感谢您对我们的支持！请使用以下二维码进行捐赠：</p>

    <div class="donation-container">
        <img class="payment_code" alt="支付宝捐赠" src="https://storage.gdyuanpeng.com/default/20240516/18/01/7/zfb.jpg"
            data-src="支付宝收款码的图片URL">


        <img class="payment_code" alt="微信捐赠" src="https://storage.gdyuanpeng.com/default/20240516/18/00/7/wx.jpg"
            data-src="微信收款码的图片URL">
    </div>

    <p>扫描二维码后，请按照提示完成捐赠流程。</p>

    <footer>
        <p>所有捐赠将用于我们的运营和持续发展。</p>
    </footer>
</template>



<style scoped>
    .donation-container {
        text-align: center;
        margin-top: 50px;
        display: flex;
        justify-content: space-between;
        width: 50%;
        margin: auto;
    }

    .payment_code {
        display: inline-block;
        margin: 10px;
        max-width: 300px;
        height: 400px;
        width: 300px;
    }
</style>