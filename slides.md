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

<div class="text-center mt-20">
  <h3 class="text-gray">请按空格键播放...</h3>
</div>

<div class="absolute bottom-10 left-0 right-0 flex justify-center space-x-8">
  <div class="flex items-center text-gray-300">
    <carbon:user-avatar class="text-xl" />
    <span>北京大学</span>
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
class: text-center
---

<div class="absolute top-4/9 left-1/2 -translate-x-1/2 -translate-y-1/2 w-full">
  <h1 class="text-6xl mb-4">感谢观看！</h1>
  <h2 class="text-2xl text-gray-200">大语言模型驱动的多智能体协作框架增强电子病历预测建模</h2>
</div>

<!-- 底部联系方式 -->
<div class="absolute bottom-15 left-1/2 -translate-x-1/2 text-center text-xl">
  <div class="flex items-center space-x-3">
    <!-- 二维码 -->
    <div class="w-32">
      <img src="/figures/paper.png" alt="联系二维码" class="rounded-lg shadow-lg">
      论文查阅
    </div>
    <div class="w-32">
      <img src="/figures/page.png" alt="联系二维码" class="rounded-lg shadow-lg">
      合作联系
    </div>
    <div class="w-32">
      <img src="/figures/medx.jpg" alt="联系二维码" class="rounded-lg shadow-lg">
      关注我们
    </div>
    <!-- 联系方式文字 -->
    <!-- <div class="space-y-2">
      <div class="flex items-center">
        <carbon:document class="text-yellow-600" /> <a href="https://arxiv.org/pdf/2410.02551" class="ml-2">论文查阅</a>
      </div>
      <div class="flex items-center">
        <carbon:email class="text-yellow-600" /> <a href="http://scholar.pku.edu.cn/malt" class="ml-2">合作联系</a>
      </div>
      <div class="flex items-center">
        <carbon:scan class="text-yellow-600" /> <a href="http://scholar.pku.edu.cn/malt" class="ml-2">关注我们</a>
      </div>
    </div> -->
  </div>
</div>

<div class="text-sm absolute bottom-4 text-center text-gray-300 left-1/2 transform -translate-x-1/2">
  论文链接：<a href="https://arxiv.org/pdf/2410.02551"> https://arxiv.org/pdf/2410.02551 </a> <br>
  合作联系：<a href="http://scholar.pku.edu.cn/malt"> http://scholar.pku.edu.cn/malt </a>
</div>

<style>
a {
  color: #2E90E5;
  text-decoration: none;
  transition: color 0.2s;
}

a:hover {
  color: #1C6DAF;
}
</style>