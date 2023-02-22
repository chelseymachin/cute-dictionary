<script setup>
</script>
<template>
    <div class="flex input-container w-full">
        <input type="text" placeholder="Type here" />
        <img src="@/assets/images/icon-search.svg" class="filter-border content-end" />
    </div>
</template>
<style>
.input-container {
    margin-top: 2rem;
    height: 3rem;
    padding: 0.8rem;
    border-radius: 20px;
    border-color: hsl(var(--b2));
    border-width: 1px;
}
input {
    all: unset;
    width: 97%;
    color: hsl(var(--bc));
}
img {
    margin: auto;
}
.filter-border {
    filter: invert(90%) sepia(54%) saturate(1234%) hue-rotate(276deg) brightness(94%) contrast(81%);
}
</style>