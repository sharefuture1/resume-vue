<script setup lang="ts"></script>

<template>
  <div flex="~ 1 justify-center" class="page" ma>
    <div mt-2 p-5 class="content" m-2>
      <SelfProfile />
      <Divider title="教育背景" />
      <School />
      <Divider title="自我介绍" />
      <SelfIntroduction />
      <Divider title="个人技能" />
      <PersonalSkills />
      <Divider title="工作经历" />
      <WorkExperience />
      <Divider title="项目经历" />
      <ProjectExperience />
    </div>
    <Operation />
  </div>
  <Drawer />
</template>

<style scoped>
.content {
  box-shadow: 1px 1px 6px 1px #ccc;
  overflow: auto;
}
</style>
