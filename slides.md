---
# You can also start simply with 'default'
theme: seriph
background: /figures/bg.jpg
# some information about your slides (markdown enabled)
title: ColaCare
info: |
  ## Slidev Starter Template

# apply unocss classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
---

# ColaCare

<div class="text-center">
  <h2 class="text-2xl mt-4 text-gray-200">
    大语言模型驱动的多智能体协作框架增强电子病历预测建模
  </h2>
  <h3 class="text-xl mt-8 text-gray-300">
    新型临床决策支持系统
  </h3>
</div>

<div class="absolute bottom-10 left-0 right-0 flex justify-center space-x-8">
  <div class="flex items-center space-x-2 text-gray-300">
    <carbon:user-avatar class="text-xl" />
    <span>北京大学</span>
  </div>
  <div class="flex items-center space-x-2 text-gray-300">
    <carbon:calendar class="text-xl" />
    <span>{{ new Date().toLocaleDateString() }}</span>
  </div>
</div>

<style>
h1 {
  text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.5);
}
</style>
---
src: slides/pipeline.md
---

---
src: slides/spipeline.md
---

---
src: slides/patient.md
---

---
src: slides/initial.md
---

---
src: slides/doctor1.md
---

---
src: slides/doctor2.md
---

---
src: slides/doctor3.md
---

---
src: slides/meta.md
---

---
src: slides/con1.md
---

---
src: slides/con2.md
---

---
src: slides/con3.md
---

---
src: slides/final.md
---

---
layout: cover
background: /figures/bg.jpg
---

# 感谢观看！

<div class="text-center">
  <h2 class="text-2xl mt-4 text-gray-200">
    ColaCare
  </h2>
  <h3 class="text-xl mt-8 text-gray-300">
    大语言模型驱动的多智能体协作框架增强电子病历预测建模
  </h3>
</div>

<div class="absolute bottom-10 left-0 right-0 flex justify-center space-x-8">
  <div class="flex items-center space-x-2 text-gray-300">
    <carbon:user-avatar class="text-xl" />
    <span>北京大学</span>
  </div>
  <div class="flex items-center space-x-2 text-gray-300">
    <carbon:calendar class="text-xl" />
    <span>{{ new Date().toLocaleDateString() }}</span>
  </div>
</div>

<style>
h1 {
  text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.5);
}
</style>