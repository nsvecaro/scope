<template>
    <div class="card">
        <h1 class="card-title">{{ title }}</h1>
        <p class="card-description">{{ description }}</p>
        <div class="card-number">{{ number }}</div>
    </div>
</template>

<script setup>
defineProps({
    number: [String, Number],
    title: String,
    description: String
})
</script>

<style scoped>
.card {
    display: flex;
    position: relative;
    flex-direction: column;
    width: 300px;
    height: 400px;
    padding: 50px 20px;
    background: linear-gradient(135deg, #202020aa, #303030aa, #202020aa);
    border-radius: 15px;
    color: #e8e9e3;
    transition: all 0.5s ease;
    border: 1px solid #ffffff2b;
    backdrop-filter: blur(10px);
}

.card:hover {
    transform: scale(1.05);
}

.card-title {
    font-size: 1.8rem;
    font-weight: 600;
    line-height: 1.3;
    margin-bottom: 10px;
    min-height: 50px;
}

.card-description {
    color: #e8e9e36a;
    font-size: 1.2rem;
    font-weight: 400;
    line-height: 1.4;
    flex: 1;
}

.card-number {
    font-size: 2.5rem;
    font-weight: bold;
    color: #e8e9e337;
    position: absolute;
    bottom: 0px;
    right: 5px;

}
</style>