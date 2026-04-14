<template>
    <div>
        <header>ここがヘッダー</header>
        <main>
            <slot />
        </main>
        <footer>ここがフッター</footer>
    </div>
</template>
<style>
header {
    background-color: #f0f0f0;
    padding: 20px;
    text-align: center;
}
footer {
    background-color: #f0f0f0;
    padding: 20px;
    text-align: center;
}
</style>