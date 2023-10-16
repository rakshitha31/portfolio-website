<template>
    <div class="navbar padding mt-9">
      <nuxt-link
        to="/"
        class="navbarBtn thinText display-inline-block mr-5 hover:text-blue-500"
        :class="{ 'text-blue-500': $route.path === '/' }"
      >
        Home
      </nuxt-link>
      <nuxt-link
        to="/about"
        class="navbarBtn thinText display-inline-block mr-5 hover:text-blue-500"
        :class="{ 'text-blue-500': $route.path === '/about' }"
      >
        About
      </nuxt-link>
      <nuxt-link
        to="/contact"
        class="navbarBtn thinText display-inline-block mr-5 hover:text-blue-500"
        :class="{ 'text-blue-500': $route.path === '/contact' }"
      >
        Contact
      </nuxt-link>
      <nuxt-link
        to="/activities"
        class="navbarBtn thinText display-inline-block hover:text-blue-500"
        :class="{ 'text-blue-500': $route.path === '/activities' }"
      >
        Activities
      </nuxt-link>
    </div>
  </template>
  