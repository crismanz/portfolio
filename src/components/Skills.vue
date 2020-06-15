<template>
  <div id="skills" class="container">
    <h2>What I Use To Create.</h2>
    <div class="list">
      <div v-for="skill in skills" :key="skill" class="list-item">
        <img :src="skill.logo">
        <p>{{skill.name}}</p>
      </div>
    </div>
  </div>
</template>

<script>
import html5 from '../assets/html5.png'
import css3 from '../assets/css.png'
import javascript from '../assets/javascript.png'
import vue from '../assets/vuejs.png'
import react from '../assets/react.png'
import angular from '../assets/angular.png'
import git from '../assets/git.png'
import bootstrap from '../assets/bootstrap.png'
import linux from '../assets/linux.png'
import wordpress from '../assets/wordpress.png'
import ruby from '../assets/ruby.png'

export default {
  name: 'Skills',
  data() {
    return {
      skills: [
        { name: "HTML5", logo: html5 }, 
        { name: "CSS3", logo: css3 },
        { name: "JavaScript", logo: javascript },
        { name: "Vue.js", logo: vue },
        { name: "React", logo: react },
        { name: "Angular", logo: angular },
        { name: "Git", logo: git },
        { name: "Bootstrap", logo: bootstrap },
        { name: "Linux", logo: linux },
        { name: "Wordpress", logo: wordpress },
        { name: "Ruby", logo: ruby }
      ]
    }
  }
}
</script>

<style scoped>
.list { 
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  justify-content: space-evenly;
  align-items: center;
}
.list-item {
  width: 60px;
  padding: 20px;
}
</style>
