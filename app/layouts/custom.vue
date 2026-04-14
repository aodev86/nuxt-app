<template>
    <div>
        <header>ここがカスタムヘッダー</header>
        <main>
            <slot />
        </main>
        <footer>ここがカスタムフッター</footer>
    </div>
</template>
<style>
header {
    background-color: #e0e0e0;
    padding: 20px;
    text-align: center;
}
footer {
    background-color: #e0e0e0;
    padding: 20px;
    text-align: center;
}
</style>