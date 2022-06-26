<template>
  <main>
    <section class="self-center flex flex-col flex-1 items-center justify-center">
      <h1 class="title text-center">En cours de dev</h1>
      <h2 class="subtitle text-center">Stay tuned</h2>
      <img src="https://lh3.googleusercontent.com/pw/AM-JKLXg9wHHU9QYROa6nIvsd41OqrQ3IlEM3iby9MoSDUOfsPTcR7dj5igjNo88aEzpSACzVjcwvYtu2IcEgyg0aGZA9RBcAKIKl_-G14zQJgpAPfHSF7AOu2Yfwx-qT88uWUNAJGh8VQhsIvKGdxx_6tnJKw=w960-h1279-no?authuser=0">
    </section>

    <section class="mt-8">
      <h3 class="text-primary-600 dark:text-primary-400 max-w-5xl mx-auto">Latest blog post</h3>
      <posts post-type="blog" :amount="1" />
    </section>
  </main>
</template>