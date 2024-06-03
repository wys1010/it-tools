<script setup lang="ts">
    import { useHead } from '@vueuse/head';

    useHead({ title: 'donat' });

</script>

<template>

    <div style="margin-top: 20px;">
        <label id="ethereum-address" aria-label="evm-address">EVM Address：</label>
        <span id="address-value" aria-hidden="true">0xd868ea7d8cb66af30398f9503a99b77147d5ee0d</span>
    </div>

</template>

<style scoped>
    #ethereum-address {
        font-size: 1.5rem;
        font-weight: bold;
    }

    #address-value {
        font-size: 1.2rem;
        font-weight: normal;
        margin-left: 0.5rem;
    }

    button {
        margin-left: 1rem;
        padding: 0.5rem 1rem;
    }
</style>