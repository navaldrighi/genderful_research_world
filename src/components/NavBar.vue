<script setup>
import content from '@/assets/content.yml';
</script>

<template>
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <div class="container-fluid">
      <router-link class="navbar-brand" to="/">
        <img alt="Genderful Research World logo" src="../assets/logo.png" width="100" />
        GRW
      </router-link>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
            <router-link class="nav-link" to="/quiz">{{ content.navigation.quiz }}</router-link>
        </li>
        <li class="nav-item">
            <router-link class="nav-link" to="/research">Research road</router-link>
        </li>
        <li class="nav-item">
            <router-link class="nav-link" to="/funding">Funding</router-link>
        </li>
        <li class="nav-item">
            <router-link class="nav-link" to="/assembling_teams">Assembling teams</router-link>
        </li>
        <li class="nav-item">
            <router-link class="nav-link" to="/case_studies">Case studies</router-link>
        </li>
        <li class="nav-item">
            <router-link class="nav-link" to="/about">About</router-link>
        </li>
      </ul>
    </div>
  </div>
</nav>
</template>